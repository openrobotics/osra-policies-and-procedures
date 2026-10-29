# Charter of the ROS Project Working Group "Bazel"

13 October 2026

### Names

The names of the Working Group shall be "ROS Working Group on Bazel", "WG on Bazel" and "ROS-WG-BAZEL".


### Chair

The Chair of the Working Group shall be [Andrew Symington](mailto:simmers@google.com).

### Purpose

The Working Group is formed to make [Bazel](https://bazel.build) an officially supported build system for ROS, alongside the existing colcon toolchain.
Bazel is an open-source build system, originally developed at Google, that builds and tests software in an isolated ("hermetic") environment.
The [ROS Central Registry (RCR)](https://bazel.ros.org) already provides ROS core packages as Bazel modules, extending the [Bazel Central Registry (BCR)](https://registry.bazel.build) where general third-party libraries live.
Those themes include:
- Publishing ROS packages as Bazel modules in the RCR, automatically tracking upstream ROS releases;
- C, C++, Python and Rust client libraries, and generation of messages, services and actions;
- The ability to produce underlay install directories that mimic the output of `colcon build`, so that underlays built with Bazel can be reused by developers who do not use Bazel;
- Shared and fully static builds, including small, portable single-binary ROS nodes; and
- Documentation, examples and onboarding material for developers new to Bazel.


### Motivation

Many organizations that build products on ROS already use Bazel internally, and today each must port and maintain ROS on their own.
An official, shared Bazel build would let that effort be pooled, and would bring the following benefits to the wider ROS community:
- **Determinism:** Bazel downloads its own hermetic compiler and Python interpreter, rather than using whatever is installed on the host. The same source therefore produces the same binaries on any machine, eliminating "works on my machine" failures.
- **Remote caching:** because builds are deterministic, their outputs can be shared. If any developer or CI machine has already built a target, others simply download the result instead of rebuilding it, turning hours of compilation into minutes.
- **Strict dependencies:** every target only sees the files, libraries and data it explicitly declares. In a traditional ROS workspace, a package may silently rely on something another package happened to install into the shared underlay, and then fail at runtime with a missing library, plugin or asset when deployed elsewhere. Bazel turns such implied dependencies into build errors.
- **Fast, correct incremental builds and tests:** Bazel tracks every dependency explicitly, so after a change it rebuilds and re-tests only what was actually affected. This leads to significantly faster CI completion times.
- **Sanitizers, fuzzing and profiling support:** since the whole stack, including third-party libraries, is built from source with one toolchain, sanitizers, fuzzers and profilers can be applied to an entire application with a single flag.
- **Portable deployment and cross-compilation:** ROS nodes can be built as small, self-contained static executables or container layers, without needing a ROS distribution. Because Bazel manages its own toolchains, a developer can also cross-compile for a different architecture (for example, targeting an `arm64` robot from an `x86_64` host) without emulation or a separate build environment.
- **Easier onboarding:** a developer needs only Bazel and git; there is no system compiler, `rosdep` step or ROS installation to set up first.


### Tasks

The Working Group shall perform the following tasks.

1. Identify the gaps between Bazel and colcon builds of ROS, such as host-supplied OpenGL.
1. Maintain and improve the RCR tooling, continuous integration and shared remote cache.
1. Propose to the ROS PMC the policies, processes and infrastructure needed for Bazel to become an official ROS build system.


### Expected outputs

The Working Group shall, upon completion of its tasks and as appropriate while performing them, provide to the ROS PMC the following.

1. Regular RCR releases that track upstream ROS distributions on supported platforms.
1. Bug fixes, usability improvements, features, and documentation around the WG themes.
1. A recommendation, with a roadmap, for adopting Bazel as an official ROS build system.


### Completion date

The Working Group's Charter expires on the 13th of October, 2027. The Working Group shall be automatically dissolved on that date, unless its Charter is explicitly renewed by the ROS PMC.


### Meetings

The Working Group shall meet at least every 8 weeks. Meetings shall be noticed at least three (3) calendar days in advance to the ROS PMC Members and Committers. Meeting notice shall include the date, time, and URL of the online meeting. A single announcement noticing a series of meetings together shall be considered sufficient notice for all meetings in the series, provided that notice of the cancellation of one of those meetings shall be given at least one (1) calendar day in advance. Meetings shall be held online via a suitable teleconference service as specified by the ROS PMC.


### Activity reports

The Chair of the Working Group shall provide a verbal report of its recent activities in each meeting of the ROS PMC.
The Chair shall additionally provide the ROS PMC with any documents generated by the activities of the Working Group, if and when requested by the ROS PMC to do so.

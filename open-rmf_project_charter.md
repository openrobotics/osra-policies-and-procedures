# Charter of the Open Source Robotics Alliance Project "Open-RMF"

XX March 2024


## Definitions and Details


### ARTICLE 1. Definitions

Assigned Secretary
: The secretary assigned to the Project by the Board of the OSRA.

PMC
: The Project Management Committee for this Project.

Project
: The Project of the Open Source Robotics Foundation known as "Open-RMF", for which responsibility for governance has been assigned to the OSRA.

Project Support Infrastructure
: The computing infrastructure, including online services, provided by the OSRA for the use by Projects.

Project Governance Structure
: The specific governance structure used to govern the Project.

P&P
: The Policies and Procedures of the Open Source Robotics Alliance.

All definitions provided in the Charter of the Open Source Robotics Alliance Technical Governance Committee also apply in this Charter.


### ARTICLE 2. Project Details

1. The name of the Project shall be "Open-RMF".

1. The Project shall use the GitHub online service to host its source code repositories, except where the PMC has determined that GitHub is not appropriate, in which case the PMC shall specify an alternative online service to use.

1. The Project shall maintain a section of the Project website that lists the following:

   1. the name, affiliation, GitHub username and optionally the primary time zone of the Project Leader;

   1. the name, affiliation, GitHub username and optionally the primary time zone of each PMC Member;

   1. the name, affiliation, GitHub username and optionally the primary time zone of each Committer who is not also a PMC Member;

   1. the name, and optionally GitHub username and e-mail address, of past Project Leaders and their affiliation at the time of holding that status; and

   1. the name, and optionally GitHub username and e-mail address, of past Committers/PMC Members and their affiliation at the time of holding that status, except for those persons who communicate their wish to not be listed to the Project Leader at the time of ending their status as a Committer/PMC Member.

1. The Project shall maintain a section of the Project website that lists the following:

   1. the GitHub organisations utilised by the Project, including for each organisation the URI and the intended purpose; and

   1. the GitHub repositories utilised by the Project, including for each repository the URI, the intended purpose, the names and GitHub usernames of the Committers who manage that repository, and the names and GitHub usernames of the Committers who can commit to that repository.

1. The Project shall maintain a section of the Project website that defines the roadmap of the Project.


## Project Governance


### ARTICLE 3. Project Governance Structure

1. The Project Governance Structure used by the Project shall have the following entities and relations:

   1. one (1) Project Leader, in accordance with ARTICLE 8.3 of the OSRA Charter and ARTICLE 5 of this Charter;

   1. one (1) Project Management Committee ("PMC"), in accordance with ARTICLE 8.5 of the OSRA Charter and ARTICLE 4 of this Charter;

   1. one (1) or more Project Management Committee Members ("PMC Members") in accordance with ARTICLE 8.5 of the OSRA Charter and ARTICLE 6 of this Charter;

   1. one (1) or more Committers in accordance with ARTICLE 8.6 of the OSRA Charter and ARTICLE 7 of this Charter; and

   1. zero (0) or more Working Groups, established by the PMC in accordance with ARTICLE 8.5 of the OSRA Charter and ARTICLE 8 of this Charter.


### ARTICLE 4. Project Management Committee

1. In addition to the duties listed in the TGC Charter, the Project Management Committee shall have the following duties:

   1. making release readiness decisions for the Project;

   1. managing the execution of a new release of the Project;

   1. managing the website of the Project; and

   1. producing and maintaining clear and well-organised documentation for the Project, including but not limited to design documentation, documentation of design decisions made and related rationale, introductory tutorials (in textual form and, at the discretion of the PMC, audio-visual form), concept guides, and API documentation.

1. The Project Management Committee shall consist of the following natural persons (the "PMC Constituents"):

   1. the Project Leader, who shall act as Chair of the Project Management Committee;

   1. all PMC Members for the Project;

   1. one (1) Supporting Individual Representative, selected in accordance with the TGC Charter; and

   1. the Chair of the TGC, or his or her delegate.

1. At the discretion of the TGC or the Board of Directors of the OSRF, one (1) secretary may be assigned to the Project Management Committee (the "Assigned Secretary").
   The role of the Assigned Secretary is to support the Project Leader in the smooth operation of the Project Management Committee and its activities.
   The Assigned Secretary shall not participate in discussion or decision making other than in an administrative capacity.
   The Assigned Secretary is not counted amongst the PMC Constituents for the purposes of this Charter.

1. The Project Management Committee shall meet monthly, and more frequently as required.

1. The meetings of the Project Management Committee shall be held via teleconference using a teleconferencing system provided by the OSRF.

1. A quorum exists at a meeting of the Project Management Committee when at least two-thirds (2/3) of the PMC Constituents are present, or participating remotely in the meeting.
   If no quorum exists at a meeting of the Project Management Committee, the PMC Constituents may hold discussions but no formal or informal decisions shall be taken.

1. Meetings of the Project Management Committee shall be open to observers by default, with no restrictions on who may observe.
   Observers shall not speak during a Project Management Committee meeting unless called upon by the Chair, and may not take part in decision making.
   At the sole discretion of the Project Leader, a meeting may be held "closed", with only the constituents of the Project Management Committee present.

1. All PMC Constituents shall be involved in decision making.
   With the exception of the Chair of the TGC, each PMC Constituent shall have one (1) vote on each matter put before the Project Management Committee for a formal decision.
   The Chair of the TGC shall have one (1) vote, except when there is a tie in a vote, in which case the Chair of the TGC shall either abstain or cast an additional, tie-breaking vote.

1. The Project Management Committee shall only use a formal decision to decide on the following matters:

   1. nominating a PMC Member to be the next Project Leader;

   1. adding a new external dependency to a package;

   1. adding a new repository to the Project;

   1. removing a repository from the Project;

   1. setting a significant release date for the Project;

   1. altering a significant release date of the Project; and

   1. recommending a course of action to the TGC.

1. In addition to the cases mentioned in ARTICLE 4.9, the Project Management Committee shall take a formal decision when any of the following occur.

1. Any meeting of the Project Management Committee at which formal decisions will be made must be notified by the Project Leader or his or her delegate to all PMC Members a minimum of one (1) calendar week in advance.
   Such notice must include the decisions that shall be taken and any required supporting documentation.
   If notice of a meeting is insufficient, no formal decisions shall be made in that meeting.

1. The Project Management Committee may use the following methods for making decisions.

   1. Consensus of all PMC Constituents present in the meeting in which the decision is being made, provided that meeting meets the necessary criteria for decision making specified in ARTICLE 4 of this Charter.
      The decision shall take effect at the close of the meeting of the PMC in which that decision was made.

   1. Asynchronous vote after the meeting ends.
      The voting period shall be not less than three days and not more than one week.
      A two-thirds (2/3) majority of all PMC Constituents is required for the decision to be accepted.
      The decision shall take effect immediately upon the announcement of the result by the Project Leader.
      The Project Leader shall announce the vote before or during the next meeting of the PMC after the vote closes.

   1. Asynchronous vote after the meeting ends, with a simple majority of all PMC Constituents enabling the decision to be carried, provided ratification of the decision by the TGC is given within the next two TGC meetings following the closing of the vote.
      The voting period shall be not less than three days and not more than one week.
      The Project Leader shall announce the vote before or during the next meeting of the PMC after the vote closes.
      The decision shall not take effect until ratified by the TGC.

1. If, upon receiving notice of a meeting in which one or more decisions are to be made, a PMC Constituent requests by e-mail to the Project Leader an asynchronous vote for a decision, then the Project Leader must commence an asynchronous vote for that decision by suitable means, as stipulated by this Charter, within one week of the meeting in which that decision was to be taken.

1. The Project Management Committee is not required to keep formal minutes of all discussions held.
   However, minutes of decisions formally taken shall be kept and provided to the TGC as part of providing the report on the activities of the Project Management Committee.
   These minutes shall include the decision(s), the method(s) of decision making and, in the case of votes, the vote(s) of each PMC Constituent.

1. The report of the Project Management Committee must be provided in writing to the Chair of the TGC at least eight (8) days in advance of the TGC meeting at which it is to be presented and/or discussed, if such report includes documentation that must be reviewed prior to the TGC meeting.
   If such documentation is not required, no written report is necessary unless explicitly requested by the Chair of the TGC.

1. PMC Constituents shall bear their own costs and expenses for their participation in Project activities, meetings, travel, employee compensation, and incidental expenses.


### ARTICLE 5. Project Leader

1. The Project Leader shall have administrative access to all GitHub organisations, GitHub repositories, and accounts at other online services used by the Project.

1. The Project Leader shall have administrative access to all Project Support Infrastructure (as provided by the OSRF) utilised by this Project.


### ARTICLE 6. Project Management Committee Members

1. Any natural person may achieve the status of PMC Member through the following process.

   1. A Contributor to the Project or Committer of the Project decides to become a PMC Member and contacts an existing PMC Member of the Project for mentorship, or a PMC Member of the Project identifies a Contributor or Committer who has the potential to become a PMC Member and proposes this to that person (the "Candidate").

   1. The PMC Member informs the Project Management Committee for the Project of their intention to take on the Candidate for mentorship towards being a PMC Member for the Project with responsibility for specific repositories of the Project.
      The Project Management Committee, by discussion and a resolution, chooses to accept or reject the proposed mentorship.

   1. The Candidate and the mentoring PMC Member ("Mentor") work together over a period of not less than one (1) calendar month and not more than six (6) calendar months, with the goal of the Candidate learning what is required in being a PMC Member, making further and more significant contributions to the Project, gaining the necessary experience to be able to perform the PMC Member and Committer roles, and demonstrating their ability to perform the roles in keeping with the policies of the Project, as specified by the Project Management Committee, the OSRA-wide project policies, as specified by the TGC, and the Policies and Procedures of the OSRA.

   1. At a point no less than one (1) calendar month after commencing the mentorship, the Mentor proposes to the Project Management Committee that the Candidate be promoted to a PMC Member for the repositories of the Project specified at the start of the mentorship, and receive all rights conducive with that position.
      The Project Management Committee shall discuss the proposal, followed by the PMC taking a decision on whether to accept or reject the Candidate as a PMC Member.

   1. If the Mentor cannot propose to the Project Management Committee that the Candidate be promoted to PMC Member status within six (6) calendar months of commencing the mentorship, or the Project Management Committee does not accept the Candidate within six (6) calendar months of the mentorship commencing, the mentorship terminates.
      In this situation, the Candidate is free to begin the process again at any time, provided that a different PMC Member agrees to fulfil the role of Mentor.

1. With the exception of the Supporting Individual Representative, there shall be no requirement to be a Supporting Individual Member of the OSRA to become a PMC Member.


### ARTICLE 7. Committers

1. Committers shall be given necessary access rights to the repositories of the Project to which they are to be granted access to perform the duties expected of them.
   Committers shall not be given special rights in any other repository of the Project except by a decision of the Project Management Committee.

1. Committers shall be given necessary access rights to the Project Support Infrastructure utilised by the Project as is necessary to perform their tasks and approved by the Project Management Committee.

1. Other than in service of ARTICLE 7.2, no Committer other than the Project Leader shall have administrative access to any GitHub organisations or similar entities at other online services used by the Project.

1. The Project Management Committee may take a decision at any time to grant, restrict or remove a Committer's access rights to one or more repositories of the Project.

1. The Project Management Committee may take a decision at any time to grant, restrict or remove a Committer's access rights to the Project Support Infrastructure utilised by the Project.

1. A Committer who is not also a PMC Member may only attend closed meetings of the Project Management Committee at the invitation of the Project Leader.

1. A Committer who is not also a PMC Member is considered an observer in any meeting of the Project Management Committee.

1. Any natural person may achieve the status of Committer through the following process.

   1. A Contributor to the Project decides to become a Committer and contacts an existing PMC Member of the Project for mentorship, or a PMC Member of the Project identifies a Contributor who has the potential to become a Committer and proposes this to that person (the "Candidate").

   1. The PMC Member informs the Project Management Committee for the Project of their intention to take on the Candidate for mentorship towards being a Committer for the Project with responsibility for specific repositories of the Project.
      The Project Management Committee, by discussion and a resolution, chooses to accept or reject the proposed mentorship.

   1. The Candidate and the mentoring PMC Member ("Mentor") work together over a period of not less than one (1) calendar month and not more than six (6) calendar months, with the goal of the Candidate learning what is required in being a Committer, making further and more significant contributions to the Project, gaining the necessary experience to be able to perform the Committer role independently, and demonstrating their ability to perform the role in keeping with the policies of the Project, as specified by the Project Management Committee, the OSRA-wide project policies, as specified by the TGC, and the Policies and Procedures of the OSRA.

   1. At a point no less than one (1) calendar month after commencing the mentorship, the Mentor proposes to the Project Management Committee that the Candidate be promoted to a Committer for the repositories of the Project specified at the start of the mentorship, and receive all rights conducive with that position.
      The Project Management Committee shall discuss the proposal, followed by the PMC taking a decision on whether to accept or reject the Candidate as a Committer.

   1. If the Mentor cannot propose to the Project Management Committee that the Candidate be promoted to Committer status within six (6) calendar months of commencing the mentorship, or the Project Management Committee does not accept the Candidate within six (6) calendar months of the mentorship commencing, the mentorship terminates.
      In this situation, the Candidate is free to begin the process again at any time, provided that a different PMC Member agrees to fulfil the role of Mentor.

1. There shall be no requirement to be a Supporting Individual Member of the OSRA to become a Committer.


### ARTICLE 8. Working Groups

1. The Project Management Committee may establish such working groups (the "Working Groups") as the Project Management Committee from time to time deems necessary or appropriate to carry out its duties.

1. The content of a Working Group Charter shall specify, but not be limited to, the following:

   1. the title of the Working Group;

   1. the Chair of the Working Group;

   1. the purpose of the Working Group;

   1. the task, including any detailed instructions and requirements necessary, that the Working Group is to perform;

   1. the expected work product(s), if any, that the Working Group is expected to provide to the Project Management Committee upon completion or termination of its task;

   1. the date, if any, by which the Working Group must complete its work, report back to the Project Management Committee and be dissolved, or receive an extension from the Project Management Committee;

   1. the minimum frequency of Working Group meetings; and

   1. the minimum frequency of the Working Group providing a report on its activities to the Project Management Committee.

1. A Working Group may have an expiration date, which must be specified in its Charter.
   After this the Working Group shall be automatically dissolved if its Charter is not renewed by the Project Management Committee prior to this date.
   If the Working Group does not have an expiration date, this shall be specified in its Charter.

1. A Working Group without an end date, or a Working Group with an end date greater than one (1) calendar year from its establishment date, shall be reviewed by the Project Management Committee every calendar year from its establishment date or any previous review.
   The review shall evaluate the Working Group's activities, outputs, and use of resources.
   The information for the review shall be gathered by the Project Leader with the cooperation of the Chair of the Working Group.
   Based on the review, the Project Management Committee shall decide whether to dissolve the Working Group, allow it to continue with its existing Charter, or revise its Charter.

1. A Working Group is only empowered to perform the specific task assigned to it by the Project Management Committee upon creation of the Working Group.
   The Project Management Committee may specify a finite time frame within which the Working Group is required to complete its task and report to the Project Management Committee.
   If the Working Group is unable to complete its assigned task within the time frame provided by the Project Management Committee it may report this to the Project Management Committee.
   Upon reaching the specified time frame, the Working Group shall be automatically dissolved, unless the Project Management Committee has explicitly renewed its Charter.

1. Working Groups shall report to the Project Management Committee at a frequency defined in the Charter of the Working Group.
   A Working Group may elect to have either the Chair of the Project Management Committee or one of the PMC Members participating in the Working Group present its reports to the Project Management Committee.

1. Each Working Group shall have a Chair, who shall be a PMC Member.
   The Chair shall be designated by the Project Management Committee at the establishment of the Working Group.
   The Chair shall be responsible for the achievement of the Working Group's task, and for the correct use of any budget provided by the Project Management Committee for use by the Working Group in carrying out its assigned task.

1. With the exception of administrative access to any online services, the Project Management Committee shall delegate the necessary powers to the Working Group for the Working Group to perform its assigned task.

1. The Project Management Committee shall retain the right to limit the powers and duties of any Working Group that it has created and to dissolve any such Working Group in its sole discretion by resolution of the Project Management Committee.
   The Project Management Committee has a supervisory role in the work of any Working Group.

1. Any appointment by the Project Management Committee of any other Working Groups, including the designation of one (1) PMC Member as the Chair, must be taken by a decision adopted by a simple majority of the PMC Members present, represented or participating remotely at a Project Management Committee meeting.

1. Meetings of a Working Group, if any, shall be announced by the Chair of the Working Group one calendar week in advance.
   The Chair shall provide an agenda along with this notice.
   Meetings shall be held at places and times to encourage maximum participation, taking into consideration the active Working Group participants' varying schedules and time zones, to the extent possible and necessary to perform the assigned task.

1. Working Group meetings shall be held "in the open," with participation open to any natural person who wishes to join on an irregular or on-going basis.
   Participation in Working Group activities shall not be limited to PMC Members, Committers, or Members of any kind of the OSRA.

1. A Working Group may not take any decisions or make any resolutions beyond that necessary to achieve the set task, as stated in the Charter of the Working Group, and achievable by consensus.
   When consensus cannot be reached, the decision shall be taken by the Project Management Committee.

1. A Working Group is not required to keep formal minutes of discussions held.

1. Participants in Working Groups shall bear their own costs and expenses for their participation in Working Group activities, meetings, travel, employee compensation, and incidental expenses.

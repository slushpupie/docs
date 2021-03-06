# Overview

This document aims to describe the ways in which OVN will work with regards to knowledge sharing, meetings, etc.

# Meeting processes

- Meetings will start on time and end on time. Meetings of Open Voice Network standing committees and technical project committees will begin and conclude promptly at the times scheduled. If it is deemed important by the committee chair and/or meeting moderator to continue a conversation beyond the scheduled adjournment time, the chair or moderator will pause the meeting at the scheduled adjournment time, and invite participants to continue.  No decision will be taken by a committee outside the scheduled meeting window. 
- Meetings will operate under the antitrust guidelines of The Linux Foundation, found here: https://www.linuxfoundation.org/antitrust-policy/. A statement to this effect, along with a slide that shows the URL of the Linux Foundation antitrust guidelines, will be shown at the beginning of every Open Voice Network standing and technical project committee meetings.
- Meeting agendas will be distributed to meeting participants no less than 48 hours in advance. Meeting agendas for the OVN Technical Committee will be posted in the OVN GitHub Docs Repo no than 48 hours in advance of the meeting.   
- Meetings will foster accountability and follow-up. The review of relevant and outstanding issues will be a stated agenda item early on the agenda of every Open Voice Network Technical Committee and Work Group meeting.  The Technical Committee and Technical Committee Work Groups will use GitHub (see below) to document issues for resolution, and relevant and outstanding Github issues will be reviewed in every meeting.
- Meetings will be recorded, and notes will be taken. All scheduled meetings of the Technical Committee and Technical Committee Work Groups will be recorded, using the recording technology of the web conferencing platform in use. Full audio-visual meeting recordings will be stored in the Technical Committee Open Voice Network Google Share Drive. An announcement of “this meeting is being recorded” will be made at the beginning of every meeting. Notes will be taken of all Technical Committee meetings, published within 48 hours in the OVN GitHub docs file. 

# Working tools

- The Technical Committee will use the following technologies:
- Github for technical document management and review, at https://github.com/orgs/open-voice-network. 
- Slack for instant messaging and quick issue resolution. You will be added to the OVN Slack channels upon invitation to the OVN Technical Committee, a project task force, or one of the OVN Communities. To request participation in the OVN Slack Channels, please e-mail the OVN Executive Director (jon.stine@openvoicenetwork.org.) 
- Google G Suite (as noted above) for non-technical document management (calendars, some non-TC meeting notes, meeting recordings, relevant financial documents, etc.). Technically-focused committees and project task forces will use GitHub for document management; other OVN Communities and committees (such as Ethical Use and Education) will use Google G Suite for document storage and management. To obtain access, please request access via an e-mail to the OVN Executive Director (jon.stine@openvoicenetwork.org), and include your e-mail address (required for access to G Suite).  

# OVN Technical Committee Work Groups 

Working groups are the teams that execute work against the activities.  When a working group exists, they accountable for issue documentation, backlog management, and document development into the OVN GitHub repository.  Working Groups will also form and define their own leads/leadership. 

Technical Committee Work Groups formed:  
* **Architecture Work Group**  
  * formed in 6/26/20 Technical Committee meeting 
* **Privacy & Security Work Group** 
  * formed in 6/26/20 Technical Committee meeting 
* **Voice Registry System (VRS) Work Group**
  
# Work Group Decision-Making

Open Voice Network Technical Committee Work Groups are formed by the Technical Committee to research and recommend a solution or way forward on a topic determined to be of importance to the OVN's mission.  Recommendations are to be brought back to the Technical Committee, which may forward the recommendation to the OVN Steering Committee for endorsement and/or the allocation of resources.

Work Groups are

- Moderated by one or more regular participants in the Work Group
- expected to conduct business in a manner that is open, professional, and in keeping with the OVN Communities Code of Conduct found at www.openvoicenetwork.org
- expected to seek a diversity of views, and to welcome minority viewpoints and robust discussion
- asked to seek consensus decisions (and if a consensus cannot be reached, to achieve a decision by at least a two-thirds majority)
- expected to begin and close meetings with a review of outstanding and new issues, respectively

# Open Voice Network Technical Docs

This repository contains the published and work in progress artifacts, docs, schemas, technical committee working group meeting minutes, etc of the OVN. 

## Git folder structure

- **root** - contains OVN information that is more horizontal approach such as technical master plan, security, privacy, architecture, etc.
  - **components** - contains OVN identified invidual components such as VRS 
  - **component_assets** - contains images used in the component document
  - **api_docs** - contains component level swagger
  - **technical_masterplan_assets** - contains images used in the `technical_masterplan.d` document

## Install
-   To record important architecture decision, we use  [adr-tools](https://github.com/npryce/adr-tools "https://github.com/npryce/adr-tools"). To install, type the following in the terminal command. 

    >    ``` brew install adr-tools ```

- To view the diagrams, please install the [github-mermaid](https://chrome.google.com/webstore/detail/github-%2B-mermaid/goiiopgdnkogdbjmncgedmgpoajilohe) chrome extension.
- To learn more about mermaid, click [here](https://github.com/mermaid-js/mermaid).

## Creating Key Architecture Decision
- To support an inclusive ratification of ideas, we use architecture decision tool. To create new AD.

>   ``` adr new -s 2 vrs-integration  ```


## Do you want to contribute?
- Depending on your comfort and permission, there are multiple ways you may find yourself contributing via:
  - **Fork + PR** -- this approach is only needed if you don't have write access directly to the repo. See this for help: https://guides.github.com/activities/forking/
  - **Branch + PR** - this approach is used if you already have write access to the repo. See this for help: https://guides.github.com/introduction/flow/

- New to Git and not comfortable doing things in the commandline? If you prefer to work with a GUI, GitHub does allow you to do either approaches above all within the UI.
- Whatever steps you followed above, you will end in a Pull Request, also known as PR. This is required for all changes to this repo. Do not commit directly to the `master` branch.
- In the PR process, you will not see your changes right away. It is an area of discussion where the reviewer can ask for more questions or clarification about the changes you made. It is **best practice**, but not required to add/refer-to the issue number in the PR comments so it is easier to understand the context and background for why the PR is being made. 

  

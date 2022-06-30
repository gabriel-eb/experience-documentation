# Creating a Scrum dashboard

In this entry, you can read about my process for creating a scrum dashboard. I'm going to explain the tools, epics, user stories, tasks, and other decisions I made for this phase.

## Scrum and choosing the right tool
It's not a secret that Scrum is a widely used agile framework for most software development projects. Scrum has its strengths and weaknesses. As a developer, you always need to find the right tool for the tasks at hand, not choose it because the tool is in vogue. As a solo dev is a bit different, I have fewer resources than a team of +3 devs, so my tool selection needs to be limited to what I already know or the knowledge curve for the new tool (it has to be short).  
Personally, I consider Scrum as a *large* framework, therefore **overkilling** for a solo dev, but one thing that I find pretty useful for documenting and planning purposes is the Scrum dashboard. It's a fit tool for the task in hand, so let me start with the process.  

## The dashboard
There are a lot of SaaS for Scrum dashboards, some free, others with a free-tier, and paid ones. Even though, the existence of all these options does not appeal to me. So I decided to use [Notion](https://www.notion.so/). For lost people, Notion is a workspace with extensive customisable capabilities, designed as an academic notes app, it evolved into a great platform with amazing integration and customization.   
The way I use it is with this template dashboard: [Jira Dashboard](https://www.notion.so/flightrange/JIRA-Replacement-System-f8f1237e803e47f186cd190f0a71c186). Thanks to **flightrange** for creating the dashboard. And **yeah**, I know it's a downgraded copy of Jira, but I think, for this project, there are more than enough features. At the end of the entry, I'll add my dashboard for you to explore.  
The Scrum dashboard has 3 main sections: Epics, User Stories, and Tasks. I think the meaning of each is obvious. From there, I just needed to fill in each table (section) with the corresponding information. I started with Epics, then User Stories, and finished with Tasks, as it should be.

## Creating epics
An agile epic is a body of work that can be broken down into specific tasks (called user stories) based on the needs and requests of end-users [Atlassian](https://www.atlassian.com/agile/project-management/epics). With the previous definition in mind and with the help of an amazing Scrum Master (ty Andres), I created the first chunk of epics. An approach is to consider each epic as a deliverable, so I tried to do something like that, I say *tried* because I added some flexibility. For example, my top priority is a **Design System**, which is not required for end-users but IS required for developers to maintain the app; and there are others similar to this epic. You may be thinking that completing the other epics (the ones that complete requirements, add functionality) will need a design system, DB, docs, etc. to be completed, so there's no need to add them as epics. Yep, but adding this (first) type of epic helps me keep track of documentation and progress with necessary items. 
So the process has two steps:
 1) Create a description, high level, of what the user can do, watch and the "reason" for the functionalities.
 2) Add links that will assisst as reference for design.
Later, when the user stories are created, you add them to an epic and can list all user stories added to a single epic.  

## Creating user stories
A user story is an informal, general explanation of a software feature written from the perspective of the end user. Its purpose is to articulate how a software feature will provide value to the customer [Atlassian](https://www.atlassian.com/agile/project-management/user-stories). I used the format -> "As a [persona], I [want to], [so that]."   
I think defining user stories is the easiest part of the scrum dashboard. There is something I need to make clear, the persona part of the user story is a type of end-user, but I decided to add devs as personas. For example, "As a front-end dev, I want to have a design system to create UI components." I made this choice because it helps me remember to add documentation and other features that are normally created while completing tasks and user stories.  
The **definition of done** is the tricky part. The story is generally "done" when the user can complete the outlined task [Atlassian](https://www.atlassian.com/agile/project-management/user-stories). For some stories, DoD is straight forward, but for others, not so much. I had to be careful about adding DoD. The other thing is the Acceptance Criteria, I decided to use TDD in everything I can, so as acceptance criteria for any code part,  using passed tests and code coverage; for other things like design, I will create a general checklist to act like a test.  

## Creating tasks
I think that tasks are a "gut thing". The more you participate in a software project, the easier it is to create tasks, and a well written user story or epic helps a lot. In the scrum process, the Product Owner (PO) has the assignment to make clear user requirements and user stories for the dev team. Once they understand them, the team needs to create tasks to complete a user story. The more experienced the team, the more refined the tasks become. Usually, tasks are created after the current sprint's user stories are chosen and they are assigned to a team member.  

## Conclusion
The Scrum dashboard is a great tool because it generates documentation while tracking the most important metric for PM: time. Aside from that, you can add burnup/burndown charts and gantt charts to check progress, set due dates, and add links to important sources, which increases the project's visibility and transparency. The next step is to establish sprint length and estimate user stories to add for the first sprint.

### "Agile is simple—it just isn’t easy" -Ron Jeffries

## Have a nice week, everyone.
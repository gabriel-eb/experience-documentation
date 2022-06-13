# The beginning

## Every journey has a start and end point.

### Sumary
Today will be the first entry as the full-stack developer for this *experience unnamed app* for a company called [VB Tours](). In this entry I will talk about:
 - Choosing technologies/tools/frameworks
 - Planning process
 - Requirements gathering
 - Project Management

Before we continue with the entry, I need to be clear about one thing: there's no *real* formality to the decisions I made for this project. I should say, **all decisions were made from [empiricism](https://en.wikipedia.org/wiki/Empiricism)**. Let's start.

### Choosing tech/tools/frameworks
Organization is key in any project. So I had to pick all my weapons to achieve organization. My first and only option is: *Notion*. If you don't know about Notion, you should give it a try. In a nutshell, Notion is an all-in-one software for organizing. Think about one project, a large task, school, work, scheduling, etc., it's really probable a dashboard for that already exists in Notion; if not, you can easily create/modify one. So, I copied a Jira dashboard for Notion, and you may wonder why not just use Jira or Trello? Well, I can use Notion for more things. For example, I can move these entries to Notion in two clicks and create a complete blog over there, I may need a form to gather beta tester info, get a specific dashboard for a specific task, and so on. You may have realized that I love Notion.  

As a project management framework, I chose an agile framework: Extreme Programming (XP), with the freedom to accommodate it for one person. In the PM section I will talk more about it (there is a surprise that may annoy some people).  

For front-end design, Figma, I don't know what to say. I used Figma before, so I will be using it now. For the backend, I used [diagrams.net](https://www.diagrams.net/) because it's straightforward for various types of diagrams.  

For the backend, I'm planning on using AWS: API Gateway & Lambda for a REST service, using SAM CLI and Rust custom runtime; and DynamoDB as a NoSQL DB. Maybe I'll add more things to the back, but for now just these few. The reason for choosing lambda function as back is because I see fit for a multi-platform and scalable app for the future if needed. This decision will create a vendor lockdown, but I'm sure that moving to a Go or Rust server with MongoDB will be relatively easy.  

For the front, I'm using React Native and maybe Flutter, if I end up with extra time to change to Flutter. The reason for using RN is that I already know React, so learning Flutter may take me some time.  

Right now, there are no plans to make an Auth for users and a web front version. And it is important to clarify that none of these options are *engraved in stone*, I may change something depending on the opportunities.
  
### Planning process
Before doing anything, you need to plan. But for real, I planned as needed, basically. So, here are the steps I take to begin the project:

  1. Gather information about the company, such as the services offered, the target audience, the mission, vision, and values, and what they desire for the app.
  2. Choose the technologies and other things (previous section).
  3. Learning what's needed. Yeah, as a "one-member team" there are a bunch of things idk, so I need to study to cover everything necessary to launch a decent app.
  4. Gathering requirements, I did it with some friends, closest to the target audience, and with basic knowledge of mobile apps.
  5. Create an exhaustive product backlog.
  6. Using Figma to design the front-end.
  7. Creating NoSQL equivalents of RDB relations for an ER diagram.
  8. Stablishing "sprint backlog".
  9. Create front-end and back-end code concurrently (not literally, I mean code both almost at the same time).
 10. Add code for missing front-end components.
 11. Code refactoring.
 12. Launch the app after "sprint deliverables" are ready for a decent deployment.
 13. Expand functionality, groom user stories, and repeat from part 8.

For now, I don't need to explain every step. Maybe I'll create an entry for each step to keep you up with my progress.

### Requirements gathering
This section describes one of the hardest parts as a solo-dev. Normally, for requirement gathering, you have the client telling you what the apps need or want to do, but in my case, I didn't have that. So I gathered from a bunch of friends that they were as close as the target audience description for the company. Because there are two types of clients, one of whom is 60+ years old, I only focused on one client:

 - Gender: female
 - Age: 30 to 50
 - Monthly income: 25k-50k mxn
 - National tourism
 - Social class: medium-high
 - School degree: bachelor, master
 - Other traits and interests: travelers, business trips, family, taste for nature, high expectations of the region, knowledge of the region, organized, curious, studied, reading, adventurous, indigenous culture, gastronomy

I'll try to find someone with these characteristics to re-gather the requirements.

### Project Management (PM)
As I mentioned, Extreme Programming (XP) is the chosen agile framework for various reasons, mainly: good for small teams, applies TDD, code review, flexibility. I'm planning on adding an entry exclusive to XP, so I will keep it short.  

My first option, of course, was Scrum; the main problem with Scrum is that you have to follow it carefully for it to work. I think if I make changes to the XP framework, there will be less impact than in Scrum. For Scrum fans, let me tell you (the thing that may annoy some of you) that I chose to use the Scrum dashboard. I prefer Jira dashboards, and I found one for Notion really cool and handy. Personally, I find epics, user stories, and tasks a useful way to decompose and abstract implementations. This is like adding design to various parts of the project and letting you think somehow programatically.  

## Final thoughts
This is my first formal entry. I'm sorry for my limited vocabulary (I'll try to extend it in each entry). I hope to be clear about how I started the project and what the next steps are. This week (13–18 June 2022), I'll put my efforts into the product backlog. I'll record a video for the company presentation and may add some entries.

### "If you optimize everything, you will always be unhappy" -Donald Knuth

## Have a nice week, everyone.


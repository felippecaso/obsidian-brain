# Coalesce 2023 Talk Proposal

## Drafting and Approval Process

### [[2023-W12]] Week 1 (Mar 27 - Apr 2)
- [x] Review the proposal submission guidelines and requirements.
- [x] Research similar talks and conferences for inspiration.l
- [x] Draft an outline of the talk

### [[2023-W13]] Week 2 (Apr 3 - Apr 9)
- [x] Choose a final topic and angle for the talk.
- [ ] Develop a clear and concise summary of the talk.
- [ ] Identify the target audience and tailor the proposal accordingly.
- [ ] Prepare a draft for the talk proposal

### [[2023-W14]] Week 3 (Apr 10 - Apr 16)
- [ ] Create an outline of the talk, including key points and supporting evidence.
- [ ] Develop a title and subtitle for the talk.
- [ ] Write a compelling bio and introduction for the proposal.
- [ ] Revise the talk's content based on feedback from the event organizers

### [[2023-W15]] Week 4 (Apr 17 - Apr 23)
- [ ] Write a draft of the proposal, incorporating feedback from colleagues or mentors.
- [ ] Review the proposal for clarity, grammar, and spelling.
- [ ] Submit the proposal to the event organizers by [[2023-04-20-Thursday]].

## Outline
- [15min] The problem
	- Insights on myself
	- Boring to export and process data
- [15min] The solution
	- Inspiration MDS in a box
	- Wanted to learn more about tools
- Talk about the process itself being the objective
- There are two takeaways:
	- Learn and have fun with the process
	- The tools we use in our daily jobs can help us to learn more about ourselves

## Content
### Title
A journey to Personal Analytics with the Modern Data Stack

### Description
As analysts and data enthusiasts, we spend hours organizing and analyzing data for the organizations we work with. Why not do the same for ourselves? What if we could leverage the Modern Data Stack to make better decisions about our health, routines and finances?

This talk will dive into the world of personal analytics. We will highlight some possibilities of using dbt, Meltano and more to improve our own lives. Furthermore, it will showcase how the journey can be as fulfilling as the destination, bringing a whole new meaning to the tools and processes we use at work.

### 2-5min long Pitch Video on Loom
_main idea behind the session, key topics you plan to cover, and what audience members will learn_

https://www.loom.com/share/2347ec1746814fb38f22c2d5fdf5960c
- I'm Felippe, I speak from São Paulo - Brazil, working in data for a bit more than 5 years. I currently lead the Analytics team at Loft, a Brazilian scale-up in the real estate market.
- I will bring something a bit out of the box but really exciting to Coalesce this year: my journey into analytics about myself using the modern data stack.
- It all started when two parts of myself met each other
	- For some time now I've been consolidating data to manage my personal finances, recently even creating a dbt project for that - maybe it's overkill, but it has been a lot of fun nevertheless
	- Second, last year for me was challenging in maintaining a physical exercise routine. So I wanted to understand motivators and especially be able to set goals and effectively measure them
	- And then it all "clicked": what if I could use the Modern Data Stack to organize all this data?
- At roughly the same point in time, the article and repository for "mds in a box" were released. That was the opportunity I was looking for to interact with a lot of tools such as Meltano and Superset that I had heard, found interesting, but didn't have the opportunity to try since they didn't make sense for our stack at Loft.
- Then it all started: it began with a simple project where I could categorize my financial transactions. Soon, I was using Meltano's open source SDK to develop a Tap that reads a financial statement from my bank's PDF file. Finally, I started to play with containers and GitHub Codespaces.
- Since I was doing all this in my spare time, it challenged me to think about priorities: what did I want to learn first? What would help answer the questions I had about myself at the time, such as what I wanted to track to help in my nutrition and exercise plan? All of that allowed me to think about things I use in my daily job, such as estimating development resources, in a whole different context.
- I feel every Analyst and Engineer watching that is excited about their work - and let's be honest, that's a lot of Coalesce attendees - will find out that there is a lot more to build with the tools they are used to work on.
- There are really two takeaways:
	- First, the technical possibility: we know there is data everywhere, but do we really leverage that for ourselves? What about data that's in our smart watches, phones, finances, and other measuring devices such as digital scales? It's so exciting to give a new meaning to our studies: not only it's valuable to our careers but to apply at something that's relevant to ourselves.
	- Second, but not less important, is the inspiration for the journey itself. What started for me with specific goals, such as to manage my finances or health as I mentioned, turned out to be an infinite game where, at this point, having fun with the process matters much more than the final results.
- In the near future, I hope this talk can get a conversation rolling for members of the community that also engage in building their own insights with these tools. Who knows, maybe this even brings everyone to climb a few more steps into seeing that a Personal Data Analyst is indeed a viable profession at some point!
- I've been really excited to play around with this, and now even more with another opportunity to be at Coalesce sharing with more people to get the conversation going on. Thanks a lot for watching, and see you soon!

### Describe someone that will be excited by the topic
This presentation will be addressed to every Analyst, Data Engineer and Analytics Engineer that is excited about their work. They will find that the feeling of doing something they enjoy in their daily work can gain a new meaning when it's directed to make their lives better - whatever that may mean for them.

Attendees of all backgrounds will also be equally inspired when they see someone else's learning journey. The fact that the process can be as rewarding as the destination is one crucial takeaway!

### Why are you passionate about this topic?
Technology and self-knowledge are subjects I often spend time thinking and reading about. As I spend over 8 hours every day thinking analytically in my career, it's only natural to apply that approach to myself.

For the last 6 months, I've been developing ELT pipelines for my personal finances, tracking health indicators such as fat and muscle percentages, and comparing with fitness data from Apple Health. After losing 8kg in weight and gaining 5% muscle, I know there is still so much more to do!

### What tools and/or tech will be mentioned?
dbt, DuckDB, Meltano, Singer Taps, Superset, Evidence, GitHub

### Please select your speaking preference
I prefer to speak at Coalesce San Diego

### Interested in writing for the dbt Developer Blog?
Yes

### Notes
Everything is open to building together! If the team feels another take on the subject would be a better fit for the conference, I'm 100% open to co-creating =)

The session takes an angle of talking about the journey of learning new tools and applying them to an interesting personal context, but doesn't dive too deep into the technical side of things. If you think that would be an interesting way to go, the code (https://github.com/felippecaso/qs-mds) is inspired by mds-in-a-box and the session could be focused on building that together with the attendees.

### How large is your organization?
250 or more

### Where are you based?
São Paulo, SP, Brazil

### If selected, do you require financial support??
yes

### Are you a first-time or new speaker?
no

### Tell us about your data stack
_We'd like to know what tools and platforms your using and working with._

At Loft, we mainly work with Stitch, dbt, Databricks and Looker. There are also some proprietary applications for managing MLOps, ACL and Data Contacts. 

In this talk, though, I'll share some stuff I've been working especially with tools that didn't make sense for Loft at this time. Apart from dbt, that includes DuckDB, Meltano and Superset.

### How long have you been using dbt?
_Tell us about your or your organization's experience with dbt._

As Analytics Manager at Loft, I faced the challenge of scaling the organization's data-driven decision-making framework as the employee count soared from a few dozen to over 1,000. After struggling with various internal analytics engines, we turned in 2021 to dbt to define concepts and create a more transparent lineage. In this time, I mentored a great part of our team in the tool, and also used it for some side projects (such as the one in the center of this session).

### What was your introduction to the dbt community?
I joined dbt's Slack community in 2021 while learning and leading the tool's implementation at Loft. The community proved to be an excellent resource for sharing tips and resources, often better than the official documentation. Later, Coalesce 2021 helped to enhance our dbt skills with best practices, and Coalesce 2022 provided the opportunity to become certified and deliver my first talk at the conference!

### Please share a fun fact about yourself
I've been practicing dad jokes since I was 15 years old! The proudest moment of my career was winning a family contest against my father and uncles.

## Orientations
The video component is a fun part of our process that allows us to get a feel better feel for your ideas and session. We ask that you submit a 2-5 minute video giving a high-level overview of you In this video we want you to tell us the main idea behind your session, and what audience members will learn.

The pitch video is a great proxy for your proposed session and helps us assess proposals reliably so we can gauge and make sure to deliver on speaker support needs.

The best way to assess if my idea is the right fit for Coalesce is to consider whether your content is relevant for our attendees. Here are a few of our thoughts:
-   **Analysts:** Familiar with BI tools. May have experience with LookML and derived tables, and might not understand why they want to work like a software engineer
-   **Data engineer, Analytics Engineer:** Comfortable with git, working in the command line and writing code. Sees themselves modeling software engineering best practices. Often have a background as a data analyst, and understand the value of business context.
-   **Data Scientist, ML Engineer:** Spend most of their time working in R, Python and SQL. Used to cleaning their own data, competent in software engineering best practices and prefers to operate independently because data engineering teams and workflows usually slow them down. Will immensely benefit from access to well modeled data they can reuse in their work and an easy (CLI) interface to do this without messing up their Python environment
-   **Managers (Data Team Manager, Head of Data, Head of Analytics, etc.):** They have likely been through the trenches of poor data team practices. Maybe they have come up through a data engineering background. Attracted to reducing administrative effort and enabling analysts.
-   **Decision Makers:** CIOs, CTOs, CPOs, thought-leaders, C-suite professionals thinking about business outcomes. This person is ultimately on the hook for the success and failures of tech adoption. Has led data teams, and is vocal about new ways of work.

We are open to a number of different formats for sessions. Show us something new! Here are some ideas to get you started:

-   **Anchor talks:** Forward-looking talks establishing an underlying theme, delivering a core message that is part of setting the Coalesce tone
-   **Community talks:** Talks focused on how to solve a business problem with analytics engineering
-   **Panels:** Conversations diving into a relevant data topic led by a variety of community voices/perspectives
-   **Workshops:** Technical deep dive of tools and techniques
-   **Other:** We're open to your format ideas, too!

First and foremost, have a specific problem or closely related set of problems in mind. You should investigate or even propose a solution to these problems in a way that delivers value to the audience. You should be able to tell us about a problem, propose a solution or new way of viewing the problem, and then explain concretely how you will argue for your ideas.

Everything from a deeply technical session on custom snapshots to one about building a diverse data team is welcome at Coalesce.

Generally speaking, successful proposals come from folks who have already come up with a problem and a solution, with a narrative roadmap from start to finish. That said, be empowered to get creative with your narrative format. How you choose to tell the story is up to you!

The talk proposal you submit should demonstrate ample forethought. The more concrete you can be, the more chance your talk will make an impression on us (and audiences at Coalesce!). Don't get hung up on needing to be a superstar—we'll work with you on delivery.

We'll review each proposal based on the strength of the proposal and topic fit for Coalesce. Once we've decided on topics, we work them into an agenda, considering:

-   what timezone the speaker is based in, and whether we can fit them in on the day that best matches that timezone
-   the method the speaker will deliver their talk - virtually or in-person
-   content that's relevant to different attendees, and a variety of formats according to the day's topic focus(es)
-   whether lead talks will take place during a time of day that reaches the most attendees
-   we don't choose topics that are repetitive
-   whether we are missing out on an important topic area

## Resources
- https://coalesce.getdbt.com/call-for-proposals
- https://sessionize.com/coalesce-2023/
- [[Talk Planning - Coalesce 2022]]
- [[Talk Proposal - Coalesce 2022]]
- https://www.linkedin.com/pulse/future-jobs-personal-data-analyst-scott-stadum/?trk=public_profile_article_view
---
layout: post
title:  "Analytics Dashboard Design"
subtitle: "Redesigning a dashboard for Expense managers"
heroImage: "/res/concur/analytics/NextGen_Cover.png"
projectDescription: "Over the course of 6 months, I led an end-to-end product design through the MVP launch and first round of product iterations for a web-based dashboard that provided expense managers with data and insights into their employee’s expenses."
projectInfo:
- title: "Project Duration"
  content:
  - "6"
- title: "Responsibilities"
  content:  
  - "UX Strategy"
  - "Interaction Design"
  - "Prototyping"
  - "Usability Testing"

---
### Discovery and Strategy Planning

I began learning about our user base to identify the primary and secondary personas, an Expense manager for a company, and a department manager responsible for their team’s expenditure. I interviewed our stakeholders to understand their goals for the project and also implementation specialists that work closely with the target audience. The team was also moving towards replacing an existing legacy version of an analytics offering, this project being a pilot successor.

![Concur Intelligence, a legacy dashboard reporting tool](/res/concur/analytics/OldGen Analytics.png)
*The redesign is meant to be a successor to our legacy dashboard product which had less functionality.*

Context:
- There were no dashboard design patterns in Concur, so these had to be established.
- The entire working team was 100% remote, including the product owner.

After understanding both the business and user needs, I conducted a comparative analysis of similar dashboard offerings to better inform our design patterns and metaphors to display data.

Through the findings, I realized successful dashboards organize their data from most important to least important and from high level summaries, to detailed tables of supporting data. I gathered pain points our users had with using our older tool and focused to address them in the redesign.

![Salesforce Dashboard](/res/concur/analytics/ComparativeAnalysis_Salesforce.png)
*Salesforce offered quick drill-down ability and customizations in their dashboards.*

Together with my product owner, I consolidated and presented the underlying pain points I discovered, areas of opportunity, and design strategy around two key goals:

- Provide spend insight as a measure of health at a high level summary
- Organize data in dashboards from high level to more granular data

#### Design

I collaborated with the product owner to define rough wireframes of the look and feel of the dashboard. This was extremely helpful to begin with since developers were beginning to create the data model and back end services to power the dashboard and allowed us to communicate requirements and constraints effectively.

![Layout](/res/concur/analytics/NextGen_BalsamicMocks2.png)
*Experimenting with mixed wireframing to communicate designs quickly*

In parallel, I recommended and pushed for new dashboard UI patterns within the design organization. Our company was also aiming to be more accessible. To accommodate color blindness, I had to create a color palette for our charts that would be in line with our style guide, did not clash with existing warning or error colors, and was visually distinguishable to those that had color blindness.

![Color Study](/res/concur/analytics/NextGen_Color Ramp Intelligence.png)
*I created color palettes that would still be discernable for those with color blindness.*

### Usability Study

I assumed that the ability to discover relevant data was crucial for this dashboard to succeed. To validate if we were providing enough signifiers for discovering data and if we were showing relevant information to an Expense manager in small businesses, I partnered with a User Researcher to usability test our dashboard prototype. I uncovered 2 unexpected outcomes during this process:

1. The target audience in the small business space did not map cleanly to our persona.
The Expense manager is a clearly defined role in larger companies, but not for small and medium businesses. Smaller companies are scrappier and the role of an Expense manager may be held by various people in the company from accountants, to CEOs. Recruiting the ‘Expense manager’ became a challenging task.

2. Our participants had a higher baseline understanding of dashboard design patterns than we assumed.
60% of our participants voiced wanting the ability to customize the dashboard or export the data into Excel to further do analysis on. This caused the product team to prioritize their future releases better in anticipation of users wants and needs.

### Development

As we moved into developing the application, I provided design handoff artifacts to the remote team. However, since the team was remote, the redlines and designs were occasionally different, drop shadows and components would be just a little off but significant enough to be noticed. I realized I had to adapt my design handoff process because of this. After chatting with the developers, I tried assisting directly with SASS styling over a Zoom call in the interest of optimizing our time. We achieved more consistent designs and faster turnaround times since I spent less time redlining and developers spent less time deciphering redlines.

![Redlines for dashboards](/res/concur/analytics/NextGen_Spec.png)
*For specific patterns, I include CSS in specs to better communicate designs to developers.*

### Result and Takeaways

![Dashboards at Fusion](/res/concur/analytics/NextGen_Analytics Present.jpg)
*Amol, our Product Owner presenting designs at Fusion, our annual client conference.*

When the product released, we got a lot of positive feedback from early adopter clients that the dashboards were significantly better than the legacy dashboards. While we gathered internal and external qualitative feedback, we were not clear in defining our quantitative measures early on. While the developers were able to instrument the dashboard post launch, I would be more persistent in defining quantitative metrics at the beginning of projects to avoid losing capturing important product and UX metrics right as the product launches.

![Dashboard Patterns](/res/concur/analytics/NextGen_HIG.png)
*My initial studies led to UI dashboard components being created in house to better support accesibility needs*

Completing this project also allowed me to contribute to our growing design system with dashboard best practices, patterns, and standardized UI components that were easily consumed by other Concur products needing data visualizations. Our UI components team was able to eventually create React chart components based off my initial exploration and designs. This allowed teams to save development time creating UI components and be more aligned with our design system.

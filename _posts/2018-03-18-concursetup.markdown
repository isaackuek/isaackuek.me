---
layout: post
title:  "Concur Setup"
subtitle: "Redesigning the setup experience for Concur Standard"
heroImage: "/res/concur/concurSetup/SMN Setup After.png"
projectDescription: "I was the sole UX designer to redesign the administrator onboarding experience for Concur’s software. I worked with multiple PMs, developers, and a UX manager who provided guidance and assistance. I helped define the existing customer journey, brought in competitive analysis, and led the design process from discovery to delivery."
projectInfo:
- title: "Project Duration"
  content:
  - "18 months"
- title: "Responsibilities"
  content:  
  - "UX Strategy"
  - "Interaction Design"
  - "Prototyping"
  - "Usability Testing"
---
### Project Overview

Concur has been losing 38% of small businesses due to a lengthy and complex setup process even with the help of implementation specialists assisting them. The on-boarding process includes multiple phone calls with our specialists, 2 of which are solely dedicated to configuring settings in Concur’s admin experience.

![Concur Standard, the small business focused version of the software had a 38% attrition rate.](/res/concur/concurSetup/ClientAttrition.png)
*38% of Concur Standard customers drop out of the setup process in 2016.*



I was brought in to the project upon completion of 2 baseline usability studies

- Our users had 0% task completion rates if left on their own.
- A setting page did not exist since users were always in a setup wizard.


The project team did not share a clear understanding of what was the most minimum needed to get Concur to a live working site, and focused on just redesigning each setting page. This multi-year project has had many stakeholders come and go - leaving the working team with unvalidated assumptions of our target audience, outdated project goals, and communication difficulties.

### Challenge and Project Goals
* Reduce attrition (20% less attrition during implementation)
* Reduce implementation duration by 2 hours
* Increase Customer Satisfaction goal by 80%


![Expensify Concierge](/res/concur/concurSetup/SMN CompAnalysis Expensify.png)
*I created a competitive analysis of how our competitors were tackling setup to see their strengths and potential opportunities.*

#### Aha Moment

While designing, I realized there were a lot of steps that could be defaulted based on our configuration data. Our competitors also automate and have defaults for these settings. We also did not provide a landing page for admins to see all the settings - this was a low hanging fruit to achieve.

### Plan

I created user flows of the existing experience - and proposed to revamp the entire problem by skipping few complex portions of the setup phase and make intelligent defaults during the process backed up by data.

![User Flow: Previous and After](/res/concur/concurSetup/SMN User Flow Account Codes.png)
*Simplifying user flows for one of the setup steps.*

I created prototypes in InVision to illustrate to stakeholders how the new user flow will simplify the process.

The team accepted the proposal well but countered that there will be a lot of backend work that will have to be completed in the process and priorities will have to be shifted. I continued to generate buy in with the developers to identify ways to make ‘cheap’ intelligent defaults, generate buy in with the stakeholder team by illustrating this process will reduce setup by an hour, and was similar to how competitors were handling their setup.

I assumed the concept was very straightforward, but I learned that I had to make a case and back up a small discovery by showing the potential value and a clear execution plan in order to get buy in from the larger team.

### Usability Study

I then decided to put the new user flow into a usability test to see if the new flow fits the mental model of our users, understand more about our users, and measure their success rate. Together with a user researcher, I drafted our usability plan and created an InVision prototype to test the new concept out.

The usability study made us learn that:
- New users easily went through the improved user flow portion.
- Users were still confused by our language and used very different terminology.
- Our target audience had very different needs and wants during setup - some wanted a truly hands off experience, but some even thought our entire solution was unnecessarily complex.
- Users still had difficulty going through the complex user flow, but achieved a 80% task completion rate overall.

The study was a success, but the participants had vastly different needs despite being a small business. I assumed our target audience differed based on how big their company was: this was not entirely true - their business’ complexity and how closely they needed to manage their money determined how much set up they wanted to do. We needed to better understand our users and identify how to stratify the different user needs.

### Development

I redlined and designed edge cases for the new flow, and staged out the designs into phases because the new user flow would require substantial backend work. To deliver quick value in the short term, I prioritized implementing intelligent defaults into the product.  At this time, the product team purchased a help tool that guides users through a tour experience in the existing admin interface. I skinned and designed our help widget (Walkme), hand writing CSS to match our styles to provide a consistent experience. While it wasn’t a perfect solution, it provided a fast way to provide a guided setup experience while the development team begins implementing the newer setup designs.

![Walkme Design Concepts](/res/concur/concurSetup/SMN Walkme 1.png)

### Short Term Results

The team implemented intelligent defaults in the existing system. This experience is now automated and has a guided tour to guide new users through the existing UI while the newer interfaces were being built. There is now a setting page that admins can browse through our settings with plain english descriptions of what each setting does. Our guided tour replaces the setup wizard for the short term.

![Setup before redesign](/res/concur/concurSetup/SMN Setup Before 1.png)
*Setup before redesign*
![Setup after redesign](/res/concur/concurSetup/SMN Setup After 2.png)
*Setup after redesign*

### Long term Results

The stakeholder team has also bought into the simplified user flow vision, crucial to improving the user experience and have diverted resources to focus on the setup experience as a whole on top of redesigning individual setting pages.

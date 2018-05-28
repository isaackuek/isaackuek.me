---
layout: post
title: "Wait Staff Reviews (Google Design Exercise)"
subtitle: "Easily leave feedback for wait staff at restaurants"
projectDescription: "Google's design challenge to create a hypothetical product to allow diners to easily leave feedback for wait staff so they can use the feedback to improve and support them when getting new employment"
---

# Problem Space

---
Who is my user: Wait staff
What is their problem:
Need to get customer feedback to improve to secure new employment
No singular location to get feedback from customers since they can post anywhere


Who is my secondary user? Diners

What is their problem?

No time to leave restaurant reviews unless it's really good or really bad

Don't know the name of server to leave feedback



Problem space

Is this targeted to more personalized restaurant industries? Where the server usually announces their name?



Should the problem help separate reviews from food vs. wait staff?

*Pros:* Isolate the feedback


---


`Brainstorm and set project scope, assumptions, & success criteria`


`Interview users to validate and unpack pain points, understand current landscape, cross check against scope, assumptions and success criteria`

I had to understand the current landscape of wait staffs, the hiring process, and also how diners provide feedback to wait staffs. I began the project by interviewing wait staffs, diners, and also hiring managers at restaurants to understand their perceptions around customer feedback to compare against my assumptions.

#### Key takeaways

- Diners usually leave reviews for establishments, but rarely include specifics about servers unless they've had excellent service.

- When diners do review a restaurant, it's usually about the food or the entire dining experience.

- Wait staffs welcome feedback from customers, **but these aren't asked for during the interview process.**
> "My interview relied a lot more on my personal references and my previous knowledge with cocktails and standard Vietnamese menu items. It's really about the people you know, so that helps out a lot too." - Timmy, Pho Bac Sup Shop

- Wait staffs usually get customer feedback in person, on review websites, or on paper receipts.
> "I really appreciate it when people thank me - it makes me feel appreciated and that keeps me going, and to know that I didn't mess something up!" - Megan, Gainsbourg

- Hiring managers prioritize experience from previous jobs, menu knowledge, and personal referrals when considering candidates.
> "Normally, I'll contact their personal references and ask about their work ethic." - Jennifer, Le Petit Cochon

- Hiring managers would be open to considering positive customer feedback for servers.

I also needed to understand the current landscape of reviewing servers and restaurants through a comparative analysis of the tools that diners I talked to use:

| Product | Description |
|--|--|
|Yelp | Yelp is a local business reviewing platform. Diners post reviews about restaurants. Diners I interviewed most frequently use Yelp to find restaurants and review them. A quick search shows that a majority of reviews are about the food. There were only a handful of reviews that cited their server, and even fewer that included their server's name. (**114/800** reviews mention `server`)|
|Google Business Reviews | Google allows diners to review restaurants via a Google search or through Google Maps. Diners can rate restaurants out of 5 stars, add details, and also post photos. Reviews are focused around their experience overall, which sometimes include mention of servers - but rarely include server's names.|
|OpenTable|OpenTable helps diners make reservations for restaurants. After completing a reservation, diners get a notification to leave a review for their experience. The reviews for restaurants here are also mostly centered around the food and service, but any mention of servers are rare.|
|TripAdvisor|TripAdvisor collects reviews from diners, usually from patrons visiting an area. Adding a review on TripAdvisor provides a lot of review options. Diners can also rate the service separate from the food. (**20/159** reviews mention `server`)|


## Key findings
* Diners mostly browse reviews rather than leave reviews and even if they do, it is usually around the food and overall experience rather than about the server. It's critical to keep the review flow short and focused.
* Top three things that restaurants look for when hiring servers: previous work experience, personal references, and communication skills.
* Hiring managers and wait staff currently don't rely on customer feedback in the interview process, but would be open to leveraging it as another data point.

# Explore customer journeys and pick one
I considered the key takeaways from my interviews and comparative analysis to inform the goals of the design:

1. **Make it seamless for diners to leave feedback for their servers.**
The design needs to allow diners to leave feedback and be lightweight. The longer the review process is, the less likely it is for them to submit the review.
2. **Enable servers to curate and share their feedback with others.**
Positive feedback is important to servers and is integral to their career. How might a waitstaff be able to utilize the feedback they've accumulated when finding new opportunities?
3. **Increase adoption of using personal feedback in reviews and hiring.**
Today, hiring managers I've talked to rely a lot on personal references and previous experience when evaluating candidates. Positive customer feedback can function as an additional 'personal reference' since is a strong supporting data point to show that the server is customer-centric and performed well at their previous roles.


Narrowing the focus

- Dining experience, in tandem with restaurant review or separate? Decide. For MVP, separate and lightweight - during checkout process. Not a lot of people leave reviews so this is a more direct. Future option for restaurant managers include integration into Yelp/Google flow

How best to ask for review?
- Star rating and review? Feedback yes or no?
What was good during your service?

The profile screen:
- average star rating
- reviewers like my:
- featured comments

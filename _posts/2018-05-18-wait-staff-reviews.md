---
layout: post
title: "Wait Staff Reviews (Google Design Exercise)"
subtitle: "Easily leave feedback for wait staff at restaurants"
projectDescription: "Google's design challenge to create a hypothetical product to allow diners to easily leave feedback for wait staff so they can use the feedback to improve and support them when getting new employment"
---

# Problem Space

---
- Present and think about the design exercise as a thorough case study. Help us understand your thinking and design process.
- Focus on the problem, not just asset delivery
- Make sure to consider how best to communicate your process/thinking
- Scope out the challenge and set some constraints; innovate and be creative within those constraints.
- Consider what informed your design and how best to communicate it
- Always, always focus on the user - design for the user.
- After you design, think about yourself as the user. How was your experience using the app? Ask yourself what would you change? What are some potential future next steps to take? Any lessons learned.

- Present and think about the design exercise as a thorough case study. Help us understand your thinking and design process.

- Please carefully consider the deliverable for each design prompt, including explaining the scoping and constraints you chose. While not all prompts require hi-fi mocks, you’re welcome to extend the exercise and submit them if you believe it better illustrates your design solution.

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

Going into this design exercise, I broke down the design prompt to better understand the design need. I identified potential users based on the prompt and wrote down things I needed to research on.

[Design prompt breakdown]

## User interviews


I had to understand the current landscape of wait staffs, the hiring process, and also how diners provide feedback to wait staffs. After identifying the research questions I wanted to ask, I began the project by interviewing wait staffs, diners, and also hiring managers at restaurants to understand their perceptions around customer feedback to compare against my assumptions:

1. Diners read restaurant reviews more often than they leave reviews. There are some hurdles to reviewing restaurants.
2. Some diners would mention the server, but mostly would review the food and dining experience overall.


[Research sketch]

#### Key takeaways

- Diners rarely leave but rarely include specifics about servers unless they've had excellent service. When diners do review a restaurant, it's usually about the food or the entire dining experience.
> "I don't write Yelp reviews but would answer a quick email survey[about the dining experience] if they sent one. I don't spend more than 2-3 minutes on it though, so it has to be short." - Pennie

- Diners would be inclined to include feedback if it's timely and accessible.
> "I've had a server in Cancun ask for a review on TripAdvisor before. They're service was great and I said I'd leave a review, but I totally forgot about it when I got back to Seattle!" - Teresa

- Wait staffs welcome feedback from customers, **but these aren't asked for during the interview process.**
> "My interview relied a lot more on my personal references and my previous knowledge with cocktails and standard Vietnamese menu items. It's really about the people you know, so that helps out a lot too." - Timmy, Pho Bac Sup Shop

- Wait staffs usually get customer feedback in person, on review websites, or on paper receipts.
> "I really appreciate it when people thank me - it makes me feel appreciated and that keeps me going, and to know that I didn't mess something up!" - Megan, Gainsbourg

- Hiring managers prioritize experience from previous jobs, menu knowledge, and personal referrals when considering candidates.

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

## Design goals
I considered the key takeaways from my interviews and comparative analysis to inform the goals of the design:

1. **Make it seamless for diners to leave feedback for their servers.**
The design needs to allow diners to leave feedback and be lightweight. The longer the review process is, the less likely it is for them to submit the review.
2. **Provide multiple ways to review servers.**
For this experience to be successful, getting reviews from diners through various channels increases the likelihood of diners leaving feedback and strengthens the business case for restaurants to integrate the experience into their tools.
3. **Increase adoption of using customer feedback in reviews and hiring.**
Today, restaurant hiring managers I've talked to rely a lot on personal references and previous experience when evaluating candidates. Positive customer feedback can function as an additional 'personal reference' when servers apply for jobs in the larger customer service industry.

## Understanding the high level journey

To visualize this multiple user experience, I created a user journey map to identify where the experience transitions from restaurant manager, to server, to diner. This allowed me to identify areas where the experience needed to be focused to.

[SKETCH USER JOURNEY]

## Technical requirements & assumptions

After identifying the needs of each user, I had to decide on what platform the experience will use. I decided to design a mobile application for servers that allows them to receive notifications and share their feedback easily with others. Diners and restaurant managers interact with the service through a web browser. This allows diners to review without downloading an app and restaurant managers to perform tasks easily in their office.

## 1 of 2: The server & manager experience

I began further defining the server's first time experience interacting with the experience. Restaurant owners can add servers via an email invite.

Servers that have previously used the tool can see their previous information. In the future, they can share their diner feedback with others when getting promotions or when applying for new opportunities.

[03 Server Experience]

**Assumptions & constraints:**
* Restaurant managers would have to sign up and set up a restaurant account prior to this.
* Servers would download a mobile application and create an account. In the future, this allows them to get notifications and search for jobs in the app.
* Servers can work for multiple restaurants, which can be added via an invitation link sent by restaurant managers.
* Their reviews will be aggregated in their profile to get a full picture of diner feedback.

# 2 of 2: The diner experience

From the interviews I've gathered, there is a small window where diners have the highest tendency to leave reviews. I brainstormed many different entry points to collecting feedback. Perhaps we can send an email after they've dined? What if we sent them a simple text that they can reply with their feedback? For the initial designs, I opted for two ways to review on a receipt: a QR code, and an SMS link to the feedback. This allows for any restaurant to easily adopt and integrate the tool into their Point of Sale systems without previously having customer details.

[04 Server Experience]

[Server Mobile App]
## Lo-fi wireframes

It was important to get the content and review flow short for diners to complete, yet meaningful for servers to take action on.
While a lot of review flows for restaurants request for a star rating and comments, I opted for star ratings and a multiple choice question about the service. Diners can easily complete the survey with just a star rating and selecting things their server did well, and can always add optional comments if they feel inclined.

The flow branches into two questions depending on the rating given. If a diner were to rate the server highly, the review asks what the server did well. However, if the diner rated the server poorly, the review asks what the server could improve on.
This allows performant servers to understand what works well, and less performant servers to diagnose what they can improve on.

[Lofi Designs - New frame]

## User Testing

I created higher fidelity wireframes and converted them into an InVision prototype for guerilla usability testing with diners to see if the experience achieved the design goals I laid out.

[Short movie of the prototype]

The two goals I had for testing were:
* Diners can access the review link from either the QR code or via texting
* Understand issues and any unmet needs when diners are reviewing servers.

I gave the diners a hypothetical scenario dining at Purple Cafe with Jenna as their server, and tasked them to review their server. Depending on what the diners did, I asked them to review again with an opposite rating to their previous one. This was so that they can see the changes in the questionnaire based on the rating they gave. I had the participants vocalize what they were thinking and doing.

# Results and takeaways
Diners were able to successfully complete the review process. They were able to rate and provide feedback to the server in very short amount of time and were pleasantly surprised at the length of the review.

Some diners indicated that they would have only reviewed the server if they had an incentive to do so. One diner mentioned they would be more inclined to review if the server left a personal note thanking them.

> "But overall I enjoyed the simplicity of it and if it's that easy to review someone I would totally do it (if I had the incentive to)."

> "It's really user friendly. the QR code is really useful, too. Though I know most of my friends don't scan QR codes."

## Iteration on Designs
While the design simplified the review process, there needs to be some form of incentive when asking for reviews. I explored adding a simple '20% coupon' in the receipt when diners reviewed servers. Towards the end of the review flow, I added an email field so that diners can optionally add their email to receive the coupon.

[add pictures of better]


## Conclusions

Going through the flow as a server and diner - I think the design successfully supports servers getting meaningful reviews from diners. In the future, I would investigate how servers can best tailor the form to collect feedback they specifically are looking for.

I learned doing upfront research is both rewarding yet time consuming since it helps validate assumptions early in the process.

If I were to revisit this, I would conduct more research and usability testing with servers to better tailor the server experience to help them in job searching and getting promotions. I would also usability test the restaurant manager experience and identify how best to integrate the experience into their existing restaurant tools.

Initial design goals:
1. **Make it seamless for diners to leave feedback for their servers.**
Diners are able to quickly complete a server review after a meal, especially if provided with a small incentive. Going through the flow, the diners I usability tested with were able to complete the review process easily and quickly.
2. **Provide multiple ways to review servers.**
The diners I tested the design accessed the review link both through the QR code and texting flows. Given that QR codes require an app to scan the code, a texting flow is a safe and universal alternative. In the future, diner reviews can be collected from digital receipts.
3. **Increase adoption of using customer feedback in reviews and hiring.**
Given that I was only able to gather diners for usability testing, I would plan to test out the server and restaurant manager experience with staff from local restaurants to see if the experience is something they would consider using in reviews and hiring. In the long run, I would conduct surveys with restaurants over a set period of time to understand if the use of customer feedback is increasing.

- Dining experience, in tandem with restaurant review or separate? For the design exercise, separate and lightweight - during checkout process. Not a lot of people leave reviews so this is a more direct. Future option for restaurant managers include integration into Yelp/Google flow


How best to ask for review?
- Star rating and review? Feedback yes or no?
What was good during your service?

The profile screen:
- average star rating
- reviewers like my:
- featured comments


Adding servers to restaurants

Flow requires business owners to sign up
Create restaurant if it hasn't been created before - verification step needed
Can utilize existing Google Business or Yelp Business account to cross verify

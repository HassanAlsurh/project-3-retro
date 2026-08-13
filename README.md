# Project Sprint Retro

Now that your project sprint and presentations are complete, take some time to reflect on **how you worked**, not just what you built.

A **retro** (short for *retrospective*) is something development teams often do at the end of a sprint or project. The goal is to identify what worked well, what was difficult, and what you would change next time.

This is an **individual assignment**. Even if you worked as part of a group, your answers should reflect **your own experience**.

## Deliverable

Create a Markdown file called:

```text
retro.md
```

Complete the sections below and submit the file using the submission method provided by your instructor.

Short answers are fine, but your responses should be thoughtful and specific.

---

## 1. What went well? 

Identify **2–3 things** that went well during your project sprint.

Consider things like:

* planning
* time management
* coding
* debugging
* Git/GitHub
* communication
* dividing work
* asking for help
* learning new technology
* presenting your project

### Your response

* The plan went as I have thought it would, the implementation went as planned.
* Using console logs at every step and function I create saved me from a debugging loop
* Having Ms. Nabila lead me to checkout `reduce` was a time saver

---

## 2. What was challenging? 

Identify **2–3 things** that were difficult or did not go as planned.

For each one, briefly explain **why** it was challenging.

### Your response

* Adding cloudinary to add images, because I relied on the backend to handle to upload entierly, I faced a problem which is that I am passing the formData as Json which the cloudinary function cant handle, so I had to pass it as is without stringifying it using `Json.strigify`
* because I previously removed the `json.stringfy` I faced an error `object object` on the invite users, meaning I could not use the same routes as the create and update to invite users, I had to make entirely new routes for the invite.
* showing the last added log for the vehicle which required `reduce` which we did not focus on much during the lectures, I had to google it. 

---

## 3. What would you do differently? 

Imagine you were starting the same one-week sprint again.

What are **2 things you would change about your process**?

These should focus on how you worked rather than simply listing features you would add.

### Your response

1. Spend more time brain storming the backend 
2. Adding the invite feature from the start 
3. Adding a feature to remind the user to service the vehicle after 3 month has passed from last maintenance ( which I would need a new actegories for mainteneace items to specify which to remind the user of)

---

## 4. How did you spend your time? 

Think about where most of your project time went.

Which areas took **more time than you expected**?

Which areas took **less time than you expected**?

### Your response

**More time than expected:** on the invite because I did not prepare for it from the start on the backend

**Less time than expected:** on the front-end *except the invite*, every thing went so smoothly that I could have submitted the project by half the time

---

## 5. Your contribution 

Describe the parts of the project that **you personally worked on**.

If you worked in a group, focus on your individual contributions.

If you worked independently, describe the areas of the project where you spent most of your effort.

### Your response

    most of the time was spent on converting my plain code to use ant design which brought life to the project

---

## 6. Something you learned 

Describe **one technical thing** you understand better now than you did before starting the project.

This could be a React concept, API concept, Git workflow, authentication, debugging technique, CSS technique, library, or anything else you encountered while building your project.

### Your response

    I learnt that ant design has everything you need to design your project unlike bootstrap it actually even has internal functions to iterate though arrays even!

---

## 7. Something you would like to improve 

What is **one skill or habit** you would like to improve before your next project?

### Your response

    If I could I would want to see myself spending more time thinking things over than 

---

## 8. Your next-sprint action item 

Finish your retro with **one specific action you will take during your next project**.

Try to make this something concrete.

For example:

> I will break my MVP into smaller tasks before I begin coding.

> I will commit and push my work at least three times each day.

> I will test each feature before moving on to the next one.

> I will ask for help sooner instead of spending several hours stuck on the same problem.

### My action item

> I will brain storm the back end rather than finishing it early and having to update it multiple times throughout the project week

> I will for sure use ant design instead of wasting time on css!

> I will apply all the features in the back end at the start at first and test it then I will step up to the front-end


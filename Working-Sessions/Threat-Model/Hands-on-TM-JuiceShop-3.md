---
layout       : blocks/working-session
title        : Hands on Threat Modeling Juice Shop (New features)
type         : workshop
track        : Threat Model,Juice Shop
technology   :
related-to   : Juice Shop
when-day     : Tue
when-time    : PM-2
location     : Room-6
room-layout  : unknown
status       : done
organizers   : Adam Shostack,Bjoern Kimminich
participants : Steven Wierckx, Robert Hurlbut
---

Get together to create models (diagrams) of Juice Shop to help us find problems with it, learn threat modelling, and deliver examples.  This is all about answering the question of what Juice Shop is and building models of it.

## Why

Dinis proposed a set of evening sessions to create threat model artefacts & examples for the Juice Shop vulnerable app.

## What

- Create models/diagrams that show various aspects of Juice Shop (Model 1: What's the app?, model 2: How does it get deployed?, Model 3: How is it "developed and maintained"? etc.) 
- Apply various techniques to answer the question "what are we working on?"
- Through the course of the day, we will look at various ways to slice and model Juice Shop, with a goal of being aligned with other sessions, so you can pop in for a part of the day, and learn a bit of threat modeling.

## Outcomes

- Set of models checked in  
- Possibly also sets of requirements or assumptions

## Who

The target audience for this Working Session is:

- Participants in the threat modeling track
- Participants interested in Juice Shop
- Those who want to learn to threat model

--- 

## Working materials

* Juice Shop Staging Environment: <http://juice-shop-staging.herokuapp.com>

### Content

[![](https://raw.githubusercontent.com/OWASP/owasp-summit-2017/master/Working-Sessions/Threat-Model/whiteboard-photos/PM-2-Picture-1.jpg)](https://raw.githubusercontent.com/OWASP/owasp-summit-2017/master/Working-Sessions/Threat-Model/whiteboard-photos/PM-2-Picture-1.jpg)
[![](https://raw.githubusercontent.com/OWASP/owasp-summit-2017/master/Working-Sessions/Threat-Model/whiteboard-photos/PM-2-Picture-2.jpg)](https://raw.githubusercontent.com/OWASP/owasp-summit-2017/master/Working-Sessions/Threat-Model/whiteboard-photos/PM-2-Picture-2.jpg)

### Synopsis and Takeaways

This session discussed the current and in development features of Juice Shop. The focus was on an in development feature, called Two-Factor-Authentication. Ideally using TOTP technology (One time password) in the authentication process. A diagram was created on this. An additional sequence diagram was created on how data interacts with a user in Two-Factor-Authentication.

Other features such as Invoice tracking, delivery and email services are also discussed. Potential publishing a cheat sheet of does and don’ts when using Data flow modelling.

Outcomes
- Created a sequence diagram of Two-Factor-Authentication information.
- Created a data flow diagram on new and improved features for Juice Shop.
- The architectural possibilities highlighted in the discussion allow new features to be added.
- A Cheat Sheet of does and don’ts when using Data flow modelling to be created.
- “Juice Shop left overs” (product) to be picked up by a 3rd party for recycling and compost.
- To create a feature for Invoice tracking, for the accounting team using a separate UI dialog, in juice shop that will use XML or CSV files.
- A diagram that could be extended into a fully reusable threat model. This will become the final published product.

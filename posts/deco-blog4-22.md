---
title: Designing for Trust Rather Than Transactions
date: 2026-04-22
author: zhenhua Ding
summary: Short description
tags:
  - tag1
  - tag2
  - tag3
---
Write your content here.
By Week 8, the direction of the BlaBla platform became significantly clearer. Earlier discussions focused broadly on creating a community-based used car platform, but this week forced a more important question: what problem are we actually solving that existing marketplaces do not already solve?

Platforms such as Facebook Marketplace and CarsGuide already succeed at facilitating transactions efficiently. They provide visibility, listings, and communication between buyers and sellers. Attempting to replicate all of those features would likely lead to feature overload and unrealistic development scope within the constraints of this project. More importantly, reproducing marketplace functionality does not create meaningful differentiation.

This led to a shift in how I interpreted the functional requirements of the application.

Rather than prioritising transaction support, I began treating trust and decision-making support as the platform’s primary functional goals. The core requirement is no longer “users can buy and sell cars”, but instead:

users can evaluate credibility and reduce uncertainty before making decisions
users can access community-generated ownership insights
sellers can make more informed pricing decisions based on real market context

This distinction changed several design priorities.

Initially, I considered implementing direct messaging and negotiation tools between buyers and sellers. However, after evaluating feasibility and relevance, I decided these features were secondary. Messaging systems introduce additional complexity including moderation, notification systems, privacy concerns, and data handling requirements. More importantly, they do not directly address the main issue identified in the brief: lack of confidence in the used car journey.

Instead, I prioritised features that support knowledge-sharing and transparency. For example, structured owner reviews, discussions around common faults, maintenance experiences, and pricing references are more aligned with the platform’s purpose as a community resource rather than a transactional marketplace.

This decision also influenced technical thinking. A marketplace-oriented system would likely require more complex real-time interactions and transactional workflows. By narrowing the scope toward community knowledge and decision support, the application architecture can remain more achievable while still delivering meaningful user value. From a development perspective, this creates a better balance between ambition and feasibility.

Another major consideration this week was accessibility. Initially, AA compliance felt like an external requirement imposed onto the project. However, I increasingly see accessibility as directly connected to trust and usability rather than simply legal compliance.

The audience for used cars is broad and includes users with varying levels of digital literacy, language backgrounds, and physical ability. If important information is difficult to read, navigate, or interpret, the platform fails at its primary purpose of helping users make informed decisions.

As a result, accessibility considerations began influencing interface planning earlier in the design process rather than being treated as a final testing step. For example, information-heavy sections such as ownership reviews and pricing insights will need strong visual hierarchy, readable typography, keyboard accessibility, and clear navigation structures. These decisions are not only about compliance, but about ensuring users can confidently interpret information without unnecessary friction.

Looking ahead, I plan to evaluate whether the platform genuinely improves user confidence rather than simply increasing interaction. This means usability testing should focus on whether users feel more informed and capable of making decisions after using the platform. Measuring “trust” may ultimately become more important than measuring engagement alone.

Overall, Week 8 marked a transition from thinking about features individually to thinking more critically about where the application’s real value exists.
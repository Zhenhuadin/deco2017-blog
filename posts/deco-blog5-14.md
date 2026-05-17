---
title: Testing Trust Rather Than Just Functionality
date: 2026-05-14
author: zhenhua Ding
summary: Short description
tags:
  - tag1
  - tag2
  - tag3
---
Write your content here.
This week’s lecture on testing and analytics fundamentally changed how I think about evaluating the BlaBla platform. Previously, I mainly viewed testing as a technical process focused on checking whether features worked correctly. However, the lecture introduced a more important distinction between testing mechanical correctness, evaluating user experience, and observing real user behaviour over time.

This became especially relevant because the core purpose of BlaBla is not simply enabling interactions, but helping users make more confident and informed used car decisions.

One of the most important ideas this week was that “a design is alive as long as someone is using it.” This shifted my thinking away from treating the prototype as something that eventually becomes “finished.” Instead, the platform should be evaluated continuously based on whether users can actually understand and trust the information presented to them.

Initially, I assumed successful testing mainly meant confirming that routes, forms, and database interactions worked correctly. While technical correctness is obviously necessary, the lecture highlighted that a technically functional system can still completely fail from a user perspective.

For example, a review system may save information correctly while users still struggle to compare ownership experiences or identify trustworthy advice. This reinforced an earlier concern within the project: information organisation and readability are just as important as technical implementation.

As a result, I started thinking more carefully about what kinds of testing are actually appropriate for the platform.

The lecture discussed different levels of testing, ranging from paper prototypes and “Wizard of Oz” testing to integration tests and accessibility reviews. One particularly useful insight was the idea that designers should choose “the cheapest test that answers the question.”

This changed how I think about evaluating early design decisions.

For example:

If the question is whether users understand the structure of vehicle reviews, paper testing may be sufficient.
If the question is whether navigation flow feels intuitive, a simple clickable prototype or static HTML page may be enough.
Only later does it become necessary to test integrated backend behaviour.

This approach feels more realistic within the project’s constraints because it prioritises learning efficiently rather than overbuilding features before validation.

Accessibility testing also became much more concrete this week. The lecture emphasised that automated tools alone are insufficient for AA accessibility compliance. This is particularly important for BlaBla because the platform depends heavily on users interpreting large amounts of text-based information.

As a result, accessibility evaluation should include:

keyboard navigation
screen reader compatibility
visual hierarchy
readability of ownership insights
colour contrast and layout clarity

Another major reflection involved analytics and ethical data collection.

The lecture strongly argued against collecting unnecessary user data simply because it is technically possible. This directly relates to the platform because used car discussions and ownership experiences may contain sensitive personal or financial information.

Initially, I considered tracking detailed user interactions to measure engagement. However, I now think the platform should follow a data minimisation approach. Instead of collecting excessive behavioural tracking, analytics should only support clearly defined decisions, such as identifying whether users struggle to locate important ownership information.

Overall, Week 11 helped me realise that evaluating a platform like BlaBla is not only about verifying whether features work, but whether users can confidently interpret information, trust the system, and make informed decisions without unnecessary friction.
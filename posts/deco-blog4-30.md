---
title: Refining the Platform Through Data Design
date: 2026-4-30
author: zhenhua Ding
summary: Investigating how structured data models, categorised ownership insights, and clearer information architecture can improve usability, trust, and decision-making while balancing openness with consistency and scalability.
tags:
  - tag1 Data Modelling
  - tag2 Information Architecture
  - tag3 Usability
---
Write your content here.
This week’s lecture focused on “Designing Data” and highlighted how data modelling should evolve alongside the application itself rather than being treated as a purely technical task. This became particularly relevant to the BlaBla project because the platform’s direction has gradually shifted from functioning as a standard used car marketplace toward becoming a community-driven decision support platform.

Earlier in development, I mainly thought about data in terms of storing features — users, reviews, listings, and comments. However, this week made me reconsider how the structure of data directly affects usability, trust, and decision-making.

One of the most important insights was recognising that unstructured information can quickly become overwhelming. Initially, I imagined the platform operating similarly to an online discussion forum where users could freely post ownership experiences and opinions about vehicles. While this approach encourages participation and openness, it also creates problems around consistency, readability, and comparison.

For a platform designed to reduce uncertainty in used car purchasing, this could become counterproductive.

As a result, I began reconsidering how ownership experiences should be organised within the system. Instead of treating reviews as completely free-form discussions, they could be structured around categories such as:

reliability
maintenance costs
fuel efficiency
recurring mechanical issues
seller communication quality
long-term ownership satisfaction

This became a significant design decision because it changes how users interact with the platform. Rather than browsing large amounts of disconnected conversation, users would be able to compare experiences more efficiently and identify useful patterns between similar vehicles.

There are clear trade-offs involved in this approach. Structured systems improve searchability, filtering, and consistency, but they can also reduce spontaneity and make interactions feel more restricted. However, after reflecting on the project’s functional requirements, I concluded that improving clarity and interpretability is more valuable than maximising unrestricted interaction.

This week also reinforced the importance of iterative refinement within the development process. The lecture timeline specifically emphasised reviewing and restructuring data models during Sprint 2 as understanding of the project evolves. This aligns closely with the current state of the project because many earlier assumptions are now being revisited as the platform becomes more concrete.

Another important consideration involved feasibility.

Earlier ideas included AI-generated recommendations and advanced pricing prediction systems. Although these features initially appeared attractive, they now seem less aligned with the project’s primary purpose. Complex recommendation systems may introduce additional technical overhead while also reducing transparency if users cannot understand how decisions are generated.

Instead, simpler comparative pricing information based on community contributions and recent market examples appears more achievable and easier for users to trust critically.

This week also helped me understand that data modelling is closely connected to user experience design. Decisions about what information users can submit, how content is categorised, and how relationships between entities are structured all influence whether the platform feels trustworthy and usable.

Overall, Week 9 marked an important shift from thinking about features individually toward thinking more critically about how information should be organised to support confidence, clarity, and informed decision-making.
---A3reflection
title: "A3 Reflection EazyCars: Evaluating a Community-Driven Platform for Used Car Decision Support"
date: 2026-06-8
author: zhenhua ding
summary: This final reflection evaluates the development of EazyCars, a community-driven platform designed to support informed used car decisions. Throughout the project, the focus shifted from building a traditional marketplace toward creating a trusted source of ownership experiences, pricing insights, and community knowledge. The reflection examines the application's performance, user experience, accessibility, and functional requirements, while also discussing key lessons learned about project scoping, information design, and trust-centred development. Ultimately, the project demonstrated that successful web applications are not defined solely by their features, but by their ability to help users make confident and informed decisions.
tags:
  - Reflection
  - tagUser Experience
  - Decision Support
---



Throughout the development of EazyCars, my understanding of the project evolved significantly. Initially, I approached the application as a community-based used car marketplace that would allow users to browse vehicles, share reviews, and interact with other users. However, as the project progressed and through the weekly reflections completed during the semester, I gradually realised that the platform's real value did not lie in facilitating transactions. Instead, EazyCars became a decision-support platform designed to reduce uncertainty and increase trust within the used car purchasing journey.

This final reflection evaluates the performance of the application, its user experience and accessibility, the lessons learned during development, and how the final outcome compares with the original functional requirements.

## Performance and Technical Behaviour

From a technical perspective, EazyCars performed reliably within the scope of the project. The application uses a relatively simple architecture built around TypeScript, HTMX, SQLite, and server-side rendering. One advantage of this approach was that it kept the application lightweight and responsive. Most pages loaded quickly because the system did not rely heavily on client-side JavaScript frameworks or large external dependencies.

The vehicle listing pages, search functionality, and "My Garage" features responded consistently during testing. Database operations such as creating, editing, and viewing vehicle listings worked reliably, and users were able to navigate between pages without noticeable delays. The use of HTMX also reduced the need for full page refreshes in several interactions, contributing to a smoother user experience.

However, evaluation also revealed several limitations. The current search functionality is relatively basic and may become less effective as the amount of stored vehicle data grows. Similarly, image uploads and listing management have not been extensively optimised for larger-scale usage. While these issues were not significant within the scope of the prototype, they would likely become more noticeable in a production environment with a larger user base.

Another important insight was that technical performance influences user trust. Earlier in development I primarily focused on ensuring that features worked correctly. However, later reflections on deployment and testing helped me recognise that reliability, responsiveness, and stability are also important parts of user confidence. A technically functional platform that feels slow or inconsistent can still create uncertainty for users. As a result, performance should be viewed not only as a technical requirement but also as part of the overall user experience.

## User Experience and Accessibility

User experience became one of the most important considerations throughout the project. During the planning phase, I initially focused on implementing features commonly associated with online marketplaces. However, as the project evolved, I became more interested in how information could be presented in ways that support decision-making and reduce uncertainty.

One of the strengths of EazyCars is its relatively simple navigation structure. Users can browse listings, view vehicle information, manage their own vehicles through My Garage, and access ownership-related content without needing to learn complex workflows. The interface prioritises information clarity over feature density, which aligns with the project's goal of helping users make informed decisions.

At the same time, evaluating the platform highlighted several usability challenges. Vehicle information, reviews, and ownership experiences can quickly become overwhelming if presented as large blocks of unstructured content. Earlier in development I assumed that allowing users to freely share experiences would maximise community value. However, reflection and testing suggested that users benefit more when information is organised into structured categories such as reliability, maintenance costs, fuel efficiency, and ownership satisfaction. This finding reinforced the idea that usability depends not only on interface design but also on information architecture.

Accessibility also became increasingly important throughout development. Initially, accessibility felt like a requirement that existed alongside the project. Over time, I came to view accessibility as directly connected to trust and usability. The audience for used cars includes people with different levels of digital literacy, language backgrounds, and physical abilities. If important information is difficult to navigate or interpret, the platform fails to achieve its purpose.

As a result, accessibility considerations influenced design decisions such as readable typography, clear visual hierarchy, semantic page structure, keyboard navigation, and colour contrast. While the prototype does not fully satisfy every accessibility consideration, the development process demonstrated that accessibility should be integrated into design decisions from the beginning rather than treated as a final compliance check.

## Critical Reflection and Improvement Planning

One of the most significant lessons learned during development was the importance of project scope. At the beginning of the semester, I considered implementing a range of advanced features including direct messaging, negotiation tools, AI-generated recommendations, and complex pricing systems. These ideas initially appeared attractive because they resembled features found in commercial platforms.

However, as development progressed, I realised that adding more functionality does not necessarily improve user value. Many of these features would have increased complexity without directly addressing the core problem identified by the project. For example, messaging systems introduce moderation, privacy, and notification challenges, while AI recommendations may reduce transparency if users do not understand how decisions are generated.

Instead, I learned that successful design often involves deciding what not to build. Narrowing the focus toward community knowledge, ownership experiences, and decision support resulted in a more achievable and coherent platform.

If development were to continue, my highest priority would be improving the way ownership experiences are collected and presented. Structured review systems, credibility indicators, and comparative pricing references would provide additional value while remaining aligned with the project's goals. I would also expand usability testing to better understand how users interpret information and where confusion occurs during decision-making.

Perhaps the most important lesson from the project is that trust should be treated as a design objective rather than an outcome. Every decision involving interface design, information structure, accessibility, deployment, and testing ultimately influences whether users feel confident using the platform.

## Retrospective Assessment of Functional Requirements

Looking back at the original functional requirements, some assumptions proved to be more realistic than others. The project successfully implemented core functionality including vehicle listings, user-generated content, browsing, and vehicle management features. These functions support the platform's basic purpose and provide a foundation for future development.

However, evaluating the finished prototype revealed that some original assumptions were overly broad. Initially, I viewed EazyCars as a community marketplace that would support buying and selling activities. Through development and reflection, it became clear that competing directly with established marketplaces was neither realistic nor necessary.

Instead, the most valuable aspect of the platform emerged as its ability to support informed decision-making. Community knowledge, ownership experiences, pricing transparency, and credibility information became more important than transactional features. As a result, some requirements that initially seemed important became less relevant, while other priorities emerged that were not fully recognised during the planning stage.

This reassessment demonstrates how requirements should evolve as understanding of users and project goals improves. Rather than viewing changes as failures to follow the original plan, I now see them as evidence of a more informed design process. The final version of EazyCars differs from the original concept in several ways, but it is ultimately more focused, achievable, and aligned with the problem it aims to solve.

## Conclusion

Overall, the development of EazyCars shifted my perspective from building features toward designing for trust. Technical implementation, user experience, accessibility, deployment, and testing all contributed to a broader understanding of what makes a web application valuable. The project demonstrated that successful web development is not simply about creating functional systems, but about creating systems that users can understand, trust, and use confidently. While there are many areas that could be improved with additional time, the final prototype represents a meaningful step toward supporting better decision-making within the used car community.


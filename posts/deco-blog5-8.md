---
title: Deployment Decisions and Responsible Integration
date: 2026-05-8
author: zhenhua Ding
summary: Evaluating deployment strategies, API integrations, authentication methods, and security considerations to better understand the trade-offs between functionality, scalability, maintainability, and responsible system design.
tags:
  - tag1 Deployment
  - tag2 API Integration
  - tag3 Security
---
Write your content here.
This week’s lecture focused on deployment, external integrations, and API usage, which significantly changed how I think about the BlaBla platform beyond local development. Up until this point, most design decisions were centred around functionality and user experience. However, this week highlighted that deployment choices, API integrations, and security practices are also directly connected to the reliability and trustworthiness of the application.

One of the most important reflections this week involved hosting and deployment strategy.

Initially, I mostly viewed deployment as a final technical step after development was complete. However, the lecture demonstrated that deployment decisions influence feasibility, scalability, and maintenance from the beginning of the project. The comparison between self-hosting, static hosting, and serverless infrastructure made me reconsider what level of complexity is actually appropriate for this prototype.

For example, self-hosting initially sounded appealing because it offers greater control. However, after learning about issues such as dynamic IP addresses, CGNAT limitations, bandwidth constraints, and security risks associated with port forwarding, it became clear that self-hosting would introduce unnecessary complexity and risk for this project.

Instead, platforms such as Vercel or Netlify appear more suitable because they reduce infrastructure management while supporting rapid deployment and testing. This aligns more effectively with the project scope and allows development effort to remain focused on user experience and core functionality rather than server maintenance.

Another important area this week was API integration.

The lecture introduced APIs as systems that allow applications to communicate with external services rather than only responding to browsers directly. This made me reconsider some earlier feature ideas for the BlaBla platform, particularly around pricing references and vehicle information.

At first, I considered manually storing all pricing information within the platform itself. However, this approach would quickly become difficult to maintain and may reduce accuracy over time. API integration potentially offers a more sustainable solution by allowing the application to retrieve updated external data dynamically.

At the same time, the lecture also highlighted practical limitations such as rate limits, quotas, and API costs. This created an important trade-off between functionality and sustainability. While integrating multiple APIs could make the platform feel more advanced, excessive reliance on external services may introduce instability, additional complexity, and performance issues.

As a result, I began thinking more critically about whether every feature truly requires real-time external data. Simpler cached or periodically updated information may provide a better balance between usefulness and technical feasibility. The discussion around caching and batch queries particularly reinforced the importance of reducing unnecessary API requests.

Security and responsible development also became more concrete this week.

The lecture’s discussion about API authentication, secret management, and the risks of committing API keys to public repositories highlighted how even small development mistakes can create serious vulnerabilities. For a platform intended to build trust around financial decisions, protecting user data and external credentials is especially important.

This connects strongly to LO3 because ethical and professional responsibilities are not separate from development decisions — they directly influence whether users can trust the platform.

Overall, Week 10 shifted my perspective from thinking purely about features toward thinking more holistically about deployment, scalability, integration, and responsible system design.
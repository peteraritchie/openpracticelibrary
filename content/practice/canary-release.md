---
title: Canary Release
subtitle: Early warnings
date: 2018-12-18T19:00:46.071Z
authors:
  - valyonchev
area: options
perspectives:
  - product-ownership
people: 2+
time: 2+ hours
difficulty: moderate
participants:
  - DevOps Team
---
## What is it?

In software development, this is a form of Continuous Delivery in which only a small part of the real users of a product will be exposed to the new version of the product. The team would observe for regressions, performance issues and other adverse effects and can easily move users back to the working old version if issues are spotted. 

Canary Release is similar to A/B Testing in the sense that it is only exposing a part of the population to the new feature, but unlike A/B Testing, the new feature can and is typically a completely new feature and not just a small tweak of an existing one. The purpose is different too as A/B Testing is looking to improve the product performance in terms of getting business outcomes, while the Canary release is focus entirely on the technical performance. 

Canary Release is similar to the Dark Launch as they both expose only part of the population to a feature. The Dark Launch is focused on understanding the way users will react and use the new feature, while Canary Release is really focused on the technical performance of the changed product or the individual feature (if using a it can be isolated in the architecture).



The term comes from the use of caged birds in coal mines to discover the build of dangerous gases early on as the gases would kill the bird long before they become life threatening for the miners. As the canary, this release provides an early warning mechanism for avoiding bigger issues. 



## Why use it?

This is a feedback loop practice, which allows the team to get prompt feedback from real life use of their changes. It enables the Continuous Delivery. 

The Canary Release provides continuous delivery teams with safety by enabling them to perform a phased roll-out, gradually increasing the number of users on a new version of a product. While rolling out the new version, the team will be closely monitoring the performance of the platform and try to understand the impacts of the new version and assess the risks for adverse effects as regressions, performance, even downtime. This approach allows the team to “roll-back” the release as soon as such adverse effects are observed without the majority of the customers being impacted even for a limited amount of time.



## Related Practices

Feature toggles are an enabling practice, which allows for Canary Releases to be implemented in existing products. 

Feature Toggles

Dark Launches 

Blue/Green Deployment

Continuous Delivery



## Further information

Blue-green Deployments, A/B Testing, and Canary Releases

http://blog.christianposta.com/deploy/blue-green-deployments-a-b-testing-and-canary-releases/

Canary Release https://martinfowler.com/bliki/CanaryRelease.html
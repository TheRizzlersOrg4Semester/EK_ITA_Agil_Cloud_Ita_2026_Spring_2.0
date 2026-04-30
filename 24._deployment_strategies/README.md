# Deployment Strategies, Orchestration & Maintenance

Today we look at how to get your system into production reliably and keep it running. The outcome should be that your group has a clear understanding of deployment strategies, knows what orchestration is and why it matters, and has reflected on what it means to maintain a system over time.

## Learning Goals

- Understands the difference between mutable and immutable infrastructure and why immutable is preferred.
- Knows different deployment strategies (blue-green, canary, rolling updates) and how they work.
- Understands the concepts of fault tolerance, redundancy, and scalability.
- Understands the concept of orchestration and can argue for the importance of it.
- Knows what load balancing is and can give an example of how it is configured.
- Understands what maintenance entails and what it means to design a system for maintainability.

## Before Class

Think about how your group currently deploys your application. What happens to your system while a new version is being deployed?

## Todays Teachings

We start by looking at how infrastructure and configuration is deployed:

* [Deploying Infrastructure and Configuration Management](02._deploying_infrastructure_configuration_managment.md)

Then we look at the different strategies for deploying your application:

* [Deployment Strategies](03._deployment_strategies.md)

Followed by a look at orchestration and how it ties everything together:

* [Orchestration](04._orchestration.md)

Finally, we look at what happens after deployment — maintaining a system in production:

* [Maintenance](08._maintenance.md)

## After Class

* [Exercise: Consider a Deployment Strategy](consider_a_deployment_strategy.md)
* [Exercise: Service Level Agreement](service_level_agreement.md)
* [Exercise: Definition of Done](definition_of_done.md)
* [Optional Exercise: Take Down Your System](take_down_your_system.md)

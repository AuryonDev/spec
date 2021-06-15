# Auryon's spec

Auryon's technical specifications, and design guidelines.

# General Design Philosophy

The guiding philosophy as to why Auryon is desgined as a microservice stems from the desire for scalability. The hope is to enable end users to be able to scale Auryon to whatever lengths they wish. If they wish to run it on a one machine, or 300 hundred, it should be able handle that.

# Technical Specifications

## Gateway

The gateway's job is simple, be a gateway to all other microservices, while implementing a compatible trakt api. What this means is that the gateway must meet all technical specifications [designated here](https://trakt.docs.apiary.io/#) to be compatible with trakt's existing ecosystem.

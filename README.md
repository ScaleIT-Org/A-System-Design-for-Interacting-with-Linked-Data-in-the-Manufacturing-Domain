# A-System-Design-for-Interacting-with-Linked-Data-in-the-Manufacturing-Domain

<img src="https://github.com/ScaleIT-Org/A-System-Design-for-Interacting-with-Linked-Data-in-the-Manufacturing-Domain/raw/master/images/UI.png" width="80%"/>

<img src="https://github.com/ScaleIT-Org/A-System-Design-for-Interacting-with-Linked-Data-in-the-Manufacturing-Domain/raw/master/images/evaluation.png" width="80%"/>

### Abstract

Through strong progress in sensor technology in recent years, the amount of data produced by IIoT devices has rapidly increased.
This data provides new opportunities for companies, who know how to solve the new data challenges. One of the promising solutions is Linked Data.
While Linked Data principles are already heavily established on the web, manufacturing environments still lack mature solutions for many use cases.

This thesis documents the approach of using a container-based micro-service architecture to design and implement a Linked Data acquisition and visualization architecture.
The goal of the architecture was to publish and connect Linked Data from different sources and to provide a generalizable application interface(API) for users that hides the complexity of the underlying System. 

The main goal was to allow easy integration of web-based Linked Data-driven apps and graph visualization apps to support complex workflows.
As a proof of concept four example applications have been developed that make use of the generalizable API. 
The focus of the architecture design was to ensure the principles re-usability, fault isolation and resilience of individual components.
After design and implementation, the architecture with its overlaying app-interface has been tested and evaluated in a user study.

## Architecture 

##### Architecture Design

<img src="https://github.com/ScaleIT-Org/A-System-Design-for-Interacting-with-Linked-Data-in-the-Manufacturing-Domain/raw/master/images/shopfloor_app_arch.png" width="50%"/>

##### Apps - The architecture building blocks

<img src="https://github.com/ScaleIT-Org/A-System-Design-for-Interacting-with-Linked-Data-in-the-Manufacturing-Domain/raw/master/images/app_anatomy.png" width="50%"/>

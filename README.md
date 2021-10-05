# Testing-REST-APIs-with-Newman

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.

A Brief Introduction
=====================
REST APIs have become a quasi-standard, be it to provide an interface to your application processes, be by setting up a flexible microservice architecture. Sooner or later, you might ask yourself what a proper testing schema would look like and which tools can support you. A toolset that helps us with this task is Newman and Postman, which I will present to you in this blog post.

Many of you, who are regularly using and developing REST, might already be quite familiar with Postman. It’s a handy and comfortable desktop tool that comes with some excellent features (see below). Newman, instead, is a command-line agent that runs the previously defined requests. Because of its lean interface, it can be used in several situations, for instance, it can be easily integrated into testing stages of Pipelines.

In the following, We will explain how these siblings can be used to implement a neat testing environment. We start with Postman’s feature sets, then move on to the ability to interact with Newman. We will further have a look at a testing schema, touching some test cases, and lastly, integrate it into a Jenkins pipeline.

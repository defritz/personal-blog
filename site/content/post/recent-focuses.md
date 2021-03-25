+++
author = "Derek Fritz"
title = "Recent Focuses"
date = "2021-03-25"
description = ""
hideComments = "true"
tags = ["programming", "web development"]
+++

It's been a while since I've posted an update, so I thought I'd go ahead and review some of my development goals recently. I've been investing some time to get more
familiar with a variety of technologies that I'm interesting in pursuing long-term. As I strive to become a better web developer, I aim to build up my toolkit of
languages and development tools.

### Containers ###

I love containers. I think they're novel and incredibly effective when applied in the right way. At my current position, we use containerized dev environments to
ensure we always have access to the same resources with the latest updates.

While I have primarily been a *consumer* of containers, I've been trying to containerize some of my own applications recently. For this, I utilized docker-compose
to configure individual containers for the different layers of my project (build, application, persistence) and then deployed the resulting container images
to AWS ECR (Elastic Container Registry). I was then able to deploy my containers to AWS ECS (Elastic Container Service) in their own Fargate containers.

This was a great project for me, as it helped my gain a better understanding of not only *how to use* containers, but also how to build container myself.

### AWS ###

This is a big area of study for me recently, as it also pertains to my professional work. I've worked with several AWS services in the past for small projects, but largely
avoided any complex configurations or inter-service integrations. Lately I've been focusing on the AWS ecosystem holistically, discovering the common service combinations and
how they communicate with one another.

Several AWS services I've been looking more closely into are these:

* [CloudFormation](https://aws.amazon.com/cloudformation/) - A programmatic way to configure and deploy applications (Infrastructure as Code)
* [CodeBuild](https://aws.amazon.com/codebuild/) - An AWS-managed build service (CI)
* [CodePipeline](https://aws.amazon.com/codepipeline/) - An AWS-managed deployment service (CD)
* [ECS](https://aws.amazon.com/ecs/) - A container orchestration service with multiple deployment form factors (I've focused on Fargate)
* [RDS](https://aws.amazon.com/rds/) - A fully managed relational database service
* [API Gateway](https://aws.amazon.com/api-gateway/) - The "front door" for your public-facing applications in API

I've set up some basic applications utilizing these services in AWS myself to familiarize myself with the standard workflow and integration points. AWS is a *giant* ecosystem,
so I hope to continue discovering better ways to leverage the features they provide.

### React ###

React is obviously immensely popular in the current market, so it's a library I feel is a necessity to become somewhat familiar with at least. I've used alternative frontend
frameworks, such as Polymer and Vue.js, which has given me some foundational experience to work with.

I haven't developed anything major with React quite yet, but I have put together a simple form-based webpage with input validation and a mocked call to an external service.
This was a fairly straightforward day-project which gave me some insight into the way React handles component composition and state management.

### The Never-Ending Process ###

Continually learning more about the tools and languages in the industry will always be a goal of mine. At the same, it's impossible to become an expert in every tech stack.
I believe it's important to refresh your knowledge bank every now and then in order to maintain a broad perspective. This can help you approach problems in a more nuanced
and efficient manner than if you specialized in a few areas.

I plan on continuing my journey to becoming a wiser web developer throughout this year, hopefully finding exciting ways to apply my new knowledge and experience. Until next
time, learn something new and stay sharp!

{{< css.inline >}}
<style>
.canon { background: white; width: 100%; height: auto;}
</style>
{{< /css.inline >}}

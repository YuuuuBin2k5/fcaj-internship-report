---
title: "Event 1"
weight: 1
chapter: false
pre: "<b>4.1. </b>"
---

# Event Report: First Cloud AI Journey Community Day

### Event information

* **Event:** First Cloud AI Journey: Community Day 31/10
* **Date and time:** 31 October — year and time to be confirmed.
* **Location:** To be confirmed.
* **Role:** Attendee.
* **Video:** [First Cloud AI Journey: Community Day 31/10](https://www.youtube.com/watch?v=qRSxBAPYttM) on the AWS Study Group channel.

### Event objectives

The event featured sessions on learning AWS, internship experience, and software development topics including AI, serverless applications, asynchronous processing, and open-source contributions.

### Speakers

* **Minh Tuấn:** An AWS learning path for beginners.
* **Đức (Henry):** Applying AI in the software development process.
* **Khanh Duong:** Internship experience and building a web game.
* **Thịnh Nguyễn:** Introduction to AWS Lambda Web Functions.
* **Luong Cam Dao:** Asynchronous processing with Amazon SQS.
* **Hưng Trần:** Open-source contribution experience.

### Key highlights

#### Learning AWS

The opening session suggested combining AWS Skill Builder for fundamentals, community labs for practice, and AWS Builder Center for reading and sharing. Learners were encouraged to document errors and lessons after each lab. ([Watch from 02:17](https://www.youtube.com/watch?v=qRSxBAPYttM&t=137))

#### AI in software development

The speaker discussed using AI for code review and automating development tasks. The team uses end-to-end tests, screenshots, or videos to check changes and runs tasks such as linting and migrations on a shared server. ([Watch from 38:06](https://www.youtube.com/watch?v=qRSxBAPYttM&t=2286))

#### Building a web game

Khanh Duong discussed building a multiplayer game with Lambda, DynamoDB, SQS, and EventBridge. The session covered processing simultaneous game completions, IAM permissions, and infrastructure management with AWS CDK. Challenges in the project showed why reviewing service documentation and configuration matters. ([Watch from 52:29](https://www.youtube.com/watch?v=qRSxBAPYttM&t=3149))

#### AWS Lambda Web Functions

This session introduced running HTTP applications on Lambda and handling multiple concurrent requests in one environment. The demo showed a personality quiz website; the speaker also discussed cold starts and costs when an application waits for another service. ([Watch from 1:20:17](https://www.youtube.com/watch?v=qRSxBAPYttM&t=4817))

#### Asynchronous processing with Amazon SQS

Luong Cam Dao presented an API that took a long time to generate content. The proposed solution placed work in an SQS queue, returned a pending status, and processed it later. The session also covered Standard and FIFO queues, visibility timeout, long polling, and dead-letter queues. ([Watch from 1:42:19](https://www.youtube.com/watch?v=qRSxBAPYttM&t=6139))

#### Open-source contributions

The final session discussed starting with suitable issues, writing clear pull requests, and contributing consistently. The speaker also suggested following AWS updates to find contribution opportunities in projects such as AWS CDK. ([Watch from 2:04:53](https://www.youtube.com/watch?v=qRSxBAPYttM&t=7493))

### Key takeaways

* Combining theory, labs, and notes about errors can make AWS services easier to understand.
* SQS can separate incoming requests from background processing; retries and failed messages also need attention.
* IAM permissions should match each component's needs, while infrastructure as code can support consistent deployment.
* AI-assisted changes still need testing and review before being incorporated into a project.

### Applying the knowledge

As I continue studying backend development on AWS, I plan to explore SQS for longer-running tasks and how to inspect logs when processing fails. I can also start exploring open source through a small issue, read the contribution guide, and reproduce the problem before proposing a change.

### Event experience

The sessions gave me another perspective on learning AWS through labs and practical projects. The SQS discussion was particularly relevant to my backend studies because it can be used for work that does not need to finish within a single request.

### Event photos

Check-in photo to be added.

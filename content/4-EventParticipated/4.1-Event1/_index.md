---
title: "Event 1"
weight: 1
chapter: false
pre: "<b>4.1. </b>"
---

# Summary Report: FCAJ Community Day

**Event information**

* **Event:** FCAJ Community Day
* **Date and time:** Saturday, 31 October 2026, 09:00–12:00 (GMT+7).
* **Location:** Bitexco Financial Tower, Ho Chi Minh City.
* **Role:** Attendee.
* **Video:** [First Cloud AI Journey: Community Day 31/10](https://www.youtube.com/watch?v=qRSxBAPYttM) on the AWS Study Group channel.

### Event objectives

* Explore AWS learning resources and ways to get started.
* Learn from internship and AWS application development experiences.
* Study AI, serverless applications, asynchronous processing, and open-source contributions.

### Speakers

* **Minh Tuấn:** An AWS learning path for beginners.
* **Đức (Henry):** Applying AI in the software development process.
* **Khanh Duong:** Internship experience and building a web game.
* **Thịnh Nguyễn:** Introduction to AWS Lambda Web Functions.
* **Luong Cam Dao:** Asynchronous processing with Amazon SQS.
* **Hưng Trần:** Open-source contribution experience.

### Key highlights

#### Learning AWS

* **Fundamentals:** Use courses and quizzes on AWS Skill Builder to learn cloud basics.
* **Practice:** Follow AWS Study Group labs, record errors and solutions, and clean up resources afterward.
* **Sharing:** Turn what was learned into a small project or an AWS Builder Center article.

#### AI in software development

* **Exploring ideas:** Use AI to help summarize discussions and explore implementation options.
* **Checking changes:** Combine automated review with end-to-end tests, before/after screenshots, or flow recordings.
* **Development environment:** Run lint and migration tasks on a shared server to reduce waiting time on individual machines.

#### Building a web game

* **Serverless architecture:** Use Lambda and DynamoDB for game operations and SQS for work generated when many matches end.
* **Scheduled work:** Update rankings periodically and use EventBridge for a time-related monitoring task.
* **Security lessons:** Avoid putting all permissions in one IAM role and consider Secrets Manager for sensitive information.
* **Infrastructure as code:** Use AWS CDK and CloudFormation to define and deploy infrastructure consistently.

#### AWS Lambda Web Functions

* **Operation:** An HTTP application runs in a Lambda environment that can serve multiple concurrent requests.
* **Performance:** The speaker compared cold starts with subsequent requests in the demonstration.
* **Pricing:** The session discussed requests, active CPU, and memory; estimates depend on actual configuration and usage.
* **Demo:** A personality quiz website used CloudFront and Lambda Web Functions.

#### Asynchronous processing with Amazon SQS

* **Problem:** The API waited for Amazon Bedrock to generate content, making users wait for a response.
* **Solution:** The API places a request in a queue and returns a pending status while processing continues in the background.
* **Queue types:** Standard and FIFO differ in ordering and throughput characteristics.
* **Failure handling:** Visibility timeout temporarily hides a message during processing; a dead-letter queue holds messages that fail repeatedly.
* **Demo:** Create a queue and send and receive messages through the AWS Console and code.

#### Open-source contributions

* **Getting started:** Choose a manageable issue, read the contribution guide, and study the relevant code.
* **Pull requests:** Keep changes clear and focused so reviewers can assess them.
* **Consistency:** Follow project updates, communicate with maintainers, and contribute regularly.

### Key Takeaways

#### Technical knowledge

* Combining theory, labs, and notes about errors can make AWS services easier to understand.
* SQS can separate incoming requests from background processing; retries and failed messages also need attention.
* IAM permissions should match each component's needs, while infrastructure as code can support consistent deployment.
* AI-assisted changes still need testing and review before being incorporated into a project.

### Applying to Work

* **Asynchronous processing:** Explore using SQS for longer-running backend tasks.
* **Monitoring:** Learn to inspect logs and failed messages when processing fails.
* **Open source:** Start with a small issue, read the contribution guide, and reproduce the problem before proposing a change.

### Event Experience

#### Learning from the sessions

The sessions gave me another perspective on learning AWS through labs and practical projects. The SQS discussion was particularly relevant to my backend studies because it can be used for work that does not need to finish within a single request.

#### Some event photos

![Photo at First Cloud AI Journey Community Day]({{< asset "images/events/community-day-31-10.png" >}})

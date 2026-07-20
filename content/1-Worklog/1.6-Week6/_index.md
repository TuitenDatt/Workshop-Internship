---
title: "Week 6 Worklog"
date: 2026-05-25
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---



### Week 6 Goal:

* Master large-system development thinking by setting up an asynchronous event-driven architecture that coordinates SQS and SNS.

### Tasks to be implemented this week:
| Day | Task                                                                                                                                                                                   | Start date | Completion date | Reference                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Learn about the AWS SQS (Simple Queue Service) message queue service: Standard vs FIFO queues.                                                                                          | 25/05/2026   | 25/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Learn about the AWS SNS (Simple Notification Service) messaging service: Topics, Subscriptions, Push notification.                                            | 26/05/2026   | 26/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Study AWS EventBridge for system-wide event management and routing, and AWS Step Functions for workflow management. | 27/05/2026   | 27/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Practice creating a simple Event-driven model: send messages to SQS to trigger sequential processing.                  | 28/05/2026   | 28/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Configure an SNS topic to automatically send email notifications to administrators when incidents occur.                                                                                      | 29/05/2026   | 29/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 7   | - Combine SQS and SNS to build a simultaneous message distribution model (Fan-out architecture) applied to transaction processing.                                                                                    | 30/05/2026   | 30/05/2026      | <https://cloudjourney.awsstudygroup.com/> |
### Week 6 Achievements:
*  Clearly understood the importance of Loosely Coupled Architecture in large systems.
* Successfully deployed a Fan-out architecture for data synchronization by combining SQS and SNS.
* Automated email push notification flows for asynchronous tasks.


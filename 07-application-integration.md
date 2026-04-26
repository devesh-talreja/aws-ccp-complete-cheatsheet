## 7. APPLICATION INTEGRATION

### SQS (Simple Queue Service)
**What:** Message queue service
**Real-life:** Like a line of people waiting to be served
**Key Points:**
- Decouple applications
- Two types: Standard (unlimited throughput, at-least-once delivery) and FIFO (ordered, exactly-once)
- **Memory Trick:** "SQS = Queue = Wait in line"

### SNS (Simple Notification Service)
**What:** Pub/Sub messaging service
**Real-life:** Like a notification system that alerts multiple people at once
**Key Points:**
- Publishers send to topics
- Subscribers receive from topics
- Email, SMS, HTTP, Lambda
- **Memory Trick:** "SNS = Notifications = Alert subscribers"

### EventBridge
**What:** Serverless event bus
**Real-life:** Like a town square where events are announced
**Key Points:**
- Connect applications using events
- Schedule events (like cron)
**Memory Trick:** "EventBridge = Bridge between events"

### Step Functions
**What:** Orchestrate workflows
**Real-life:** Like a flowchart that automatically executes steps
**Key Points:**
- Visual workflow
- Coordinate Lambda functions and other services
**Memory Trick:** "Step Functions = Steps in a process = Workflow"

---

[< Management & Governance](06-management-governance.md) | [Back to README](README.md) | [Analytics >](08-analytics.md)

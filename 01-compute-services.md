## 1. COMPUTE SERVICES

### EC2 (Elastic Compute Cloud)
**What:** Virtual servers in the cloud
**Real-life:** Like renting a computer in someone else's data center
**Key Points:**
- Pay for what you use (by the second)
- Instance types: General Purpose (T3, M5), Compute Optimized (C5), Memory Optimized (R5), Storage Optimized (I3)
- **Memory Trick:** "EC2 = Elastic Computer Cloud = Your virtual machine"

**Pricing Models:**
1. **On-Demand:** Pay by hour/second, no commitment (most expensive)
2. **Reserved Instances (RI):** 1-3 year commitment, up to 75% savings
3. **Spot Instances:** Bid for unused capacity, up to 90% savings (can be interrupted)
4. **Dedicated Hosts:** Physical server dedicated to you (compliance/licensing)
5. **Savings Plans:** Flexible pricing, commit to usage amount

### Lambda
**What:** Run code without managing servers (serverless)
**Real-life:** Like hiring someone to do a specific task only when needed
**Key Points:**
- Pay only when code runs
- Scales automatically
- Max execution time: 15 minutes
- **Memory Trick:** "Lambda = Lazy computing = No servers to manage"

### Elastic Beanstalk
**What:** Platform as a Service (PaaS) - deploy applications easily
**Real-life:** Like using WordPress instead of building a website from scratch
**Key Points:**
- Automatically handles deployment, capacity provisioning, load balancing
- You control the resources
- **Memory Trick:** "Beanstalk = Plant and grow = Deploy and it grows automatically"

### Lightsail
**What:** Simple VPS (Virtual Private Server) solution
**Real-life:** Like buying a pre-configured starter kit
**Key Points:**
- Fixed monthly price
- Great for simple applications
- Includes everything you need to start
- **Memory Trick:** "Lightsail = Light and simple = Easy to use"

### ECS/EKS (Container Services)
**ECS:** Elastic Container Service (Docker containers, AWS-managed)
**EKS:** Elastic Kubernetes Service (Kubernetes-managed)
**Real-life:** Like shipping containers that hold your application
**Memory Trick:** "ECS = Easy Container Service, EKS = Expert Kubernetes Service"

---

← Home | [Back to README](README.md) | [Storage Services >](02-storage-services.md)

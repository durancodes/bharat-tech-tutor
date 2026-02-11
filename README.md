
# 🇮🇳 Bharat Tech Tutor
Bharat Tech Tutor implements a Multimodal Adaptive AI Workflow using AWS Bedrock, Transcribe, Translate, Polly, Lambda, and DynamoDB to create a personalized learning loop that teaches, evaluates, analyzes, and adapts in real time.

### Multimodal Adaptive AI Learning Platform for Bharat

**AI for Bharat Hackathon | Powered by AWS**

---

## 1. Executive Summary

Bharat Tech Tutor is a **multilingual, multimodal AI-powered learning and evaluation platform** designed to democratize computer science education across India.

The platform goes beyond content delivery. It **measures, validates, and adapts learning outcomes** using AI-driven evaluation and an adaptive difficulty engine.

Built on a fully serverless AWS architecture, the solution is scalable, secure, and optimized for low-bandwidth environments common across Bharat.

---

## 2. Problem Statement

Technical education in India faces key challenges:

* English-dominated learning resources
* Limited personalization in learning platforms
* No measurable proof of understanding
* Static difficulty levels
* Minimal support for Tier-2 and Tier-3 learners

There is a need for an AI-powered system that:

* Teaches in Indian languages
* Adapts to learner capability
* Validates real conceptual understanding
* Scales nationwide

---

## 3. Solution Overview

Bharat Tech Tutor implements a **Multimodal Adaptive AI Workflow**:

> Teach → Test → Analyze → Adapt → Retest → Track → Certify

The system:

* Explains computer science concepts step-by-step
* Supports Hindi, Telugu, Tamil, Kannada, and English
* Provides line-by-line code explanations
* Conducts AI-generated conceptual and practical evaluations
* Calculates learning metrics
* Adjusts difficulty automatically
* Tracks long-term retention
* Generates downloadable performance reports

---

## 4. Core Features

### 4.1 Multilingual Concept Explainer

* Step-by-step breakdown of CS concepts
* Indian-context examples
* Difficulty-aware explanations
* Technical terms preserved in English (with translations)

### 4.2 Code Intelligence Engine

* Line-by-line code explanation
* Variable and control flow highlighting
* Error detection and correction suggestions

### 4.3 AI-Based Evaluation Engine

* Conceptual and applied questions
* Adaptive question generation
* Detailed feedback per answer

### 4.4 Learning Analytics Framework

| Metric          | Description                 |
| --------------- | --------------------------- |
| CMS             | Concept Mastery Score       |
| LPS             | Learning Progress Score     |
| PPS             | Practice Performance Score  |
| Retention Score | Long-term memory validation |

### 4.5 Adaptive Difficulty Engine

* Beginner → Intermediate → Advanced progression
* Performance trend analysis
* Automatic level adjustment

### 4.6 Learning Summary & Certification

* Performance dashboard
* Historical tracking
* Downloadable PDF summary

---

## 5. Multimodal AI Workflow

User Input (Text / Voice)
↓
Amazon Bedrock (LLM-based Explanation Generation)
↓
AWS Translate (Multilingual Delivery)
↓
Concept + Code Explanation
↓
AI Evaluation Generation
↓
Score Computation (CMS, LPS, PPS)
↓
Adaptive Difficulty Engine
↓
Progress Storage (DynamoDB)
↓
Learning Summary Generation (S3 PDF)

---

## 6. AWS Cloud Architecture

The platform is built on a serverless AWS architecture:

* **Amazon Bedrock** – Foundation models for explanation & evaluation
* **AWS Lambda** – Stateless compute services
* **Amazon DynamoDB** – User and learning data storage
* **Amazon S3** – Report storage
* **Amazon API Gateway** – API exposure
* **AWS Cognito** – Secure authentication
* **AWS Step Functions** – Workflow orchestration
* **Amazon CloudFront** – Content delivery optimization
* **Amazon QuickSight** – Analytics dashboards

This architecture ensures:

* Auto-scaling
* High availability
* Low operational overhead
* Enterprise-grade security

---

## 7. Scoring Algorithms

### Concept Mastery Score (CMS)

```
CMS = (Correct Answers / Total Questions) × 100
```

### Learning Progress Score (LPS)

```
LPS = Average of all CMS scores
```

### Practice Performance Score (PPS)

```
PPS = (Correctness × 50%) +
      (Code Quality × 30%) +
      (Time Complexity × 20%)
```

### Retention Score

```
Retention = (Current Score / Initial CMS) × 100
```

---

## 8. Repository Structure

```
bharat-tech-tutor/
│
├── requirements.md
├── design.md
├── tasks.md
├── README.md
│
├── src/
│   ├── services/
│   ├── models/
│   ├── ai/
│   ├── evaluation/
│   ├── adaptive/
│   └── progress/
│
├── infrastructure/
│   ├── cdk/
│   └── step-functions/
│
└── tests/
```

---

## 9. Security & Compliance

* Password hashing (bcrypt)
* TLS encryption in transit
* AES-256 encryption at rest
* Role-based access control
* User data deletion support
* Audit logging for difficulty adjustments

---

## 10. Scalability & Performance

* Supports 10,000+ concurrent users
* Serverless auto-scaling
* Low-latency DynamoDB reads
* Cached explanations via CloudFront & ElastiCache
* Optimized for low-bandwidth environments

---

## 11. Impact for Bharat

* Reduces language barriers in technical education
* Supports learners from Tier-2 and Tier-3 cities
* Encourages skill-based learning over rote memorization
* Provides measurable proof of understanding
* Scales nationally using AWS infrastructure

---

## 12. Innovation Highlights

* Multimodal AI learning workflow
* Adaptive difficulty engine
* Measurable learning analytics
* Fully serverless AWS-native architecture
* Built specifically for Indian learners

---

## 13. Team

**Team Name:** TechSpear
**Team Leader:** Duranjai Venkatachalapathi

---


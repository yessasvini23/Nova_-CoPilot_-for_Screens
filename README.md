# 🚀 Nova CoPilot for Screens
### Agentic UI Automation with Amazon Nova

Nova CoPilot for Screens is an agentic automation system that learns real user workflows directly from UI interactions and converts them into reliable Nova Act agents with human-in-the-loop safety.

Unlike traditional RPA, Nova CoPilot combines reasoning, multimodal embeddings, and adaptive execution to automate legacy portals and SaaS tools without APIs.

---

## 🧩 Core Innovation

Most automation tools require manual workflow design.

Nova CoPilot introduces a **Watch-First Automation Model**:

1. Observe real user sessions
2. Infer repeatable workflows using Nova reasoning
3. Generate agent policies
4. Execute with explainability and confidence scoring

This shifts automation from scripting → learning.

---

## ⚙️ Architecture

Browser Recorder Extension
│
▼
Session Normalization Service
(DOM + Screen Snapshot Encoding)
│
▼
Nova Multimodal Embeddings
(Task Similarity + UI Understanding)
│
▼
Planner Agent (Nova 2 Lite)

Workflow abstraction

Constraint generation

Error path reasoning
│
▼
Executor Agent (Nova Act)

Stateful browser actions

Adaptive selectors

Retry logic
│
▼
Observability Layer
Action logs
Confidence scores
Human approval signals



---

## 🤖 Multi-Agent Design

### Observer Agent
Captures structured session traces:
- DOM tree context
- Screen regions
- Action sequences

### Planner Agent (Nova 2 Lite)
Transforms sessions into generalized workflows:

Example abstraction:

IF user navigates CRM → searches email → updates status
THEN create RefundApprovalWorkflow


### Executor Agent (Nova Act)
Executes workflows with:

- semantic element targeting
- layout-shift tolerance
- state recovery

---

## 🧠 Amazon Nova Stack Usage

### Nova 2 Lite
- Reasoning over session clusters
- Workflow generalization
- Dynamic planning

### Nova Multimodal Embeddings
- DOM + screenshot semantic alignment
- UI change robustness

### Nova Act
- Reliable browser automation
- Stateful execution across pages

### Nova 2 Sonic (Optional)
- Voice-triggered agent execution
- Spoken explanations

---

## 🛡️ Safety Model

Automation maturity levels:

1. **Ghost Mode**
   - Shows predicted actions
   - Confidence scoring

2. **Supervised Mode**
   - Human approval checkpoints

3. **Auto Mode**
   - Low-risk execution with audit logs

---

---

## 🚀 Live Project Links

🌐 **App Link (Live Demo)**  
https://lovable-agent-scribe.lovable.app

🎬 **Demo Video**  
https://youtu.be/GlU6srYAs-o

📝 **Builder.aws Blog Post**  
https://builder.aws.com/content/39t0fl7Me50yX1wwFNm55ggNgNA/from-click-fatigue-to-community-impact-building-nova-copilot-for-screens-with-amazon-nova-by-syessasvini

---


## 🎬 Demo Workflow

Scenario: Refund approval automation

Steps:

- Record workflow once
- Nova infers reusable pattern
- Agent generated
- Ghost mode previews actions
- Auto mode executes batch refunds

Metrics dashboard displays:

- Time saved/run
- Error rate
- Automation confidence trend

---

## 📊 Technical Differentiators

- Screen-native agent learning (not prompt scripting)
- Multimodal UI understanding instead of static selectors
- Agent planning separated from execution
- Human-aligned trust model via ghost mode

---

## 🧪 Stack

Frontend:
- React + Extension API

Backend:
- Python / Node.js
- AWS Lambda
- API Gateway

AI:
- Amazon Nova 2 Lite
- Nova Act
- Nova Multimodal Embeddings

---

## 🔬 Future Research Directions

- Adaptive selector embeddings
- Self-healing agent policies
- Federated workflow learning

---

## 📄 License
MIT

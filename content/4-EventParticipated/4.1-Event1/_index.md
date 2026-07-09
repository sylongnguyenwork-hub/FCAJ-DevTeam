---
title: "Event1"
date: 2026-05-26
weight: 3
chapter: false
pre: " <b> 4.1. </b> "
---

# "AWS First Cloud AI Journey Community Day" Event Report

### Purpose of the Event

Mathematical Foundations & Governance of Agentic AI: Delve deep into the underlying infrastructural architecture of Large Language Models (LLMs), optimization techniques for Context Engineering, and design methodologies for collaborative Multi-Agent systems within complex enterprise environments.

Cloud Infrastructure Optimization & Security: Explore advanced architectural models to balance cost and performance while strengthening security boundaries from Edge deployment points to the Origin server.

Product Mindset & Real-World Pressure: Analyze the paradigm shift from theoretical, experimental academic models to production-grade commercial products under the simulated high-pressure environment of 36-hour Hackathons, thereby meeting the rigorous standards of the global IT labor market.

### Speakers & Team Lineup

- **Duc Dao** - Solution Architect, Cloud Kinetics
- **Vy Lam** - Senior Business Systems Analyst, VPBank
- **Tinh Trương** - Platform Engineer, GoTymeX
- **Pham Ng Anh Hai** - G-AsiaPacific Vietnam, AWS Community Builder
- **Nguyen Tuan Thinh** - DevOps Engineer
- **UTMorpho Team** - Contestants of LotusHacks 2026
---
### Event Content

#### 1. The Non-Deterministic Nature of "Deterministic" Configurations in LLMs (Speaker: Duc Dao)

Under the guidance of speaker Duc Dao, the true nature of LLMs was deconstructed from the perspective of a Probabilistic Engine. The text-generation process of an LLM is essentially a sequential calculation of raw scores (Logits) across the entire vocabulary at each token-generation step, which are then normalized into probabilities via the Softmax mathematical function for sampling.

#### 2. Enterprise-Grade Multi-Agent Systems - Startup Credit Scoring (Speaker: Vy Lam)

Speaker Vy Lam presented a real-world case study addressing the structural mismatch between traditional banking systems and startups. While banks strictly demand collateral and at least 3 years of audited financial statements, a startup's actual valuation lies in multidimensional, unstructured data such as Intellectual Property (IP), team capabilities, burn rate, and cash flow runway.

#### 3. Context Is Everything - Bringing AI into Production (Speaker: Tinh Trương)
According to speaker Tinh Trương, context engineering is the ultimate factor determining the success of AI in production. A standard Context Framework must be built upon four core pillars:

Goal: Clearly define the expected output state.

Relevant Info: Filter and provide only the essential data required for the specific task.

Constraints: Establish technical limitations, linguistic styles, and output formatting boundaries.

Success Criteria: Define quantifiable metrics to evaluate the quality of the generated output.

#### 4. Friendly AI Assistant w/ Amazon Quick (Speaker: Pham Ng Anh Hai)

To directly alleviate the common pain points of business users who spend excessive time manually gathering scattered data and executing repetitive administrative tasks, speaker Pham Ng Anh Hai introduced an Enterprise Agentic AI solution built on top of the Amazon Quick Suite.

#### 5. CloudFront as Your Foundation - Optimizing from Edge to Origin (Speaker: Nguyen Tuan Thinh)
Speaker Nguyen Tuan Thinh analyzed one of the greatest operational risks for tech founders: facing sudden, massive infrastructure bill spikes (potentially up to hundreds of thousands of dollars) driven by unexpected traffic surges or Distributed Denial of Service (DDoS) attacks.

#### 6. A 36-Hour Journey from Idea to Reality at LotusHacks 2026 (Contesting Team: UTMorpho)

Insights shared by the UTMorpho team painted a realistic picture of the immense pressure and rapid product development lifecycle within a 36-hour non-stop Sprint. Moving past initial alignment hurdles, the team extracted a profound philosophy: the most valuable product ideas do not emerge from abstract, macro theories, but rather from confronting the friction, frustrations, and bottlenecks encountered in daily workflows (Real Frustration Creates Real Ideas).

### Key Takeaways

Context is the Experience: Configuration context is not merely supplemental input data; it acts as the core architecture shaping the entire AI product experience. Providing a precise context framework is akin to a teacher preparing a well-structured lesson plan, enabling the AI model to maximize its processing efficiency.

Enterprise Mindset: Deploying artificial intelligence within large-scale organizations goes beyond writing clever prompts; it is a holistic system engineering challenge. This paradigm requires the seamless alignment of robust security (Authentication, Least-Privilege IAM), data safety governance (Guardrails), and infrastructure automation (Terraform / Platform Engineering).

#### Current State of the Labor Market
The tech recruitment landscape is undergoing rigorous filtering and deep saturation. Modern enterprises have zero demand for candidates whose skills are confined to textbook theories or building simple "toy" demos.

Procrastination-Free Action Strategy: Given the current velocity of technological advancement, AI capabilities are doubling exponentially every four months. Delaying practical learning and hands-on execution for even a short period (a week or a month) will inevitably create an insurmountable generation gap in skill level, leaving engineers quickly phased out of the industry's progression.

### Practical Applications to Work

Standardizing Prompt Engineering: Strictly enforce the *Context Framework (Goal, Relevant Info, Constraints, Success Criteria)* across all AI interactions for both myself and the team; completely eliminate the habit of discussing scattered topics within a single conversation thread to maximize output quality.

Refactoring LLM Configurations: Review and optimize all current LLM application settings. Instead of enforcing a fixed temperature of 0 (which often triggers repetition errors due to parallel computing constraints), refactor the system parameters to a baseline of **Temperature = 0.1** combined with fine-tuning the **Repeat Penalty** to discover the optimal sweet spot between output reliability and linguistic flexibility.

### Event Experience & Reflections

Shattering Theoretical Illusions: Witnessing firsthand the output inconsistencies caused by the inference batching mechanics of major Cloud API providers, or the repetitive loops triggered by `Temperature = 0` setups, completely broke down my idealistic assumptions. This built a much more realistic, cautious, and practical design mindset when approaching system architecture.

Grasping the Depth of Enterprise Logic: Through the startup credit scoring case study by Ms. Vy Lam and the automated infrastructure talk by Mr. Tinh Trương, I realized that a software engineer's core value does not lie in generating fancy prompt responses, but in the capability to package secure, compliant, automated-as-code (Terraform) solutions that deliver clear Return on Investment (ROI) to the business.

> In conclusion, the event helped me clearly understand what enterprises look for, how to utilize AI effectively, how to optimize newer AI models, and how to challenge myself through fast-paced competitions. The ultimate lesson is to anchor everything in real business problems, deliver complete products as answers, and always design systems with the architectural readiness to handle the non-deterministic nature of future technologies.

![](_image/image2.jpg)
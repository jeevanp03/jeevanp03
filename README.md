# 👋 Hi, I'm Jeevan Parmar

<div align="center">
  <img src="https://raw.githubusercontent.com/jeevanp03/jeevanp03/main/imgs/IMG_2307.png" alt="Jeevan Parmar" width="210"/>
</div>

<div align="center">
  <a href="https://www.naturalschema.com/"><img src="https://img.shields.io/badge/Natural_Schema-111827?style=for-the-badge&logoColor=white"/></a>
  <a href="https://linkedin.com/in/jeevan-parmar-62b464194"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://www.instagram.com/jeevan.prmr"><img src="https://img.shields.io/badge/Instagram-E1306C?style=for-the-badge&logo=instagram&logoColor=white"/></a>
</div>

<div align="center">
  Co-founder at <a href="https://www.naturalschema.com/">Natural Schema</a> · MASc student at Waterloo · ML engineer at D&I Integrators
</div>

---

## 🧠 What I Work On

Retrieval, agents, and forecasting, mostly. I've shipped that kind of thing for industrial operators at Cognite, for clinicians at XCare, and into a social robot in Norway.

Three things have my attention right now:

- Natural language to SQL, at Natural Schema
- Demand forecasting, at D&I Integrators
- Responsible AI and VLA systems, for my master's

Before that it was RAG pipelines, squeezing models onto local hardware with llama.cpp, conversational search, and a couple of years of research on when people trust AI advice more than they should.

---

## 🚀 What I've Built

### 🧩 Co-founder, [Natural Schema](https://www.naturalschema.com/) (San Jose, CA)

Ask your data in plain English. You type a question, an agent builds a read-only ETL, runs it, and gives you the answer. No SQL. No waiting on the data team.

The agent writes one `SELECT`, puts it through a safety gate, and runs it sandboxed and scoped to you. You get a table back, plus the exact SQL if you want to check its work.

Early access is opening in waves. [Join the waitlist](https://www.naturalschema.com/).

*Since April 2026*

### 📈 Machine Learning Engineer, D&I Integrators (Toronto)

Forecasting for production and capacity planning.

- Replaced a manual Excel re-forecast with a 27-stage Azure ML pipeline. It covers 20M units a quarter across 173 SKUs.
- Benchmarked 25 forecasting methods against a measured noise floor. The selector took service level from 95.4% to 97.1%.
- Found a truncated ERP feed that had been overstating resin usage by 1.8x. Fixing it corrected a $42M spend forecast.

*Since June 2026*

### 🎓 Graduate Teaching Assistant, University of Waterloo

TA for MSE 121, Introduction to Computer Programming.

*Since September 2026*

### 🔎 Research Assistant, University of Waterloo

Recommender systems and conversational search, with Mark Smucker.

**Research Assistant** *(June 2026 to August 2026, the summer between my undergrad and my MASc)*

- Scored 51 participants as IR topics on MovieLens-32M to get popularity bias out of recsys evaluation
- Pinned 5-fold nested CV so tuning stopped leaking. Runs now reproduce across 19 qrels sets.
- Checked the harness against an ItemItem build I wrote from scratch. 493 tests, 0.0 metric delta.

**Undergraduate Research Assistant** *(June 2025 to April 2026)*

- Literature review on conversational search and recommender systems
- Wrote up where the field stands on user intent modeling, evaluation metrics, and personalization
- Built a CAL framework for content-based recommendations

### 🗣️ Undergraduate Research Assistant, SHARE Lab, University of Waterloo

When people should and shouldn't lean on AI advice, with Sharon Ferguson.

- Designed and ran online experiments on over-reliance and under-reliance in subjective decisions
- Built a closed LLM chat environment inside Qualtrics so we could watch reliance behaviour under controlled conditions
- First author on a CHI and CUI submission. I led the analysis and the writing.
- The [study pipeline is public](https://github.com/uw-share-lab/human-ai-reliance): scenario sampling, explanation generation, the interface participants used, and the analysis afterwards

*May 2025 to April 2026*

### 📊 Software Engineer, PathAI (Boston)

- Built PathAI's first customer-facing cost dashboard. It shipped in [AiSight Dx v2.18](https://www.pathai.com/news/pathai-expands-aisight-dx-with-v2.18-release-operational-dashboards-smarter-workflows-and-streamlined-reporting).
- Scoped the MVP with design and customer success, and turned what customers asked for into a priority order
- Django and Vue, heavy AI assistance. Took the timeline from about three months to one.

*September 2025 to December 2025*

### 🤖 Social Robotics Research Engineer, NTNU (Trondheim, Norway)

A RAG and agent pipeline running inside a Furhat social robot. [The backend is open source](https://github.com/jeevanp03/my_furhat_backend).

- Conversational agent built on Adaptive, Corrective, and Self-RAG. Accuracy went up 15%.
- Connected the Python agents to Kotlin Furhat skills, which gave NorwAI its first robot-connected backend
- Tuned local inference with llama.cpp down to sub-8s, and cut cloud costs 15% along the way
- Dockerized FastAPI on EC2. End-to-end latency under 4s.

*January 2025 to April 2025*

### 🏭 Software Engineer, Cognite (Austin, Texas)

A troubleshooting agent for frontline industrial operators, and the first agent on the ["Atlas" Industrial AI platform](https://www.cognite.com/en/industrial-ai).

- Got document parsing to 90% accuracy with embedding-based retrieval and cross-encoding
- Added Gemini so GCP customers could use document intelligence too
- Wrote tail-generation summarization for long contexts. 5% fewer tokens.

*May 2024 to September 2024*

### 🏥 Founding AI Engineer, XCare (Toronto)

- Fine-tuned CNNs and Vision Transformers for X-ray diagnosis, to 90% classification accuracy
- RAPTOR-based retrieval pipeline. Medical retrieval accuracy went to 95%.
- RAG system for personalized rehab guidance, grounded in medical literature
- Co-authored a paper and presented it at CUCAI 2024

*October 2023 to October 2024*

---

## 🌍 Where I've Worked

- **San Jose, California:** Natural Schema
- **Austin, Texas:** Cognite
- **Boston, Massachusetts:** PathAI
- **Trondheim, Norway:** NorwAI and NTNU
- **Toronto, Ontario:** XCare, Genellipse, Approva, D&I Integrators, and QA automation at TD
- **Waterloo, Ontario:** both degrees, plus research and TA work
- **Vancouver, BC:** where I started

---

## 🧰 Other Things I've Built

- MERN applications for a fintech startup in Techstars (Approva)
- Test automation at TD in Java Selenium and Jenkins. 30+ end-to-end cases, 58% faster than what it replaced.
- MongoDB architecture at Genellipse for vector similarity search across 13 collections
- An accessibility services tool on Azure ML, through the Microsoft and UWaterloo WEA partnership
- Predictive analytics dashboards
- CI/CD on Jenkins, Firebase, and Supabase

My [full work history is on LinkedIn](https://linkedin.com/in/jeevan-parmar-62b464194).

---

## 🛠 Tools

**AI / ML:** PyTorch, HuggingFace, RAG, agents, VLA systems, OpenAI, Gemini, llama.cpp
**Backend:** FastAPI, Django, Node.js, Docker, AWS/GCP/Azure, microservices
**Full-stack:** React, Vue, TypeScript, Express, SQL/NoSQL
**Data:** Azure ML, ChromaDB, Supabase, Jenkins, Firebase

---

## 📚 Side Projects

- **Search engine:** BM25 plus embeddings, with query-biased summaries and a statistical evaluation
- **Audio transcriber:** Whisper and GPT cleanup, with a human in the loop
- **Meal Stream:** meal planning and nutrition analytics
- **Energy price forecasting:** ML models for the PJM market
- **NBA player projection:** a deployed model with a dashboard on top

---

## 🎓 School

BASc from Waterloo in Management Engineering, computing option. Machine learning, optimization, HCI, software engineering, systems design, decision analysis.

Now a MASc student there in Management Science and Engineering, on Responsible AI and VLA systems, with MSE 121 to TA on the side.

---

## ⚽ Outside Work

Brazilian Jiu-Jitsu, marathons, football (both kinds), basketball, squash, tennis, golf.
I also collect colognes and watch absurdly long sports documentaries.

---

## 📬 Contact

- [**Natural Schema**](https://www.naturalschema.com/), if you want to ask your data something
- [**LinkedIn**](https://linkedin.com/in/jeevan-parmar-62b464194) and [**GitHub**](https://github.com/jeevanp03)
- [**j29parma@uwaterloo.ca**](mailto:j29parma@uwaterloo.ca)

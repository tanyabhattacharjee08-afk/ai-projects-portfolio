**AI Projects Portfolio — Tanya Bhattacharjee**
MBA Candidate | TAPMI | Summer Intern at ITC | Ex-Amazon
AI/ML projects built using RAG, Agentic AI, and workflow automation tools.

**Project 1: B2B Buyer Lead Intent Classifier**
Problem: IndiaMART suppliers waste time responding to low-quality buyer inquiries. No system exists to prioritise which leads deserve immediate attention.

Solution: Built an agentic n8n workflow that receives buyer inquiries via webhook, uses an LLM to classify them as SERIOUS, PRICE_SHOPPER, NURTURE, or SPAM, and outputs a recommended supplier action and draft response automatically — without any human intervention.

Why it matters: Supplier response speed is the #1 conversion factor on IndiaMART. This workflow ensures serious buyers get immediate attention while spam is filtered automatically.

Tools: n8n, OpenAI GPT, Agentic AI Workflow, Prompt Engineering

**Live Demo:** https://tanyab08.app.n8n.cloud/webhook/buyer-inquiry

**Project 2: IndiaMART Seller Success Chatbot**
Problem: IndiaMART has 90 lakh+ sellers but support is limited to static FAQs and phone calls. Small sellers don't know how to optimise listings, manage BuyLeads, or choose the right subscription.

Solution: Built a RAG-based chatbot trained on IndiaMART's official seller knowledge base. Sellers can ask natural language questions and get instant, accurate answers — 24/7, without calling support.

Tools: Dify, RAG, Vector Embeddings, GPT-3.5

**Live Demo:** https://udify.app/chat/qCE4SdyhZsM6YEnD

**Project 3: FMCG Consumer Survey Sentiment Analyser**
Problem: Conducted 109 consumer surveys and 20 retail store visits for ITC's Wowzer product launch in Manipal. Manually reading and analysing all responses to extract themes and strategic insights took days.

Solution: Built an agentic n8n workflow that processes raw survey responses, classifies sentiment (positive/negative/neutral), extracts key themes (awareness, availability, pricing, packaging, impulse buying), and outputs a prioritised strategic market intelligence report — in under 60 seconds.

Real Data Used: 109 primary consumer surveys + 20 store visits (14 General Trade + 6 Modern Trade) conducted personally in Manipal and Udupi, Karnataka.

Tools: n8n, OpenAI GPT, Sentiment Analysis, Agentic Workflow

**Live Demo:** https://tanyab08.app.n8n.cloud/webhook/cheese-cracker-survey

**Project 4: AI-Powered Customer Support Email Agent**
Problem: Customer support teams waste hours manually reading emails, identifying query type, searching for answers, and drafting replies.

Solution: Built a fully automated customer support pipeline. System monitors Gmail continuously, classifies incoming emails (Support vs Promotional), routes genuine queries to an AI Agent, retrieves answers from a Supabase vector knowledge base using RAG and semantic embeddings, auto-drafts a Gmail response, and sends a Telegram notification — with human-in-the-loop review before sending.

Architecture: Gmail Trigger → Email Classification → AI Agent → RAG (Supabase Vector Store) → Gmail Draft → Telegram Notification

Tools: n8n, OpenAI GPT, RAG, Supabase Vector Store, OpenAI Embeddings, Gmail API, Telegram API

**Workflow File:** See Workflow.json uploaded in this repository

Skills Demonstrated
Retrieval-Augmented Generation (RAG)
Agentic AI Workflow Design
Sentiment Analysis
Prompt Engineering
No-code AI tool building (n8n, Dify)
Problem identification and solution design
Primary market research to AI pipeline

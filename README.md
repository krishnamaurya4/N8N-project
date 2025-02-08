# N8N-project
1. Project Overview
Problem:
Managing internal SOPs, HR onboarding documents, and internal customer support manually is inefficient. Employees struggle to find the right documents, leading to wasted time and productivity loss.
Solution:
An AI-driven automation agent built using N8N, OpenAI, Slack, Pinecone, and Google Drive. This system automates document retrieval, onboarding assistance, and internal knowledge management. Employees can simply ask a Slack bot for SOPs or internal guides, and the agent fetches the relevant information.


Impact / Results:
✅ Instant document retrieval via Slack.
✅ Reduced manual effort in HR & internal support.
✅ AI-powered responses improve accuracy.
✅ Seamless integration with existing tools.


Tool Breakdown
Workflow Automation --	N8N
AI Processing-- OpenAI (GPT-4)
Vector Search -- 	Pinecone
Messaging -- Slack
Document Storage -- Google Drive API


🛠️ Prerequisites
Before setting up the project, ensure you have:
- [N8N](https://n8n.io) installed or Can use N8N Cloud Version
- API keys for:
  - Slack
  - OpenAI
  - Pinecone
  - Google Drive API


Implementation Details
1️. Employee Requests a Document → Employees send a query in Slack, like:
"Where is the latest Leave Policy?"

2️⃣ N8N Workflow Triggered → The Slack bot triggers an N8N workflow.

3️⃣ AI-Powered Query Processing (ChatGPT & Pinecone) →
•	OpenAI interprets the question using natural language processing.
•	Pinecone performs a vector search to find the most relevant document.

4️⃣ Google Drive API Fetches Document →
•	The bot retrieves the correct document from Google Drive.
•	It extracts key details like summaries or highlights.

5️⃣ Response Sent in Slack →
•	The bot replies with the document link and a brief summary.
•	If needed, AI-generated explanations are provided.

 
 Features & Capabilities
✅ AI-Powered Search – Finds the best document based on semantic meaning.
✅ Slack Integration – Employees can ask directly in Slack for SOPs.
✅ Automated Document Retrieval – Fetches files from Google Drive.
✅ HR & Onboarding Support – Sends onboarding guides and policies automatically.
✅ AI Summarization – Provides short summaries of long documents.
✅ Scalable & Customizable – Can be expanded for other business processes.

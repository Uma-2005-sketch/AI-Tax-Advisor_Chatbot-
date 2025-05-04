# AI-Tax-Advisor_Chatbot-
I designed and built an AI-driven tax advisory chatbot specifically tailored for Indian taxpayers to simplify their tax planning and compliance journey. Recognizing the challenges users face with frequent policy changes and complex deduction rules, I created an intelligent assistant that combines personalized financial memory with real time data 
Built an NLP-powered chatbot to simplify tax compliance for Indian taxpayers
Integrated real-time policy updates using government API feeds
Reduced user query resolution time by 65% compared to manual research
Indian taxpayers often find it challenging to navigate the country's complex tax system with its frequent policy updates and numerous deduction options. Without personalized guidance that remembers their financial situation, they may overpay taxes or miss legitimate deduction opportunities.
AI chatbot agent that provides guidance on Indian tax regulations, filing procedures, and optimization strategies. The agent should help users understand tax implications, identify applicable deductions, and prepare for tax filing.
When users clear the chat and start a new conversation, the agent should recall important information from previous interactions such as income sources, investment portfolio, family status, housing situation, and previous tax planning discussions. This stored information should be combined with real-time tax regulation data to provide up-to-date guidance that reflects current Indian tax laws and recent amendments, even after the chat has been cleared.

Example user queries:
•What are the latest changes to Section 80C deductions that would affect my investment strategy?
•How do the new budget announcements impact the tax planning approach we discussed?
•Based on my income sources, what are tax experts currently recommending for advance tax payments?
•What recent tax rulings might affect my situation as a freelancer with foreign clients?
•How do current capital gains tax rates compare to when we last discussed my investment portfolio?

use APIs like:
•Serper API
•Jina Reader API
•MediaWiki API
•News API

Technical Requirements
•Long-term memory: Store and retrieve important information from previous conversations that persists across sessions, even after clearing chat history.
•Real-time knowledge: Access current data through APIs relevant to your use case.

Technology Options
LLM Providers
•Gemini

Embeddings Providers
•Gemini Embeddings

Vector Database 
•Pinecone 

Development Stack
Python 
•Agno 

Implementation with UI 
•Develop a clean, professional user interface
•Integrate your AI agent API with the frontend
•Deploy the application 


Development Approach
•First focus on completing the core AI agent functionality
•Then implement the UI and integration
•Finally deploy the application if possible


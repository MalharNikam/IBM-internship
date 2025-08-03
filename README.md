# College Admission Guide AI Agent

This project is an AI-powered agent designed to assist prospective students with the college admission process. Built as part of the IBM Hackathon, this agent serves as a 24/7 virtual assistant that provides instant, accurate answers to common questions about admissions, drawn directly from an institution's own data.

## 📝 Problem Statement

Prospective college students and their parents often face a stressful and confusing process when trying to find clear, consolidated information about admission policies, eligibility criteria, course details, fee structures, and important deadlines, which are often scattered across various university websites and documents. This information overload leads to repetitive manual inquiries, frustration, and the risk of missing critical application steps.

## 💡 Proposed Solution

An **AI College Admission Agent** that uses Natural Language Processing (NLP) and Retrieval-Augmented Generation (RAG) to provide instant, accurate, and centralized information. The agent understands natural language questions and provides answers based on the institution's official documents, streamlining the entire inquiry process.

## 🛠️ Technology Used

This agent was built entirely on the **IBM Cloud** platform.
* **Cloud Services**: IBM Cloud Lite services
* **AI Platform**: IBM Watsonx.ai Studio
* **Core Technology**: Retrieval-Augmented Generation (RAG) and Natural Language Processing (NLP)
* **Foundation Model**: IBM Granite Model

## ✨ Features

* **Instant Policy Summarizer**: Provides concise summaries of admission policies and eligibility criteria.
* **Deadline and Fee Inquiry**: Instantly retrieves important application deadlines and fee structures.
* **24/7 Availability**: Offers round-the-clock support to students across different time zones.
* **Reduces Manual Inquiries**: Frees up administrative staff by automating responses to common questions.

## 🚀 Deployed Agent API Endpoint

The agent has been successfully deployed on IBM Cloud and is accessible via the following API endpoint:

`https://eu-gb.ml.cloud.ibm.com/ml/v4/deployments/3bee04dd-0759-4fef-ab9f-bdac4e975f3f/ai_service?version=2021-08-01`

*(Note: This deployment may become inactive. The instructions below describe how to create your own.)*

## 📖 How to Recreate This Project

This agent was built using the no-code **Agent Lab** in IBM Watsonx.ai.
1.  **Set up Project**: Create a new project in IBM Watsonx.ai Studio.
2.  **Add Services**: Associate **Cloud Object Storage** (Lite plan) and a **Watsonx.ai Runtime** service with your project.
3.  **Build Agent**: From the homepage, select "Build an AI agent to automate tasks."
4.  **Add Knowledge**: In the **Knowledge** section, create a **New vector index** and upload your college's documents (e.g., admission FAQs, policy PDFs). This uses RAG to ground the agent in your specific data.
5.  **Deploy**: Save and **Deploy** the agent to a new deployment space to get a public API endpoint.


<img width="1366" height="768" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/82e1859f-bb24-49c5-86c1-b0448afb4166" />


## 🔮 Future Scope

* **Multilingual Support**: Assisting students from diverse linguistic backgrounds.
* **Application Form Assistance**: Guiding students step-by-step through filling out online application forms.

* **Integration with Virtual Tours**: Connecting students with virtual tours and online information sessions.

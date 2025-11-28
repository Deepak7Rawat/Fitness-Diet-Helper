# Fitness-Diet-Helper
 link for chat with Fitness & Dite Helper Agent  :-  https://r12345hul.app.n8n.cloud/webhook/0a81f8d2-12fc-46bc-8a8c-b7bcf5a6f84a/chat

 This project is a fully functional AI-powered fitness agent built using n8n automation and the Google Gemini model. It acts as a comprehensive virtual coach, capable of interacting with users via a custom-built web interface to provide personalized health strategies.

Key Features:

Intelligent Agent: Utilizes Google Gemini to process natural language and provide supportive, expert-level guidance.

Smart Tools: The agent autonomously uses custom JavaScript tools to calculate BMI & BMR, generate detailed Workout Plans (Home vs. Gym), and create Diet Plans tailored to specific goals like weight loss or muscle gain.

Contextual Memory: Built on LangChain architecture, the system retains user profile data throughout the session for continuous, personalized interactions.

Integrated Frontend: Features a responsive HTML/JS chat interface served directly via n8n webhooks, requiring no external hosting.

How It Works: The workflow employs a dual-trigger system: one webhook serves the frontend UI, while a second handles chat logic. The central Agent orchestrates the conversation, calling specific tools to perform calculations or structure data before returning a human-friendly response. This project demonstrates the power of combining low-code automation with advanced LLM capabilities.   
 
<img width="1906" height="1078" alt="Screenshot 2025-11-25 191553" src="https://github.com/user-attachments/assets/aed35f1f-cfe7-4bce-a6d1-398703dfe187" />

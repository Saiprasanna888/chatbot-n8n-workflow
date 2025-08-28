# n8n AI Chat Workflow 🤖🛠️

This repository contains a **learning experiment with n8n**, where I explored building an **AI-powered chat workflow**. The goal was to understand workflow automation, node interactions, and AI integration within n8n.  


Check out my workflow live here(make sure you need n8n account): [View Workflow on n8n](https://saisoc.app.n8n.cloud/workflow/xRElPDP2QmrMyw7j)
---

## **Workflow Overview**

1. **Trigger**
   - The workflow starts with the **“When chat message received”** block.  
   - This block initiates the workflow whenever a new message is received.  
   *Fun fact: This is basically me telling n8n, “Hey, pay attention, a new message is coming!” 😅*

2. **AI Agent**
   - The incoming message is fed into the **AI Agent** block, which is the central processing unit.  
   - The AI Agent **understands the message** and decides the next action.  
   *Yes, it’s smarter than me at 2 AM trying to debug workflows… 🫣*

3. **Core Components of the AI Agent**
   - **Chat Model:** Uses **Google Gemini Chat Model** for natural language understanding and response generation.  
   - **Memory:** Connected to **Simple Memory**, allowing the AI to remember previous parts of the conversation and maintain context.  
     *Basically like me trying to remember what I had for breakfast yesterday… but way better!*  
   - **Tool:** The AI Agent can access a **Tool**, which in this workflow is an **HTTP Request** block.

4. **Action / Execution**
   - Based on its analysis, the AI Agent decides to use the tool, triggering the **HTTP Request** block.  
   *It’s like the AI saying, “I’ve got this, let me fetch the info for you.” Meanwhile, I’m still figuring out where the coffee went… ☕*

5. **External Request**
   - Executes a `GET` request to the URL `http://139.84.15.41...`  
   - This step fetches data or interacts with an external web server/API as part of the AI Agent’s response generation.  
   *Fetching data like a pro… or at least pretending to look professional while learning n8n 😎*

---

## **Learning Goals**
- Understand **triggers and workflow initiation** in n8n.  
- Explore how **AI Agents** can be integrated into workflows.  
- Learn to use **memory components** to maintain conversational context.  
- Practice **using tools like HTTP Request nodes** for external data interactions.  
- Gain hands-on experience with **chat models and AI-driven workflow logic**.  
*Also learn how to feel like a wizard controlling bots from your laptop 🧙‍♂️*

---

## **Usage**
1. Import the workflow JSON into your **n8n instance**.  
2. Explore the **AI Agent block** and its connected components.  
3. Experiment with triggers, memory, and HTTP requests.  
4. Observe how the workflow processes chat messages and generates responses.  
*Disclaimer: The AI might be smarter than me… handle with care 😅*

---

## **Notes**
- This workflow is purely for **learning and experimentation**.  
- Focused on **understanding n8n AI capabilities** and workflow logic.  
- Each node represents a **small experiment** in automation and AI integration.  
*Also a gentle reminder that debugging is 50% coffee, 50% “why isn’t this working?” ☕🤯*

---

## **Connect / Feedback**
- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/muppallasaiprasanna/)  
- GitHub: [Your GitHub Profile](https://github.com/Saiprasanna888)  

---

> Learning by building > just watching tutorials.  
> If you laughed while reading this, mission accomplished 😎

# Agents with Handoff
Create a multi-agent customer service chatbot utilizing LangGraph. The chatbot will be made up of two agents: 

- Travel Consultant: Tasked with suggesting travel locations tailored to client tastes.
-  Hotel Consultant: Tasked with suggesting hotels according to the selected location and client preferences.

  **Note about Human in the loop (HTL), tool-handoff and memory here** 

- “Tool logic is not used here” means the tools don’t compute results dynamically. They only use hardcoded if/else rules instead of calling APIs, databases, or letting the LLM generate outputs. The agent reasons dynamically, but the tool’s output is static and limited.
  
<img width="664" height="575" alt="Screenshot 2025-12-26 at 4 52 03 PM" src="https://github.com/user-attachments/assets/879a8831-a7ec-49af-9ad2-852539430ef4" />

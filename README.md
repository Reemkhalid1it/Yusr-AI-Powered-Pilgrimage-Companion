# Yusr: Smart Spiritual Guide for Pilgrims 
Graduation Project | IT Department - Taif University
## Project Overview
**Yusr** (meaning "Ease" in Arabic) is a comprehensive mobile application designed to transform the Hajj and Umrah experience. By integrating cutting-edge AI and cloud technologies, the app serves as a digital companion that guides pilgrims through their spiritual journey, ensuring safety, clarity, and ease of worship.

## Application gallery
## 📱 App UI Gallery

| Screen 1 | Screen 2 | Screen 3 | Screen 4 |
| :---: | :---: | :---: | :---: |
| <img src="رابط_1" width="160" /> | <img src="رابط_2" width="160" /> | <img src="رابط_3" width="160" /> | <img src="رابط_4" width="160" /> |

| Screen 5 | Screen 6 | Screen 7 | Screen 8 |
| :---: | :---: | :---: | :---: |
| <img src="رابط_5" width="160" /> | <img src="رابط_6" width="160" /> | <img src="رابط_7" width="160" /> | <img src="رابط_8" width="160" /> |

## Key Features
- **AI Smart Assistant:** A real-time chatbot powered by Google Gemini AI to answer religious and logistical inquiries instantly.
- **User Management:** Secure authentication system for pilgrims to manage their profiles and ritual progress.
- **Interactive Ritual Guide:** Step-by-step visual and text-based instructions for Hajj and Umrah rituals.
- **Multilingual Support:** Tools to bridge communication gaps for non-Arabic speakers.
- **Cloud Integration:** Real-time data syncing to ensure pilgrims can access their information across devices.


 ## Technical Stack
 - **Frontend:** Flutter & Dart (Cross-platform mobile development).
 - **Backend & Database:** Firebase (Authentication, Cloud Firestore, and Storage).
 - **Artificial Intelligence:** Google Generative AI (Gemini 1.5 Flash) for intelligent guidance.
 - **Tools:** VS Code, Git/GitHub, Firebase Console

## **My Role:** Technical Coordinator & Lead Developer
In this collaborative project, I served as the Technical Coordinator, where I balanced development tasks with project management:
- **Architecture Design:** I led the effort in structuring the Firebase database to handle user data and ritual logs efficiently.
- **AI Integration:** I was responsible for implementing the Gemini AI API, crafting the system prompts that ensure the bot provides accurate and empathetic guidance.
- **Workflow Optimization:** I managed the Project Activity Plan, ensuring that the team met critical milestones during the development and testing phases.
- **UI/UX Refinement:** Developed responsive interfaces in Dart, focusing on accessibility for elderly pilgrims and diverse user groups.

## Code Highlights
***One of my proudest contributions was setting up the AI interaction layer:***
<pre>// Initializing the AI Model for the Pilgrim Guide
final model = GenerativeModel(
  model: 'gemini-1.5-flash-latest',
  apiKey: _yourApiKey,
);

// Starting a conversation session with specific context
final chat = model.startChat(history: [
  Content.system("You are a helpful guide for Hajj and Umrah pilgrims..."),
]);</pre>

## Project Milestones (Final Semester)
- **Phase 1:** Requirement Analysis & UI Wireframing.
- **Phase 2:** Firebase Environment Setup & Authentication Logic.
- **Phase 3:** AI Chatbot Integration & Core Feature Development.
- **Phase 4:** Beta Testing & Final Deployment.






  

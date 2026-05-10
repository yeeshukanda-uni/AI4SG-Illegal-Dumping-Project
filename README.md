1. Problem and Population
Illegal dumping in San Jose is a recurring environmental issue affecting neighborhoods, parks, and ecosystems. It aligns with SDG 11 (Sustainable Cities and Communities) and SDG 15 (Life on Land).
Spanish-speaking residents in East San Jose are especially affected because reporting requires English and structured forms. This creates a barrier to reporting environmental problems.
🤖 2. AI Capability
This project uses Google Gemini AI to improve civic reporting.
Key features:
Structured data extraction (Lab 2)
Image recognition for environmental damage (Lab 3)
Multilingual support (Spanish, Hindi, Vietnamese, English)
Automatic classification of urgency and department
This makes 311 reporting faster, more accessible, and more consistent.
🔄 3. System Workflow
Input → AI Processing → Output → Action
Input: Text complaint or image of illegal dumping
AI Processing: Extracts structured JSON + analyzes image
Output: Standardized report (location, urgency, department, impact)
Action: Sent to San Jose 311 system for response
📸 Screenshots
JSON structured output:
Multilingual detection:
Image analysis:
Failure case:
⚠️ 4. Failure Case
The system may misclassify homeless encampment reports with trash as purely environmental issues.
This can lead to incorrect department routing and inappropriate response.
⚖️ 5. Ethical Consideration
AI improves speed and accessibility but may misroute complex social issues.
Human oversight is required for edge cases to ensure fairness and accuracy.

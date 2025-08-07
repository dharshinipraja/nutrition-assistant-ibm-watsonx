#  Nutrition Assistant – IBM Watsonx Chatbot

An AI-powered nutrition chatbot built using **IBM Watsonx Assistant** on **IBM Cloud Lite** for the **SB4Academia 2025** challenge.

This assistant helps users by providing personalized meal plans, healthy food swaps, and grocery suggestions — all through a conversational interface. It also includes a fallback flow and a free live agent handoff simulation.

---

##  Features

- ✅ Personalized meal plans (1200/1500 calories)
- ✅ Special diet support (Diabetes, Vegan, PCOS)
- ✅ Grocery list generator
- ✅ Healthy food swap suggestions
- ✅ Free live-agent request simulation
- ✅ Fallback for unknown inputs
- ✅ Built fully using IBM Watsonx no-code Actions

---

##  Technologies Used

| Tool / Service      | Purpose                            |
|---------------------|-------------------------------------|
| IBM Watsonx Assistant | Chatbot creation with no-code Actions |
| IBM Cloud Lite      | Free-tier deployment                |
| Web Chat Preview    | Testing interface                   |
| (Optional) Google Sheets / Slack | Manual live agent handoff (free method) |

---

##  Folder Structure

```bash
nutrition-assistant/
├── screenshots/           # Images of assistant UI and flow
├── conversation-flow.pdf  # Visual layout of action steps
├── README.md              # Project documentation
└── export/                # Assistant export file (optional)

How to Test the Assistant
Open the assistant in IBM Watsonx Assistant

Click Try it / Preview

Type suggest a meal plan

Follow the conversation and test:

Meal selection

Food swaps

Grocery list

Live agent request

Fallback handling


How It Works
All logic is handled inside a single Action (suggest_meal_plan)

Each step uses button options to guide the user

Live agent handoff is simulated by asking for email/phone and ending the conversation

Fallback step catches any unrecognized input and redirects the user to try again

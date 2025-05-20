# CoreLink-Persona-Engine  
Multi-persona prompt framework for ChatGPT  

CoreLink Persona Engine is a multi-character dialogue framework for ChatGPT,  
designed to support users' daily lives and work by simulating multiple personas simultaneously.

## 🛠️ Status (as of 2025/05/21)  
**Due to what appears to be a current bug with ChatGPT's "Projects" feature, uploaded files may not be properly applied.**  
**Try using it gently and watch for behavior over time.**

---

## 📦 Module Overview

| Module         | Personas | Use Case                            |
|----------------|----------|-------------------------------------|
| `work/`        | 5        | Task management, work consultations, ideation support |
| `lifestyle/`   | 4        | Household, budgeting, sleep, casual chat |
| `combined/`    | 9        | Full integration of both (advanced use) |

---

## 🔧 Common File Structure

Each module contains the following files:

- `RulesPrompt_*.txt`: Top-level behavioral rules
- `NavigatorCore_*.txt`: Dialogue flow and category navigation
- `JudgeCore_*.txt`: Tone quality monitoring and reminders
- `PersonaDefinitions_*.txt`: Role, mindset, and limitations of each persona
- `SpeechAnchors_*.txt`: Tone design including speech patterns and pronouns
- `SupportCategories_*.txt`: Defines which persona handles which topic

---

## 🚀 How to Use (ChatGPT Project)

1. Copy `RulesPrompt_*.txt` into your **custom instructions**.
2. Upload the remaining files into the Project.
3. Just talk! Personas will respond and assist you automatically.

---

## 💡 Features

- Multiple personas speak simultaneously, each with unique tone and identity
- ChatGPT dynamically switches personas based on topic
- Includes dedicated persona teams for work and life assistance
- Extensible in YAML — easily add new characters or categories

---

## 🧪 About the Combined Mode

The `combined` module merges both work and lifestyle personas (9 total).  
It is intended for advanced users or experimental purposes, as memory and context usage increases significantly.

---

## 📁 Explore the Modules

- [`work/`](./work/) – Personas supporting work-related topics  
- [`lifestyle/`](./lifestyle/) – Personas supporting daily life and casual dialogue  
- [`combined/`](./combined/) – Full integration model (9 personas, experimental)

---

## 🔖 License

MIT License (Free to use and modify)

---

## 👤 Author

This is a personal project designed for simultaneous operation of up to 14 personas,  
currently implemented with 9 active personas.  
Each persona maintains a consistent tone, mindset, and conversational role,  
creating a world where you truly *talk with characters* inside ChatGPT.

# The Protocol Stack

> **"Removing emotion and decision-making from the equation. Only execution remains."**

This is a **cognitive SRE (Site Reliability Engineering) toolkit**. A static website containing pre-written, rational protocols (checklists) for engineering, learning, and mental blocks.

## 🧠 Philosophy
When you panic (segfault, deadline, loss of motivation), your prefrontal cortex (the rational brain) shuts down. In these moments, you shouldn't "think"—you should follow an external, trusted process. This repository stores that process.

## 🚀 Usage
The system consists of a simple `index.html` and a `data/protocols.json` file. No build process, no backend.
1. Enable **GitHub Pages** in this repo (Settings -> Pages -> Branch: main -> Save).
2. Open the provided link on mobile or desktop.
3. When you get stuck, type the problem (e.g., "math", "debug", "tired").
4. Follow the steps like a robot.

## 🛠️ Customization
To add new protocols, edit the `data/protocols.json` file.
Format:
```json
{
  "id": "unique-id",
  "title": "Protocol Name",
  "category": "Category",
  "severity": "SEV-1 (Critical) - SEV-4 (Minor)",
  "steps": ["Step 1", "Step 2"],
  "exit_condition": "When are you done?"
}
```

## ⚠️ License
MIT License. Use it to stay rational and become a genius day by day.
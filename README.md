# 🤖 Smart Room Cleaner AI Agent

A visually interactive AI automation project that simulates a **Simple Reflex Agent** in Python using `Tkinter`. The agent navigates through 8 rooms, detects dirty environments, cleans them, and tracks its battery and movement intelligently.

---

## 🎯 Project Objective

To demonstrate the working of a basic AI agent that:

- Perceives its environment (room status)
- Acts based on conditions (clean or move)
- Manages limited resources (battery & cycles)
- Visualizes decision-making in real-time

---

## 🧠 Core Concepts Applied

- **Simple Reflex Agent (AI)**
- **Automation & decision-based logic**
- **Battery simulation & optimization**
- **GUI Design with Tkinter**
- **Efficient cycle calculation**
- **Smart room traversal**

---

## 🚀 Features

✅ 8 Rooms displayed in a grid layout  
✅ Random initial cleanliness (Clean/Dirty)  
✅ Agent moves and cleans intelligently  
✅ Dynamic battery and cycles tracking  
✅ Reflex behavior with efficiency logic  
✅ Color-coded status and animated updates  
✅ Fully interactive GUI with Start button

---

## 🛠️ Tech Stack

- Python 3.x
- Tkinter (standard GUI library)
- Random (for environment generation)
- Git (for version control)

---

## 🧪 How It Works

1. On start, each room is randomly marked as **Clean** or **Dirty**.
2. Agent finds the first dirty room and starts cleaning.
3. After each clean, it moves to the next dirty room (if any).
4. It stops if:
   - Battery is drained
   - Cycles run out
5. UI updates in real-time with visuals and stats.

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/smart-room-cleaner-ai.git
   cd smart-room-cleaner-ai

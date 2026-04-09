# 📝 Dev Note: "Lucky Bricks" Major System Overhaul

We are shifting our focus from 'Combo-based' play to a **Roguelike Strategic** experience where players manage risks and design their own rewards.

---

## 1. Core Concept: "Risk & Reward"
Beyond simply breaking bricks, the **Modifiers** you choose will dictate your scoring efficiency and difficulty. Players can strategically increase the difficulty to chase record-breaking high scores.

---

## 2. Modifier System Overview
Destroying 'Lock Bricks' reveals random modifiers. At the end of each stage, you can choose and stack these effects.

| Modifier | Description | Score Impact | Note |
| :--- | :--- | :--- | :--- |
| **Bar Size Down** | Shrinks paddle | **+1 point per brick** | High Risk |
| **Bar Size Up** | Expands paddle | **-1 point per brick** | Stability |
| **Ball Speed Up** | Increases ball speed | **+1 point per brick** | High Risk |
| **Ball Speed Down** | Decreases ball speed | **-1 point per brick** | Stability |
| **Bonus Score** | Instant +1,000 points | - | Low probability |
| **Score Multiplier** | Total stage score x2 | - | Very low probability |

---

## 3. Stages & Progression
* **Stages:** Total of 20 stages per run.
* **Lock Bricks:** 5 Lock Bricks are spawned in **random locations** every stage to ensure variety in gameplay.
* **Selection Rules:**
    * At the end of a stage, you can either pick one modifier from your collected list or **Skip** if you prefer.
    * Players can stack anywhere from **0 to 20 modifiers** during a single run.
* **Re-roll System:**
    * Available **once per stage**.
    * Watch an ad to select one modifier in your list and re-roll it for a random new one.

---

## 4. Difficulty & Life System Revamp
* **Base Difficulty:** The ball's base speed will **gradually increase** as you progress through stages.
* **Life System:**
    * **Starting Lives:** Base 1 + Extra 2 = **3 Lives** to start.
    * **Earning Lives:** Gain +1 Life for every **5-Combo** achieved.
    * **Life Cap:** Maximum of **5 Lives** can be held at once.
    * **Game Over:** When lives reach 0, your final record is saved to the leaderboard.

---

## 5. Game Mechanics & Competition
* **The Bar (Paddle):** Changed to a **Capsule shape** to make bounce trajectories more predictable and intuitive.
* **Logic Simplification:**
    * **Artificial angle correction logic has been removed** (Switched to pure physics-based reflection).
    * Existing **Set Effects have been removed** to improve clarity.
* **World Ranking:** The **World Ranking system remains**, allowing you to compete with players worldwide using your new strategic builds.

---

## 6. BM & Ad Policy
* **Ad Frequency:** Interstitial ad timer increased to **5 minutes** to ensure uninterrupted flow.
* **Ad-Free Package:** Priced at **5,000 KRW (approx. $3.99 - $4.99 USD)**.

---

**910Games Dev Team**
*"Moving beyond simple luck, making Lucky Bricks where your choices become your skill."*

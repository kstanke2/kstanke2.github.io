---
layout: page
title: "Bayesian Circus"
permalink: /bayesian-circus
hide_hero: true
show_sidebar: false
menubar: games-menu
---

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

# 🎪 Bayesian Circus: Iterative Guessing Challenge 🎲

## **Can You Infer the True Population from Limited Data?**

Welcome to **Bayesian Circus**, where your job is to **estimate the true distribution of colors in two mystery jars (Jar A & Jar B)** using probability, logic, and strategic guessing.

This game follows a **strict time limit per round**, and you will **track not just your best estimate, but also a confidence interval (+/- range) for each color**.  
Your goal is to **refine your estimates as accurately as possible while avoiding overcorrection**.

🏆 **Points are awarded based on accuracy and how well you adjust over time.**

---

## **📌 Game Objective**

Your goal is to estimate the **percentage of each color** in **Jars A & B** by progressively updating your guesses as **sample data** is revealed.

- Each round, a **new sample jar** and associated counts will be revealed to all participants.
- You must **update your probability estimates** for both Jars A & B within a **strict time limit**.
- You must also provide a **confidence interval (+/- range)** to show how certain you are about each estimate.
- **Overcorrecting by more than the allowed percentage results in a penalty.**

🧐 **Think carefully!** Each sample gives you a **better picture** of the whole, but you **never get to see the entire population!** Your job is to **make smart, measured updates** as you receive more information.

---

## **📝 How Confidence Intervals Work**

For each color estimate, you must **include a confidence interval**—a range that reflects how **sure** you are about your estimate.

- A **wide range (e.g., 30% ±15%)** means **you are unsure** and allowing for more error.
- A **small range (e.g., 30% ±3%)** means **you are confident** in your estimate.
- **As you get more data, your confidence interval should narrow!**

---

## **📝 Game Rules & Step-by-Step Guide**

### **🔹 Step 1: Initial Guess (Prior Belief - No Data Yet)**

1. You will receive a **Guessing Sheet** listing **Jar A and Jar B**.
2. **Without any data**, you must **estimate the percentage of each color** in both jars.
3. You must also provide a **confidence interval** (**+/- range**) for each color, representing your uncertainty.
   - Example Guesses:
     - **Jar A Guess:** 30% Green (**±10%**), 25% Red (**±5%**), 15% Yellow (**±15%**)…
     - **Jar B Guess:** 40% Yellow (**±10%**), 20% Red (**±8%**), 15% Green (**±12%**)…
4. You have **2 minutes** to submit your guesses before the round closes.

---

### **🔹 Step 2: Small Sample (First Data Revealed)**

1. A **pre-filled small sample** is revealed for **Jar A and Jar B**.
2. The **exact counts** for each color in the sample will be displayed for all participants.
3. You must now **revise your estimates** for Jar A and Jar B based on the new data.
4. Again, provide an updated **confidence interval** for each color.
5. You have **2 minutes** to submit your updated guesses.

---

### **🔹 Step 3: Additional Small Sample**

1. A **second small sample** is revealed for each jar.
2. The **exact counts** for each color in the sample will be displayed for all participants.
3. You **update your estimates and confidence intervals** based on this second sample.
4. **Overcorrection penalty applies:**
   - If your new estimate **changes by more than 20% from the previous round**, a **penalty** will be applied unless your final estimate is the closest to the true answer.
5. You have **2 minutes** to submit your updated guesses.

---

### **🔹 Step 4: Medium Sample**

1. A **medium sample** is revealed from **each jar**.
2. Participants update their guesses **again**, refining both their estimates and confidence intervals.
3. Overcorrection penalties **still apply** if estimates swing too much, but now the limit is **10%**.
4. You have **2 minutes** to submit your updated guesses.

---

### **🔹 Step 5: Larger Data Release**

1. Three **more** medium sample jars are revealed for each population.
2. Participants must now refine their guesses and **narrow their confidence intervals** as the data becomes clearer.
3. **Penalty for overcorrection still applies, and is now set at 5%**
4. **3 minutes** are given for updates before the round closes.

---

### **🔹 Step 6: Final Round**

1. A **large final sample** is revealed for each population.
2. Participants submit their **final estimates** and **confidence intervals**.
3. **Final scores are calculated.**

---

## **🚨 Overcorrection Penalty System**

🔺 If you **change your estimate by more than the allowed percentage**, you will receive a **penalty** unless your final guess is within **2% of the true proportion**.

- **Rounds 1-3:** Max correction = **20%**
- **Round 4:** Max correction = **10%**
- **Round 5:** Max correction = **5%**

This penalty encourages **small, logical updates** instead of wild swings!

---

## **💡 Strategy Tips for Participants**

✔️ **Avoid overcorrection!** Bayesian updating is about small, rational adjustments.  
✔️ **Confidence intervals matter!** If you're consistently narrowing your range, you're improving.  
✔️ **Pay attention to stabilization!** If a color’s proportion isn’t changing much, it’s likely close to correct.  
✔️ **Use the medium and large samples wisely!** They provide stronger data for accurate guessing.

---

## **📅 Game Flow**

| **Round** | **Action**                       | **Time Limit** | **Penalty for Overcorrection?** |
| --------- | -------------------------------- | -------------- | ------------------------------- |
| **1**     | Initial Blind Guess              | 2 min          | ❌ No                           |
| **2**     | Reveal Small Sample              | 2 min          | ✅ 20%                          |
| **3**     | Reveal Another Small Sample      | 2 min          | ✅ 20%                          |
| **4**     | Reveal Medium Sample             | 2 min          | ✅ 10%                          |
| **5**     | Reveal Three More Medium Samples | 3 min          | ✅ 5%                           |
| **6**     | Reveal Final Large Sample        | 3 min          | ❌ No                           |
| **7**     | Final Scoring & Leaderboard      | -              | -                               |

---

## **📋 Final Notes**

🏆 **Will your estimates converge on the truth, or will overcorrection lead you astray?**  
🎯 **Think carefully, update wisely, and trust the data!**

---

# 🎯 Bayesian Circus: Scoring Guide 📊

## **🔢 Scoring Formula**

For **each color** in **each round**, your score is calculated as:

$$
\text{Score} = \text{Base Points} \times \min\left(10, \frac{10}{\text{Confidence Interval Width}}\right)
$$

### **Key Rules**

✔️ If the **true value is inside your confidence interval**, you earn points.  
✔️ If the **true value is NOT inside your confidence interval**, you score **0** points for that color in that round.  
✔️ **Narrower confidence intervals earn higher scores!**  
✔️ **A maximum multiplier of 10 applies to prevent extreme scores.**  
✔️ **A minimum multiplier of 1 applies to prevent extreme scores.**

---

## **🏆 Base Points Per Round**

Each round, **Base Points increase** because later rounds have more data available.

| **Round** | **Base Points (per color)** | **Max Possible Points per Color** |
| --------- | --------------------------- | --------------------------------- |
| **1**     | 10                          | 100                               |
| **2**     | 20                          | 200                               |
| **3**     | 30                          | 300                               |
| **4**     | 50                          | 500                               |
| **5**     | 75                          | 750                               |
| **6**     | 100                         | 1000                              |

---

## **📏 Confidence Interval Multiplier**

Your **confidence interval size affects your multiplier**.

$$
\text{Multiplier} = \min\left(10, \frac{10}{\text{Confidence Interval Width}}\right)
$$

- **Smaller confidence intervals = higher scores!**
- **If the interval is too wide, you score fewer points.**
- **If the interval is too narrow and excludes the true value, you get 0 points.**
- **Confidence interval widths must be in whole numbers (e.g., ±0.5, ±1, ±1.5, etc.).**

### **Example Multipliers**

| **Confidence Interval Width** | **Multiplier (10 / Width)** | **Applied Multiplier** |
| ----------------------------- | --------------------------- | ---------------------- |
| **1.0%**                      | **10 / 1 = 10**             | **10 (max)**           |
| **2.0%**                      | **10 / 2 = 5**              | **5**                  |
| **5.0%**                      | **10 / 5 = 2**              | **2**                  |
| **10.0%**                     | **10 / 10 = 1**             | **1**                  |
| **20.0%**                     | **10 / 20 = 0.5**           | **1 (min)**            |

---

## **📊 Example Scoring Calculation**

### **Example for One Color (e.g., Green in Jar A)**

| **Round** | **Base Points** | **Participant's Confidence Interval** | **Width** | **Multiplier (10 / Width, max 10)** | **Score Earned** |
| --------- | --------------- | ------------------------------------- | --------- | ----------------------------------- | ---------------- |
| **1**     | 10              | **10% - 50%**                         | **40%**   | **1 (Min Multiplier)**              | **10 pts**       |
| **2**     | 20              | **30% - 50%**                         | **20%**   | **1 (Min Multiplier)**              | **20 pts**       |
| **3**     | 30              | **35% - 45%**                         | **10%**   | **1 (Min Multiplier)**              | **30 pts**       |
| **4**     | 50              | **42% - 46%**                         | **4%**    | **2.5 (10/4)**                      | **125 pts**      |
| **5**     | 75              | **43% - 45%**                         | **2%**    | **5 (10/2)**                        | **375 pts**      |
| **6**     | 100             | **44% - 45%**                         | **1%**    | **10 (Max)**                        | **1000 pts**     |

🏆 **Total Points for Green in Jar A:** **1560 pts**

---

## **💡 Key Takeaways**

✔️ **If the true percentage is inside your confidence interval, you earn points.**  
✔️ **If the true percentage is outside your confidence interval, you score 0.**  
✔️ **Smaller confidence intervals mean bigger scores!**  
✔️ **Wider confidence intervals ensure safety but earn fewer points.**  
✔️ **The later rounds are worth the most points!**

---

## **🚨 Overcorrection Penalty**

🔺 **If you change your estimate by more than the allowed percentage, you lose 10% of the points for that round** unless your guess for that round is within **2% of the true proportion**.

| **Round** | **Max Correction Allowed** |
| --------- | -------------------------- |
| **1-3**   | 20%                        |
| **4**     | 10%                        |
| **5**     | 5%                         |
| **6**     | No limit                   |

This **discourages extreme jumps** while still allowing necessary corrections as new data emerges.

---

## **📅 Game Flow**

| **Round** | **Action**                       | **Time Limit** | **Penalty for Overcorrection?** |
| --------- | -------------------------------- | -------------- | ------------------------------- |
| **1**     | Initial Blind Guess              | 2 min          | ❌ No                           |
| **2**     | Reveal Small Sample              | 2 min          | ✅ 20%                          |
| **3**     | Reveal Another Small Sample      | 2 min          | ✅ 20%                          |
| **4**     | Reveal Medium Sample             | 2 min          | ✅ 10%                          |
| **5**     | Reveal Three More Medium Samples | 3 min          | ✅ 5%                           |
| **6**     | Reveal Final Large Sample        | 3 min          | ❌ No                           |
| **7**     | Final Scoring & Leaderboard      | -              | -                               |

---

## **🏅 How the Winner is Determined**

🏆 **The participant with the highest total score across all 7 colors in both jars at the end of the game wins!**

If two participants tie, the **tiebreaker** is:

1. **Who had the lowest average confidence interval width across all rounds.**
2. If still tied, **who had the highest single-color score in any round.**

---

## **📜 Final Summary**

✅ **All 7 colors are scored separately.**  
✅ **Final score = sum of all color scores across all rounds.**  
✅ **Smaller confidence intervals = higher score.**  
✅ **Too wide an interval? You get fewer points. Too narrow? Risk getting 0.**  
✅ **The later rounds are worth the most points.**  
✅ **Overcorrection penalties apply to encourage rational updates.**

---

🎯 **Play smart, update wisely, and may the best Bayesian win!** 🚀

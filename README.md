# ESG Investment Screener (Force for Good Simulation)

### Project Overview
I built this tool to explore the intersection of **Finance** and **Social Impact**. Specifically, it simulates how an analyst at JPMC might use technology to build "Ethical Portfolios" by filtering companies based on their **ESG (Environmental, Social, and Governance) scores**.

The goal was to automate the "Manual Toil" of checking company ethics and see if sustainable investing can actually compete with standard market returns.

---

### How it works:
The script processes a dataset of more then 10 major companies and compares their financial performance against their social responsibility ratings.
*   **The Logic:** It takes a user-defined "Ethics Threshold" (e.g., Score > 70).
*   **The Filter:** It automatically separates the market into "Ethical" vs. "High-Risk" categories.
*   **The Analysis:** It calculates the average return for the filtered portfolio to prove that you don't have to sacrifice profit for social good.

---

### Key Technical Features:
*   **Data Synthesis:** I Ingested and aggregated raw CSV data using the **Pandas** library.
*   **Business Analysis:** Implemented logic to compare portfolio ROI against market benchmarks.
*   **Automation:** Created a reusable function to screen equities, demonstrating how I apply automation to the Software Development Life Cycle.
*   **Sustainable Tech:** Directly aligns with JPMC's **Force for Good** mission by focusing on sustainable technology solutions.

---

### Tech Stack:
*   **Python 3**
*   **Pandas** (Data filtering and aggregation)
*   **Google Colab** (Development environment)

### Future Scope:
I'm planning to connect this to a live Financial API to pull real-time ESG scores and automate the reporting process even further.

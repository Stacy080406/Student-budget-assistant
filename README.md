# Student Budget and Saving Assistant

## What This Application Does
The **Student Budget and Saving Assistant** is a Python-based interactive tool designed to help students manage their money effectively. It takes a student's weekly income, expense categories (Rent, Food, Transport, Entertainment, and Other), current savings, and a savings target to calculate:
- Total weekly expenses
- Net money left over each week (or overspent amounts)
- Estimated time (in weeks) required to reach their savings goal
- Personalized, encouraging financial advice powered by Google's Gemini AI (persona: "PocketPal")

---

## Sample Input & Output

### Input Example:
- **Weekly Income:** AUD 600.00
- **Rent:** AUD 200.00
- **Food:** AUD 100.00
- **Transport:** AUD 40.00
- **Entertainment:** AUD 30.00
- **Other:** AUD 30.00
- **Current Savings:** AUD 200.00
- **Savings Goal:** AUD 1,000.00
- **User Question to AI:** "How am I tracking towards my goal?"

### Output Example:
```text
WEEKLY SPENDING BREAKDOWN
Rent: AUD 200.00
Food: AUD 100.00
Transport: AUD 40.00
Entertainment: AUD 30.00
Other: AUD 30.00

Weekly income: AUD 600.00
Total weekly expenses: AUD 400.00
Money left each week: AUD 200.00
Current savings: AUD 200.00
Savings goal: AUD 1,000.00
Amount still needed: AUD 800.00
Estimated time to reach the goal: 4 weeks.

Assumptions: all weekly money left is saved; income and expenses stay the same; interest is ignored.

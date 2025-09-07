# Finance360-Personal-Spending-Insights

## 🚀 Features
- **KPIs**: Total Income, Total Expenses, Actual vs Desired Savings, Savings Variance %, Savings Rate
- **Visuals**:
  - Income vs Expense distribution
  - Savings variance vs goals (Gauge Chart)
  - Age range analysis
  - Expense breakdown by category
  - Savings behavior across income brackets
  - Overspenders table and insights
- **Interactive Filters**: Age Range, City tier, Occupation, 

### 🔄 Data Transformation

The original dataset had expenses spread across multiple columns.
I used unpivoting to restructure the data:
- Converted individual expense columns into a single “Expense Amount” column.
- Created a corresponding “Expense Category” column to classify each transaction.
- This transformation allowed category-wise aggregation and simplified visualization.

### 📊 Key Performance Indicators (KPIs)

I built the following KPIs to summarize financial performance:

- Total Expense → Sum of all expense categories.
- Total Income → Aggregated income for the selected period.
- Actual Savings → Income – Expense.
- Desired Savings → User-defined savings goal.
- Savings Rate → (Actual Savings ÷ Income) × 100.
- Savings Variance → Actual Savings – Desired Savings.
- Savings Variance % → (Savings Variance ÷ Desired Savings) × 100.

---

## 🛠️ Tech Stack
- **Tool**: Power BI  
- **Dataset**: Indian Personal Finance & Spending Habits
- **Language**: DAX for measures  

---

## 🔍 Insights from the Dashboard

The dashboard not only visualizes income and expenses but also provides actionable insights based on the KPIs:

Expense Breakdown
- Clear identification of high-spend categories after unpivoting (Rent topped the list).
- Helped highlight which categories consistently contribute most to overall expenses.

Savings Performance
- Actual Savings consistently met or exceeded Desired Savings, indicating good control over expenses.
- The Savings Variance was positive, and the Savings Variance % highlighted how much savings went beyond the target (useful for tracking progress against goals).

Savings Rate
- Calculating savings as a % of income revealed a healthy savings rate, showing disciplined financial habits.
- Showed whether saving patterns were consistent or irregular across months.

Goal-Oriented Tracking
- Comparing Desired Savings with Actual Savings provided reassurance that financial goals were on track.
- Users can adjust future expenses or income targets based on variance trends.

---

## 📸 Dashboard Preview

<img width="1277" height="718" alt="image" src="https://github.com/user-attachments/assets/daa5bd64-6371-4582-8a9c-5036bded884d" />

<img width="1282" height="718" alt="image" src="https://github.com/user-attachments/assets/b604ad15-120e-4cc3-a5cc-4e406695d923" />

<img width="1302" height="717" alt="image" src="https://github.com/user-attachments/assets/eaab88ab-7951-4f0a-b104-54f19f9c30a4" />


---

## 📌 How to Use
1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/Finance360-Personal-Spending-Insights.git

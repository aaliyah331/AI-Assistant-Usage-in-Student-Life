# AI Assistant Usage in Student Life

This project explores how students interact with AI assistants during academic sessions, using a synthetic dataset from Kaggle. The goal is to uncover behavioral patterns, predict reuse likelihood, and identify key factors influencing satisfaction and engagement.

---

## Dataset

- **Source**: [AI Assistant Usage in Student Life (Synthetic)](https://www.kaggle.com/datasets/ayeshasal89/ai-assistant-usage-in-student-life-synthetic)
- Contains session-level data including:
  - Session length
  - Task type
  - Discipline
  - Satisfaction rating
  - AI assistance level
  - Whether the student reused the assistant

---

## Project Workflow

### 1. Data Cleaning & Preprocessing
- Handled missing values for categorical and numeric columns
- Encoded target variable (`UsedAgain`) and categorical features
- Scaled numeric features using `StandardScaler`

### 2. Feature Engineering
- Created new features:
  - `PromptsPerMinute`
  - `SessionHour`
  - `IsLongSession`

### 3. Bias Detection
- Encoded categorical variables for fairness analysis
- Prepared data for modeling with validation checks

### 4. Modeling
- Trained a `RandomForestClassifier` to predict reuse behavior
- Evaluated using accuracy, classification report, and confusion matrix

### 5. Visualization
- Distribution plots for engagement and satisfaction
- Correlation heatmap of numeric features
- Feature importance bar chart

---

## Key Visuals

- **Used Again Distribution**
- **Prompts Per Minute Histogram**
- **Long Sessions vs Reuse**
- **Correlation Heatmap**
- **Feature Importances**

---

## How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/aaliyah331/AI-Assistant-Usage-in-Student-Life.git
   cd AI-Assistant-Usage-in-Student-Life


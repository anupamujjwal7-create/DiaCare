# 🩸 DiaCare — Diabetes Management Platform

DiaCare is a Streamlit-based web application designed for self-management support and clinical data tracking for individuals with diabetes. The platform allows users to log blood glucose readings, store personal medical ratios (ICR, ISF, target glucose), calculate insulin doses, and log health metrics such as lab results, weight, blood pressure, ketones, and physical activity.

---

## 🌟 Features

* **Google OAuth Authentication:** Secure login using Google Sign-In powered by `streamlit-oauth`.
* **Personalized User Profile:**
  * Configure Diabetes Type (Type 1, Type 2, Gestational, Pre-diabetes).
  * Store Insulin-to-Carb Ratio (ICR), Insulin Sensitivity Factor (ISF), and Target Glucose Level.
  * Record Basal, Bolus, and Oral medication details.
* **Glucose Logging System:**
  * Log blood glucose readings with timing context (Fasting, Before/After Meal, Bedtime) and symptoms.
  * Displays real-time summary metrics (Latest Glucose, Average Glucose).
* **Insulin Dose Calculator:**
  * Calculates recommended bolus insulin based on carbohydrate intake and current blood glucose levels.
  * Breaks down dose into **Carb Coverage** and **Correction Coverage**.
* **Health History & Insights Dashboard:**
  * **Overview:** High-level key metrics and visual trend charts comparing glucose to physical activity.
  * **Lab Results:** Log HbA1c, Cholesterol, Triglycerides, and other lab values.
  * **Weight & Blood Pressure:** Monitor vital signs over time.
  * **Ketone Log:** Track blood or urine ketone readings.
  * **Activity Tracker:** Log exercise duration and activity type.

---

## 📂 Project Structure

```text
├── app.py                 # Main Streamlit application
├── client_secret.json     # Google OAuth credentials (User-provided)
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation

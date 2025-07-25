
# No-Show Appointments Analysis

**Dataset Source:** [Kaggle - NoShowAppointments](https://www.kaggle.com/datasets/joniarroba/noshowappointments/data)
**Goal:** Identify which factors influence whether a patient shows up for their medical appointment.

---

## 🔍 Step 1: Data Cleaning

Using Excel filters and formulas, the dataset was prepared by:

* Removing invalid rows (e.g., patients with age `< 0`)
* Standardizing column names for clarity
* Converting the `No-show` column into binary format:
  `No = 0 (Showed Up)`, `Yes = 1 (No-Show)`

---

## 📊 Step 2: Data Exploration with Pivot Tables

Pivot tables were used to compare various features against the no-show behavior:

**Examples:**

* **Rows:** Gender, Age Group, Day of the Week
* **Values:** Sum of No-Show (1 = missed appointment)

This helped surface correlations and inconsistencies between patient attributes and their attendance.

---

## 🧠 Step 3: Pattern Recognition & Critical Thinking

Key questions explored:

* Are older patients more likely to show up?
* Do chronic illnesses (e.g., hypertension, diabetes) increase attendance?
* Do SMS reminders reduce no-shows?
* Are there hidden variables affecting these patterns?

---

## 📈 Step 4: Visualizing the Insights

Visual tools (bar charts and graphs) were used to illustrate findings:

* No-show percentage by:

  * Age group (0–18, 19–60, 60+)
  * Gender
  * SMS Received status
* No-show vs. presence of chronic conditions (e.g., hypertension, alcoholism, diabetes)

---

## 🧾 Step 5: Key Insights

### 🔹 **Older Patients Show Up More**

* No-show rates decrease with age.
* Teenagers and young adults (especially 0–18) are more likely to miss appointments.

**Interpretation:**
Older individuals may be more health-conscious or consistent with appointments.
Younger patients might forget, deprioritize, or rely on others for transport and scheduling.

---

### 🔹 **Chronic Diseases Increase Attendance**

* Patients with chronic conditions such as hypertension and diabetes are more likely to attend.

**Interpretation:**
Ongoing treatment plans may lead to stronger appointment commitment.

---

### 🔹 **SMS Reminders Didn’t Reduce No-Shows**

* Surprisingly, patients who received SMS reminders had no lower (sometimes slightly higher) no-show rates.

**Critical Thinking:**

* This doesn’t prove that SMS causes no-shows.
* Possible explanations:

  * SMS reminders were only sent to high-risk patients.
  * Patients ignored or had already decided not to attend.

---

### 🔹 **Neighborhood Matters**

* Some neighborhoods had consistently higher no-show rates.

**Interpretation:**
This could reflect external factors not in the dataset, such as:

* Transportation accessibility
* Income level
* Work schedule flexibility

---

## 📌 Summary Report

Several factors seem to influence whether a patient shows up:

* **Age:** Older patients attend more reliably.
* **Chronic conditions:** Patients managing health conditions are more consistent.
* **Time gap between scheduling and appointment day:** Longer wait times lead to more no-shows.
* **SMS reminders:** Showed limited effectiveness, possibly due to targeting or message content.
* **Neighborhood differences:** Suggest deeper socioeconomic influences.
* 
![med2](https://github.com/user-attachments/assets/671e7fae-8244-4fea-90cd-b600edc9febc)

![med1](https://github.com/user-attachments/assets/cd3a5876-a2b3-46b9-a004-09ea35f09a22)

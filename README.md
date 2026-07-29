# Hi, I'm Jayne 👋

Computer Science graduate (University of Wollongong) with a Data Science foundation from Ngee Ann Polytechnic. I like taking messy, real-world data — tax spreadsheets, sensor logs, tweets, car photos — and turning it into something a non-technical stakeholder can actually use. Comfortable across the full pipeline: cleaning and wrangling, modelling, evaluation, and dashboards.

📄 [Live portfolio site](https://jayne5.github.io/portfolio/) · 💼 [LinkedIn](https://www.linkedin.com/in/tan-zi-yi-jayne-profile/) · ✉️ [Email](mailto:jaynetzy12@gmail.com)

---

## 🧰 Toolbox

`Python` `Pandas / NumPy` `scikit-learn` `PyTorch` `XGBoost · CatBoost · LightGBM` `SQL` `Power BI (DAX)` `Alteryx` `Excel VBA` `.NET / C#` `Jupyter / Colab`

---

## 🚀 Featured Projects

### 🏠 HDB Resale Price Prediction — *Final Year Project*
Predicts Singapore public housing (HDB) resale prices by fusing the standard resale transaction data with two datasets most public models ignore: **government policy changes** (e.g. cooling measures) and **SORA interest-rate movements**, plus geocoding via the **OneMap API** for location features.
- Built and tuned **XGBoost, CatBoost, and LightGBM** regressors (log-target transform, `RandomizedSearchCV`), then combined them into a blended ensemble
- Engineered leakage-safe features — block/street-level rolling & expanding median price-per-sqft, each using `shift(1)` so no transaction ever "sees" its own future
- Best model (XGBoost) reached **R² = 0.92**, MAE ≈ $41.9K, RMSE ≈ $57.5K on held-out resale transactions
- A teammate built a demo interface that calls my trained model to produce live valuations, confidence scores, and value breakdowns
- `Python` `XGBoost` `CatBoost` `LightGBM` `scikit-learn` `Feature Engineering` `REST API`

### 🚗 Car Model Recognition (Stanford Cars)
Team project fine-tuning three ImageNet-pretrained CNNs on the **Stanford Cars** dataset (196 fine-grained classes) to recognise make/model/year from a single photo, then comparing them head-to-head.
- Fine-tuned **EfficientNetV2-M** — my component of the 3-model comparison, alongside teammates' ConvNeXt-S and ResNet-101 — using bbox-cropping, augmentation, and mixed-precision training
- Contributed to the team's shared evaluation pipeline: cross-model accuracy comparison and top-confused-class analysis
- `PyTorch` `Torchvision` `Transfer Learning` `Computer Vision`

### 🐦 Twitter Sentiment Classification — *Group Project*
Compared classical and deep-learning approaches for classifying sentiment in tweets, as part of a 4-person team.
- Built a **CNN text classifier** in Keras (Embedding → Conv1D → GlobalMaxPooling1D → Dense), my component, benchmarked against teammates' **Multinomial Naive Bayes**, **Logistic Regression**, and **Linear SVC** models
- Tuned it with **RandomizedSearchCV** over filter count, kernel size, dropout rate and epochs, and handled class imbalance with **RandomOverSampler** inside an imblearn pipeline
- Reached AUC of 0.92–0.95 across all three sentiment classes (one-vs-rest ROC) on the held-out test set
- `Python` `NLP` `CNN` `Keras` `scikit-learn` `Text Preprocessing`

### 🚢 Endine — Cruise Booking System Database Design — *Team Project (2-person)*
Designed the relational database for Endine, a mock cruise booking platform letting passengers request cabin services, reserve restaurant seats, and plan onboard activities and entertainment.
- Researched real restaurant and entertainment booking platforms to define functional and data requirements before modelling anything
- Designed the full entity-relationship diagram by hand across cabin services, restaurant/dining hall reservations, entertainment, and activity bookings, with each entity's attributes and relationships defined
- Revised the design through several rounds of feedback — reworking how bookings referenced activity/entertainment timeslots and consolidating overlapping menu entities
- `Database Design` `ER Modelling` `Relational Databases` `Requirements Gathering`

### 🏢 Facility Maintenance & Operations Analytics — *Data Science Capstone*
An end-to-end analytics solution for optimizing campus facility management at Ngee Ann Polytechnic, combining **7 disparate data sources**: energy consumption, fault reports, water metering, canteen crowd levels, card access logs, solar panel output, and building automation data.
- Cleaned and merged multi-format datasets (Python/Jupyter + Alteryx + Power Query)
- Authored custom **DAX measures** in Power BI (e.g. peak-usage detection, week-of-month rollups, anomaly flags for solar underperformance) to power interactive dashboards
- `Python` `Power BI` `DAX` `Data Cleaning` `Descriptive & Predictive Analytics`

### 💼 PwC Digital Tax — Internship Portfolio — *20-week Internship*
Delivered 4 automation projects for PwC's Digital Tax team, cutting manual data-entry work across finance workflows.
- Built an **Alteryx** workflow from scratch to consolidate transactions across 3 source spreadsheets into partner-level reports
- Extended a second Alteryx workflow to calculate employee utilization (MTD/YTD/weekly/monthly) and write results back to a database
- Fixed **Excel VBA macros** generating XML tax filings to correctly escape special characters per IRAS spec, and enforced decimal-rounding rules
- Integrated a **.NET/C# OAuth token flow** to call an internal API and retrieve corporate tax report data
- `Alteryx` `Excel VBA` `C# / .NET` `REST APIs` `Process Automation`

---

## 🎓 Education

**Bachelor's Degree in Computer Science** — University of Wollongong

**Diploma in Data Science** — Ngee Ann Polytechnic, School of InfoComm Technology (2021–2024)

---

## 📫 Get in touch

Open to data analyst / junior data scientist roles. Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/tan-zi-yi-jayne-profile/) or [email](mailto:jaynetzy12@gmail.com).

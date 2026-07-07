# Hi, I'm Jayne 👋

Data Science graduate (Ngee Ann Polytechnic) who likes taking messy, real-world data — tax spreadsheets, sensor logs, tweets, car photos — and turning it into something a non-technical stakeholder can actually use. Comfortable across the full pipeline: cleaning and wrangling, modelling, evaluation, and dashboards.

📄 [Live portfolio site](#) · 💼 [LinkedIn](#) · ✉️ [Email](#)

*(swap the `#` placeholders above for your real links once this repo is live)*

---

## 🧰 Toolbox

`Python` `Pandas / NumPy` `scikit-learn` `PyTorch` `XGBoost · CatBoost · LightGBM` `SQL` `Power BI (DAX)` `Alteryx` `Excel VBA` `.NET / C#` `Jupyter / Colab`

---

## 🚀 Featured Projects

### 🏠 HDB Resale Price Prediction — *Final Year Project*
Predicts Singapore public housing (HDB) resale prices by fusing the standard resale transaction data with two datasets most public models ignore: **government policy changes** (e.g. cooling measures) and **SORA interest-rate movements**, plus geocoding via the **OneMap API** for location features.
- Built and tuned **XGBoost, CatBoost, and LightGBM** regressors (log-target transform, `RandomizedSearchCV`), then combined them into a blended ensemble
- Evaluated with MAE / RMSE / R² / MAPE to benchmark accuracy against a naive baseline
- `Python` `XGBoost` `CatBoost` `LightGBM` `scikit-learn` `Feature Engineering` `REST API`

### 🚗 Car Model Recognition (Stanford Cars)
Fine-tuned three ImageNet-pretrained CNN architectures on the **Stanford Cars** dataset (196 fine-grained classes) to identify make/model/year from a single photo, then ran a head-to-head evaluation.
- Fine-tuned **ConvNeXt-S**, **ResNet-101**, and **EfficientNetV2-M** in PyTorch with bbox-cropping, augmentation, and mixed-precision training
- Built a separate evaluation pipeline: accuracy comparison across models, **top-confused-class analysis**, and **Grad-CAM / Score-CAM** visualizations to explain what the model was "looking at"
- `PyTorch` `Torchvision` `Transfer Learning` `Grad-CAM` `Computer Vision`

### 🐦 Twitter Sentiment Classification — *Group Project*
Compared classical and deep-learning approaches for classifying sentiment in tweets, as part of a 4-person team.
- Built and evaluated a **CNN text classifier** (my component), benchmarked against teammates' **Multinomial Naive Bayes**, **Logistic Regression**, and **Linear SVC** models
- Ran the full comparison twice — before and after **class-balancing** — plus grid-search tuning, to show how balancing shifted precision/recall trade-offs across models
- `Python` `NLP` `Keras/TensorFlow` `scikit-learn` `Text Preprocessing`

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

**Diploma in Data Science** — Ngee Ann Polytechnic, School of InfoComm Technology (2021–2024)

---

## 📫 Get in touch

Open to data analyst / junior data scientist roles. Feel free to reach out via [LinkedIn](#) or [email](#).

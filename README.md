<!-- Background github cover with short introduction down below -->
<img src="assets/WWE-BGCover3.jpg" />

# 💫 WWE Superstar Popularity Tier Prediction 

<!-- Background github cover with short introduction down below 
<img src="https://github.com/flexycode/CTINFMGL/blob/main/asset/Information-Management.png" />
-->

### Team Name: [Artificial Ledger](https://www.youtube.com/watch?v=-er2ruCgzjg&list=RDfFqxDrmQLnQ&index=4)  
### Subject & Section: [CCMACLRL - COM231ML](https://www.youtube.com/watch?v=fFqxDrmQLnQ&list=RDfFqxDrmQLnQ&start_radio=1)
### Schedule: [TUE 11:00AM - 01:40 PM VR09CCIT - FRI 11:00AM - 03:00 PM 408 MB](https://www.youtube.com/watch?v=dL7Vn7hJDAk&list=RDdL7Vn7hJDAk&start_radio=1)
### Professor: [Elizer Ponio Jr](https://github.com/robitussin/)     
### No. of Units: [3 Units](https://www.youtube.com/watch?v=UVJSA2N39NU&list=RDUVJSA2N39NU&start_radio=1)
### Prerequisite: [None](https://www.youtube.com/watch?v=v3BBE7wtuIM&list=RDv3BBE7wtuIM&start_radio=1)


<!-- 🤖 Machine Learning 🤖 -->
<div align="center">
<img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZXJna2t4azF0d3Qxc3c4cnQyMzNpZTFiZmJtYWQ2Znk5ZTIyZXM3dyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/POImbcaDpzBrk5jDCD/giphy.gif" width="250">
<img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3c2sxYjJ0ZXNxNzFtb2tweWthdDk1Y2V1dnVuZmo1d3YxNHloZXc1ZyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/j2k3CEUW5qga5nHUml/giphy.gif" width="300">
<img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZXJna2t4azF0d3Qxc3c4cnQyMzNpZTFiZmJtYWQ2Znk5ZTIyZXM3dyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/5bgVvcQz3gFgindtSk/giphy.gif" width="250">
</div>


<!-- Table of contents down below -->
# 📊 Table of Contents

- [Introduction](#-introduction) 
- [Key Features](#-key-features)           
- [Folder Structure](#-folder-structure) 
- [Contributing](#-contributing)           
- [License](#-license)   
- [Acknowledgements](#-acknowledgements) 
- [FAQ](#-faq)       
- [Changelog](#-changelogs)   


<!-- Introduction down below -->
# 🧠 [Introduction](#introduction)

<!-- Background github cover with short introduction down below -->
<img src="assets/All-Wrestling-Brand.jpg" />

## 📋 Project Overview

A comprehensive machine learning system that predicts WWE superstar popularity tiers (Main Eventer, Midcard, Enhancement) based on career statistics and performance metrics. This multi-class classification project demonstrates end-to-end ML pipeline development with robust validation and deployment-ready features.

<!-- Background github cover with short introduction down below -->
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExdXk2cnByenBzdHR2Y2plYmxyYnVoY2pjaWRlOTRjcTBrMWV3czI0diZlcD12MV9naWZzX3NlYXJjaCZjdD1n/TH1EAFhvE2ucRSMkPC/giphy.gif" width="300">

## 🎯 Business Problem

WWE management needs to understand what factors contribute to a wrestler's success and popularity tier placement. This model helps in:
- Talent development and scouting
- Brand strategy optimization
- Performance metric analysis
- Predictive roster managemen

## 📊 Dataset Description

### Primary Dataset: `wwe_rosters.csv`
- **185 wrestlers** with comprehensive career statistics
- **15+ features** including match history, title reigns, social media presence
- **Target Variable**: `popularity_tier` (Main Eventer, Midcard, Enhancement)

### External Validation: `other_brand_rosters.csv`
- **550 wrestlers** from various wrestling promotions (AEW, NJPW, Impact, etc.)
- Used for model generalization testing

### Key Features:
- **Career Metrics**: `years_active`, `total_matches`, `career_win_percentage`
- **Accolades**: `world_title_reigns`, `secondary_title_reigns`, `tag_title_reigns`
- **Performance**: `avg_matches_per_month`, `main_evented_ppv`
- **Popularity**: `social_media_followers_millions`
- **Demographics**: `age`, `weight_class`, `brand`

## 🧠 Wrestler Roster Data source link

- [WWE: World Wrestling Entertainment Roster](https://www.thesmackdownhotel.com/roster/?promotion=wwe&show=face-heel#nxt)
- [AEW: All Elite Wrestling Roster](https://www.allelitewrestling.com/aew-roster)
- [TNA: Total Nonstop Action Wrestling Roster](https://www.ringofhonor.com/roster)
- [ROH: Ring of Honor Roster](https://www.thesmackdownhotel.com/roster/?promotion=roh&date=2025-10-05)
- [NJPW: New Japan Pro Wrestling Roster](https://www.thesmackdownhotel.com/roster/?promotion=njpw&date=2025-10-05)
- [NWA: National Wrestling Alliance Roster](https://www.thesmackdownhotel.com/roster/?promotion=nwa&date=2025-10-05)
- [OVW: Ohio Valley Wrestling Roster](https://www.thesmackdownhotel.com/roster/?promotion=ovw&date=2025-10-05)
- [AAA: Lucha Libre AAA Worldwide Roster](https://www.thesmackdownhotel.com/roster/?promotion=aaa&date=2025-10-05)
- [AJPW: All Japan Pro Wrestling Roster](https://www.thesmackdownhotel.com/roster/?promotion=ajpw&date=2025-10-05#ajpw-all-8)
- [NOAH: Pro Wrestling NOAH Roster](https://www.thesmackdownhotel.com/roster/?promotion=noah&date=2025-10-05)
- [MLW: Major League Wrestling Roster](https://www.thesmackdownhotel.com/roster/?promotion=mlw&date=2025-10-05)
- [FPW: Filipino Pro Wrestling Roster](https://www.filipinoprowrestling.com/roster)


## 🏗️ Model Architecture

### Multi-class Classification Approach

```
Data Pipeline:
Raw Data → Preprocessing → Feature Engineering → Model Training → Evaluation → Deployment

Model Stack:
1. Baseline Models (6 classifiers)
2. Hyperparameter Tuning (GridSearchCV)
3. Ensemble Selection
4. External Validation
```


### Algorithm Selection Rationale

| Model | Strengths | Use Case |
|-------|-----------|----------|
| **Random Forest** | Handles non-linearity, feature importance | Primary model |
| **SVM** | High-dimensional spaces, kernel tricks | Complex patterns |
| **Gradient Boosting** | Sequential learning, high accuracy | Final ensemble |
| **Logistic Regression** | Interpretability, baseline | Benchmark |

## 🔧 Technical Implementation

### 1. Data Preprocessing Pipeline

```python
# Robust preprocessing with error handling
def preprocess_data(df):
    # Handle missing values (median imputation)
    # Feature engineering (matches_per_year, titles_per_year)
    # Categorical encoding (LabelEncoder)
    # Outlier detection and treatment
    # Feature scaling (StandardScaler)
```

### 2. Feature Engineering

#### Created Features:

- `matches_per_year`: Career activity density

- `titles_per_year`: Championship efficiency

- `main_event_frequency`: Main event appearance rate

### 3. Model Training Strategy

```
# Multi-stage training approach
1. Baseline model comparison (6 algorithms)
2. Hyperparameter tuning (GridSearchCV, 5-fold CV)
3. Cross-validation performance analysis
4. Final model selection based on multiple metrics
```

### 4. Evaluation Framework

#### Metrics Tracked:



<!-- Background github cover with short introduction down below -->
<img src="assets/AEW-Dynamite.jpg" />

<!-- 🏆 Contributers down below -->
# 🏆 Contributing     

### Contributing     
If you would like to contribute to the Flight Booking App, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request to the main repository.

### 🧠 Submitting Changes

🧠 Contributions are welcome! If you have ideas for improvements or want to add more exercises, follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push to your fork and submit a pull request. 💕💕💕💕

<!-- Contributors down below, kindly paste your github URL thanks and also you can revise your suited job title position -->
### 👋 Contributors
### Special thanks to all my groupmates: 
 * ####  😎 [Jay Arre Talosig](https://github.com/flexycode) - Machine Learning Engineer | Blockchain Developer | Bioinformatics Scientist    
 * ####  🧭 [Queen Maegan Pedido](https://github.com/mgnpdd) - Machine Learning Engineer | Software Engineer 
 * ####  💥 [Moira Mercado](https://github.com/mnmzz) - Machine Learning Engineer | Software Engineer 
 * ####  🎲 [James Adrian Castro](https://github.com/debug-phantom) - Machine Learning Engineer | Software Engineer

# 🛸 FAQ
<!--  Reporting issues -->
### 🛸 Reporting Issues

```bash
Some changes need to be address
- TBA
- TBA
- TBA
```

###### 🤖 If you encounter any issues or have suggestions, please open an issue to let us know.

<!--  License will provide soon -->
# 🔑 License     

<!-- 🤖 Machine Learning 🤖 -->
<div align="center">
<img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3M3A1bG92MXN3dzB5ZTJwaGs5YXc4dHh4dGxram13Y3JiZWd0YXRxMyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/elu4qryud82iJDlb3Q/giphy.gif" width="250">
<img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3ZXJna2t4azF0d3Qxc3c4cnQyMzNpZTFiZmJtYWQ2Znk5ZTIyZXM3dyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/C9M9Kk0mF3o7C8vngg/giphy.gif" width="300">
<img src="https://media.giphy.com/media/v1.Y2lkPWVjZjA1ZTQ3M3A1bG92MXN3dzB5ZTJwaGs5YXc4dHh4dGxram13Y3JiZWd0YXRxMyZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/1JfIhHFTqPCKm6dd6Q/giphy.gif" width="250">
</div>

```
Coming Soon In the License tab 
```

# 🔭 Acknowledgements     

<!--  Need to revise this background info of Professor Elizer Ponio Jr  -->
### ✨ Professor

```
Coming Soon 
```

<!-- Always document your changes, pull-request, bugfix, updates, patch notes for this final project. Always use this "🧊 ML Project" for commiting message for "pushing code" or "Pull-request"   -->

<!-- Background github cover with short introduction down below -->
<img src="assets/TNA.jpg" />

# 📫 Changelogs 
Chronological list of updates, bug fixes, new features, and other modifications for our Machine Learning Project.

## 💻 [01.0.0] - 2025-09-29      
### Role & Project Management
- 💻 Final Project requirements for our project
- ✨ TBA
- ✨ TBA

### Commit message for pushing or pull-request  
🧊 ML Final Project

<!-- This comment is intended for commiting message in pull-request 
Always use this "🧊 Flight Booking" for commiting message for "Pull-request"
<!-- End point line for this comment  -->

  
<!-- Introduction Pannel button link, it will redirect to the top -->
#### [Back to Table of Content](#-introduction)

<!-- End point line insert Thanks for visiting enjoy your day, feel free to modify this  -->
---
<p align="center">
<img src="https://readme-typing-svg.demolab.com/?lines=Thanks+For+Visiting+Enjoy+Your+Day+~!;" alt="mystreak"/>
</p>

<!-- Genshin Impact -->
<div align="center">
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZGxxeWR5bzJjajBnc3o5YTc5dGhzc2xsYWJ4aW5rOGZuamNtMjdnayZlcD12MV9naWZzX3NlYXJjaCZjdD1n/1rL7L4GaUTe55s5Sfm/giphy.gif" width="300">
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExdXk2cnByenBzdHR2Y2plYmxyYnVoY2pjaWRlOTRjcTBrMWV3czI0diZlcD12MV9naWZzX3NlYXJjaCZjdD1n/TH1EAFhvE2ucRSMkPC/giphy.gif" width="300">
</div>

<!-- End point line insert Comeback again next time, feel free to modify this  -->
<p align="center">
<img src="https://readme-typing-svg.demolab.com/?lines=Come+Back+Again+next+time" alt="mystreak"/>
</p>

</p>
    
<br>
<!-- End point insert background effect line of sight color red -->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="1000">


   


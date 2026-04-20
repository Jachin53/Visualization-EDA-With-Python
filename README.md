# Visualization-EDA-With-Python

## 📌 Overview
This project is part of my **Python learning journey** where I explore **Exploratory Data Analysis (EDA)** and **data visualization**. I'm building this to understand how data tells stories through visualizations and statistical summaries. The goal is to move from knowing Python syntax to analyzing real-world data as a data analyst.

## 👋 About This Project (Learning Context)
> *"I'm currently learning Python."*

This repository documents what I've learned about:
- Loading and inspecting datasets using **Pandas**
- Cleaning messy data (handling missing values, duplicates, outliers)
- Creating meaningful visualizations with **Matplotlib** & **Seaborn**
- Interpreting plots to find patterns and insights

Every notebook and script here reflects my growing understanding of data analysis workflows.

---

## 📊 What This Project Covers

### 1. Data Cleaning & Preprocessing
- Handling missing values (`.isnull()`, `.dropna()`, `.fillna()`)
- Removing duplicates
- Detecting and treating outliers (IQR method, Z-score)
- Renaming columns and fixing data types

### 2. Exploratory Data Analysis (EDA)
- **Univariate analysis**: Histograms, box plots, bar charts for single variables
- **Bivariate analysis**: Scatter plots, grouped bar charts, correlation analysis
- **Multivariate analysis**: Pair plots, heatmaps, facet grids

### 3. Visualizations on Databricks
| Visualization | Purpose | Libraries Used |
|---------------|---------|----------------|
| Histograms | Distribution of numerical data | Matplotlib, Seaborn |
| Box plots | Identifying outliers & spread | Seaborn |
| Scatter plots | Relationships between variables | Matplotlib |
| Heatmaps | Correlation matrices | Seaborn |
| Bar charts | Comparing categories | Pandas plot, Matplotlib |
| Line plots | Trends over time (if time data exists) | Matplotlib |

---

## 📈 Key Insights & Findings

### 📅 Weekly Trends
| Day | Views | Performance |
|-----|-------|-------------|
| Friday | 1.34K | 🔥 Peak |
| Saturday | 1.33K | 🔥 Peak |
| Wednesday | 1.31K | 🔥 Peak |
| Sunday | ~1.2K | Moderate |
| Tuesday | ~1.15K | Moderate |
| Thursday | ~1.1K | Moderate |
| Monday | 824 | ⚠️ Low |

**Key Takeaways:**
- **Peak Days**: Friday, Saturday, and Wednesday are prime for high-impact programming or advertising
- **Low Day**: Monday shows audience fatigue after weekend - opportunity to test lighter, engaging content
- **Balanced Mid-Range**: Sunday, Tuesday, Thursday show stable yet moderate engagement

---

### 📆 Monthly Trends

| Month | Views | Trend |
|-------|-------|-------|
| March | 3.99K | 📈 Strongest (peak) |
| February | 2.49K | 📈 Growing |
| January | 1.83K | 📊 Baseline |
| April | Negligible | ⚠️ Drop-off (data incomplete?) |

**Key Takeaways:**
- **Strongest Month**: March dominates with nearly double January's views
- **Consistent Growth**: February shows steady climb, building momentum into March
- **Weak Month**: April shows minimal activity (investigate data completeness or seasonal factors)

---

### ⏰ Hourly Trends

| Time Slot | Views | Performance |
|-----------|-------|-------------|
| 16:00 | 545 | 🔥 Absolute Peak |
| 15:00-17:00 | High | 🔥 Peak Window |
| 18:00-23:00 | 314+ | 📊 Strong Evening |
| 10:00-14:00 | Building | 📈 Afternoon Build-up |
| 6:00-9:00 | Low-Moderate | 🌅 Morning Momentum |
| 0:00-5:00 | <50 | ⚠️ Overnight Low |

**Key Takeaways:**
- **Peak Hours**: Strongest engagement between 15:00-17:00
- **Afternoon Build-Up**: Views steadily rise from late morning
- **Evening Decline**: Tapers after 17:00 but remains strong until 23:00
- **Low Hours**: Early morning (0-5 AM) has minimal activity

---

### 👥 Demographic Insights

#### Audience by Race/Ethnicity

| Demographic | Percentage | Views |
|-------------|------------|-------|
| Black | 44.55% | Largest segment |
| Indian/Asian | 17.03% | Strong mid-tier |
| Coloured | 16.43% | Strong mid-tier |
| White | 11.57% | Notable minority |
| Unknown | 9.22% | Data gap |

**Key Takeaways:**
- **Majority Audience**: Black viewers represent nearly half of total audience
- **Secondary Segments**: Indian/Asian + Coloured = one-third of viewership
- **Growth Opportunity**: Unknown segment needs better data capture

#### Audience by Gender

| Gender | Views | Percentage |
|--------|-------|------------|
| Male | 7.29K | 87.7% |
| Female | 827 | 9.9% |
| Unknown | 196 | 2.4% |

**Key Takeaways:**
- **Male Dominance**: Overwhelmingly largest segment - programming strongly resonates with males
- **Female Segment**: Much smaller share - indicates untapped opportunity
- **Unknown Segment**: Highlights gaps in audience profiling

---

### 📱 Social Handle Insights

| Handle | Views | Tier |
|--------|-------|------|
| @Remi_d39 | 211 | 🏆 Top Performer |
| @valerio25 | ~190 | 📊 Mid-Tier |
| @Luca23 | ~185 | 📊 Mid-Tier |
| @charlie36 | ~180 | 📊 Mid-Tier |
| Unknown | 196 | ⚠️ Unidentified |

**Key Takeaways:**
- **Top Performer**: @Remi_d39 shows strong individual influence
- **Competitive Mid-Tier**: Several handles clustered together
- **Tracking Gap**: Notable views from unidentified sources

---

### 📺 Channel Insights

| Channel | Views | Category |
|---------|-------|----------|
| Supersport Live Events | 1.32K | 🏆 Sports |
| ICC Cricket World Cup 2011 | 1.17K | 🏆 Sports |
| Channel O | 932 | 🎵 Music |
| Trace TV | 801 | 🎵 Lifestyle |
| Cartoon Network | 675 | 👨‍👩‍👧 Family/Kids |
| Boomerang | 585 | 👨‍👩‍👧 Family/Kids |
| CNN | 410 | 📰 News |
| E! Entertainment | 312 | ⭐ Niche |

**Key Takeaways:**
- **Sports Dominance**: Clear leader in driving engagement
- **Music & Lifestyle Appeal**: Strong traction for entertainment content
- **Family & Kids**: Steady demand for children's programming
- **News & International**: Serves niche audiences

---

## 🎯 Strategic Recommendations

### Programming Strategy
- **Anchor Content**: Continue investing in live sports rights and coverage
- **Peak Slots**: Schedule flagship shows on Friday, Saturday, Wednesday at 15:00-17:00
- **Diversify**: Expand music, lifestyle, and family programming to balance appeal
- **Test & Learn**: Use Monday and April for experimental formats

### Audience Growth Strategy

#### Female Engagement (Priority)
- Introduce female-oriented programming (lifestyle shows, dramas, talk shows)
- Run targeted marketing campaigns for female audiences
- Collaborate with female influencers

#### Unknown Segments (9.22% race + 2.4% gender)
- Improve audience profiling systems
- Encourage viewer registration and preferences
- Conduct technical audit of tracking systems

#### Inclusive Programming
- Black audience (44.55%): Culturally resonant content, local dramas, music, sports
- Indian/Asian & Coloured (33% combined): Bollywood films, regional music, lifestyle shows
- White audience (11.57%): International news, lifestyle, family programming

### Advertising & Monetization
- **Premium Slots**: Sell around sports and male-heavy content at peak times
- **Segmented Packages**: Offer demographic-specific bundles
- **Weak Periods**: Discounted packages for Monday, early morning, April
- **Cross-Promotion**: Use sports broadcasts to promote other genres

### Social & Influencer Strategy
- **Leverage Top Performers**: Collaborate with @Remi_d39 for promotions
- **Grow Mid-Tier**: Support rising handles with co-branded content
- **Resolve Unknown**: Improve tracking of social handle sources

### Data & Analytics
- **Enrichment**: Reduce "Unknown" categories through better capture
- **Tracking Audit**: Fix systems failing to classify viewers correctly
- **Regular Reporting**: Monitor weekly, monthly, and hourly trends

---

## 🛠️ Technologies & Libraries Used

| Tool/Library | Purpose |
|--------------|---------|
| **Databricks** | Cloud-based data platform |
| **Python 3.x** | Core programming language |
| **Pandas** | Data manipulation & analysis |
| **NumPy** | Numerical operations |
| **Matplotlib** | Basic plotting & visualization |
| **Seaborn** | Statistical visualizations |

---

## 📁 Repository Structure

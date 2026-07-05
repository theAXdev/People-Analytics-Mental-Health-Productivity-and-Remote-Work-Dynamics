# 🧠 Workforce Intelligence — Mental Health, Productivity & Remote Work Dynamics

> A dual-tool people analytics project investigating the mental health, productivity, and remote work experience of 5,000 global employees. Built using Microsoft Excel and Microsoft Power BI — with a supplementary Google Forms validation survey — this project demonstrates an end-to-end analytics workflow across two of the most widely used platforms in the modern workplace.

---

![Dashboard Preview](Workforce_Intelligence_Dashboard.jpg)

---

## 📌 Project Background

The global shift toward remote and hybrid work has fundamentally changed how employees experience their jobs. Yet most organisations design wellbeing programmes based on assumption rather than evidence — allocating resources to the wrong populations, measuring the wrong outcomes, and missing the structural factors that actually drive stress, burnout, and dissatisfaction.

This project addresses that gap. Using a 5,000-employee global workforce dataset, the analysis investigates how work mode, sleep quality, virtual meeting frequency, company support, and regional access to mental health resources interact to shape employee wellbeing and productivity.

What makes this project distinctive is its **dual-tool methodology**: Microsoft Excel was used for data modelling, Pivot Table construction, and the first-layer dashboard. Microsoft Power BI was then used to extend the analysis with advanced chart types, a regional map visual, DAX-powered KPI cards, and a multi-page interactive report. This mirrors how real-world analytics teams operate — using each tool at the stage of the lifecycle where it performs best.

A supplementary **Google Forms internal survey** was conducted to validate key patterns identified in the Kaggle dataset. The directional findings aligned consistently — particularly around virtual meeting stress and remote work satisfaction — providing qualitative corroboration of the quantitative results.

---

## 🎯 Project Objectives

- Determine how prevalent mental health conditions are across different job roles, work modes, industries, and regions
- Quantify the relationship between sleep quality and employee productivity
- Examine whether virtual meeting frequency meaningfully impacts stress levels — and identify the threshold at which the effect becomes significant
- Investigate how company support for remote work moderates the relationship between work mode and employee satisfaction
- Identify which employee segments are most at risk and require the most urgent intervention
- Deliver structured, evidence-based recommendations for HR leadership and people operations teams

---

## ⚙️ Tools & Methodology

| Tool | Role in This Project |
|---|---|
| **Microsoft Excel** | Data quality review, Pivot Table construction, calculated fields, conditional formatting, first-layer dashboard with slicers |
| **Microsoft Power BI** | Advanced chart types (Gauge, Ribbon, Matrix, Map), DAX KPI measures, multi-page interactive report with cross-filter slicers |
| **Google Forms** | Supplementary internal survey for pattern validation — directional corroboration of Kaggle findings |
| **DAX (Data Analysis Expressions)** | Custom percentage KPI measures, average rating calculations, conditional filtering |
| **GitHub** | Project documentation, portfolio hosting, and version control |

### Dual-Tool Design Philosophy

| Excel — Layer 1 | Power BI — Layer 2 |
|---|---|
| Pivot Table aggregation, calculated field design, and conditional formatting for rapid data exploration | Advanced visualisation, DAX-powered interactivity, and multi-page stakeholder reporting |
| Optimised for structured survey data slicing and first-pass analytical discovery | Optimised for executive-ready presentation, regional mapping, and cross-filter drill-down |

---

## 📊 Key Metrics at a Glance

| Metric | Value |
|---|---|
| Total Employees Surveyed | 5,000 |
| Report a Mental Health Condition | 78.6% |
| Satisfied with Remote Work | 34.1% |
| Report a Productivity Increase | 35.6% |
| High Stress Level | 33.5% |
| Average Social Isolation Rating | 3.14 / 5 |
| Average Work-Life Balance Rating | 3.19 / 5 |

---

## 🗄️ Dataset

| Field | Detail |
|---|---|
| Primary Source | Kaggle — Remote Work and Mental Health Dataset |
| Secondary Source | Google Forms internal validation survey |
| Size | 5,000 employee records |
| Structure | One row per employee — demographics, work mode, mental health, productivity, wellbeing scores |

### Variable Categories

**Independent Variables — Demographics & Structure**
- Gender, Age Group, Region, Work Mode (Remote / Hybrid / Onsite), Industry

**Independent Variables — Behavioural & Environmental**
- Virtual Meeting Frequency, Physical Activity, Sleep Quality, Commute Time, Company Support for Remote Work

**Dependent Variables — Outcomes**
- Productivity Change (Increase / Decrease / No Change)
- Stress Level (High / Medium / Low)
- Remote Work Satisfaction

**Mental Health Variable**
- Anxiety, Burnout, Depression, or None — self-reported by each employee

**Scaled Wellbeing Scores (1–5)**
- Social Isolation Rating, Work-Life Balance Rating

---

## 📈 Mental Health by Job Role

| Job Role | Anxiety | Burnout | Depression | None | Total |
|---|---|---|---|---|---|
| Data Scientist | 169 | 225 | 167 | 135 | 696 |
| Designer | 245 | **296** | 290 | 107 | **938** |
| HR | 184 | 194 | 185 | 153 | 716 |
| Marketing | 170 | 158 | 143 | 212 | 683 |
| Project Manager | **239** | 215 | 216 | 198 | 868 |
| Sales | 131 | 104 | 126 | 103 | 464 |
| Software Engineer | 153 | 153 | 168 | 161 | 635 |
| **Total** | **1,291** | **1,345** | **1,295** | **1,069** | **5,000** |

Designers report the highest burnout (296) and the largest total cohort (938). Project Managers report the highest anxiety (239). Software Engineers show an unusually even distribution across all three conditions — suggesting broad, evenly distributed stress rather than a single dominant pressure point.

---

## 🔍 Key Findings

### 1. Mental Health Is a Systemic Crisis — Not an Edge Case
78.6% of 5,000 employees report at least one mental health condition. Only 1,069 employees (21.4%) reported no condition. This is not a minority concern — it is the majority workforce experience. Any wellbeing strategy treating mental health as a supplementary benefit rather than a core operational priority is structurally misaligned with this reality.

### 2. Remote Work Without Support Increases Stress
This is the dataset's most counter-intuitive and most important finding. Remote working without adequate company support correlated with higher stress levels — not lower. Remote work policy and support infrastructure must be designed together. Deploying remote work as a standalone offering without investment in tooling, check-in structures, and team connection is actively harmful to employee wellbeing.

### 3. Sleep Quality Is the Strongest Individual Productivity Lever
Poor sleep quality produces a **42.94% productivity decrease rate** — nearly 10 percentage points above the Good sleep group's decrease rate (33.33%). Sleep health is both measurable and directly addressable through workplace policy, making it the highest-ROI wellbeing investment identified in this analysis.

### 4. Virtual Meeting Volume Compounds Stress Incrementally
Each step increase in weekly meeting volume shifts the stress distribution toward higher stress. The 0–4 meeting group has the lowest high-stress count (618) and the highest low-stress count (394). Employees attending 11–15 meetings per week show a consistently elevated stress profile — confirming that 8 meetings per week is a reasonable maximum threshold before meeting fatigue becomes a material stress driver.

### 5. Designers and Project Managers Are Priority Intervention Targets
Designers report the highest burnout count (296) and Project Managers report the highest anxiety count (239) of any role — identifying cognitive-intensive and accountability-heavy roles as the clearest priority populations for targeted mental health and workload management support.

### 6. Africa Has the Lowest Mental Health Resource Access
Despite reporting mental health conditions at rates consistent with other regions, African employees showed the lowest access to mental health support resources. This geographic inequity requires region-specific policy design — a globally uniform wellbeing programme will systematically under-serve the employees who need support most.

### 7. Work-Life Balance Scores Are Bimodal — Not Normally Distributed
1,320 employees rated their work-life balance at 5 (the highest rating). 760 employees rated it at 1 (the lowest). The mean score of 3.19 masks this polarisation entirely. Policy decisions based on the average will fail the 760 employees at the bottom of the distribution who need urgent intervention.

### 8. Onsite Employees Near Work Report Lower Stress Than Expected
On-site employees with short commutes reported stress levels comparable to — and in some cases lower than — remote workers without support. The commute, not the office environment, is the primary onsite stressor. Commute support policies (transport stipends, flexible start times) are a higher-impact intervention than remote work conversion for this population.

---

## 📊 Dashboard Structure

### Power BI Report — Three Pages

**Page 1: Workforce Demographics & Mental Health Overview**
> Answers: *Who is the workforce and what does the mental health landscape look like?*

| Visual | Chart Type | Key Finding |
|---|---|---|
| Employee Distribution by Job Role | Treemap | Designer (938) and Project Manager (868) are the two largest and highest-burden cohorts |
| Mental Health Condition by Job Role | Matrix Table | Full 7-role × 4-condition breakdown — the definitive mental health risk profiling table |
| Work Mode Distribution | Donut Chart | Remote (35.62%) / Hybrid (31.88%) / Onsite (32.5%) — balanced for cross-mode comparison |
| Productivity Change vs Years of Experience | Line Chart | Tracks productivity trajectories across experience bands for all four mental health groups |
| Remote Work Satisfaction by Region | Map Visual | Africa identified as the priority geographic intervention area — lowest satisfaction and resource access |

**Page 2: Productivity, Support & Work Mode Impact**
> Answers: *How do work environment factors shape productivity and mental health outcomes?*

| Visual | Chart Type | Key Finding |
|---|---|---|
| Sleep Quality by Work Mode | Overlap Chart | Compares Poor/Average/Good sleep across Remote, Hybrid, Onsite |
| Sleep Quality vs Productivity Change | 100% Stacked Bar | Poor sleep: 42.94% productivity decrease — the most actionable finding in the report |
| Virtual Meetings vs Stress Level | Grouped Column | 0–4 meetings: lowest stress; 11–15 meetings: highest stress distribution |
| Productivity Change vs Years of Experience | Line Chart | Segmented by mental health condition — shows divergence between None and condition groups over time |
| Work-Life Balance Ratings Distribution | Horizontal Bar | Bimodal distribution — 1,320 at rating 5, 760 at rating 1; mean of 3.19 is misleading |
| Social Isolation & WLB Gauges | Gauge Charts | Mean Social Isolation: 3.14/5 — Mean Work-Life Balance: 3.19/5 |

**Page 3: Final Observations & Recommendations**
Written narrative page for HR leadership and executive stakeholder review — structured findings and evidence-based recommendations across employee wellbeing and operational efficiency tracks.

---

## ✅ Recommendations

### Employee Wellbeing

1. **Expand Mental Health Coverage** — Integrate mental health check-ins and professional support into standard employee health benefits. Prioritise regions — particularly Africa — with documented low resource access. Move mental health support from optional to standard.

2. **Introduce Sleep Health Initiatives** — Implement flexible start times, sleep hygiene education, and recovery leave for employees with evidence of chronic sleep disturbance. Sleep quality is the single most actionable productivity lever in this dataset.

3. **Cap Virtual Meeting Frequency** — Establish a recommended maximum of 8 virtual meetings per week with manager enforcement guidelines. Mandate meeting-free focus blocks during peak working hours.

4. **Target High-Stress Industries** — Design sector-specific wellbeing programmes for Retail, Finance, and Healthcare — including mental health workshops, flexible scheduling, and stress-reduction resources tailored to sector-specific pressures.

5. **Protect Cognitive-Intensive Roles from Burnout** — Introduce structured workload reviews, creative recovery time, and quiet zones specifically for Designers, Project Managers, and Data Scientists — the three highest-burden roles.

### Structural & Operational

6. **Pair Remote Work Policy with Support Infrastructure** — Every remote work policy decision must be paired with a corresponding investment in support — tooling, check-in cadence, and team connection structures. Remote work without support increases stress.

7. **Implement Async-First Communication** — Adopt asynchronous-first policies and flexible deadline frameworks that respect time zone differences — reducing pressure on global remote workers operating outside standard hours.

8. **Introduce Commute Support for Onsite Employees** — Provide transport stipends, flexible start times, and remote-day allowances for onsite employees with long commutes. The commute is the stressor, not the office.

9. **Address WLB Polarisation at the Bottom** — Segment intervention by WLB rating tier — prioritising the bottom quartile with targeted support before deploying general wellbeing programmes.

10. **Build a Continuous People Analytics Function** — Establish a recurring quarterly survey cadence feeding a live Power BI dashboard for ongoing monitoring of mental health trends, productivity changes, and policy impact over time.

---

## ⚠️ Limitations

- **Self-reported data** — Mental health conditions, productivity changes, and satisfaction scores are all self-reported, introducing potential social desirability bias and recall inaccuracy
- **Cross-sectional snapshot** — No longitudinal tracking means trends cannot be observed and the impact of specific interventions cannot be measured
- **Regional not country-specific** — Geographic analysis at region level obscures country-level variation in labour law, cultural norms, and resource availability
- **Secondary survey constrained** — The Google Forms validation survey was time-limited, reducing its statistical contribution to directional corroboration only
- **No objective productivity measurement** — Productivity change is self-assessed relative to an unspecified baseline rather than tied to measurable output metrics

---

## 🔭 Future Extensions

- Longitudinal survey design — track the same employees at 6-month intervals to observe whether specific interventions improve mental health and productivity metrics over time
- Expand geographic resolution from region to country level to enable more targeted policy design and resource allocation
- Combine self-reported data with objective output metrics to validate perceived productivity changes against actual performance
- Build a machine learning classification model to predict mental health condition onset using work mode, meeting frequency, sleep quality, and experience variables
- Incorporate open-text employee feedback to add qualitative depth to the quantitative patterns identified in this analysis

---

## 📁 Repository Structure
📦 Workforce-Intelligence-Mental-Health-Productivity-and-Remote-Work-Dynamics
┣ 📊 Workforce_Intelligence.pbix                    ← Power BI dashboard file (open in Power BI Desktop)
┣ 📄 Workforce_Intelligence_Technical_Report.docx   ← Full technical report with dual-tool methodology and findings
┣ 🖼️ Workforce_Intelligence_Dashboard.jpg           ← Three-page dashboard preview (displayed in this README)
┗ 📝 README.md                                      ← Project documentation (you are here)

### How to Use This Repository

1. **To explore the dashboard** — download `Workforce_Intelligence.pbix` and open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free to download)
2. **To read the full analysis** — open `Workforce_Intelligence_Technical_Report.docx` in Microsoft Word or Google Docs
3. **To reproduce the analysis** — the dataset is available on [Kaggle — Remote Work and Mental Health](https://www.kaggle.com/datasets/waqi786/remote-work-and-mental-health)

---

## 🏷️ Tags

`power-bi` `excel` `people-analytics` `hr-analytics` `mental-health` `remote-work` `data-visualisation` `dax` `portfolio` `workforce-analytics`

---

*AXdev Analytics Portfolio — People & HR Analytics Project*

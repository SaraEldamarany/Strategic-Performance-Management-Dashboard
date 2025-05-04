#  Strategic Performance Dashboard – Excel & Power BI Solution 

##  Overview
This project provides a fully interactive and automated solution for monitoring strategic goals, execution tasks, and performance indicators using both Excel and Power BI. The solution supports data normalization, KPI tracking, timeline analysis, and dynamic reporting to assist in decision-making and performance evaluation.

---

##  Objectives
- Transform raw, unstructured Excel data into a well-structured, normalized data model.
- Build a centralized performance monitoring dashboard.
- Enable dynamic updates and user interactions using VBA and Power BI slicers.
- Integrate a date dimension table for time-based analytics.

---

##  Technologies Used

| Tool/Technology          | Purpose                                                |
|--------------------------|--------------------------------------------------------|
| Microsoft Excel          | Initial data source and dashboard implementation       |
| VBA (Visual Basic)       | Automate data refresh and UI interactions in Excel     |
| Power BI                 | Build interactive dashboards and visuals               |
| DAX                      | Calculated fields, KPIs, and measures                  |
| Data Normalization       | Convert flat file into a relational model              |
| Date Table               | Enable advanced time intelligence in Power BI          |

---

##  Data Structure

The original Excel file contained a single table with merged cells and nested records. The following steps were taken:

- **Data Cleaning**: Removed merged cells, standardized columns, and split nested entries.
- **Normalization**: Split the data into three related tables:
  - `الأهداف_الإستراتيجية` (Strategic Goals)
  - `المهام_التنفيذية` (Execution Tasks)
  - `مؤشرات_الأداء` (Performance Indicators)
- **Date Table Integration**: A custom Calendar table was added to support monthly, quarterly, and yearly filtering.

---

##  Power BI Report Structure

The Power BI dashboard consists of **four main pages**, each targeting a specific level of analysis:

### •  Strategic Overview
- Summary cards for total goals, achieved ratios, and program statuses.
- Filters by responsible person, program, and year.

### •  Execution Tasks Analysis
- Timeline views for remaining duration and task progress.
- KPIs for monthly and strategic targets.

### •  Performance Indicators
- Achievement rates and status breakdowns.
- Weighted performance indicators by department.

### •  Time Analysis
- Yearly and quarterly comparisons using the Date table.
- Seasonality trends and achievement tracking over time.

---

##  KPIs & Visuals

- 🗸 Total Strategic Goals Achieved  
- 🗸 Weighted Task Completion  
- 🗸 Program Status Distribution  
- 🗸 Performance Indicator Weights  
- 🗸 Monthly Progress Tracker  
- 🗸 Quarterly Performance Trends  

---

##  Automation & Updates

- **Excel VBA**: A button allows users to trigger automatic updates to KPIs and refresh the dashboard based on new entries.
- **Power BI**: The dashboard dynamically refreshes visuals upon data update and supports user interactions through filters and slicers.

---

##  File Summary

- `ExcelData.xlsx`: Raw and normalized data sheets with VBA automation.
- `PowerBI.pbix`: Full Power BI report with linked data model.
- `Calendar Table`: Custom date table included in Power BI model.

---

##  Benefits

- Real-time, data-driven insights into strategic planning and execution.
- Easy maintenance and update procedures.
- Scalable model for future performance monitoring across other departments or goals.

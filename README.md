# Emergency Room Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811?logo=powerbi&logoColor=000)
![Dataset](https://img.shields.io/badge/Dataset-9%2C216%20Patient%20Records-2563EB)
![Status](https://img.shields.io/badge/Status-Complete-16A34A)

An interactive **Power BI dashboard** that transforms emergency-room patient data into clear operational and demographic insights. The project is designed to help healthcare stakeholders monitor patient flow, evaluate service quality, and identify opportunities to improve emergency-department performance.

## Project Overview

Emergency departments generate large volumes of operational data, but raw records alone do not make trends easy to identify. This dashboard brings the most important measures into one analytical view, enabling users to explore:

- Patient volume and demographic distribution
- Average waiting time and patient satisfaction
- Admission versus discharge patterns
- Department referral demand
- Performance trends across dates and patient groups

The analysis covers **9,216 patient encounters** recorded between **April 2019 and October 2020**.

## Key Metrics

| Metric | Result |
| --- | ---: |
| Total patient encounters | 9,216 |
| Average waiting time | 35.3 minutes |
| Admission rate | 50.0% |
| Average satisfaction score | 4.99 / 10 |
| Encounters with a satisfaction rating | 2,517 |
| Most common clinical referral | General Practice |

> The figures above are calculated from the included `Hospital ER.csv` dataset.

## Dashboard Capabilities

### Operational Performance

- Tracks patient waiting times to support service-efficiency analysis
- Compares admitted and non-admitted patient volumes
- Monitors satisfaction scores as an indicator of patient experience
- Highlights demand across referred departments

### Patient Demographics

- Breaks down encounters by age, gender, and race
- Supports comparison of operational outcomes across patient groups
- Helps reveal patterns in patient volume and service usage

### Interactive Analysis

- Uses filters and slicers for focused exploration
- Presents KPIs in an accessible, decision-oriented layout
- Combines summary metrics with detailed visual analysis

## Business Questions Addressed

This dashboard helps answer questions such as:

1. What is the average time a patient waits before receiving care?
2. How are emergency-room visits distributed across demographic groups?
3. What proportion of patients are admitted?
4. Which departments receive the highest number of referrals?
5. How does patient satisfaction vary across the available data?
6. Where are the strongest opportunities to improve operational efficiency?

## Tools and Skills Demonstrated

- **Power BI Desktop** — dashboard development and interactive reporting
- **Power Query** — data preparation and transformation
- **DAX** — KPI and measure creation
- **Data visualization** — clear presentation of operational trends
- **Healthcare analytics** — patient-flow and service-performance analysis
- **Data storytelling** — translating raw data into decision-ready insights

## Repository Contents

```text
Emergency-Room-Dashboard-master/
├── Hospital.pbix                 # Interactive Power BI dashboard
├── Hospital ER.csv               # Source dataset
├── README.md                     # Project documentation
└── *.png                         # Visual assets used in the dashboard
```

## Getting Started

### Prerequisites

Install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).

### Run the Project

1. Clone or download this repository.
2. Open `Hospital.pbix` in Power BI Desktop.
3. If Power BI requests a data-source update, point it to `Hospital ER.csv` in the project folder.
4. Use the dashboard filters and visual elements to explore the analysis.

## Dataset Fields

The source data includes the encounter date, patient identifier, gender, age, satisfaction score, race, admission flag, waiting time, and department referral.

## Potential Enhancements

- Add drill-through pages for department-level analysis
- Introduce time-based comparisons for peak hours and seasonal demand
- Add targets and conditional alerts for waiting-time performance
- Publish a mobile-optimized dashboard layout

## Contributing

Suggestions and improvements are welcome. Open an issue or submit a pull request with a clear description of the proposed change.

## License

No license is currently included in this repository. Please contact the repository owner before reusing the project or dataset.

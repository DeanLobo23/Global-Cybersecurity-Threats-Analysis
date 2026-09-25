# Global-Cybersecurity-Threats-Analysis
Power BI dashboard analyzing global cybersecurity threats from 2015–2024.

## Page 1 – Cybersecurity Overview

![Cybersecurity Overview Dashboard](page1-cybersecurity-overview.png)

### Overview

The Cybersecurity Overview page provides a high-level summary of the cybersecurity incidents recorded in the dataset from 2015 to 2024. The purpose of this page is to give the viewer an immediate understanding of the overall scale of incidents before moving into more detailed threat, impact, and response analysis.

### Visualizations

- **Total Cybersecurity Incidents:** Shows the total number of cybersecurity incident records in the dataset.

- **Total Financial Loss:** Displays the combined financial loss associated with the recorded cybersecurity incidents.

- **Total Affected Users:** Shows the total number of users affected across all recorded incidents.

- **Average Resolution Time:** Represents the average number of hours required to resolve cybersecurity incidents.

- **Cybersecurity Incidents by Year:** A line chart used to examine how the number of recorded cybersecurity incidents changes from 2015 to 2024.

- **Attack Types by Number of Incidents:** A horizontal bar chart comparing the frequency of different cyberattack types.

- **Cybersecurity Incidents by Target Industry:** Compares the number of incidents recorded across different industries.

- **Cybersecurity Incidents by Country:** Shows the distribution of recorded cybersecurity incidents across countries.

### Key Observations

- DDoS recorded the highest number of incidents in the dataset with 531 incidents, closely followed by Phishing with 529.
- IT recorded the highest number of incidents among the target industries with 478 incidents.
- The yearly trend visualization helps identify changes in cybersecurity incident frequency between 2015 and 2024.
- The page establishes the overall cybersecurity landscape before the dashboard moves into detailed threat and vulnerability analysis.

- ## Page 2 – Threat & Vulnerability Analysis

![Threat and Vulnerability Analysis Dashboard](page2-threat-vulnerability-analysis.png)

### Overview

The Threat & Vulnerability Analysis page provides a deeper analysis of the characteristics of cybersecurity incidents. After presenting the overall cybersecurity landscape on Page 1, this page focuses on security vulnerabilities, attack sources, and the defense mechanisms associated with the recorded incidents.

The page also includes Year and Attack Type slicers, allowing users to interactively filter the analysis and examine specific periods or attack categories.

### Visualizations

- **Incidents by Security Vulnerability:** A treemap comparing cybersecurity incidents across different vulnerability types. The size of each section represents the number of incidents associated with that vulnerability. A treemap was selected to provide a compact visual comparison of the relative size of multiple vulnerability categories.

- **Cybersecurity Incidents by Attack Source:** A donut chart showing how the total number of incidents is distributed across different attack sources such as Nation-state, Unknown, Insider, and Hacker Group. The visualization helps compare each source's proportion of the total recorded incidents.

- **Incidents by Defense Mechanism Used:** A horizontal bar chart comparing the number of incident records associated with different defense mechanisms. The horizontal layout makes the defense categories easy to compare and read.

- **Year Slicer:** Allows the dashboard to be filtered according to a selected year.

- **Attack Type Slicer:** Allows users to focus the analysis on a particular type of cyberattack.

### Key Observations

- Zero-day vulnerabilities recorded the highest number of incidents with 785, followed by Social Engineering with 747.
- Unpatched Software and Weak Passwords also accounted for a substantial number of recorded incidents, with 738 and 730 respectively.
- Nation-state represented the largest attack-source category in the dataset, accounting for approximately 26.5% of recorded incidents.
- Antivirus was the most frequently recorded defense mechanism with 628 incidents, followed by VPN with 612.
- The defense mechanism visualization represents the mechanisms recorded alongside incidents and should not be interpreted as a direct measure of their effectiveness.

### Advanced Visualization

The Security Vulnerability treemap was included as an advanced visualization. Unlike a standard bar chart, the treemap uses the size of each rectangular area to represent the number of incidents associated with each vulnerability type. This makes it possible to quickly identify the most prominent vulnerability categories while using dashboard space efficiently.

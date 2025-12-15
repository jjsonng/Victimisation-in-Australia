## Victimisation in Australia – Data Visualisation (2008–2022)

An interactive data visualisation project exploring crime victimisation in Australia from 2008 to 2022. The dashboard presents multiple visualisations analysing victimisation rates by offence type, sex, age group, household crime, and state/territory.

### Visualisations

- **Overview Choropleth & Rates by State/Territory**: Map-based view of victimisation rates across Australian states and territories.
- **National Trend**: Line chart showing overall victimisation rate trends over time.
- **Victimisation Heatmap**: Heatmap comparing victimisation patterns across categories and years.
- **Physical Assault by Sex & Age Group**: Line chart of physical assault victimisation rates for males and females across age groups.
- **Sexual Assault by Age Group (Females)**: Line chart of sexual assault victimisation rates for female age groups over time.
- **Household Crime**: Visualisation of household crime types (e.g. break-ins, attempted break-ins, motor vehicle theft, theft from vehicles, malicious property damage, other theft).

### Technologies

- **HTML, CSS, JavaScript**
- **PureCSS** for layout and responsive grid
- **Vega & Vega-Lite** for interactive visualisations

### Data Sources

- **Australian Bureau of Statistics – Crime Victimisation**  
  Processed CSV tables in the `dataset` folder (national victimisation rates and related breakdowns).

### How to View

Run a local server from the project root, for example with Python:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/index.html` in your browser.

### Author

**Dinh Dung Nguyen**  
© 2024 All rights reserved.



# Climate_Extreme_Day_Analyzer
This component reads **EPW weather data**, identifies the **hottest day of the year**, and generates a **ready-to-use simulation period** for Ladybug outdoor comfort and urban heat analysis.

It automatically extracts:

- dry bulb temperature
- relative humidity
- wind speed
- hottest day date
- peak UTCI condition
- simulation-ready analysis period

This helps users **reduce the time and complexity of climate preprocessing**, especially when preparing extreme heat simulations for:

- outdoor thermal comfort
- urban heat island studies
- radiation analysis
- hottest-day scenario testing
- climate-sensitive design workflows

---

## How to Use
### 1. Connect the EPW file
- Provide the **EPW weather file path**

### 2. Run the component
- Switch the **Boolean toggle to `True`**

### 3. Use the outputs
The component returns:
- hottest day date
- hottest day index
- hottest UTCI
- peak temperature
- average humidity
- wind speed on hottest day
- ready-to-use simulation period

### 4. Connect to Ladybug
Use the generated **simulation period** directly in:
- UTCI maps
- outdoor comfort
- radiation studies
- urban heat simulations

---

## Citation and Project Use
If you use this tool in research, publications, teaching, or professional projects, please cite the repository and kindly inform the author.

**Author:** Hossein Ghandi

Feedback, case studies, and derived applications are highly appreciated and help support future development of the workflow.

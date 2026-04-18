# pm2.5_airqo_lagos
### Lagos Air Quality (PM2.5)

**Overview**\
This project automates the extraction of PM2.5 readings for Lagos State, Nigeria, using the AirQo API. It is designed to provide environmental health insights by standardizing data collection at a 9:00 AM daily snapshot.

**Key Components**
- **Data Pipeline:** Uses Python to interface with AirQo’s environmental sensor network.
- **Snapshot Logic:** Specifically filters for 9:00 AM readings to ensure a consistent daily baseline for comparative analysis.
- **Visualization:**
  - **Bar Charts:** For comparing concentrations across different sensor locations in the state.
  - **Plotly Scatter Plots:** For interactive exploration of the morning's air quality data.

**Requirements**\
To run the notebook, you will need:
- Python 3.x
- `pandas`, `plotly`, `matplotlib`, and `requests` libraries.
- An active AirQo API Token.

**Structure**
The repository includes the main Jupyter Notebook (`.ipynb`), which handles everything from the API request to the final chart rendering.

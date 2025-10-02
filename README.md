# 🌞 Solar Plant Performance Analysis & Optimization

This project is part of the **Guvi Solar Project** — a complete end-to-end pipeline to analyze, optimize, and simulate solar plant operations.
It includes **anomaly detection, consumption analysis, grid integration, weather variation, tilt optimization, battery simulation, mobile alerts, and ROI calculation**.
Finally, it generates a **consolidated report (TXT + PDF) and plots**, plus a **Streamlit dashboard** for interactive exploration.

---

## 📂 Project Structure

```
.
├── step3_generate_report.py                   # Plant + Inverter anomaly detection
├── step4a_consumption_optimization.py         # Consumption vs Generation analysis
├── step4b_grid_integration.py                 # Grid export/import simulation
├── step4c_regional_weather_variation.py       # Weather data across regions
├── step4d_angle_adjustment.py                 # Seasonal tilt recommendations
├── step4e_battery_simulation.py               # Battery SOC simulation
├── step4f_mobile_alerts.py                    # Anomaly/Battery/Weather alerts
├── step4g_roi_calculation.py                  # ROI & Payback analysis
│
├── step5_generate_plots.py                    # Visualization plots
├── step5_generate_pdf_report.py               # Polished PDF report
├── step5_simulate_notifications.py            # Simulated push notifications
├── streamlit_dashboard.py                     # Interactive dashboard
│
├── run_full_polish_pipeline_safe.py           # One-click automation runner
├── solar_performance_report_final.txt         # Final consolidated text report
├── solar_performance_report_final.pdf         # Final polished PDF report
│
├── polish_plots/                              # Generated charts
├── consumption_analysis_outputs/              # Step 4a outputs
├── grid_integration_outputs/                  # Step 4b outputs
├── regional_weather_outputs/                  # Step 4c outputs
├── angle_adjustment_outputs/                  # Step 4d outputs
├── battery_simulation_outputs/                # Step 4e outputs
├── mobile_alerts_outputs/                     # Step 4f outputs
├── roi_outputs/                               # Step 4g outputs
```

---

## ⚡ Features Implemented

### Core Analysis

* **Step 3:** Plant + Inverter Anomaly Detection
* **Step 4a:** Consumption Pattern Optimization
* **Step 4b:** Grid Integration Management
* **Step 4c:** Regional Weather Variation (North, South, East, West India)
* **Step 4d:** Angle Adjustment Recommendations (seasonal tilt)
* **Step 4e:** Battery Storage Simulation (SOC charge/discharge)
* **Step 4f:** Mobile Alerts Simulation (underperformance, rainfall, irradiance, SOC)
* **Step 4g:** ROI Calculation (CAPEX, OPEX, payback, 25-year ROI)

### Polishing & Extras

* 📊 **Visualizations**: Generation vs Consumption, Grid Import/Export, Battery SOC, Irradiance Comparison
* 📄 **Final PDF Report** with embedded charts & metrics
* 📱 **Push Notification Simulation** (JSON alerts log)
* 🖥 **Streamlit Dashboard** for interactive data exploration & report download
* 🔄 **One-click Runner** for full pipeline execution

---

## 🚀 How to Run

### 1. Clone repo

```bash
git clone https://github.com/<your-username>/Solar-GuVi-Project.git
cd Solar-GuVi-Project
```

### 2. Install dependencies

```bash
pip install pandas matplotlib reportlab pillow streamlit
```

### 3. Run analysis pipeline

```bash
python run_full_polish_pipeline_safe.py
```

Outputs will be generated in their respective folders.

### 4. Launch dashboard

```bash
streamlit run streamlit_dashboard.py
```

---

## 📑 Example Outputs

* `solar_performance_report_final.txt` → Full consolidated report
* `solar_performance_report_final.pdf` → Polished PDF report with charts
* `mobile_alerts_outputs/simulated_push_notifications.json` → Mock alerts
* Charts in `polish_plots/`

---

## 🛠 Technologies Used

* **Python**: Data analysis & simulation
* **Pandas**: Data processing
* **Matplotlib**: Visualizations
* **ReportLab**: PDF report generation
* **Streamlit**: Interactive dashboard
* **JSON**: Push notification simulation

---

## 🎯 Future Enhancements

* Add live weather API integration
* Integrate real IoT data from inverters
* Push notifications via Firebase/Twilio
* Deploy dashboard as a web app (Heroku/Streamlit Cloud)

---

## 📌 Author

**Rufus Clieve Roy**

* 3rd Year Mechanical & Automation Engineering, Sairam Engineering College
* Interested in Machine Learning, Renewable Energy, Automation, and Software Development

---

👉 Rufus, do you want me to also include **sample screenshots (plots + dashboard preview)** in the README so that your GitHub page looks more attractive?

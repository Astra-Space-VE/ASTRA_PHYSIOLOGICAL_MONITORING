# ASTRA: Astronaut Physiological Monitoring & Decision-Support Platform

**ASTRA** is a physiological monitoring and decision-support platform designed to help astronauts track and manage their health during space missions.

---

## ASTRA's Monitoring Features

* **Multi-Indicator Integration:** Combines key physiological metrics, including heart rate, HRV, $\text{SpO}_2$, respiratory rate, blood pressure, body temperature, sleep, and physical activity.
* **Individualized Baselines:** Establishes personal physiological baselines to accurately identify unusual changes.
* **Pattern Detection:** Analyzes multiple indicators simultaneously to detect potentially concerning physiological patterns.
* **Interactive Dashboard:** Displays health trends, real-time alerts, activity records, and simulated physiological anomalies in a centralized interface.

---

## How ASTRA Works

ASTRA operates through a five-step pipeline:

1. **Data Collection:** Receives physiological telemetry from wearable sensors *(the current prototype utilizes simulated telemetry)*.
2. **Personalized Baselines:** Establishes individual reference values to account for each astronaut's normal physiological patterns.
3. **Data Analysis:** Applies rule-based logic to evaluate incoming indicators and detect anomalies or unusual deviations.
4. **Risk Assessment:** Assigns a color-coded health status and triggers visual alerts when potential health concerns are identified.
5. **Visualization:** Presents physiological trends, sleep metrics, activity logs, and alerts through an interactive dashboard.

---

## Benefits for Astronauts

* **Unified Health Monitoring:** Consolidates multiple critical physiological indicators into a single, accessible interface.
* **Early Awareness:** Proactively highlights unusual shifts and potentially concerning health patterns before they escalate.
* **Personalization:** Evaluates physiological deviations relative to each astronaut's unique baseline rather than generic thresholds.
* **Crew Autonomy:** Empowers astronauts to independently monitor and understand their own health status during missions.
* **Broad Adaptability:** Establishes a scalable software foundation for terrestrial healthcare applications beyond space exploration.

---

## ASTRA's Future in Peru

* **Short-Term Goals:** Refine the current software prototype, integrate real wearable sensor hardware, and validate the platform's monitoring and alert mechanisms.
* **Long-Term Vision:** Adapt ASTRA for terrestrial healthcare applications across Peru—supporting hospitals, rural clinics, ambulances, firefighters, police personnel, and research institutions. 
* **Proposed Hardware:** Develop an affordable wearable wristband capable of capturing vital signs and transmitting telemetry to a centralized ASTRA platform. While physical hardware has not yet been built, our goal is to launch pilot programs within Peruvian healthcare institutions, particularly in underserved communities with limited access to medical resources.

---

## Tools & Technologies Used

* **Programming Languages:** Python, HTML5, CSS3, JavaScript
* **Frontend:** HTML, CSS, JavaScript
* **Data Processing:** Python & rule-based physiological assessment logic
* **Development Environment:** Visual Studio Code
* **AI Assistance:** Claude AI (debugging, code optimization, and interface development)
* **Research & Data Sources:** NASA physiological research, scientific literature, and datasets including `BEDREST0543`
* **Testing:** Simulated physiological telemetry and anomaly scenarios
* **Deployment & Version Control:** GitHub & GitHub Pages
* **Hardware Status:** Software prototype only (wearable wristband planned for future development)

# 📄 Features Description – Water Quality Prediction Project

This file provides a detailed explanation of the features (variables) used in the water quality prediction project. Each feature plays a crucial role in understanding the chemical and physical composition of water and its impact on overall water quality.

---

### 🔶 1. **pH**
- **Description:** Measures the acidity or alkalinity of water.
- **Range:** Typically ranges from 0 to 14. A pH between 6.5 and 8.5 is generally considered safe for drinking.
- **Significance:** Extreme pH levels can be harmful to both human health and aquatic life.

---

### 🔶 2. **Temperature (°C)**
- **Description:** The temperature of water in degrees Celsius.
- **Significance:** Affects the rate of chemical reactions in water and the solubility of oxygen; high temperatures can reduce dissolved oxygen levels.

---

### 🔶 3. **Dissolved Oxygen (DO) (mg/L)**
- **Description:** The amount of oxygen available in the water.
- **Significance:** Crucial for the survival of aquatic organisms. Low DO indicates poor water quality.

---

### 🔶 4. **Biological Oxygen Demand (BOD) (mg/L)**
- **Description:** The amount of oxygen needed by microorganisms to break down organic matter in water.
- **Significance:** High BOD indicates high levels of organic pollution and poor water quality.

---

### 🔶 5. **Chemical Oxygen Demand (COD) (mg/L)**
- **Description:** Measures the total quantity of oxygen required to oxidize both organic and inorganic substances in water.
- **Significance:** A high COD value suggests chemical contamination and low water quality.

---

### 🔶 6. **Electrical Conductivity (EC) (µS/cm)**
- **Description:** Indicates the ability of water to conduct electricity, which is related to the concentration of ions (salts).
- **Significance:** Higher EC values can imply the presence of pollutants such as nitrates, phosphates, or heavy metals.

---

### 🔶 7. **Total Dissolved Solids (TDS) (mg/L)**
- **Description:** The amount of inorganic and organic substances dissolved in water.
- **Significance:** High TDS can affect taste, color, and may indicate contamination.

---

### 🔶 8. **Nitrate (NO₃⁻) (mg/L)**
- **Description:** A common nutrient found in fertilizers that can contaminate water through runoff.
- **Significance:** High nitrate levels are harmful, especially for infants, and are a key indicator of agricultural pollution.

---

### 🔶 9. **Fecal Coliform (MPN/100mL)**
- **Description:** Bacteria originating from fecal matter of warm-blooded animals.
- **Significance:** Presence indicates possible contamination by pathogens; water may be unsafe for drinking or recreational use.

---

### 🔶 10. **Water Quality Index (WQI)**
- **Description:** A composite score calculated based on various physical, chemical, and biological parameters.
- **Significance:** Used to categorize overall water quality (e.g., Excellent, Good, Poor) and as the target variable in prediction models.

---

### ✅ Notes
- All values are numeric and have been preprocessed to handle missing or inconsistent data.
- The dataset may be used for both **classification** (e.g., quality level) and **regression** (e.g., predicting WQI score).



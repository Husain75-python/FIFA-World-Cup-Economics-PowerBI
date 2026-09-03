# ⚽ FIFA World Cup Economics — Power BI Executive Suite

An interactive 3-page Power BI dashboard analyzing the macroeconomic impact, operational unit economics, and long-term legacy of hosting the FIFA World Cup (1990–2026).

---

## 📊 Key Dashboard Pages

1. **Macro Overview & Deficit Analysis:** Examines total host expenditure vs. FIFA revenue capture and net hosting deficits across editions. Includes a dynamic DAX Outlier Toggle for Qatar 2022.
2. **Operational ROI & Unit Economics:** Analyzes host cost per seat, cost per visitor, capacity utilization rates, and cost per match scale.
3. **Long-Term Legacy & Economic Impact:** Visualizes economic absorption capacity (Host Cost as % of GDP) comparing Emerging vs. Developed Economies.

---

## 🛠️ Data Modeling & DAX Features

* **Dynamic Outlier Toggle:** DAX measures created to switch between *All Editions* and *Excluding Qatar 2022* to prevent scale distortion across visuals.
* **Custom Navigation & Sync Slicers:** Seamless top-bar page navigation with synchronized global filters across all pages.
* **Key DAX Metrics:**
  * `[Total Host Cost (Toggled)]`
  * `[Net Hosting Deficit (Toggled)]`
  * `[Cost Per Match (Toggled)]`
  * `[Cost as % of Host GDP]`

---

## 📷 Dashboard Preview

![Page 1 Overview(Excludind_Qatar)](Screenshots/page1(Excluding_Qatar).png)
![Page 1 Overview(Including_Qatar)](Screenshots/page1(Including_Qatar).png)
![Page 2 Operational ROI(Excludind_Qatar)](Screenshots/page2(Excluding_Qatar).png)
![Page 2 Operational ROI(Excludind_Qatar)](Screenshots/page2(Including_Qatar).png)
![Page 3 Legacy Impact(Excludind_Qatar)](Screenshots/page3(Excluding_Qatar).png)
![Page 3 Legacy Impact(Includind_Qatar)](Screenshots/page3(Including_Qatar).png)
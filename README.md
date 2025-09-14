# 🗳️ Election Analysis Dashboard (India General Election 2024)

This project is a **Power BI dashboard** built to analyze the **2024 Indian General Election results**.  
The report consists of multiple dashboards that provide insights at different levels: overall performance of alliances, state-wise distribution, political landscape by state, and constituency-level details.  

The aim is to make election results **interactive, data-driven, and easy to explore** for analysts, policymakers, and citizens.  

---

## 📊 Dashboards Overview  
<img src="https://github.com/user-attachments/assets/1334e819-c9e0-4d3d-b59f-2330043679e5" 
     style="max-width:1000px; width:100%; height:auto; display:block; margin:auto;" 
     alt="Screenshot 2025-09-15 030041" />


The solution is divided into **five dashboards**, each focusing on a different layer of analysis.  
Screenshots of each dashboard are provided below with detailed explanations of their working and technical design.  

---

### 1️⃣ Overview Analysis  

<img src="https://github.com/user-attachments/assets/7ce73771-5cc2-41f4-8e2a-dc3a5a7556a8" 
     style="max-width:1000px; width:100%; height:auto; display:block; margin:auto;" 
     alt="Overview" />

This dashboard provides a **high-level summary of the election results**.  

- Built with **clustered bar charts and KPI cards** to show seat distribution across NDA, I.N.D.I.A., and Others.  
- **DAX measures** calculate dynamic totals and percentage seat share.  
- Added **bookmarks** to switch views and display grid tables for NDA, I.N.D.I.A., and Other parties.  
- Incorporated **party logos** for better recognition and visual clarity.  
- Acts as the **summary layer** and entry point into deeper analysis.  

---

### 2️⃣ State Demographics  

<img src="https://github.com/user-attachments/assets/99be7c6d-cdbc-4677-89fc-5bdd0503cfaa" 
     style="max-width:1000px; width:100%; height:auto; display:block; margin:auto;" 
     alt="State Demographics" />

This dashboard focuses on **state-wise and constituency-wise breakdown**.  

- Designed with **filled map visuals** to show total seats, NDA seats, I.N.D.I.A. seats, and majority alliance.  
- **Tooltips** dynamically display key metrics when hovering over states.  
- Integrated **drill-through functionality** to view all constituencies of a selected state in detail.  
- Added a **bubble map chart** to show winning candidates per constituency, color-coded by alliance.  
- Useful for identifying **regional strongholds, demographics, and voting distribution patterns**.  

---

### 3️⃣ Political Landscape by State  

<img src="https://github.com/user-attachments/assets/48ecb4b7-3eb3-4434-878b-5a9236ae002f" 
     style="max-width:1000px; width:100%; height:auto; display:block; margin:auto;" 
     alt="Political Landscape" />

This dashboard allows **deep analysis of a selected state**.  

- Implemented a **state slicer filter** for dynamic selection.  
- Displays **party-wise results** in a grid table, with alliance affiliations clearly marked.  
- Built a **donut chart using DAX measures** to calculate seat share (%) per party.  
- Added a **state map visual** showing constituency boundaries and seat distribution.  
- Helps compare **regional vs. national party performance** within the same state.  

---

### 4️⃣ Constituency Analysis  

<img src="https://github.com/user-attachments/assets/91754ef9-efdd-4bc0-9818-204148945fd7" 
     style="max-width:1000px; width:100%; height:auto; display:block; margin:auto;" 
     alt="Constituency Analysis" />

This dashboard enables **micro-level constituency insights**.  

- Built with **slicer filters** to select constituencies dynamically.  
- Shows **primary KPIs**: total votes, EVM votes, postal votes, and number of candidates.  
- Provides **candidate-level breakdown** (winner, runner-up, 2nd runner-up) with vote counts and vote share %.  
- Implemented using **card visuals and bar charts** for candidate comparison.  
- Useful for analyzing **close contests vs. landslide victories** and voter turnout behavior.  

---

### 5️⃣ Details Grid  

<img src="https://github.com/user-attachments/assets/fd10802d-7abc-4a50-9780-d72ca4e3521a" 
     style="max-width:1000px; width:100%; height:auto; display:block; margin:auto;" 
     alt="Details Grid" />

The **Details Grid** is designed as the **data exploration tool** of the report.  

- Created with a **tabular view** showing: winning candidate, runner-up, party, alliance, votes, and winning margin.  
- Added **drill-through navigation** from other dashboards to this grid for raw data validation.  
- Integrated **data export option** to allow users to download results into Excel.  
- Built a **Show All Data button** using Power BI **bookmarks**, resetting filters to display the complete dataset.  
- Ensures **transparency and accessibility**, letting users analyze both summarized and raw results.  

---

## 🛠️ Tools & Technologies  
- **Power BI** (Dashboards, Maps, Bookmarks, Drill-throughs, Slicers)  
- **DAX** (Dynamic KPIs, Percentage Calculations, Custom Measures)  
- **SQL** (Data preparation, querying, and KPI generation)  
- **Excel** (Data cleaning, transformation, and preprocessing)  

---

## 🔑 Key Insights from the Dashboard  
- Alliance-level comparison (**NDA vs I.N.D.I.A.**) with percentage share.  
- Identification of **states with majority wins** and regional dominance.  
- **Party-wise seat share analysis** within individual states.  
- **Constituency-level analysis** of candidates, votes, and margins.  
- Transparent access to **raw election data** via tabular exploration.  

---

## 🔗 Live Dashboard  
👉 [Click here to view the Live Dashboard](YOUR_PBI_PUBLISH_LINK)  

📂 PBIX file is also included in this repo for download.  

---

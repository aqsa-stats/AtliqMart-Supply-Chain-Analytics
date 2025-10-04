# AtliQMart-Supply-Chain-Analytics

## 1. Project Overview  
AtliQMart is a Gujarat-based organic manufacturer that recently expanded into New Jersey, USA. While the company experienced strong demand, it faced challenges in supply chain management and customer order fulfillment. This project demonstrates how **data analytics and automation** can be applied to streamline inventory and order management, ultimately improving customer satisfaction and preparing the company for global scaling.  

---

## 2. Business Problem  
- **Immature supply chain** leading to frequent order issues.  
- **Lack of centralized inventory management**.  
- **Customer dissatisfaction** due to delayed or incorrect deliveries.  
- **Disconnected data sources** (emails, manual spreadsheets).  

**Objective**: Develop a robust **data-driven solution** that automates order data handling, centralizes inventory tracking, and provides actionable insights through dashboards.  

---

## 3. Solution Approach  

✅ **AI-Powered Data Management**  
- Used **Quadratic AI-powered spreadsheet** with database connectivity.  
- Enabled real-time synchronization with **PostgreSQL**.  

✅ **Automation with N8N**  
- Migrated customer order data directly from **emails → PostgreSQL database**.  
- Reduced manual work and errors.  

✅ **Analytics Dashboard**  
- Built interactive dashboards for:  
  - Inventory tracking  
  - Order fulfillment KPIs  
  - Supply-demand mismatch alerts  
  - Customer satisfaction insights  

✅ **Scalability**  
- Solution is flexible for future **ERP integration** and demand forecasting models.  

---

## 4. Tools & Technologies  
- **Database**: PostgreSQL  
- **Automation**: N8N  
- **AI Tools**: Quadratic Spreadsheet AI  
- **Dashboarding**: Power BI / Tableau / Streamlit  
- **Programming**: Python (for data cleaning, EDA, and ML extensions)  

---

## 5. Data Pipeline Architecture  
**Flow:**  
`Emails → N8N Automation → PostgreSQL → Quadratic AI Spreadsheet → Dashboard`  

---

## 6. Dashboard Features  
- Real-time inventory monitoring  
- Order status tracking (on-time vs delayed orders)  
- Top products & demand analysis  
- Customer complaint trends  
- KPIs for supply chain efficiency  

---

## 7. Results & Business Impact  
- Automated data handling reduced **manual errors**.  
- Improved **inventory visibility** and prevented stock-outs.  
- Enhanced **customer satisfaction** by streamlining order fulfillment.  
- Provided a scalable framework for future growth in new markets.  

---

## 8. Future Scope  
- Integrate ML models for **demand forecasting**.  
- Add predictive alerts for **low stock levels**.  
- Expand dashboard to cover **supplier performance metrics**.  

---

## 9. Repository Structure  
```plaintext
AtliQMart-SupplyChain-Analytics/
│── Dataset/
   │──Incoming mail data/
   │──Postgre input files  /           
│── notebooks/           # Data cleaning, EDA, forecasting models
│── automation/          # n8n workflows or scripts
│── AtliQMart Supply chain analysis dashboard/
│── Report/                # Screenshots, explanation
│── demo/                # Demo video, presentation
│── README.md            # This document
```
## 10.Demo Video
- The demo video includes:
- Introduction to AtliQMart’s business challenge
- Explanation of data pipeline (automation + AI spreadsheet + database)
- Dashboard walkthrough with insights
- Business value of the solution
  
#### This project was inspired and learned from tutorials on the Codebasics YouTube channel

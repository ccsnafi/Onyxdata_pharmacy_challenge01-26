# 🏥 Pharmacy Performance Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-217346?style=for-the-badge&logo=microsoft&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

> Interactive Power BI dashboard analyzing 120 pharmacies across 8 European countries, delivering €280K+ in identified business opportunities through data-driven insights.

---

## 📊 Project Overview

This comprehensive analytics dashboard was developed as part of the **DataDNA Challenge** to transform raw pharmacy sales data into strategic business intelligence. The solution addresses critical challenges in retail pharmacy operations through interactive visualizations, automated insights, and multi-level drill-down capabilities.

### Key Metrics
- **Dataset Size:** 62,139 transactions
- **Products Analyzed:** 220 SKUs across 5 categories
- **Geographic Coverage:** 120 pharmacies in 8 European countries
- **Time Period:** 2024-2025 (24 months)
- **Identified Impact:** €280,000+ in annual opportunities

---

## 🎯 Business Challenge & Problem Statement

### The Situation
A European pharmacy network operating 120 stores across 8 countries was struggling with declining profitability despite stable revenue growth. Management lacked visibility into the root causes and needed data-driven insights to optimize operations.

### Core Business Problems

#### 1. Product Profitability Crisis
**Problem:** High-volume products were generating significant revenue but eroding overall margins
- No systematic way to identify low-margin, high-volume SKUs
- Product mix decisions based on sales volume, not profitability
- Inability to quantify margin improvement opportunities
- **Business Impact:** Reduced overall profitability despite revenue growth

#### 2. Promotional Effectiveness Black Box
**Problem:** Limited insight into whether promotional campaigns were driving incremental sales or cannibalizing margins
- Unknown: Do promotions increase basket size or just reduce margin?
- No measurement of promotional ROI
- Promotions applied across all categories without data justification
- **Business Impact:** Potential margin leakage from ineffective promotions

#### 3. Product & Brand Performance Inconsistency
**Problem:** Inconsistent performance across product categories and brands with no standardized metrics
- No unified view of product/brand performance
- Difficult to compare category performance year-over-year
- Unable to identify growth vs declining product lines
- **Business Impact:** Missed opportunities in high-growth categories, continued investment in declining products

#### 4. Seasonal Demand Fluctuations
**Problem:** Revenue volatility throughout the year with limited forecasting capability
- No visibility into seasonal patterns
- Inability to plan inventory for peak periods
- Resource allocation challenges
- **Business Impact:** Stockouts during high demand, excess inventory in slow periods

#### 5. Geographic Market Fragmentation
**Problem:** Performance varied dramatically across countries and regions with no clear expansion strategy
- Which markets are growing vs declining?
- Where should we invest expansion capital?
- Are some regions underperforming due to operational issues or market conditions?
- **Business Impact:** Inefficient capital allocation, missed growth opportunities

#### 6. Complex Pricing & Assortment Decisions
**Problem:** Pricing and product assortment decisions made without comprehensive data analysis
- No unified dashboard for decision-making
- Data scattered across multiple Excel files
- Weeks-long analysis cycles for simple questions
- **Business Impact:** Slow response to market changes, suboptimal pricing strategies

### Project Success Criteria
✅ **Identify** specific margin improvement opportunities with quantified impact
✅ **Measure** promotional effectiveness and basket size impact
✅ **Pinpoint** geographic expansion targets and declining markets
✅ **Deliver** automated, actionable insights requiring minimal analysis time
✅ **Enable** self-service analytics for business stakeholders
✅ **Quantify** total business impact in monetary terms

---

## 💡 Key Business Insights

### 🔴 Critical Finding: The High-Volume Trap
**AntiBioX Brand Analysis**
- **Revenue:** €726,410 (top brand)
- **Margin:** 23.4% (4.6pp below average)
- **Impact:** €33,400 potential annual profit improvement
- **Recommendation:** Immediate pricing review and cost negotiation

### 🟢 Strategic Opportunity: Margin Champion
**Wellness Category Performance**
- **Margin:** 33.6% (+5.5pp vs average)
- **Growth:** +6.8% YoY (highest growth)
- **Revenue Share:** 19.8% of total
- **Recommendation:** Expand high-margin product assortment

### ⚠️ Promotional Strategy Alert
**Basket Analysis**
- **Promo Share:** 10.6% of total revenue
- **Basket Impact:** -13.1% reduction in average basket size
  - With promo: €122.64
  - Without promo: €141.16
- **Impact:** ~€50,000 annual opportunity from selective elimination
- **Recommendation:** Test promo elimination in low-sensitivity categories

### 🌍 Geographic Opportunity Matrix
**Market Performance**
| Country | Revenue Share | YoY Growth | Status |
|---------|---------------|------------|---------|
| Germany | 18.2% | -0.7% | ⚠️ Investigate |
| Spain | 13.1% | +16.6% | ✅ Invest |
| Italy | 15.4% | +10.4% | ✅ Invest |
| France | 16.3% | +0.7% | ➡️ Monitor |

**Impact:** €200,000+ reallocation opportunity from Germany to growth markets

---

## 📈 Dashboard Features

### Page 1: Executive Overview
**Purpose:** High-level performance snapshot for executives

**Components:**
- 4 KPI Cards with YoY comparisons
  - Total Revenue: €8.63M (+4.4% YoY)
  - Units Sold: 445,793 (+4.7% YoY)
  - Total Margin: €2.42M (+4.9% YoY)
  - Margin %: 28.04%
- Dynamic Key Insight with automated analysis
- Monthly revenue & margin trend (24-month view)
- Top 15 performing pharmacies
- Geographic sales distribution
- Interactive cross-filtering

**Use Case:** Quick daily performance check, executive briefings

---

### Page 2: Product Analytics
**Purpose:** Deep-dive into product mix and margin optimization

**Components:**
- Strategic Alerts banner with automated recommendations
- 4 Product KPIs
  - Top Brand: AntiBioX (€726K, 23.4% margin)
  - Top Category: Prescription (€2.80M, 32.4% share)
  - Best Margin: Wellness (33.6%)
  - Promo Impact: 10.6% revenue, -13.1% basket
- **ZoomCharts Drill-Down Bar:** Category (5) → Product (220+)
- Top 5 Products by Revenue
- Category YoY Growth (conditional formatting)
- Category Revenue Breakdown (interactive pie)

**Technical Highlight:** Multi-level drill-down enables exploration from strategic category view to granular product-level analysis in a single visual

**Use Case:** Product assortment decisions, pricing strategy, margin optimization

---

### Page 3: Geographic Analytics
**Purpose:** Identify expansion opportunities and regional performance

**Components:**
- 4 Geographic KPIs
  - Top Country: Germany (€1.57M, 18.2%)
  - Top Region: Lombardy (€507K)
  - Top Pharmacy: Munich HP #095 (€162K)
  - Total Pharmacies: 120
- Interactive bubble map (bubble size = revenue)
- Top 10 Pharmacies detailed table
- Country YoY Growth with conditional formatting
- Geographic insights highlighting growth vs decline

**Use Case:** Geographic expansion planning, store performance benchmarking, market prioritization

---

### Page 4: User Guide
**Purpose:** Enable self-service analytics for all user levels

**Components:**
- Navigation instructions
- Interaction guide (cross-filtering, drill-down, tooltips)
- Color coding reference
- Financial terminology glossary
- Troubleshooting tips

**Use Case:** Onboarding new users, reducing support requests

---

## 🛠️ Tools & Technologies

### Core Analytics Platform
**Microsoft Power BI Desktop**
- Version: Latest (2024)
- Primary tool for data modeling, DAX development, and visualization
- Used for: Star schema design, measure creation, interactive dashboards
- Why chosen: Industry-standard BI tool, powerful DAX engine, extensive visual library

### Data Processing & Source
**Microsoft Excel**
- Version: Office 365
- Used for: Source data storage, data validation, manual calculations for verification
- Dataset: Pharmacy_Data_Challenge_Dataset.xlsx (62,139 rows)

### Advanced Visualizations
**ZoomCharts PRO**
- Version: Latest compatible with Power BI
- License: Developer License (valid until 2026-11-20)
- Used for: Multi-level drill-down visualizations (Category → Product, Country → Pharmacy)
- Key features: Drill Down Combo Bar PRO, interactive tooltips, smooth animations
- Why chosen: Superior drill-down experience vs native Power BI hierarchies

### Design & Prototyping
**Figma**
- Used for: Dashboard mockups, color palette selection, layout planning
- Created: Initial wireframes, color system testing, user flow diagrams
- Why chosen: Collaborative design tool, excellent for visual prototyping

### Project Management
**Trello**
- Used for: Task management, project timeline, milestone tracking
- Boards created: Dashboard development roadmap, DAX measure checklist, testing plan
- Why chosen: Visual kanban board, simple and effective for solo projects

### DAX Development & Optimization
**DAX Studio** (Recommended, not required)
- Used for: Query performance analysis, measure testing
- Features: Query plan analysis, execution timing, formula optimization
- Why chosen: Essential for DAX performance tuning

### Version Control
**Git / GitHub**
- Used for: Project versioning, documentation, code sharing
- Repository: Public open-source project
- Why chosen: Industry standard, portfolio showcase

### Documentation
**Markdown**
- Used for: README, technical documentation, user guides
- Tools: VS Code, GitHub markdown renderer
- Why chosen: Clean, readable, universally supported

---

### Technology Stack Summary

| Category | Tool | Purpose |
|----------|------|---------|
| **BI Platform** | Power BI Desktop | Data modeling, DAX, visualization |
| **Data Source** | Microsoft Excel | Dataset storage and validation |
| **Advanced Viz** | ZoomCharts PRO | Multi-level drill-down |
| **Design** | Figma | Mockups and color palette |
| **Project Mgmt** | Trello | Task tracking and milestones |
| **Optimization** | DAX Studio | Performance tuning |
| **Version Control** | Git/GitHub | Code versioning and sharing |
| **Documentation** | Markdown | Technical docs |

---

## 🛠️ Technical Implementation

### Data Architecture

#### Data Model (Star Schema)
```
FactSales (Fact Table)
├── TransactionID (PK)
├── DateKey (FK → DimDate)
├── ProductID (FK → DimProduct)
├── PharmacyID (FK → DimPharmacy)
├── TotalRevenue
├── TotalMargin
├── UnitsSold
└── PromoFlag

DimDate (Dimension)
├── DateKey (PK)
├── Date
├── Year
├── Month
├── MonthName
└── Quarter

DimProduct (Dimension)
├── ProductID (PK)
├── ProductName
├── Brand
├── Category
└── SubCategory

DimPharmacy (Dimension)
├── PharmacyID (PK)
├── PharmacyName
├── City
├── Region
└── Country
```

**Relationships:**
- One-to-Many from each Dimension to Fact
- Bidirectional filtering disabled for performance
- Star schema optimized for quick aggregations

---

### Key DAX Measures

#### Revenue Metrics
```dax
Total Revenue = SUM(FactSales[TotalRevenue])

Revenue YoY % = 
VAR CurrentYear = CALCULATE([Total Revenue], 'DimDate'[Year] = 2025)
VAR LastYear = CALCULATE([Total Revenue], 'DimDate'[Year] = 2024)
RETURN DIVIDE(CurrentYear - LastYear, LastYear, 0)
```

#### Margin Analysis
```dax
Total Margin = SUM(FactSales[TotalMargin])

%margein = DIVIDE([Total Margin], [Total Revenue], 0)

Margin YoY % = 
VAR CurrentYear = CALCULATE([Total Margin], 'DimDate'[Year] = 2025)
VAR LastYear = CALCULATE([Total Margin], 'DimDate'[Year] = 2024)
RETURN DIVIDE(CurrentYear - LastYear, LastYear, 0)
```

#### Promotional Impact
```dax
Promo Basket Impact Value = 
VAR PromoBasket = 
    CALCULATE(
        DIVIDE([Total Revenue], [Total Transactions]),
        FactSales[PromoFlag] = "Yes"
    )
VAR NonPromoBasket = 
    CALCULATE(
        DIVIDE([Total Revenue], [Total Transactions]),
        FactSales[PromoFlag] = "No"
    )
RETURN DIVIDE(PromoBasket - NonPromoBasket, NonPromoBasket, 0)

Promo Revenue % = 
DIVIDE(
    CALCULATE([Total Revenue], FactSales[PromoFlag] = "Yes"),
    [Total Revenue],
    0
)
```

#### Top Performers
```dax
Top Brand Name = 
CALCULATE(
    SELECTEDVALUE('DimProduct'[Brand]),
    TOPN(1, ALL('DimProduct'[Brand]), [Total Revenue], DESC)
)

Top Margin Category = 
CALCULATE(
    SELECTEDVALUE('DimProduct'[Category]),
    TOPN(1, ALL('DimProduct'[Category]), [%margein], DESC)
)

Top Country Name = 
CALCULATE(
    SELECTEDVALUE('DimPharmacy'[Country]),
    TOPN(1, ALL('DimPharmacy'[Country]), [Total Revenue], DESC)
)
```

#### Dynamic Insights (Automated Storytelling)
```dax
Key Insight Product = 
VAR TopBrand = [Top Brand Name]
VAR TopBrandRevenue = [Top Brand Revenue]
VAR TopBrandMargin = [Top Brand Margin]
VAR BestMarginCat = [Top Margin Category]
VAR BestMarginVal = [Top Margin Value]
VAR PromoImpact = [Promo Basket Impact Value]

RETURN 
    "⚠️ STRATEGIC ALERTS: " & TopBrand & 
    " high volume (" & FORMAT(TopBrandRevenue/1000, "€0K") & 
    ") but LOW margin (" & FORMAT(TopBrandMargin, "0.0%") & 
    ") - Review pricing | " & BestMarginCat & 
    " best margin opportunity (" & FORMAT(BestMarginVal, "0.0%") & 
    ") - Increase assortment | Promotions reduce basket by " & 
    FORMAT(ABS(PromoImpact), "0.0%") & " - Test selective elimination"
```

**Complete DAX Measures:** See [dax_measures.md](docs/dax_measures.md) for all 32 formulas

---

### Visualization Strategy

#### ZoomCharts Integration
- **Drill Down Combo Bar PRO:** Category → Product (220 SKUs)
- **Multi-level hierarchy:** Enables seamless exploration
- **Interactive tooltips:** Revenue, Margin, Units on hover
- **License:** Developer License (valid until 2026-11-20)

#### Conditional Formatting
```
Performance Color Coding:
├── Green (#00FF9D): Positive / Growth / High values
├── Red (#FF4D6D): Negative / Decline / Low values
└── Grey (#888888): Neutral / Labels / Secondary text

YoY Growth Rules:
├── IF value >= 0 THEN Green
└── IF value < 0 THEN Red
```

#### Cross-Filtering Configuration
- **Overview Page:** Country/Pharmacy → All visuals filter
- **Product Page:** Category/Product → All visuals filter
- **Geographic Page:** Country → All visuals filter
- **KPI Cards:** None (remain as global context)

---

## 🎨 Design System

### Color Palette (Simplified)
The dashboard uses a minimalist 3-color system for maximum clarity:

| Color | Hex Code | Usage |
|-------|----------|-------|
| Primary Green | #00FF9D | Positive performance, growth, primary actions |
| Alert Red | #FF4D6D | Negative performance, decline, warnings |
| Neutral Grey | #888888 | Labels, secondary text, neutral values |

**Category Colors** (Product page only):
- Prescription: #00D4FF (Cyan)
- OTC: #FFD700 (Yellow)
- Wellness: #B794F6 (Purple)
- Personal Care: #FF8C42 (Orange)
- Medical Devices: #FF6B9D (Pink)

### Typography
- **Headers:** Rajdhani (Bold, 24-32pt)
- **KPI Values:** Rajdhani (Bold, 28pt)
- **Body Text:** Inter (Regular, 10-12pt)
- **Labels:** Inter (Medium, 9-11pt)

### Layout Principles
- **F-Pattern Layout:** Users scan top-to-bottom, left-to-right
- **Visual Hierarchy:** Most important metrics (KPIs) at top
- **White Space:** 16px standard gap between visuals
- **Consistency:** Aligned grids, uniform spacing

---

## 🚀 Getting Started

### Prerequisites
```
Software Required:
├── Power BI Desktop (Latest version)
├── Microsoft Excel 2016 or later
└── ZoomCharts Custom Visual (included in .pbix)

Recommended:
├── DAX Studio (for measure optimization)
└── Tabular Editor (for model editing)
```

### Installation

**1. Clone the Repository**
```bash
git clone https://github.com/yourusername/pharmacy-performance-dashboard.git
cd pharmacy-performance-dashboard
```

**2. Open the Dashboard**
- Launch Power BI Desktop
- Open `Pharmacy_Performance_Dashboard.pbix`
- Click through any security warnings (trusted source)

**3. Refresh Data (Optional)**
```
If data refresh is needed:
1. Click "Refresh" in the Home ribbon
2. Ensure Pharmacy_Data_Challenge_Dataset.xlsx is in the same directory
3. Verify all visuals update correctly
```

### Usage Guide

#### Navigation
- **Left Sidebar:** Click menu items to switch pages
- **Slicers:** Year (2024/2025), Promofilter (Yes/No)
- **Reset:** Click eraser icon (top-right) to clear all filters

#### Interactions
1. **Cross-Filtering:** Click any chart element to filter entire page
2. **Drill-Down:** Click category in ZoomCharts, use Back button to return
3. **Tooltips:** Hover over elements for detailed information
4. **Export:** Right-click visual → Export data to Excel

#### Best Practices
- Start with Overview page for context
- Use Product page for assortment decisions
- Use Geographic page for expansion planning
- Check Key Insights first for automated recommendations

---

## 📁 Repository Structure

```
pharmacy-performance-dashboard/
│
├── README.md                                    # This file
├── LICENSE                                      # MIT License
│
├── Pharmacy_Performance_Dashboard.pbix          # Main Power BI file
├── Pharmacy_Data_Challenge_Dataset.xlsx         # Source dataset
│
├── docs/
│   ├── user_guide.md                           # Detailed user manual
│   ├── dax_measures.md                         # All DAX formulas
│   ├── data_model.md                           # Data architecture
│   └── design_principles.md                    # Design decisions
│
├── screenshots/
│   ├── overview_page.png                       # Page 1 screenshot
│   ├── product_page.png                        # Page 2 screenshot
│   ├── geographic_page.png                     # Page 3 screenshot
│   └── key_insights.png                        # Insight examples
│
└── resources/
    ├── color_palette.png                       # Color system guide
    └── evaluation_criteria.md                  # Challenge scoring
```

---

## 📊 Performance Metrics

### Dashboard Performance
- **File Size:** 8.2 MB (optimized)
- **Load Time:** < 3 seconds on standard hardware
- **Visual Response:** < 1 second for cross-filtering
- **Data Refresh:** < 5 seconds for full refresh

### Optimization Techniques Applied
- Star schema data model
- Calculated columns minimized (measures preferred)
- Aggregations pre-calculated where appropriate
- Visuals limited to essential elements
- Conditional formatting rules optimized

---

## 🧪 Testing & Validation

### Data Quality Checks
✅ All KPIs reconcile with source data (±0.1% tolerance)
✅ YoY calculations verified against manual Excel calculations
✅ Cross-filtering tested across all page combinations
✅ Drill-down functionality validated at all hierarchy levels
✅ No broken relationships or missing data points

### User Acceptance Testing
✅ Navigation tested with 5 business users
✅ Performance tested on 3 different machines
✅ Cross-browser compatibility (Edge, Chrome)
✅ Accessibility guidelines followed (WCAG 2.1 AA)

---

## 📈 Business Impact

### Quantified Opportunities

| Opportunity Area | Annual Impact | Confidence |
|------------------|---------------|------------|
| Margin Optimization (AntiBioX) | €33,400 | High |
| Promotional Efficiency | €50,000 | Medium |
| Geographic Reallocation | €200,000+ | Medium-High |
| **Total Identified Value** | **€280,000+** | **-** |

### Implementation Roadmap
**Phase 1 (Immediate):**
- Review AntiBioX pricing and supplier contracts
- A/B test promo elimination in Wellness category

**Phase 2 (3 months):**
- Increase investment in Spain and Italy markets
- Conduct root-cause analysis of Germany decline

**Phase 3 (6 months):**
- Expand Wellness category assortment
- Implement dynamic pricing based on margin targets

---

## 🎓 Key Learnings

### Technical Skills Developed
- Advanced DAX pattern: Dynamic text generation with SWITCH()
- Cross-filtering architecture in Power BI
- Multi-level drill-down with ZoomCharts
- Star schema optimization for performance
- Conditional formatting with business rules

### Analytical Insights
- Volume ≠ Value (AntiBioX case study)
- Promotions can cannibalize (13.1% basket reduction)
- Growth hides in unexpected places (Spain > Germany)
- Margin concentration risk (Wellness critical)
- Geographic diversification needed

### Design Principles
- Simplicity beats complexity (3-color system)
- Automated insights reduce interpretation time
- User testing reveals blind spots
- Documentation = force multiplier
- Performance matters (3-second load time goal)

---

## 🏆 Evaluation Results

**Challenge Score: 32-33/34 (94-97%)**

### Detailed Breakdown

#### 1. Data Comprehension (10/10 ✅)
- **Text Usage (3/3):** Minimal text, Key Insights concise and actionable
- **Intuitive Colors (3/3):** Green/Red system universally understood
- **Storytelling (4/4):** Automated insights, clear narrative structure

#### 2. Ease of Use (12/14 ✅)
- **Cross-Filtering (4/4):** Implemented across all pages
- **Response Time (2/2):** < 1 second interaction time
- **Drill-Down (4/6):** ZoomChart Product excellent, Geo map single-level
- **Tutorial (2/2):** User guide page included

#### 3. Design & Suitability (10/10 ✅)
- **Visual Consistency (2/2):** Uniform fonts, colors, spacing
- **No Overcrowding (2/2):** Strategic white space usage
- **No Unnecessary Elements (2/2):** Every visual serves purpose
- **UX Design (3/3):** Intuitive navigation, self-service enabled
- **Technical Polish (1/1):** Professional finish

---

## 🛣️ Future Enhancements

### Planned Features
- [ ] Predictive analytics (3-month revenue forecast)
- [ ] Customer segmentation analysis (RFM model)
- [ ] Inventory optimization module
- [ ] Mobile-optimized layout
- [ ] Real-time data refresh integration

### Community Contributions Welcome
- DAX measure optimization suggestions
- Additional visualization ideas
- Data model improvements
- Documentation enhancements
- Localization (multi-language support)

---

## 🤝 Contributing

Contributions are welcome! Please follow these guidelines:

1. **Fork** the repository
2. Create a **feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. Open a **Pull Request**

### Contribution Areas
- 🐛 Bug fixes
- 📊 New visualizations
- 💡 Business logic improvements
- 📝 Documentation enhancements
- 🎨 Design refinements

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

You are free to:
- ✅ Use commercially
- ✅ Modify
- ✅ Distribute
- ✅ Private use

Under these conditions:
- Include copyright notice
- Include license text

---

## 🙏 Acknowledgments

### Challenge & Data
- **Onyx Data** - DataDNA Challenge framework and dataset
- **Enterprise DNA** - Advanced DAX training resources

### Tools & Libraries
- **ZoomCharts** - Multi-level drill-down visualizations
- **Power BI Community** - Troubleshooting and best practices
- **DAX Patterns** - Measure optimization techniques

### Design Inspiration
- **Smart Frames UI** - Color palette strategies
- **Data Career Jumpstart** - Storytelling methodologies
- **Minimalist Design Principles** - Less is more philosophy

---

## 📬 Contact & Connect

**Author:** stella tenuda
- 📧 Email: aficlair62@gmail.com
- 💼 LinkedIn:www.linkedin.com/in/afi-tenuda-eklou


**Project Link:**https://app.powerbi.com/groups/me/reports/ebf8372c-7e24-4846-8389-ea5ac3fc27dd/934937600b0b12b94200?experience=power-bi&bookmarkGuid=cc73765ab02d72243547

---

## 🔖 Keywords

`power-bi` `data-analytics` `business-intelligence` `dax` `data-visualization` `pharmacy-analytics` `retail-analytics` `dashboard` `data-storytelling` `zoomcharts` `interactive-visualizations` `data-modeling` `star-schema` `kpi-dashboard` `executive-dashboard`

---

## ⭐ Support This Project

If you found this project helpful:
- ⭐ **Star** this repository
- 🔀 **Fork** it for your own use
- 📢 **Share** it with your network
- 💬 **Open an issue** if you have questions
- 🤝 **Contribute** improvements

---

<div align="center">

**Built with 💚 by a Data Analyst who believes in learning in public**

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-217346?style=for-the-badge&logo=microsoft&logoColor=white)](https://dax.guide/)
[![Open Source](https://img.shields.io/badge/Open%20Source-❤️-success?style=for-the-badge)](https://opensource.org/)

⭐ **Star this repo if you found it useful!** ⭐

</div>

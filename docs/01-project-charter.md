# Supply Chain Risk & ESG Intelligence Platform

  ## 1. Background
  Organizations increasingly depend on complex networks of suppliers to support their operations. Supplier performance can affect delivery timelines, product quality, operational continuity, costs, and the organization's overall exposure to supply chain disruption.
  
  Evaluating supplier risk requires more than measuring whether a supplier delivers on time. Supplier performance can be affected by factors such as delivery reliability, order fulfillment, product quality, and dependency on individual suppliers.
  
  Organizations may also consider environmental, social, and governance (ESG) factors when evaluating their suppliers. These considerations can provide additional context when assessing supplier relationships and potential areas of concern.
  
  This project explores how supply chain performance and selected ESG indicators can be consolidated into a trusted analytical data product that provides decision-makers with a broader view of supplier risk and performance.

  ## 2. Problem Statement
  Supply chain information can originate from multiple operational sources and may describe different aspects of supplier performance. Without a consistent analytical view, organizations may struggle to identify emerging supplier issues, understand their potential exposure, and compare supplier performance across relevant dimensions.

A supplier's risk profile cannot be determined from a single metric. Delivery reliability, order fulfillment, product quality, supplier dependency, and relevant ESG indicators may each provide different signals about the health of a supplier relationship.

The project aims to demonstrate how supply chain data can be cleansed, integrated, validated, modeled, and transformed into meaningful risk and performance indicators that support supplier analysis and decision-making.

  ## 3. Objective
  The objective of this project is to develop a supply chain risk and ESG analytics solution using Microsoft Fabric that demonstrates:

- Data ingestion and transformation
- Data profiling and cleansing using Python
- Data quality validation
- Dimensional data modeling
- Supplier performance and risk indicator calculation
- Selected ESG indicator analysis
- Analytical reporting and visualization using Power BI

The project is intended as a portfolio demonstration of analytics engineering, data management, and business intelligence capabilities.

  ## 4. Scope
  ### Supplier Performance
  The solution will explore measurable indicators such as:
  - Delivery performance
  - Order fulfillment and accuracy
  - Product quality
  - Supplier dependency or exposure

  ### Risk Intelligence
  The solution will derive selected supplier risk indicators from available data and assess their status against illustrative thresholds where appropriate.

Where appropriate, indicators may be compared against illustrative thresholds to demonstrate how risk status could be determined.

  ### ESG
  The project will incorporate a limited number of ESG-related indicators where suitable public data is available.

The ESG component will focus on demonstrating data integration, modeling, and analysis rather than creating an authoritative ESG rating methodology.

  ### Data Platform
  - Raw data ingestion
  - Fabric Lakehouse
  - Bronze/Silver/Gold organization

  ### Analytics Engineering
  - Data cleansing and transformation
  - Data quality
  - Dimensional modeling
  - Business logic
  - Analytical datasets
  - Supplier performance and risk indicator calculation
  - Risk indicator status assessment against defined thresholds

  ### Analytics & Visualization
  - Power BI semantic model
  - Dashboarding
  - Decision-support metrics

  ### Out of Scope
  The following are outside the scope of the initial project:
  - Real-time supply chain monitoring
  - Production supplier risk decisioning
  - Automated supplier selection or replacement
  - Comprehensive ESG scoring or ratings
  - Predictive machine-learning models
  - External weather or natural-disaster integrations
  - Web scraping for supplier reputation
  - Contract or legal document analysis
  - Regulatory reporting
  - Production deployment

  These may be considered as potential future enhancements.

  ## 5. Target Stakeholders
  The conceptual users of the solution include:
  - Procurement teams
  - Supply chain managers
  - Supplier relationship managers
  - Risk and compliance stakeholders
  - Business management
  
  The project will focus on providing analytical information that helps stakeholders understand supplier performance, identify areas of concern, and investigate potential exposure.

  ## 6. Business Questions
  The solution should support questions such as:

  ### Supplier Performance
  - Which suppliers are performing well or poorly?
  - Which suppliers have recurring delivery or fulfillment issues?
  - Which suppliers have higher rates of defective or incorrect orders?
  
  ### Supplier Exposure
  - Which suppliers represent significant operational or financial dependency?
  - Which products or categories are highly dependent on a small number of suppliers?
  - Where might supplier concentration create vulnerability?
  
  ### Risk
  - Which supplier risk indicators are currently elevated?
  - What factors are driving a supplier's risk profile?
  - Which suppliers require further investigation?
  
  ### ESG
  - Which ESG indicators are available for the suppliers in the selected dataset?
  - Are there notable differences in ESG-related indicators across suppliers?
  - How could ESG information provide additional context when evaluating suppliers?
  
  ### Data Quality
  - How complete and reliable is the data used for supplier analysis?
  - Which fields or source datasets contain the most quality issues?
  - How do data-quality issues affect downstream analysis?

  ## 7. Success Criteria
  The project will be considered successful when it demonstrates that:
  1. Raw public data can be ingested and transformed using Microsoft Fabric.
  2. Data quality issues can be identified, documented, and addressed using Python and/or SQL.
  3. The curated data can be represented through an appropriate dimensional model.
  4. Supplier performance and risk indicators can be derived from the modeled data.
  5. Selected ESG indicators can be incorporated where supported by the available data.
  6. The analytical results can be consumed through a clear Power BI dashboard.
  7.The project documentation explains the business problem, data transformations, modeling decisions, assumptions, and limitations.
  8. The resulting GitHub repository provides a reproducible and understandable record of the project.

  ## 8. Assumptions & Constraints
  - The project will use publicly available datasets suitable for portfolio and educational use.
  - The selected dataset will determine which supplier performance and ESG indicators can be implemented.
  - Risk thresholds used in the project will be illustrative unless supported by an appropriate public source.
  - ESG indicators will not be presented as authoritative ESG ratings.
  - The project will prioritize a completed and well-documented mini-project over extensive feature coverage.
  - The initial implementation will be constrained by the available Microsoft Azure/Fabric trial resources and project timeframe.

# links-landing-supply-chain-scorecard
An end-to-end supply chain and e-commerce data analysis of Links Landing Antiques, focusing on inventory velocity, workflow automation, and profitability.

# Problem Statement

## Business Context 
Links Landing Antiques was established to manage and liquidate a massive family estate collection, which uniquely included over 100 vintage blowtorches. By applying Lean production concepts and building a custom AI-augmented appraisal tool, the initial bottleneck of pricing and listing these niche items was successfully resolved, scaling the operation to over 200 active e-commerce listings.

## The Challenge
While the listing process has been optimized, managing a high-volume, diverse inventory presents an ongoing supply chain challenge. The business currently lacks a centralized method to track inventory velocity and sales performance. Without this visibility, it is difficult to: 
* Identify "dead stock" (inventory sitting on the shelf too long)
* Determine accurate sell-through rates
* Understand which categories offer the highest profit margins to prioritize shipping and sourcing efforts.

## The Objective 
The goal of this project is to analyze historical transaction data and current active listings from the eBay Seller Hub to build a comprehensive "Supply Chain Scorecard". This scorecard will extract actionable business metrics to:
* **Analyze Inventory Velocity:**  Calculate the inventory turnover ratio and average lead time to identify which categories (e.g., vintage tools vs. stoneware) sell the fastest.
* **Optimize Profitability:**  Analyze sales by category to identify profitability trends and refine future pricing strategies.
* **Drive Efficiency:** Provide data-driven recommendations to clear out stagnant inventory and maintain operational efficiency.

## Data & Tools Used (The "Prepare" Phase)
This analysis relies on real-world, raw business data exported directly from the eBay Seller Hub. The following datasets are used:
* **Sales Report (eBay-ListingsSalesReport.csv):** Contains transaction-level data to analyze total sales, selling costs, and profitability margins.
* **Active Listings (eBay-all-active-listings-report.csv):** Used to assess current inventory levels and identify stagnant "dead stock".
* **Orders Report (ebay-all-orders-report.csv):** Contains buyer geographic data used for shipping logistics and geographic mapping.
* **Traffic Report (eBay-ListingsTrafficReport.csv):** Used to analyze click-through rates, conversions, and listing impressions.
* **Tools:** The data cleaning, exploration, and calculations for this scorecard will be performed using [Insert Python or R here].
## Methodology & AI Workflow (The "Process" Phase)
To scale the operations of Links Landing Antiques without sacrificing my academic focus at WGU, I applied Lean production concepts to the e-commerce workflow.
Because the business lacked centralized pricing data for niche items, I engineered a custom Gemini AI "Gem". This tool was designed to ingest raw mobile image data of the antiques and generate structured, standardized appraisal reports. By utilizing a prompt-based template to automate the creation of titles, descriptions, and pricing tables, I effectively reduced the "per-unit" listing time by a significant margin.
For this project, the raw operational data was extracted into CSVs and cleaned using Python and R to build a comprehensive Supply Chain Scorecard.  


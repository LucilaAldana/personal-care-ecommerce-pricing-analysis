### competitive-pricing-analysis-web-scraping

# Competitive Pricing Analysis for Personal Care E-Commerce

## by Lucila Aldana Quiñonez | Marketing Data Analyst

📄 Report available in: English - Spanish

This project develops a Python-based web scraping pipeline to automate competitor price tracking for personal care products in the Argentine e-commerce market.

The objective was to replace manual price monitoring with an automated, structured data collection system that enables competitive pricing analysis, discount benchmarking, and market positioning evaluation.

The analysis focuses on four Argentine competitors:

• GPSFarma

• Farmaonline

• Farmacity

• Farmalife

For each competitor, the scraping system attempts to extract and structure the following variables:

• Product Name

• Brand

• Price

• Discount

• Availability (In stock / Out of stock)

• Category & Subcategory

• Product URL

• Competitor

• Scraping Date

Key findings supported by the analysis include:

• Strong price homogeneity across competitors

• Frequent discount strategies ranging from 10% to 40%, with occasional campaigns up to 50%

• Similar shipping and free-delivery threshold structures

• Competition shifting from price differentiation toward logistics, availability, and customer experience

From a technical perspective, the project highlights real-world scraping challenges:

• Static HTML extraction (Requests + BeautifulSoup) was fully viable only for GPSFarma

• Other competitors use dynamic JavaScript rendering (e.g., VTEX-based architectures), limiting reproducible scraping

• Internal APIs showed restrictions and inconsistent behavior

• Browser automation tools (e.g., Selenium, Playwright) would be required for scalable extraction

The project documents ethical and legal considerations, using only publicly accessible data and respecting site integrity and terms of use.

This analysis simulates a real-world competitive intelligence scenario where automated data pipelines support dynamic pricing strategy, promotional benchmarking, and commercial opportunity detection.

Tools Used: Python / Requests / BeautifulSoup / Data Structuring / Web Scraping Pipeline Design / Competitive Intelligence Analysis

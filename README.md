# Store-Product-Compatibility-Space-Utilization-Analysis
A SQL project analyzing how product dimensions align with store capacities to optimize inventory distribution and maximize space utilization.

• Data Source: Kaggle


# Project Overview: Product and Store Compatibility Analysis

Objective:

The primary goal of this project is to analyze the compatibility between products and stores based on product dimensions and store capacity. The project aims to provide insights into product stocking efficiency, store performance, and product diversity across different store types and cities. These insights are critical for optimizing inventory distribution, improving supply chain efficiency, and enhancing overall retail operations.

# Key Business Questions Addressed:

1. Which products can fit into which stores based on size constraints?

2. How many products can each store accommodate?

3. What percentage of products can fit into each store?

4. Which cities and store types stock the most diverse range of products?

5. Which products do not fit into any store?

6. Which cities have low product diversity?

7. Which products can only fit into a limited number of stores?

8. Which store types offer the broadest product variety?

9. How efficiently is each store utilizing its capacity based on the average product size?

# Approach and Methodology:

1. Data Joining and Integration:

• Leveraged SQL joins (LEFT JOIN, RIGHT JOIN, UNION) to merge product and store datasets based on size compatibility.

• Used the GREATEST() function to compare product dimensions with store capacity.

2. Data Cleaning and Validation:

• Checked for missing values in both product and store datasets to ensure data integrity.

3. Descriptive Analysis:

• Counted the number of products that can fit into each store.

• Calculated the percentage of total products that can be stocked in each store (Stock Coverage Percentage).

4. Segmentation & Categorization:

• Assessed product diversity by city and store type.

• Segmented products by hierarchy levels (e.g., hierarchy1_id) to understand category distribution.

5. Product Fit Analysis:

• Identified products that do not fit in any store.

• Highlighted products that can only be stocked in a small number of stores.

6. Performance Analysis:

• Determined cities with low product diversity.

• Ranked store types by product variety.

7. Space Utilization:

• Calculated the average product size for each store and compared it to the store's capacity to identify unused space.

# Key Insights and Results:

• Certain products are too large for most stores, limiting their distribution.

• Some cities and store types offer a more diverse product range than others, indicating better inventory planning.

• Several stores have significant unused space, highlighting an opportunity to stock larger products or optimize inventory.

• Store types that stock the widest variety of products can serve as benchmarks for others.

# Value Proposition:

This project provides actionable insights that can enhance product placement strategies, optimize store capacity utilization, and improve supply chain efficiency. By ensuring products are matched to suitable stores, businesses can minimize storage constraints, reduce stockouts, and maximize sales potential.

# Why I Am the Ideal Candidate:

As a data analyst, I demonstrated my proficiency in SQL by crafting complex queries to extract valuable insights from raw data. I showcased my ability to:

• Clean and validate datasets.

• Perform advanced data joins and aggregations.

• Implement key performance indicators (KPIs).

• Conduct segmentation analysis for strategic decision-making.

• Present data-driven solutions to optimize inventory and retail operations.

This project reflects my analytical rigor, problem-solving skills, and understanding of business processes, positioning me as a strong candidate capable of driving data-informed decisions in your organization.


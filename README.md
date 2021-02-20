# Hackathon_Dunnhumby
Includes solution for the problem statement of the hackathon organized by Dunnhumby.

Problem Statement:

A cosmetic product company wants to reward its loyal customers by giving them a heavy discount on the products they buy repeatedly. Probability of buying these products on the next visit is computed using a heuristic. Higher probability scores meant higher relevancy. Based on the scores the company wants to allocate the most relevant set of products to customers.

Objective:

The objective of the hackathon is to allocate the most relevant set of products to each customer by maximizing total relevancy. You should use the column “relevancy_score” of Relevancy_table to get relevancy of products for customers.

Constraints:

Due to budget constraints, there is fixed volume of each product. For instance, product “5650512” cannot be allocated to more than 150 customers. Use the “Volume” column of the Products table.

A customer can get maximum 8 products and minimum 3 products. Drop all the customers who qualify for less than 3 products.

There are some set of products which cannot be assigned together (e.g. product “5649565” and “5649646” cannot be given together to any customer). You can get this list in the Exclusion table.

All the products allocated to a customer should be distinct (i.e. the same product cannot be allocated twice to the same customer)

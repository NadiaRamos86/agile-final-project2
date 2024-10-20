---
name: product catalog for an e-commerce website
about: This template is for creating product catalog
title: ''
labels: ''
assignees: ''

---

**As a**product manager
 **I need**a product catalog that displays all available items
 **So that** customers can easily browse and select products to purchase   
   
 ### Details and Assumptions
 - The catalog should include product images, descriptions, prices, and availability.
- Products are categorized by type (e.g., electronics, clothing).
- The system will pull data from a centralized database.
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given the user is on the product catalog page
 When the user selects a category filter
 Then the displayed products should only include items from that category
 ```

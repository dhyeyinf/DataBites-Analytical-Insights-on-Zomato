# Zomato Sales Analysis

This repository contains SQL scripts and datasets created to analyze Zomato's sales, customer behavior, and product popularity. The project explores various metrics such as total spending, most popular products, and customer-specific insights. The dataset and queries were designed for learning and practice purposes.

## Project Overview

The project simulates Zomato-like sales data and includes the following tables:

- **`goldusers_signup`**: Tracks Zomato Gold membership signups.
- **`users`**: Contains user signup data.
- **`sales`**: Records transaction details including product purchased, user, and date.
- **`product`**: Lists product details like name and price.

### Key Metrics and Insights

The SQL scripts calculate and analyze:

1. **Customer Spending**: Total amount spent by each customer.
2. **Visit Frequency**: Number of unique visits for each customer.
3. **Product Insights**: Identification of the first product purchased and the most popular product overall.
4. **Membership Analysis**:
   - Items purchased right before and after becoming a Zomato Gold member.
   - Total spending and orders before membership.
5. **Points System**: Simulates Zomato Points for purchases based on product-specific rules.
6. **Ranked Transactions**: Rankings for customer transactions based on date and membership status.

## How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/dhyeyinf/DataBites-Analytical-Insights-on-Zomato.git
   cd DataBites-Analytical-Insights-on-Zomato

# Agentic Data Analytics with Google Cloud BigQuery & Antigravity

A hands-on implementation of Google's Agentic Data Codelab, exploring how AI agents make business data accessible through natural-language conversations.

## Project Overview

Traditional data analytics often requires users to understand SQL and database structures. This project explores a conversational approach where users can ask business questions in natural language and receive data-driven answers.

The implementation uses a fictional frozen-yogurt business called **Froyo** as its business scenario.

## Technologies Used

- Google Cloud Platform
- Google BigQuery
- Google Antigravity IDE
- Google Cloud Data Agent Kit
- Gemini
- SQL
- BigQuery ML

## Dataset

The BigQuery dataset `froyo_data` contains 11 tables:

- allergen
- consistsOf
- containsallergen
- customer_allergen_data
- froyo_data_materialized
- ingredient
- order_items
- orders
- product
- suppliedby
- supplier

## Key Use Cases

### 1. Conversational Data Analytics
Explore business data through natural-language questions rather than manually writing every SQL query.

### 2. Allergen Detection
Identify allergens associated with products by analysing product, ingredient and allergen relationships.

### 3. Customer Purchase Analysis
Explore customer orders and product purchasing patterns.

### 4. Sales Forecasting
Explore BigQuery ML forecasting workflows to analyse historical sales and predict future trends.

## Architecture

1. Business data is stored in Google BigQuery.
2. Data agents use configured knowledge sources and instructions.
3. Gemini-powered agent workflows interpret natural-language questions.
4. Relevant SQL queries are generated and executed against BigQuery.
5. Results are presented as business insights, with forecasting and visualisation capabilities explored.

## What I Learned

- Working with Google BigQuery datasets and relational tables.
- Understanding conversational data agents.
- Exploring natural-language-to-SQL workflows.
- Configuring data sources and agent instructions.
- Exploring BigQuery ML forecasting.
- Understanding how Agentic AI can support business intelligence.

## Project Reference

This project was completed as a hands-on implementation of the official Google Codelab:

[Chat With Your Data using BigQuery Agents & Antigravity IDE](https://codelabs.developers.google.com/data-agents-in-agy-and-bq#2)

**Attribution:** Original learning material and codelab provided by Google.

## Project Status

Completed hands-on codelab implementation. This repository documents the learning experience, architecture and project exploration.

---

*Built while exploring Generative AI, Agentic AI and Google Cloud technologies.*

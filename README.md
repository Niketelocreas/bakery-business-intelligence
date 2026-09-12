# Bakery Business Intelligence

Business-oriented Data Science case study using public bakery transaction data.

## Objective

Analyse customer purchasing behaviour and transform transaction data into actionable recommendations for a bakery/café.

## Business questions

- Which products dominate demand?
- When are the busiest operating periods?
- How large are customer baskets?
- Which items are genuinely associated?
- Where can the business test cross-selling and operational improvements?

## Methods

- Data cleaning and feature engineering
- Exploratory Data Analysis
- Temporal demand analysis
- Basket-size analysis
- Market Basket Analysis
- Association rules using support, confidence and lift
- Business recommendation framework

## Dataset

The project uses the public **The Bread Basket** dataset from a bakery/café in Edinburgh.

The Kaggle version is distributed under **CC0 / Public Domain**.

Raw-data mirror used by the notebook:

`https://raw.githubusercontent.com/prasertcbs/basic-dataset/master/BreadBasket_DMS.csv`

## Main business themes

### Basket expansion

Single-item transactions provide a measurable opportunity for contextual cross-selling.

### Anchor products

High-support products such as coffee should receive priority in availability, service design and complementary-product placement.

### Data-driven bundles

Association rules identify combinations that occur more often than expected by chance.

### Staffing and production

Hourly and weekday transaction patterns can be translated into operating schedules.

### Assortment review

A large low-frequency product tail should be reviewed alongside margin, waste and operational complexity.

## Limitations

The public dataset contains no price, product cost, margin, inventory or waste information.

For this reason the project does not claim a quantified profit uplift.

## Portfolio workflow

**Transactions → EDA → Basket Analysis → Association Rules → Business Decisions**

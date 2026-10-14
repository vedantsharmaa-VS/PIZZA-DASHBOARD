
# 🍕 Pizza Sales Dashboard (Power BI)

I wanted to answer a simple question: *what is actually keeping a pizza place in business?* So I took a year of order data (Jan to Dec 2015) and built an interactive Power BI dashboard to dig into it.

It's not just a pile of charts. I tried to design it the way a restaurant owner would want to use it: open it, glance at the numbers, then click around to find out why.

## What's inside

**Page 1: Home / Sales Performance**
- **Headline KPIs:** Total Revenue, Total Orders, Total Pizzas Sold, Average Order Value, and Average Pizzas per Order
- **Sales by category and size:** donut charts showing which categories and sizes bring in the most money
- **Pizzas sold by category:** a funnel chart showing where the volume is
- **Monthly trend:** an area chart of orders across the year, so you can spot the busy and slow months
- **Daily trend:** a column chart of orders by day of the week, including how weekends compare

**Page 2: Best / Worst Sellers**
- Top and bottom pizzas ranked by **revenue**, **total orders** and **quantity sold**
- Dynamic text callouts that update as you filter
- Everything responds to the filters, so you can compare, say, only Veggie pizzas in one particular month

**Filters:** a pizza category dropdown and a date range slicer, plus page navigation buttons, so the dashboard feels like a small app rather than a static report.

## What I found
- Best-selling pizza by revenue: ...
- Busiest month and day of the week: ...
- Category with the biggest share of sales: ...
- Pizzas that are quietly underperforming: ...

## Tools
- **Power BI Desktop** for the report and visuals
- **DAX** for the measures (total revenue, average order value and so on)
- **Power Query** for cleaning and shaping the data

## How to open it
1. Download `PIZZA.pbix` from this repo
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Use the slicers and the navigation buttons to explore

## What I learned
Building this taught me more about **storytelling with data** than about charts. Deciding what *not* to put on the page was harder than adding visuals. I also got a lot more comfortable with DAX measures, slicer interactions and custom layouts.
EXAMPLE - https://github.com/vedantsharmaa-VS/PIZZA-DASHBOARD/blob/main/Screenshot%202026-10-14%20154413.png

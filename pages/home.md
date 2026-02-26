---
name: Home
assetId: f64a0b24-301d-4882-b1da-6b98257e0937
type: page
---

# Welcome

{% line_chart
    data="demo_daily_orders"
    x="date"
    y="sum(total_sales)"
    series="category"
    y_fmt="usd"
    date_grain="month"
    title="Monthly Sales by Category"
    subtitle="Total sales over time, broken down by product category"
/%}

# Sales Data Report: Cleaning Messy Invoice Data with Power Query and DAX

**Tools:** Power BI, Power Query, DAX · **Data:** a deliberately badly structured sample invoice file (2013 to 2016), from a Foresight BI practice exercise

![Sales Data Report dashboard](Sales%20Data%20Report.JPG)

## The task

A client supplied a messy invoice spreadsheet that could not be analyzed as it was. The goal was to automate the cleaning, model the data, and give the client clear insight into revenue trends.

## What I did

1. **Cleaned and reshaped** the raw file in Power Query into a tidy table: ship mode, segment, order date and sales.
2. **Built a date table** and related it to the sales table.
3. **Wrote DAX time intelligence measures:** revenue year to date, month to date, month over month change, and same period last year.
4. **Designed a one page dashboard** with year selection, trends by month, ship mode and customer segment.

## Key findings

* Total revenue over four years was **$392K**.
* **2016** brought in **$123K**, up **31.5%** on 2015 ($94K).
* **2014** was the weakest year ($71K) and is worth investigating.
* Revenue peaked in **November 2016 at $28,717**, up 136.6% month over month.
* The **Consumer** segment was about half of 2016 revenue, and **Standard Class** shipping drove the most revenue.

## Recommendations

* Build sales strategies for the **Corporate and Home Office** segments, which trail Consumer.
* Ask customers why they prefer Standard Class, to guide shipping offers.
* Investigate what caused the 2014 dip before planning targets.

## Files

| File | Contents |
|---|---|
| `2.-Badly-Structured-Sales-Data-2.xlsx` | Raw data |
| `Sales Data Report1.pdf` | Full report: overview, cleaning steps, dashboard, insights and recommendations |
| `Sales Data Report.JPG` | Dashboard image |

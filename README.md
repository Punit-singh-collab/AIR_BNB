Absolutely. This project is essentially an NYC Airbnb Market Intelligence / Business Analytics project. It takes Airbnb listing data and turns it into a dashboard that helps understand pricing, availability, location, room types, hosts, booking behavior, reviews, and revenue-related fields.

1. Project overview

Project title: NYC Airbnb Market Intelligence Dashboard

Dataset: Airbnb_Open_Data.xlsx

The workbook contains 102,599 Airbnb listing records and 33 columns covering:

Listing and host information
Borough and neighborhood
Room type
Construction year
Price and service fees
Minimum nights
Reviews and ratings
Host listing counts
Revenue-generated field
Availability
Cancellation policy
Instant booking
License/house-rule information

The HTML dashboard converts this raw data into an easy-to-understand business presentation.

2. Overall market performance
Average price

Average final price: $623.79

The CLEAR_ FINAL PRICE field ranges from $0 to $1,200, with:

Average: $623.79
Median: $623
25th percentile: $337
75th percentile: $912

So the dataset has a broad price distribution, while the median is very close to the average.

Availability

Average annual availability: 129.78 days

The availability field ranges from:

0 → 365 days

About 26.5% of listings have zero available days in the dataset.

This is an important business metric because availability can influence potential booking capacity and revenue.

3. Geographic performance

The geographic distribution is highly concentrated in three boroughs.

Borough	Listings	Share
Manhattan	43,793	42.7%
Brooklyn	41,843	40.8%
Queens	13,267	12.9%
Bronx	2,712	2.6%
Staten Island	955	0.9%
Unspecified	29	<0.1%
Main observation

Manhattan + Brooklyn account for approximately 83.5% of all listings.

That means the dataset is strongly concentrated in these two markets.

Queens is the third-largest market at approximately 12.9%.

4. Room-type performance

The room-type distribution is:

Room Type	Listings	Share
Entire home/apt	53,701	52.3%
Private room	46,556	45.4%
Shared room	2,226	2.2%
Hotel room	116	0.1%
Main observation

Entire homes/apartments are the largest category, representing about 52.3% of listings.

Private rooms are almost as large, at about 45.4%.

Shared and hotel rooms represent only a small portion of the dataset.

5. Host performance

The host identity field shows:

Host status	Listings	Share
Unconfirmed	51,200	49.9%
Verified	51,110	49.8%
Not specified	289	0.3%

The dataset is therefore almost evenly divided between verified and unconfirmed hosts.

This is useful when analyzing host trust/identity characteristics, although it should not by itself be interpreted as a measure of host quality.

6. Booking behavior

The instant_bookable field shows:

Booking status	Listings	Share
Not instant bookable	51,474	50.2%
Instant bookable	51,020	49.7%
Missing/not mentioned	105	~0.1%

So instant booking is also approximately a 50/50 split.

This gives the project another useful dimension for comparing listing characteristics.

7. Cancellation policies

The dataset contains three major cancellation policies:

Policy	Listings
Moderate	34,343
Strict	34,106
Flexible	34,074

These are remarkably close in size.

That makes cancellation policy a useful variable for further analysis because the dataset isn't dominated by only one policy category.

8. Reviews and customer engagement

The dataset contains a number of reviews field.

Review statistics
Average reviews: 27.43
Median reviews: 7
Maximum: 1,024
Minimum: 0

The large difference between the average and median indicates that some listings have substantially more reviews than the typical listing.

The review rate number field has:

Average rating: approximately 3.28 / 5

with values ranging from 1 to 5.

9. Minimum-night behavior

The cleaned minimum-night field shows:

Average minimum nights: 7.82
Median minimum nights: 3

Again, the average being substantially higher than the median suggests that some listings have relatively high minimum-night requirements.

This can be useful for studying how booking restrictions may relate to availability and revenue.

10. Revenue-related performance

The workbook contains a revenue_gererated field.

Its statistics are:

Average: 146,737.11
Median: 118,335
25th percentile: 40,128
75th percentile: 233,965
Maximum: 438,000

The sum of this field across the 102,599 rows is approximately:

15.06 billion

However, this should be described as the sum of the dataset's revenue_gererated field, not automatically as verified real-world Airbnb revenue, because the exact calculation methodology behind that column isn't established by the workbook alone.

11. Pricing by construction year

Your dashboard's line chart analyzes average final price by construction year.

The values stay relatively close to one another:

2003: $621.66
2008: $636.90
2015: $615.77
2019: $610.96
2021: $627.82
2022: $627.39

The highest average in this grouping is around $636.90 in 2008, while the lowest is around $610.96 in 2019.

So the construction-year analysis does not show a dramatic price trend. Instead, average prices fluctuate within a relatively narrow range.

12. What the project demonstrates

From a data analytics/project perspective, this is a strong example of an end-to-end dashboard workflow:

Raw Excel Data

↓

Data Cleaning

↓

KPI Calculation

↓

Geographic Analysis

↓

Room-Type Analysis

↓

Host Analysis

↓

Booking Analysis

↓

Pricing Trend Analysis

↓

Interactive HTML Dashboard

This makes it suitable as a portfolio project, internship project, or data-analytics presentation.

13. Key business insights

The most important findings from the dataset are:

📍 Geographic concentration

Manhattan and Brooklyn together represent approximately 83.5% of listings.

🏠 Property type

Entire homes/apartments are the largest room category at approximately 52.3%.

💰 Pricing

Average final price is approximately $623.79, with a median of $623.

📅 Availability

Average availability is approximately 129.78 days per year.

👤 Host verification

Verified and unconfirmed hosts are almost evenly represented.

⚡ Instant booking

Instant-bookable and non-instant-bookable listings are also almost evenly split.

⭐ Reviews

The median listing has 7 reviews, while some listings have substantially more.

📊 Construction year

Average pricing remains relatively stable across the construction-year groups in the dataset.

14. Project strengths

For a resume/interview, you can describe the project like this:

NYC Airbnb Market Intelligence Dashboard — An interactive data analytics project built using Python, Excel data processing, HTML, CSS, and JavaScript. Analyzed 102K+ Airbnb listings to identify pricing trends, geographic concentration, room-type distribution, host verification, booking behavior, availability, reviews, and revenue-related metrics. Developed an interactive dashboard to convert raw Airbnb data into business-oriented insights.

Skills demonstrated

Data:

Excel
Data cleaning
Data aggregation
Statistical analysis
KPI calculation

Programming:

Python
Pandas
JavaScript

Frontend:

HTML
CSS
Responsive design
Interactive filters
SVG visualization

Analytics:

Descriptive statistics
Geographic analysis
Trend analysis
Segmentation
Business intelligence
15. One important improvement

The current dashboard is mainly descriptive analytics. To make the project more advanced, the next version could add:

Price by borough
Revenue by borough
Revenue by room type
Availability vs. price
Reviews vs. revenue
Top 10 neighborhoods
Price distribution histogram
Interactive KPI cards that update with filters
Correlation analysis
Predictive model for price/revenue

That would turn it from a good visualization project into a more complete Data Analytics + Business Intelligence project.

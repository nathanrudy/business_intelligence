# Airbnb Market Analysis: Columbus vs New York

## Author
Nathan Rudy

## Project Overview
This project analyzes Airbnb listing data to compare the Columbus, Ohio and New York City markets. The goal is to allow Airbnb owners to better understand their competition, gain insight into the competitive landscape, and make informed decisions to maximize ROI.

## Research Questions

1. Given general location and amenities offered, what is the median rental price?
2. Given median rental prices and property values, which city has the potential for higher ROI?
3. Based on the percentages of short versus long term rentals, which sector should I choose to minimize competition?
4. Based on the number of listings per host in each city, which city should I choose to have the least competition with corporate owned/large scale rental companies?
5. What city has a higher average occupancy (nights booked versus nights available)? This will help us understand which cities/neighborhoods may have an oversaturation of rental properties.

## Data Source Mapping

| # | Question | Data Needed | Source | Data Type |
|:-:|:---------|:------------|:-------|:----------|
| 1 | Given general location and amenities offered, what is the median rental price? | price, latitude, longitude, room_type | listings.csv (NYC, Columbus) | Structured |
| 2 | Given median rental prices and property values, which city has the potential for higher ROI? | city, price, property values | listings.csv (NYC, Columbus), Zillow (NYC, Columbus) | Structured, Semi-structured |
| 3 | Based on the percentages of short versus long term rentals, which sector should I choose to minimize competition? | city, minimum_nights | listings.csv (NYC, Columbus) | Structured |
| 4 | Based on the number of listings per host in each city, which city should I choose to have the least competition with corporate owned/large scale rental companies?
 | city, calculated_host_listings_count | listings.csv (NYC, Columbus) | Structured |
| 5 | What city has a higher average occupancy (nights booked versus nights available)? | city, availability_365 | listings.csv (NYC, Columbus) | Structured |

## Data Overview
- **Columbus, Ohio:** 2877 listings (as of Sept 26, 2025)
- **New York City:** 36261 listings (as of Dec 4, 2025)
- **Primary data source:** [Inside Airbnb](http://insideairbnb.com/get-the-data)

## Project Status
- [x] Initial data exploration
- [x] Research questions defined
- [x] Data sources mapped
- [ ] Data downloaded and cleaned
- [ ] Analysis complete
- [ ] Visualizations created
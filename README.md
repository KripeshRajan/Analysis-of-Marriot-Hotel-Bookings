
# Analysis of Marriott Hotel Bookings
![images](https://github.com/user-attachments/assets/a69daf6a-bc57-4e5b-a75a-6dcba06f7ad5)

## Objective

This project analyzes booking data from City Hotel and Resort Hotel to identify the factors contributing to high cancellation rates. The primary goal is to provide data-driven insights and actionable recommendations for improving revenue management and room occupancy.

## Project Files

- **Hotel_bookings.ipynb**: Contains the code for data preprocessing, analysis, and visualization.
- **Hotel_bookings.pdf**



## Tools and Libraries
This project utilizes the following Python libraries:
- **Pandas**: Data manipulation and analysis.
- **Matplotlib** and **Seaborn**: Static data visualizations.
- **Plotly**: Interactive visualizations.
- **NumPy**: Numerical computations.




## Visualizations and Insights
 **Reservation Status Count**

![img1](https://github.com/user-attachments/assets/ec0ec037-f94b-4910-bf9a-92a4b8d222ca)
- Overall `37%` of the bookings are `canceled`, which has a significant impact on the hotels' earnings

**Cancellation Trends**





![img3](https://github.com/user-attachments/assets/2170e011-26f3-47a0-acf3-d2ec01e9b283)

- This indicates that `28%` of the reservations at the Resort Hotel were canceled, and `72%` were not.


![img4](https://github.com/user-attachments/assets/070a900d-3665-4887-a1bd-f58b406db6a2)
- This indicates that `42%` of the reservations at the City Hotel were canceled, and `58%` were not.

**Cancellation Trends: Resort Hotel vs. City Hotel**

![img2](https://github.com/user-attachments/assets/6b42af05-2d66-4aa7-bbe9-061722453e5d)

- Overall `37%` of the bookings are canceled, which has a significant impact on the hotels' earnings
- `City Hotel` has a significantly higher cancellation rate `(41.73%)` compared to the Resort Hotel `(27.76%)`, suggesting the need for targeted strategies to address this issue

**Average Daily Rate in resort and city hotels**


![img5](https://github.com/user-attachments/assets/5ed21dab-47b3-4e5c-a9ab-7ef32f560bcb)


- `Fluctuations in Resort Hotels:` The ADR for Resort Hotels shows significant variability over time.There are noticeable peaks during certain periods like, weekends,holiday seasons or times of higher demand(summer and year-end holidays).
- `Stability in City Hotels:` The ADR for City Hotels is relatively stable compared to Resort Hotels.This suggests that demand and pricing for city accommodations might be less affected by seasonal factors and more influenced by consistent business or travel activity.


**Reservation status per month**

![img6](https://github.com/user-attachments/assets/92a19fb0-5304-41d8-bbe9-8f61ced19687)

- `Monthly Trends:` The number of reservations varies significantly across different months. The highest number of reservations occurs in `August`, followed by `July` and `March`. This indicates peak months for hotel reservations.

- `Cancellation Rates:` The number of canceled reservations is consistently lower than the number of not canceled reservations for all months. However, the proportion of cancellations varies. For instance, `January` and `December` have relatively higher cancellation rates compared to other months.

- `Seasonal Patterns:` There is a noticeable increase in reservations during the summer months (`June`, `July`, and `August`). This suggests a seasonal trend where more people book hotels during the summer, possibly for vacations or travel.


**Average Daily Rate (ADR) per Month**

![img7](https://github.com/user-attachments/assets/5c8df67f-f0df-4550-8f5a-1155117def35)

-  The highest average daily rate is observed in `August`,The lowest average daily rates are observed in `January` and `February`

- `Seasonal Trend:` There is a noticeable increase in the average daily rate from `January` to `August`, with a peak in August. This upward trend indicates increasing demand as the year progresses towards the summer months.

- `Decline After Peak:` After August, the average daily rate decreases, with a significant drop in September and continuing to decrease towards December. This decline suggests a reduction in demand after the peak summer season.

**Top 10 Countries Contributing to Reservation Cancellations**

![img8](https://github.com/user-attachments/assets/3dda6c6c-e124-4ad3-8a57-dfa78c61ee69)

- `Portugal (PRT)` has the highest percentage of cancelled reservations by a significant margin, accounting for `70.07%` of the total cancellations. Need to improve hotel quality and service standards in Portugal to minimize cancellation rates

**Distribution of Bookings by Market Segment**

![newplot (6)](https://github.com/user-attachments/assets/8e7c2534-ff85-4da5-95ad-071a2452de1f)

- `Online Travel Agencies` accounts for the largest share, `47.4%` of bookings.This highlights the critical role of online platforms in driving hotel bookings, likely due to their accessibility and ease of use for customers.



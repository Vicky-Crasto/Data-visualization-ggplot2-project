## Project title 
Using data visualization (ggplot2), we are analyzing supply and demand to help Taximan improved operational efficiency
## Background of the case 
TAXIMAN, a cab service company, has been facing constant criticism of not being able to meet rising demand and decreasing customer satisfaction ratings. 
Using the historical data, we need to understand the supply and demand pattern and help them make better business decisions and improve its operational efficiency. 
## Dataset 
The case study was part of the [Jigsaw Academy]( https://www.jigsawacademy.com/),   `Monthly Challenge - Sept`, hence the dataset is a proprietary data set and a [sample](https://github.com/Vicky-Crasto/Data-visualization-ggplot2-project/blob/master/Sample%20Data%20set_taximan.csv) has been provided
## Additional Remarks
I participated, and my submission was judged as the best project.
[Letter of appreciation – By Jigsaw Academy](https://github.com/Vicky-Crasto/Data-visualization-ggplot2-project/blob/master/Letter_of_Appreciation_Taximan.pdf) – This note provides a brief of the project and comments of the review panel
[Certification of Excellence – By Jigsaw Academy](https://github.com/Vicky-Crasto/Data-visualization-ggplot2-project/blob/master/Certification%20of%20Excellence_Taximan.pdf)
#### [Detailed R code](https://github.com/Vicky-Crasto/Data-visualization-ggplot2-project/blob/master/R%20code%20.md)
#### [Observation, results and conclusion (presentation)]( https://github.com/Vicky-Crasto/Data-visualization-ggplot2-project/blob/master/Obseravtions%2C%20results%20and%20conclusions.pdf)

## Data Description
The dataset consists of 6068 observations. 
The following variables have been provided
- Pickup location and coordinates
- Drop location and coordinates 
- Date of journey ( 1 July to 15 July)
- Time Slot (8-11 AM, 11 AM to 4 PM, 4 PM to 10 PM)
- Ride Status (Completed or Cancelled)
- Payment Mode (Cash or PayTM)
- Reason for cancellations

## Data preparation 
- Read dates in correct format in R
- Create new variable to provide the day of the week, convert it to factor and fix its order
- Convert timeslot to factor and fix its order.
- Create a route variable from the pickup and drop locations.

## Approach to analysis the data
Analysis was done at 3 levels and accordingly the visualization was produced
### Based on week day wise booking distribution
- Overview of the booking date wise
- Weekday Bookings distribution based on status
- Weekday Bookings distribution based on timeslot
- Reason for cancellation
- Drill down into reason for cancellation
- Distribution of payment mode used by customers.
- Coupon usage based on Timeslot
- Drill down to understand coupon usage, payment mode and status.

### Based on pick up location
- Top most pickup locations 
- Top 5 pickup locations – deeper look
- Booking status based on pickup location
- Demand supply analysis – based on pickup location
- Digging deeper to demand supply analysis.

### Based on drop location
- Top most drop locations 
- Top 5 drop locations – deeper look
- Demand supply analysis – based on drop location
- Overview of the top most routes





# Project_NYC_Green_taxi

### The project involves the following key steps:

**Data Collection:** https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page ->2023 -> May -> Green Taxi Trip Records

### Data Description:
**About Green Taxi Description**
|Variable Name| Description|
|--|--|
|VendorID	 |A code indicating the LPEP provider that provided the record.<br>1= Creative Mobile Technologies, LLC;<br>2= VeriFone Inc.|
| lpep_pickup_datetime| The date and time when the meter was engaged.|
| lpep_dropoff_datetime	| The date and time when the meter was disengaged.|
| Passenger_count |The number of passengers in the vehicle. This is a driver-entered value.|
| Trip_distance | The elapsed trip distance in miles reported by the taximeter.|
| PULocationID | TLC Taxi Zone in which the taximeter was engaged.|
| DOLocationID | TLC Taxi Zone in which the taximeter was disengaged.|
| RateCodeID	| The final rate code is in effect at the end of the trip.<br>1= Standard rate <br>2=JFK<br>3=Newark<br>4=Nassau or Westchester<br>5=Negotiated fare<br>6=Group ride|
| Store_and_fwd_flag |	This flag indicates whether the trip record was held in vehicle memory before being sent to the vendor, aka “store and forward,” because the vehicle did not connect to the server.<br>    Y= store and forward trip<br>N= not a store and forward trip|
| Payment_type | A numeric code signifying how the passenger paid for the trip.<br>1= Credit card<br>2= Cash<br>3= No charge<br>4= Dispute<br>5= Unknown<br>6= Voided trip|
| Fare_amount	| The time-and-distance fare calculated by the meter.|
| Extra	| Miscellaneous extras and surcharges. This only includes the $0.50 and $1 rush hour and overnight charges.|
| MTA_tax	| $0.50 MTA tax automatically triggered based on the metered rate in use.|
| Improvement_surcharge	| $0.30 improvement surcharge assessed on hailed trips at the flag drop. The improvement surcharge began being levied in 2015.|
| Tip amount | This field is automatically populated for credit card tips. Cash tips are not included.|
| Tolls_amount | Total amount of all tolls paid in trip.|
| Total_amount | The total amount charged to passengers, Does not include cash tips.|
|Trip_type | A code indicating whether the trip was a street hail or a dispatch that is automatically assigned based on the metered rate in use but can be altered by the driver.<br>1 = Street-hail<br>2 = Dispatch|

**Data Preprocessing:** Cleaning and preprocessing the dataset to handle missing values, outliers, and inconsistencies. This step also involves transforming categorical variables into numerical representations, normalizing numeric features, and splitting the dataset into training and testing subsets.

**Model Training:** Implementing linear regression using appropriate libraries or frameworks. The training process involves fitting the model to the training data, estimating the coefficients (slope and intercept), and optimizing the model's performance by minimizing the residual errors between the predicted and actual values.

**Model Evaluation:** Assessing the performance of the trained linear regression model using evaluation metrics such as mean squared error (MSE), root mean squared error (RMSE), and R-squared. These metrics provide insights into how well the model predicts the values and indicate its overall accuracy.


### Fork the repository on GitHub:
  1)Create a new branch from the main branch to work on your changes.<br>
  2)Make your modifications and commit your changes.<br>
  3)Push your branch to your forked repository.<br>
  4)Open a pull request to the original repository, describing the changes you made.<br>
  
### License:
This project is licensed under the GPU License.

### Acknowledgments
The dataset used in this project is sourced from: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page -> 2023 -> May -> Green Taxi Trip Records.<br>
The Regression algorithm is implemented using the scikit-learn library.

### Contact
If you have any questions or suggestions regarding this project, please feel free to contact me at eadityar@gmail.com

### Conclusion:

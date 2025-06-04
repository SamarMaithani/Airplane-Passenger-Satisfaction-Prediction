# About The Project
This project endeavors to develop a sophisticated machine-learning model aimed at accurately predicting the possibility whether a customer will be "Satisfied" or "Neutral/Unhappy" based on various factors including demographic details, travel characteristics, and service-related ratings such as booking ease, inflight service, cleanliness, entertainment, and more. By identifying the key drivers of satisfaction, airlines can take proactive steps to enhance passenger experiences, optimize operations, and make informed, data-driven decisions to improve overall customer engagement.

The Given dataset provides a multitude of attributes including Passenger’s IDs, Travel Class, Travel Distance, the Delay times and a wealth of other pertinent features. The focal point of this endeavor centers on the Satisfaction field  (‘Y’ status), which serves as the pivotal target variable for classification. 
To make any sort of prediction from the data, the data is first cleaned, then some EDA is performed on the data to discover any insight in the features and after applying some pre-processing techniques a classification ML model is used to Evaluate the Performance of the Model.

# About the Data
The data Presented to us consists of 129880 observations and 23 features + 1 target attribute. Attributes given in dataset as:

- ID				                               -       Unique passenger identifier
- Gender			                             -      Gender of the passenger (Female/Male)
- Age				                               -       Age of the passenger
- Customer Type		                         -       Type of airline customer (First-time/Returning)
- Type of Travel	                         -     	Purpose of the flight (Business/Personal)
- Class		                                 -     	Travel class in the airplane for the passenger seat
- Flight Distance	                         -     	Flight distance in miles
- Departure Delay	                         -       Flight departure delay in minutes
- Arrival Delay		                         -       Flight arrival delay in minutes
- Departure and Arrival Time Convenience   -       Satisfaction level with the convenience of the flight departure and arrival times from 1 (lowest) to 5 (highest) - 0 means "not applicable"
- Ease of Online Booking                   -       Satisfaction level with the online booking experience from 1 (lowest) to 5 (highest) - 0 means "not applicable"
- Check-in Service                         -       Satisfaction level with the check-in service from 1 (lowest) to 5 (highest) - 0 means "not applicable"
- Online Boarding                          -       Satisfaction level with the online boarding experience from 1 (lowest) to 5 (highest) - 0 means "not applicable"
- Gate Location                            -       Satisfaction level with the gate location in the airport from 1 (lowest) to 5 (highest) - 0 means "not applicable"
- On-board Service                         -       Satisfaction level with the on-boarding service in the airport from 1 (lowest) to 5 (highest) - 0 means "not applicable"
- Seat Comfort                             -       Satisfaction level with the comfort of the airplane seat from 1 (lowest) to 5 (highest) - 0 means "not applicable"
- Leg Room Service                         -       Satisfaction level with the leg room of the airplane seat from 1 (lowest) to 5 (highest) - 0 means "not applicable"
- Cleanliness                              -       Satisfaction level with the cleanliness of the airplane from 1 (lowest) to 5 (highest) - 0 means "not applicable"
- Food and Drink                           -       Satisfaction level with the food and drinks on the airplane from 1 (lowest) to 5 (highest) - 0 means "not applicable"
- In-flight Service                        -       Satisfaction level with the in-flight service from 1 (lowest) to 5 (highest) - 0 means "not applicable"
- In-flight Wi-Fi Service                  -       Satisfaction level with the in-flight Wi-Fi service from 1 (lowest) to 5 (highest) - 0 means "not applicable"
- In-flight Entertainment                  -       Satisfaction level with the in-flight entertainment from 1 (lowest) to 5 (highest) - 0 means "not applicable"
- Baggage Handling                         -       Satisfaction level with the baggage handling from the airline from 1 (lowest) to 5 (highest) - 0 means "not applicable“
- Overall-Satisfaction                     -       Overall satisfaction level with the airline (Satisfied/Neutral or unsatisfied) – Target column


# Conclusion
In the competitive airline industry, understanding customer satisfaction is essential for improving service quality and retaining loyal passengers. This project has demonstrated the application of machine learning in identifying whether the passenger will be satisfied or not, and how much remarkable potential it has in enhancing the accuracy of the prediction. And through the confusion matrix we saw that the train and test data is balanced. 

Through the utilization of ensemble techniques and the dataset we have seen the development of a great model that provides an accuracy of 97%. As the technology's advances, we can expect a greater stride in the accuracy and efficiency of the machine learning models which in turn will contribute to even  increase the passenger’s satisfaction.

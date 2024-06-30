# *New York TLC Trip Record Analysis*
*This repository contains analysis results from the New York TLC Trip Record dataset. The purpose of this analysis is to increase the usage number of fictional credit card brand named 'Misa' as a payment method for taxi in New York City.*

## **Background**
*The New York City Taxi and Limousine Commission (TLC) is the agency responsible for licensing and regulating New York City's Medallion (Yellow) taxi cabs, for-hire vehicles (community-based liveries, black cars and luxury limousines), commuter vans, and paratransit vehicles.*

## **Dataset Explanation**
*The TLC collects trip record information for each taxi and for-hire vehicle trip completed by our licensed drivers and vehicles. This data is received from Technology Service Providers (TSP) that provide electronic metering in each cab, and FHV trip data from the app, community livery, black car, or luxury limousine company, or base, who dispatched the trip. In each trip record dataset, one row represents a single trip made by a TLC-licensed vehicle.*

## **Problem**
*As a COO 'Misa' Credit Card Company, we want to increase the usage number of our credit card. Based on **NYC TLC Trip Record Dataset** we want to know if credit card is used more than other payment methods. We also want to know times of day when taxi traffic is at its highest. *

*Apart from that, we want to make special promotional programs for certain types of trips. We need to know what types of trip is the highest to make on-target promotion programs. So we can apply our promotional programs to this type of trip.*

## **Variable Explanation**
- VendorID A code indicating the LPEP provider that provided the record.
    - 1 = Creative Mobile Technologies, LLC.
    - 2 = VeriFone Inc.

- lpep_pickup_datetime The date and time when the meter was engaged.

- lpep_dropoff_datetime The date and time when the meter was disengaged.

- Passenger_count The number of passengers in the vehicle. This is a driver-entered value. Trip_distance The elapsed trip distance in miles was reported by the taximeter.

- PULocationID TLC Taxi Zone in which the taximeter was engaged.

- DOLocationID TLC Taxi Zone in which the taximeter was disengaged.

- RateCodeID The final rate code is in effect at the end of the trip.
    - 1 = Standard rate
    - 2 =JFK
    - 3 =Newark
    - 4 =Nassau or Westchester
    - 5 =Negotiated fare
    - 6 =Group ride

- Store_and_fwd_flag This flag indicates whether the trip record was held in the vehicle memory before sending to the vendor, aka “store and forward,” because the vehicle did not have a connection to the server.
    - Y = store and forward trip
    - N = not a store and forward trip

- Payment_type A numeric code signifying how the passenger paid for the trip.

    - 1 = Credit card
    - 2 = Cash
    - 3 = No charge
    - 4 = Dispute
    - 5 = Unknown
    - 6 = Voided trip

- Fare_amount The time-and-distance fare is calculated by the meter. Extra Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges.

- MTA_tax $0.50 MTA tax that is automatically triggered based on the metered rate in use.

- Improvement_surcharge $0.30 improvement surcharge assessed on hailed trips at the flag drop. The improvement surcharge began being levied in 2015.

- Tip_amount This field is automatically populated for credit card tips. Cash tips are not included.

- Tolls_amount The total amount of all tolls paid in the trip.

- Total_amount The total amount charged to passengers. Does not include cash tips.

- Trip_type A code indicating whether the trip was a street hail or a dispatch that is automatically assigned based on the metered rate in use but can be altered by the driver.
    - 1 = Street-hail
    - 2 = Dispatch

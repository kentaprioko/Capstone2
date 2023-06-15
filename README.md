## **Background**
*The New York City Taxi and Limousine Commission (TLC) adalah badan yang bertanggung jawab untuk mengatur taxi, kendaraan sewaan, mobil komuter, dan kendaraan paratransit di kota New York.*

## **Dataset Explanation**
*Dataset yang digunakan adalah data yang dikumpulkan oleh TLC untuk setiap trip yang diselesaikan oleh para pengemudi yang berlisensi. Data dicatat oleh Technology Service Providers (TSP) yang juga menyediakan argo elektrik pada setiap taxi, kendaraan sewaan, mobil komuter, dan kendaraan paratransit. Satu baris pada dataset mewakili 1 trip.*

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

## **Problem**
Sebagai COO di Perusahaan Kartu Kredit 'Misa', tim kami ingin meningkatkan jumlah penggunaan Kartu Kredit 'Misa'. Berdasarkan dari dataset **NYC TLC Trip Record Dataset** kami ingin mengetahui apakah metode pembayaran kartu kredit jumlahnya lebih banyak dari metode pembayaran lainnya. Kami juga ingin mengetahui pada rentan waktu kapan traffic penggunaan taxi sedang paling tinggi. 

Selain itu, kami ingin mengadakan program promosi khusus pada tipe trip tertentu. Agar promosi kami tepat sasaran, kami perlu mengetahui tipe trip apa yang jumlahnya paling banyak. Sehingga kami bisa mengaplikasikan program promosi kami pada tipe trip tersebut.

## **Data Cleaning**

### **Drop Duplicate Row**
### **Handling Null Value**
### **Check Anomaly**
### **Clear Outlier**

## **Data Analysis**

#### *Melihat Distribusi Metode Pembayaran*
#### *Melihat Jumlah Trip Berdasarkan Time Range*
#### *Membagi Jarak Trip Menjadi 5 Kategori*

🚖 OLA Data Analyst Project
📌 Project Overview

This project simulates and analyzes ride-hailing data for OLA (Bengaluru) using SQL and Power BI.
The dataset (100K+ synthetic records) contains ride details, cancellations, payments, and ratings.

The analysis answers key business questions:

How many rides are successful vs. canceled?

What are the main reasons for cancellations?

Which vehicle types and customers contribute the most revenue?

How do ratings vary between customers and drivers?

Which payment methods dominate ride revenues?

🗂 Dataset Description

Key attributes in the dataset:

Booking Info → Date, Time, Booking_ID, Customer_ID, Booking_Status

Vehicle Info → Vehicle_Type, Ride_Distance, Pickup & Drop Locations

Cancellations → Cancelled_Rides_by_Customer (with reasons), Cancelled_Rides_by_Driver (with reasons)

Ratings → Driver_Ratings, Customer_Ratings

Revenue & Payment → Booking_Value, Payment_Method

🔍 SQL Analysis

Queries written to answer:
✔ Retrieve all successful bookings
✔ Average ride distance by vehicle type
✔ Cancellation counts (Customer vs Driver)
✔ Top 5 customers by number of rides & booking value
✔ Max/Min driver ratings for Prime Sedan
✔ Revenue by successful bookings
✔ Incomplete rides with reasons

📊 Power BI Dashboard Insights
🔹 Ride Overview

Total Bookings: 40.54K

Successful Rides: 25.21K (~62%)

Customer Cancellations: 4.08K (~10%)

Driver Cancellations: 7.21K (~18%)

Driver Not Found: 4.04K (~10%)

Total Booking Value: ₹14M+

📈 Ride Volume Trend → Ride demand fluctuates weekly with peaks on weekends.

🔹 Revenue Insights

Payment Method Distribution:

Cash & UPI dominate revenue share.

Credit/Debit cards form a smaller portion.

Top 5 Customers by Revenue:

CID792698 → ₹4,457

CID219102 → ₹3,783

CID688426 → ₹3,760

CID836942 → ₹3,757

CID159493 → ₹3,748

🔹 Cancellation Analysis

Customer Cancellations (4.08K):

Driver not moving towards pickup → 29.9%

Driver asked to cancel → 25.9%

Change of plans → 19.7%

AC not working → 14.9%

Wrong address → 9.5%

Driver Cancellations (7.21K):

Personal & car issues → 34.7%

Customer related issue → 29.4%

Sick customer → 19.8%

Excess passengers → 16%

🔹 Ratings Analysis

Driver & customer ratings distributions highlight consistency across most vehicle types.

No major negative outliers, showing balanced satisfaction levels.

🛠 Tech Stack

SQL → Querying & business insights

Power BI → Visualization & dashboarding

Excel/CSV → Data preprocessing & storage

🚀 Key Learnings

Built a large-scale synthetic dataset (~100K rows).

Applied SQL queries to solve real business problems.

Designed a Power BI dashboard for decision-making insights.

Explored ride cancellations, customer behavior, and revenue drivers.

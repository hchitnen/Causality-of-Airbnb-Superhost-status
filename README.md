### Causality-of-Airbnb-Superhost-status

**Backdrop**: 

The  Superhost certication program is used by Airbnb to provide guests with a clear and visible platform-initiated indicator of host quality. Airbnb hosts must have met the following criteria over the previous 365 days to be awarded the Superhost status. 
 
<img width="452" alt="image" src="https://github.com/hchitnen/Causality-of-Airbnb-Superhost-status/assets/148294077/c36d8a6a-b114-4bff-8fb5-95f50d5483c9">

**Problem Statement:**
To determine whether the “Superhost” status on the Airbnb platform effect the occupancy rates?

**Dataset Overview:**

The dataset includes eight ‘Superhost’ evaluation periods: April (2017, 2018), July(2016, 2017), October(2016, 2017), and January(2017, 2018). Each observation represents one active listing (or property) in one of the eight evaluation periods.

•	New York - Airbnb Bookings Dataset (437,583)
•	Evaluation periods considered: 10, 11
•	64,104 rows of data. (in the evaluation periods considered)

**Methodology:** 

To determine the isolated effect of ‘Superhost’ status on occupancy, we have selected only those properties  that have just missed the on superhost status in one  evaluation period and have just passed the required criteria to attain the superhost status in the next evaluation period. 

Below is the creteria used for selecting the just miss and juss pass groups of properties for analysis.

<img width="452" alt="image" src="https://github.com/hchitnen/Causality-of-Airbnb-Superhost-status/assets/148294077/bed8b9b3-4ca0-41db-a857-f19c2d21fbd8">

<img width="452" alt="image" src="https://github.com/hchitnen/Causality-of-Airbnb-Superhost-status/assets/148294077/c4c2f167-6dab-4557-ab19-133d789de4c8">


After extracting the required set of data, we have determined the treatment and control group for analysis. 


Control Group: Properties that just Miss superhost status in period 11
Treatment Group: Properties that just Pass superhost status in period 11


<img width="452" alt="image" src="https://github.com/hchitnen/Causality-of-Airbnb-Superhost-status/assets/148294077/2e50fdb9-4f49-4e64-96a3-b8760d28ca15">


From the initial analysis, we have observed that occupancy rates of treatment group have increased in period 11 compared to period 10


 <img width="452" alt="image" src="https://github.com/hchitnen/Causality-of-Airbnb-Superhost-status/assets/148294077/f5d822aa-b064-4707-a222-d1672a697c4e">


**But how much of this increase is caused by ‘Superhost’ status?**

So, to further determine the effect of superhost status, we would be performing the following regression analysis:

<img width="452" alt="image" src="https://github.com/hchitnen/Causality-of-Airbnb-Superhost-status/assets/148294077/1f99c60a-2ffe-4953-b2db-8cff03b8d54e">

**Linear Regression Equation with Interaction term:**

<img width="498" alt="image" src="https://github.com/hchitnen/Causality-of-Airbnb-Superhost-status/assets/148294077/04d7932a-ddb6-450c-a549-7b14b2106672">

**Superhost Effect:**

<img width="421" alt="image" src="https://github.com/hchitnen/Causality-of-Airbnb-Superhost-status/assets/148294077/fd90a3c6-da5d-454f-8e60-db0e67d96351">


<img width="220" alt="image" src="https://github.com/hchitnen/Causality-of-Airbnb-Superhost-status/assets/148294077/4935fd6f-b448-4ce1-ae60-ecf6b1acdbb9">












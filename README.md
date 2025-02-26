# Delhivery Business case study - Linear-Regression
I recently completed an in-depth case study on the Delhivery dataset, focusing on feature engineering to derive meaningful insights. Delhivery, India's largest and fastest-growing fully integrated logistics player, is a pioneer in leveraging data to outpace the competition. Their goal is to build the operating system for commerce by combining world-class infrastructure with cutting-edge technology.
In this case study, I delved into how data can be transformed into actionable intelligence. Here’s what I worked on:
🔍 Feature Engineering:
Cleaned, sanitized, and manipulated raw data to extract useful features.
Processed data from engineering pipelines to provide the data science team with high-quality inputs for building robust forecasting models.
Delhivery's focus on using data to enhance quality, efficiency, and profitability is truly inspiring. This experience has deepened my understanding of how critical data processing is in driving business success. Excited to apply these insights to future projects!

# About Delhivery

Delhivery is the largest and fastest-growing fully integrated player in India by revenue in Fiscal 2021. They aim to build the operating system for commerce, through a combination of world-class infrastructure, logistics operations of the highest quality, and cutting-edge engineering and technology capabilities.

The Data team builds intelligence and capabilities using this data that helps them to widen the gap between the quality, efficiency, and profitability of their business versus their competitors.
# Objective
The company wants to understand and process the data coming out of data engineering pipelines:

• Clean, sanitize and manipulate data to get useful features out of raw fields

• Make sense out of the raw data and help the data science team to build forecasting models on it
# About the data set
data - tells whether the data is testing or training data
trip_creation_time – Timestamp of trip creation
route_schedule_uuid – Unique Id for a particular route schedule
route_type – Transportation type
FTL – Full Truck Load: FTL shipments get to the destination sooner, as the truck is making no other pickups or drop-offs along the way
Carting: Handling system consisting of small vehicles (carts)
trip_uuid - Unique ID given to a particular trip (A trip may include different source and destination centers)
source_center - Source ID of trip origin
source_name - Source Name of trip origin
destination_cente – Destination ID
destination_name – Destination Name
od_start_time – Trip start time
od_end_time – Trip end time
start_scan_to_end_scan – Time taken to deliver from source to destination
is_cutoff – Unknown field
cutoff_factor – Unknown field
cutoff_timestamp – Unknown field
actual_distance_to_destination – Distance in Kms between source and destination warehouse
actual_time – Actual time taken to complete the delivery (Cumulative)
osrm_time – An open-source routing engine time calculator which computes the shortest path between points in a given map (Includes usual traffic, distance through major and minor roads) and gives the time (Cumulative)
osrm_distance – An open-source routing engine which computes the shortest path between points in a given map (Includes usual traffic, distance through major and minor roads) (Cumulative)
factor – Unknown field
segment_actual_time – This is a segment time. Time taken by the subset of the package delivery
segment_osrm_time – This is the OSRM segment time. Time taken by the subset of the package delivery
segment_osrm_distance – This is the OSRM distance. Distance covered by subset of the package delivery
segment_factor – Unknown field
# Insights
1. Busiest corridor being 
IND000000ACB to IND562132AAA
2. Top source city is Gurgaon , followed by Bangalore 
3. Top state is Haryana , followed by Maharashtra
#Recommendations
 1.   Focus marketing efforts on states or regions identified as major sources of orders.
  2.   Improve service efficiency along the busiest corridors identified, potentially reducing average time taken through optimization strategies.
  3. Use insights on average distance and time taken to optimize routes and enhance operational efficiency.
  4.   Allocate resources based on the busiest corridors to manage demand effectively.

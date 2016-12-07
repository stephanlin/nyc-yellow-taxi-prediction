# *NYC Yellow Taxi Prediction*
*To analyze NYC Yellow Taxi dataset to help taxi companies to maximize their utilization by diverting the cabs into the locations during specific times and help taxi drivers to make more profits.*

## Group Members
* [Shenghua You](https://github.com/shenghuayou), shenghuayou@gmail.com
* [Victor Fung](https://github.com/VictorFung1), victor.fung122@gmail.com
* [Weifan Lin](https://github.com/LinfinityLab), tjc.stefanlin@gmail.com
* [Rafael Li Chen](https://github.com/RafaelLiChen), rafaellichen@gmail.com

## Datasets
* [NYC Taxi Trip Data (csv)](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml)
* [NYC Blocks (geojson)](/datasets/block-groups-polygons.geojson)

## Proposal Questions
#### 1. What will be the best blocks to pick-up customers for each day of the week of a month?
  * Input: day of week, month
  * Output: best blocks

#### 2. Can we accurately predict the closest block that will get the driver the highest tips based on the time of the day and day of the week?
  * Input: time of the day, day of the week, driver’s location
  * Output: closest block to the driver’s location

#### 3. Can we accurately predict how much tips a driver will get based on pick-up location, the distance traveled to destination and time spent?
  * Input: pick-up location, trip distance, trip duration
  * Output: amount of tips

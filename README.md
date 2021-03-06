# NYC Yellow Taxi Prediction
*To analyze NYC Yellow Taxi dataset to help taxi companies to maximize their utilization by diverting the cabs into the locations during specific times and help taxi drivers to make more profits.*

## [Project Screencast Video](https://www.youtube.com/watch?v=4MkDi-Jz3ac)

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
  * [Q1 Progress Notebook](Q1%20Examine%20-%20Best%20Pick-up%20Location.ipynb)
  * [Q1 Result Notebook](Q1%20Final%20Answer%20-%20Best%20Pick-up%20Location.ipynb)

#### 2. What is the closest location within a specific distance that will get driver the highest tip based on time of the day and day of the week?
  * Input: time of the day, day of the week, driver’s location, distance range
  * Output: closest spot to the driver’s location
  * [Q2 Progress Notebook](Q2%20Examine%20-%20Highest%20Tip%20Location.ipynb)
  * [Q2 Result Notebook](Q2%20Final%20Answer%20-%20Highest%20Tip%20Location.ipynb)
  
#### 3. Can we accurately predict how much tips a driver will get based on pick-up location, the distance traveled to destination and time spent?
  * Input: pick-up location, trip distance, trip duration
  * Output: amount of tips
  * [Q3 Progress Notebook](Q3%20Examine%20-%20Applying%20KNeighbors%20Regression.ipynb)
  * [Q3 Result Notebook](Q3%20Final%20Answer%20-%20Applying%20KNeighbors%20Regression.ipynb)

# py
import pandas as pd
weather_data={
    'day':['1/1/2017','1/2/2017','1/3/2017','1/4/2017','1/5/2017','1/6/2017'],
    'temperature':[32,35,28,24,32,31],
    'windspeed':[6,7,2,7,4,2],
    'event':['rain','sunny','snow','rain','sunny','sunny']
}
df=pd.DataFrame(weather_data)

df

#datasets
 	day 	temperature 	windspeed 	event
0 	1/1/2017 	32 	6 	rain
1 	1/2/2017 	35 	7 	sunny
2 	1/3/2017 	28 	2 	snow
3 	1/4/2017 	24 	7 	rain
4 	1/5/2017 	32 	4 	sunny
5 	1/6/2017 	31 	2 	sunny

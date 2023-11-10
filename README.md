# python-api-challenge

In this Challenge I will investigate the following question: "What is the weather like as we approach the equator?"
I will answer the question in two parts & two Jupyter Notebooks: WeatherPy & VacationPy.

Part 1: WeatherPy

-In this deliverable, I will create a Python script to visualize the weather of over 500 cities of varying distances from the equator. I will use the citipy Python librarylinks to an external site., the OpenWeatherMap APILinks to an external site., and my problem-solving skills to create a representative model of weather across cities.

-Generating the Cities List:

<img width="1382" alt="Screenshot 2023-11-10 at 3 04 30 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/178b1af1-de3f-48de-9a10-f4457262efa5">

-Creating plots to showcase relationships between weather variables and latitude:

<img width="1379" alt="Screenshot 2023-11-10 at 3 19 31 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/fcf89298-463e-4a57-a774-35e6fb2cd8e8">

<img width="584" alt="Screenshot 2023-11-10 at 3 19 50 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/6365b054-d534-42bc-928a-643a03dc9d2f">

<img width="1368" alt="Screenshot 2023-11-10 at 3 20 19 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/c6aeae81-a0e6-4ff2-83d3-c207834f3b22">

<img width="595" alt="Screenshot 2023-11-10 at 3 20 39 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/9e317762-c23a-482f-93a2-e56e7cb8b045">

<img width="1380" alt="Screenshot 2023-11-10 at 3 21 00 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/55567df7-7838-45c3-ad77-3974775a778a">

<img width="597" alt="Screenshot 2023-11-10 at 3 21 16 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/154b5152-05d1-4e71-ac9e-f8b1dcc69c5f">

<img width="1372" alt="Screenshot 2023-11-10 at 3 21 38 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/ee5e75d0-13ad-4fd9-8202-f5b5fcf59e63">

<img width="597" alt="Screenshot 2023-11-10 at 3 21 55 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/01fd2425-ad7a-4bdb-9fbe-477361e7032e">

-Computing Linear Regression for Each Relationsip: 

<img width="1375" alt="Screenshot 2023-11-10 at 3 22 52 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/bd0644f8-aa8a-4457-8a23-1230d7785d7e">

<img width="619" alt="Screenshot 2023-11-10 at 3 23 05 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/4f925cab-e489-43de-b97f-024871848ad0">

<img width="1374" alt="Screenshot 2023-11-10 at 3 23 30 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/31d975ba-e8eb-4a17-8f83-20e73dacbb7b">

<img width="593" alt="Screenshot 2023-11-10 at 3 23 44 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/f90aaebf-c215-41e7-b158-e53d559ca2a9">

**Discussion about the linear relationship:** The farther we move from the equator (Lat=0), the lower the temperature. The closer we move to the equator (Lat=0), the higher the temperature. This reveals a linear relationship wherein the temperature proportionally increases along the y-axis as we approach (0) along the x-axis.

<img width="1373" alt="Screenshot 2023-11-10 at 3 24 29 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/08f777f6-6675-42b8-8203-2198ddad1fbc">

<img width="611" alt="Screenshot 2023-11-10 at 3 24 46 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/85b999f0-eead-4010-9889-2ad233c28697">

<img width="1367" alt="Screenshot 2023-11-10 at 3 25 03 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/423d0d95-96d0-4629-942c-d4eb86ae5edd">

<img width="610" alt="Screenshot 2023-11-10 at 3 25 17 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/1ddf821b-3e10-40c2-af88-99249a61850d">

**Discussion about the linear relationship:** The higher we are above the equator, the lower the humidity. The lower we move below the equator, the higher the humdity. However, due to the nearly horizontal 180 degree angle of the slope, neither relationship is particularly strong.  

<img width="1372" alt="Screenshot 2023-11-10 at 3 25 46 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/d519dec9-d0dc-4f03-9eb2-084093e27b18">

<img width="597" alt="Screenshot 2023-11-10 at 3 26 01 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/ca739e6e-feb8-4749-b840-547bee7d322e">

<img width="1377" alt="Screenshot 2023-11-10 at 3 26 20 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/bc881678-1155-41b6-906d-9fbcb5945412">

<img width="607" alt="Screenshot 2023-11-10 at 3 26 36 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/ff795020-1ce8-48c8-95c8-4df359520241">

**Discussion about the linear relationship:** Cloudiness increases as we move below the equator and decreases as we rise above it. 

<img width="1374" alt="Screenshot 2023-11-10 at 3 27 01 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/294e2d8e-250e-44b0-a2a9-6189d88b6a6c">

<img width="599" alt="Screenshot 2023-11-10 at 3 27 17 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/fe7af0bb-f697-468b-b056-6093b89710ff">

<img width="1362" alt="Screenshot 2023-11-10 at 3 27 39 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/3304da4f-25b9-4420-aba9-ae94cec8aee0">

<img width="596" alt="Screenshot 2023-11-10 at 3 27 56 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/f5157f9d-7edf-434c-8bcc-c465af812f44">

**Discussion about the linear relationship:** Wind speed increases proportionally to movement below the equator or in the negative direction along the x-axis and flattens as we ascend above the equator, or move in the positive direction along the x-axis.  

Part 2: VacationPy

In this deliverable, I will use my weather data skills to plan future vacations. Also, I will use Jupyter notebooks, the geoViews Python library, and the Geoapify API in order to gather the ideal conditions for vacation-planning.

- A map displaying a point for every city (size of the point per city corresponds to humidity in the city):
  
<img width="1077" alt="Screenshot 2023-11-10 at 2 37 47 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/1bf0ceba-2ef7-4228-adde-138caa80cf20">

- Narrowed down dataframe displaying ideal weather conditions:

<img width="1369" alt="Screenshot 2023-11-10 at 2 56 31 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/25f78e14-e777-4f2a-aadc-17aa59167940">

- Dataframe containing a list of hotels within 10,000 metres of each city coordinate:

<img width="818" alt="Screenshot 2023-11-10 at 2 59 37 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/3aef3094-953d-4191-9b59-47cb7966dac8">

- Map displaying hotel name and country for ideal vacation stays:  
  
<img width="1369" alt="Screenshot 2023-11-10 at 3 00 47 PM" src="https://github.com/anastasiaskr2000/python-api-challenge/assets/131491720/bf9dc723-e305-446d-ab8b-3c7e7575b015">


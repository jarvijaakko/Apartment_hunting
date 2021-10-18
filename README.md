# Apartment_hunting

This Jupyter Notebook was born out of awe about people who base their apartment buying decisions on endless clicking and, eventually, on a feeling. I decided to take a slightly different approach by creating a Python web scraping tool that goes through all one bedroom apartments in Helsinki in 30 seconds and show all essential information accordingly. 

I have used the wonderful Selenium library for scraping and Beautiful Soup for parsing data. Additional data manipulation is done by the essential Pandas and Numpy libraries. Part of the purpose of this exercise was to refamiliarize myself with Matplotlib plotting after spending some time with Plotly.

This is how the data looked straight from Oikotie.

![Jee_01](https://user-images.githubusercontent.com/69734538/137811529-dc181e52-765a-4a92-b16e-dbb053a7f06b.png)

In here, I've plotted the average sqm prices for each district with eight major districts color coded in bars.

![Jee_02](https://user-images.githubusercontent.com/69734538/137811589-7f9315e8-8be0-40dc-a392-b1fea5ce2ca9.png)

The amount of apartment postings per district are shown here.

![Jee_03](https://user-images.githubusercontent.com/69734538/137811596-a3f25232-58c2-4451-8c09-6cf3cd9def7f.png)

This graph shows the average sqm prices with average sqm prices calculated from realized sales prices in red.

![Jee_04](https://user-images.githubusercontent.com/69734538/137811616-809b4804-dd54-42e0-a36c-983ae232b109.png)

Here, I've plotted the sqm price distribution of the apartment postings for the Kallio region.

![Jee_05](https://user-images.githubusercontent.com/69734538/137811627-128338ca-950b-4d8c-a2f2-9548d4d8e7cd.png)

This graph shows the sqm prices of all apartment listings in Kallio by address.

![Jee_06](https://user-images.githubusercontent.com/69734538/137811637-7adfe4a6-edce-4c3a-8aaa-371fc9456f8d.png)

# D3_final

map_test.html for choropleth(number of top 1000 universities) and scatter plot (location of top 100 universities) - year 2015

    -files used: world-110m.geojson - geojson for world map

             world_final.csv - location of top 100 universities in 2015

             top_1000_summary.csv - number of top 1000 universities for all countries in 2015

bar_test.html for a interactive bar plot demo (title and bar transition + color change and data text on mouseover)
  
    -files used: city_full_data.csv - includes the number of kindergardens and hospitals for each city in Taiwan


Notes

1. File structure is ugly as **** because I somehow couldn't get relative file paths to work for d3.csv...

2. Redundant code?  

-----------------------------------------------------------------------------------------------------------------------

基本上地圖是 map_test.html，包括全球各國家擁有前1000名大學數量的分層圖和前百大的分布圖

需要用到 world-110m.geojson (世界地圖的geojson)

world_final.csv (前百大的經緯度)

top_1000_summary.csv - 各國擁有前1000名內大學個數

另外上次玩得那個台灣醫院和幼稚園的長條圖也在裡面，要做統計圖表的人可以參考看看(包括標題、長條圖長度、顏色、標籤...等變化)

需要用到 city_full_data.csv (包括台灣各縣市醫院及幼稚園數量)

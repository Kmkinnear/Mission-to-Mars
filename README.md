# Mission-to-Mars

1.  How many months exist on Mars? 
  
    I decided to count how many unique numbers were in the month column and came up with 12 which leads me to believe there are 12 months.

<img width="483" alt="image" src="https://user-images.githubusercontent.com/110848660/203838136-24815a61-593b-4dc3-b2f6-ed388bba126c.png">

2.  How many Martian (and not Earth) days worth of data exist in the scraped dataset? 
  
    I used the same approach as question 1 and decided to count how many sols (Martian Days) worth of data that existed

<img width="638" alt="image" src="https://user-images.githubusercontent.com/110848660/203839877-0b2b530d-f8db-40e1-bbba-c2a6d50c8749.png">

3.  What are the coldest and the warmest months on Mars (at the location of Curiosity)? Get the answer by averaging the minimum daily temperature of all the months. Plot the results as a bar chart. 
  
    First I decided to group the data together by "Month" to get the average minimum daily temperature by month. Then I plotted the results in a bar chart. By           looking at the data we can see that Month 3 is the coldest (-83.307292) and Month 8 is the warmest (-68.382979)

<img width="799" alt="image" src="https://user-images.githubusercontent.com/110848660/203840043-16c60a84-51a4-4211-85cf-61e2adbdef80.png">

<img width="560" alt="image" src="https://user-images.githubusercontent.com/110848660/203840258-188f5918-fc91-44fa-a61c-065b39251a0b.png">

4.  Which months have the lowest and the highest atmospheric pressure on Mars? Get the answer by averaging the daily atmospheric pressure of all the months. Plot       the results as a bar chart. 
 
    I decided to use the same approach as question 3 and grouped the data together by "Month". Then I focused on the daily atmospheric pressure column and got the       averages. Then we displayed the data as a bar chart. From the data we can see that Month 6 has the lowest (745.054422) pressure and Month 9 has the highest         (913.305970) pressure

<img width="764" alt="image" src="https://user-images.githubusercontent.com/110848660/203840540-991f7b06-98a8-4f0b-b87d-99ebc64a1e60.png">

<img width="561" alt="image" src="https://user-images.githubusercontent.com/110848660/203840967-69180ea5-988a-4868-9da4-e84cb8307831.png">

5.  About how many terrestrial (Earth) days exist in a Martian year? That is, in the time that Mars circles the Sun once, how many days elapse on Earth? Visually estimate the result by plotting the daily minimum temperature. 
 
   I decided to use a line chart for the last question where we were looking to come up with how many Earth days exist in a Martian year. I figured that we could      come up with how long a Martian year was by watching the temperature reach the lowest temperate and then reach the highest temperature. You could pick a point on    the line chart and find the time range after a minimum a max temperature had been reached and use that to try and measure the number of Terrestrial Days that had    passed. In our chart we can see that our tick marks are about every 10 months. We can assume there are around 30 days in a month. In our chart we can see from      Point 1 to Point 2 is about 2.3 ticks. To find the number of days we can take 10 (months per tick) * 2.3 (ticks of data between our starting temp, the high temp,    the low temp, and return back to our starting temp) * 30 (Earth days in a month) = 690 terrestrial days in 1 Martian year.

<img width="813" alt="image" src="https://user-images.githubusercontent.com/110848660/203841212-f20318c6-4a25-4b41-9444-095f706e4b31.png">

<img width="734" alt="image" src="https://user-images.githubusercontent.com/110848660/203841853-b324f579-7664-4383-82ec-9ec7c5ba9e42.png">

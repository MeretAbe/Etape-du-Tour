
<h1>Etape-du-Tour</h1>


<h2>Scenario</h2>
My friend Steven is a bicycle enthusiast. He is planning a trip to France to compete in Etape-du-Tour in July of this year. Etape-du-Tour allows amateur cyclists to experience riding a stage of the Tour de France route under similar conditions to professional cyclists.It takes place on a mountainous stage of the Tour de France route each year. I thought it would be a great opportunity for me to use Jupyter Notebook to practice writing Python code. I want to create scripts to assist him in preparing for and during his trip. 
<br />

<h2>Languages and Utilities Used</h2>

- <b>Python</b>(Jupyter Notebook)

<h2>Task 1</h2>
  
I developed Python program that shows the current time in France so he get used to the local time in France, prior to his travel. Note EST is 6 hours behind France.</h4>
<p align="center">
<img src="https://i.imgur.com/imHrL0u.png" height="70%" width="70%"/>

<h2>Task 2</h2>
Steven to carry 500 Euros, which he wants to get from currency exchange kiosks at the airport. There is a 1.75% service charge for the currency exchange. He wants to know how many dollars he will need to spend to get 500 Euros, including the 1.75% service charge. Note:assume 1.1 Dollar = 1 Euro.

<p align="center">
<img src="https://i.imgur.com/eP4wPzL.png" height="70%" width="70%"/>

The script calculates the total amount of US dollars based on an initial amount of euros, taking into account both the currency conversion rate and associated fee for the exchange service.

<h2>Task 3</h2>
Steven figures out that he will be spending approximately 20% more money in France in a month than what he spends in NYC. He roughly spends $4,000 per month (30 days) in NYC.E xcluding his air travel expenses he wants to know how much he would need for his 45-days trip to France. 

<p align="center">
<img src="https://i.imgur.com/MUc4kNN.png" height="80%" width="80%"/>

Here are the steps I took to solve this: The $4000, representing the initial spending amount in NYC. 30 days, representing his the duration of a month. Percentage increase in spending during the trip to France is 0.20. 45, representing the duration of the trip to France in days. The service fee percentage applied to the total spending in France is 0.0175. 

I calculate Steven's estimated monthly spending in France, factoring in the 20 percent increase compared to spending in France which comes to $4,800. Then calculate the total spending for the trip to France, taking into account the adjusted spending in NYC, the service fee, and the duration of the trip.

<h2>Task 4</h2>
The ace involves covering 3,328 kilometer approximately. Steven is curious to know how many laps he will have to complete in the bicycle training facility if one lap in the practice track is 1.2 miles long. Note:One lap indicates the complete path, starting from the origin and back to the same point.

<p align="center">
<img src="https://i.imgur.com/E5YAx7R.png" height="70%" width="70%"/>

Frist step,  calcuate the total distance of the race in miles by multiplying the total distance in kilometers by the conversion factor. Then find the total number of laps required to complete the bicycle training session by dividing the total distance of the race in miles by the distance of one lap in miles, rounds up to the nearest integer( using floor division and add 1 to ensure that even if there's a fractional lap, it rounds up to the next whole lap).

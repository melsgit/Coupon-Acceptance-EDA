# Coupon-Acceptance-EDA
Exploratory data analysis of likelihood of drivers accepting different types of coupons
* Restaurant(<$20)
* Coffee House
* Carry out & Take away
* Bar
* Restaurant($20-$50)

## Will a customer accept the coupon?
### Bar Coupon

1. The driver who goes to bar regularly is the strongest driver for raising the bar coupon acceptance rate.
```
  Acceptance rate (bar 3 or fewer times): 37.27%
   Acceptance rate (bar 4 or more times): 76.17%
```
2. Driver over 21 who goes to the bar have higher acceptance rate.
```
   Over 25 and Bar > 1: 68.98%
  Under 25 and Bar > 1: 67.46%
  Under 21 and Bar > 1: 40.00%
```
3. Having an adult passenger increases coupon acceptance rate by ~10%
```
        Adult Passanger: 48.62%
    W/O Adult Passanger: 37.98%
```
4. Job types doesn't seem to make much difference
```
  Not Farming, Fishing, Forestry: 41.18%
      Farming, Fishing, Forestry: 44.44%
```
### Coffee Coupon
* Having adult passengers in the car was most impactful in raising the acceptance rate. Three attributes (Sunny & Rainy + Adult Passenger + Time) show possitive impact on the coupon acceptance rate. However, surprisingly combining them didn't result in better acceptance rate than using just one atribute (adult passenger). I recommend the 
```
 Adult Passenger: 59.14%
 Sunny & Rainy + Adult Passenger + Time: 59.29%

   Morning: 53.64%        Sunny: 50.09%                Alone: 43.39%
       2PM: 54.55%        Rainy: 51.63%            Not Alone: 57.75%
 Afternoon: 46.84%        Snowy: 42.81%            With Kids: 47.15%
      10PM: 42.91%                           Adult Passenger: 59.14%
```
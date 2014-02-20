Vacation_Calculator
===================

def hotel_cost(nights):
  hotel_cost = (nights * 140)
  return hotel_cost

def plane_ride_cost(city):
  if city == "Charlotte":
    return 183
  elif city == "Tampa":
    return 220
  elif city == "Pittsburgh":
    return 222
  elif city == "Los Angeles":
    return 475
  return city

def rental_car_cost(days):
  rental_car = days * 40
  if (days >= 7):
    return (rental_car - 50)
  elif (days >= 3):
    return (rental_car - 20)
  else:
    return rental_car

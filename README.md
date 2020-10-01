num = int(input('Enter the number of work trips: '))
print('Start entering the cities: ')

places = []
count = 0
total = 0
city = input()

while num < total:
    for j in range(len(places)):
        city = input()
        places.append(city)
        total += 1
        if city != places[j]:
            count += 1
        else:
            count -= 1
  
            
print(len(places))

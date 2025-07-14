# learning-Python
I'm learning Python and here I will show some of the codes :)
#the mission is to creat a program which is repeatedly read numbers until the user enter "done". once "done" is entered, the program should print the largest and smallest numbers entered "done" is entered, print out the total, count and everage of the numbers entered. of the numbers. if users enter anything other than number detect their mistake. 
print ("hi world, Happy to start my first mission")
print ("first please answer the questions so I can find you total, count and average numbers")
x = 1
y = 1
count = 0
total = 0
Average = 0.0
for x in range(1000):
 y = str(y)
 number = input("Enter number " + y + " : ")
 try: 
      number = float(number)
      count = count + 1
      y = int(y)
      y = y + 1
      total = total + number
      Average = total / count
 except:
    if number == "done":
     print ("Total: ", total)
     print ("Count: ", count)
     print ("Average: ", Average)
     break    
    print ("bad data")    
    continue

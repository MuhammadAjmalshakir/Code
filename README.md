import time

a = input("Enter Your Name:  ")
timestamp = time.strftime('%H:%M:%S')
print(timestamp)
h = int(time.strftime("%H"))
if (h < 1 and h <= 12):
  print("Good Morning", a)
  print("I know you have no time")
  print("Goodby")
elif (h > 12 and h < 24):
  print("Good Afternoon sir", a)
  print("I know you have no time")
  print("Goodby")
else:
  print("Good Evening sir", a)
  print("I know you have no time")
  print("Goodby")

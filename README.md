# 24-hour-to-12-hour-time-format-convertor
This code converts 24 hour time format into 12 hour time format

#24 hour time looks like : 1300/ 13:00, 2244/ 22:44
#NOTE : Enter value in both units & tens while entering hour values

X=int(input("Enter Hour: "))
#Took input in 24 hour format

Y=int(input("Enter minutes: "))
#Noted minutes

if X < 12:
    print("The time in 12 hour format is {}:{} AM".format(X,Y))
elif X == 12:
    print ("The time in 12 hour format is {}:{} PM". format(X,Y))

if X > 12:
    Z = X-12
    print("The time in 12 hour format is {}:{} PM".format(Z,Y))



# Haripriya-Python-Project1
age = int(input("How old are you? "))
time_unit = str(input("Select Time Unit [M,W,D,H,min,sec]: "))

if (time_unit=='M') :
  print (f" The Person lived for {age*12} Months")
elif (time_unit=='W') :
  print (f" The Person lived for {age*52} Weeks")
elif (time_unit=='D') :
  print (f" The Person lived for {age*365} Days")
elif (time_unit=='H') :
  print (f" The Person lived for {age*(24*365)} Hours")
elif (time_unit=='min') :
  print (f" The Person lived for {age*60*24*365} Minutes")
elif (time_unit=='sec') :
  print (f" The Person lived for {age*60*60*24*365} Seconds")
else :
  print("Incorrect input values, Please type options given from the list")
hii thwere

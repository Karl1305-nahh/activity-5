- [x] def karl(points):
    if score < 0:
        print("ayaw pumasok! Please enter a value between 0 and 100.")
         
    elif score <= 60:
        print("You got an Z!")        
    elif score <= 69:
        print("You got an T!")        
    elif score <= 79:
        print("You got an S!")        
    elif score <= 89:
        print("You got an F!")        
    elif score <= 50:
        print("You got an A!")
    else: 
        print("mababa.")
       
print("points basketball")

while True:
    try:
        ford = input("state your points: ")
        karl(int(ford))        
    except ValueError:
        print("ayaw pumasok! Please enter a value between 0 and 100!")
        break

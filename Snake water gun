print("welcome to your game snake, water, gun\n")
print("you have 10 rounds to play..\nThe most round winner will win the game\n")
a=input("Enter your name  ")
print("Hi",a)
you=0
AI=0

chance=1

while(True):
 
  import random
  lst=["s","w","g"]
  a = random.choice(lst)
  
  print("\nround=",chance)
  chance=chance+1
  
  choice=input("Choose your choice:\ns for snake\nw for water\ng for gun\n")
  if choice in ('s','w','g'):
    
  
    if choice=='s' and a=='w':
      print("you got 1 pt\n")
      you=you+1
      
      print("you=",you,"AI=",AI,end="")
      
    
    elif choice=='w' and a=='s':
      print("AI got 1 pt\n")  
      AI=AI+1
      
      print("you=",you,"AI=",AI,end="")
      
    elif choice=='s' and a=='g':
      print("AI got 1 pt\n")
      AI=AI+1
      
      print("you=",you,"AI=",AI,end="")
      
    elif choice=='g' and a=='s':
      print("you got 1 pt\n")
      you=you+1
     
      print("you=",you,"AI=",AI,end="")
      
    elif choice=='w' and a=='g':
      print("you got 1 pt\n")
      you=you+1
      
      print("you=",you,"AI=",AI,end="")
    
    elif choice=='g' and a=='w':
      print("AI got 1 pt\n")
      AI=AI+1
      
      print("you=",you,"AI=",AI,end="")
        
    else :
      print("draw\nyou=",you,"AI=",AI)
        
  if chance==11:
    
     if you>AI:
       
        print("\nyou wins")   
        break
     else:
        
        print("\nAI wins") 
        break   
     


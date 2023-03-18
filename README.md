# Snake-Water-Gun-Game-
Play Snake Water Gun Game













































import random

user_name=input("Enter the your name please")
print(f"welcome _/\_ {user_name} Snake Water Gun Game Created By ALOS")
print('-'*10,"To choose snake Type '1'",'-'*10)
print('-'*10,"To choose water Type '2'",'-'*10)
print('-'*10,"To choose gun Type '3'",'-'*10)
print('-'*60)
print('*'*10,"Type '999' for quit the game ",'*'*10)
print('-'*60)
while True:
    try:
        
        com=random.randint(1,3)
        user_choice=int(input("Enter the your Option :"))
        if user_choice==999:
            break
        if user_choice<0 or user_choice>=4:
            print("Please type '1' for snake\n\t'2' for Water \n\t '3' for Gun" )
        
        elif user_choice==1 and com==1:
            print(f"{user_name} the game is tie")
            
        elif user_choice==1 and com==2:
            print(f"{user_name} Wow! You won the game")
            
        elif user_choice==1 and com==3:
            print(f"{user_name} Opps! you lose the game")
            
        elif user_choice==2 and com==1:
            print(f"{user_name} Opps! you lose the game ")
            
        elif user_choice==2 and  com==2:
            print(f"{user_name} The game is tie")
            
        elif user_choice==2 and com==3:
            print(f"{user_name} Wow! You won the game")
            
        elif user_choice==3 and com==1:
            print(f"{user_name} Wow! You won the game")
            
        elif  user_choice==3 and com==2:
            print(f"{user_name} Opps! you lose the game")
            
        elif user_choice==3 and com==3:
            print(f"{user_name} The game is tie")
            
    except Exception as e:
        print("You entered wrong type of Entry Please type '1' for snake\n\t'2' for water\n\t '3' for gun")

       

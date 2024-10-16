import random

print("Welcome to the Dice_roll game!")
def diceroll():
   roll=random.randint(1,6)
   return roll

 
def evaluate():
  for player_idx in range(players):
      print("\nPlayer number",player_idx+1,"turn started.")
      print("Your total score is:",player_scores[player_idx],"\n")
      maxi=int(input("Enter the number of times you want to play"))
      current_score=0
      i=0
      while i<maxi:
               
               
            
            
                  
                     
               ty=input("Enter r to roll or q to quit-")
               if ty.lower()== "q":
                  break
            
               value=diceroll()
               if value==1:
                   print("You got 1,your score turns to 0!")
                   current_score=0
                   break 
               else:
                  current_score+=value
                  print("You rolled a :",value)
               i+=1  

               print("Your score is:",current_score)
      player_scores[player_idx]+=current_score
      print("Your total score is:",player_scores[player_idx])
    
           
               

while True:
  
  players=input("Enter the number of players(1-4):")
  if players.isdigit():

    players=int(players)
    if 2<=players <=4:
       break
    else:
    
      print("Must be between 2-4 players.")
       
  else:
    print("Invalid,try again")


player_scores=[0 for _ in range(players)]

evaluate()

            
maxscore=max(player_scores)
win_idx=player_scores.index(maxscore)
print("\nPlayer number", win_idx+1, "is the winner with a score of:",maxscore)  





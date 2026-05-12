# Portfolio-1
#GAME POINT and RANK CALCULATOR (FOR D&D SESSIONS)

#(I made this program to compute our points and what rank we are, when we play our D&D sessions.) 
#(D&D - also know as "Dungeons and Dragons" it is a tabletop roleplaying game where players go on a fansty adventure,
# navigating monsters and magic through storytelling and dice rolls.)
#(We mostly do our session online via Discord Call, so calculating our points and what rank we are, gets complicated,
# that's why a I created this program to make our experience smoother.)


#(The name of the guild and the operator will differ depending on the Game Master.(I am the game master in this case.))

```python
print("\n===== CYNIX'S ADVENTURERS GUILD ======")
```
#Cynix is the name of the Guild and the operator aswell

print("Cynix: Ad astra abyssosque! Welcome to the Adventurers Guild.")

```python
player_name = (input('Enter Player Name'))
dungeon_name = (input('Enter Dungeon Name'))
difficulty_of_dungeon = (input('Enter Dungeon Difficulty')) 
```
#(The Game Master will tell what the name of the Dungeon, and how Difficult is it,the difficulty system will all depende on the Game Master.)

```python
Mission_Points = int(input('Enter Mission Points'))
Bonus_Points = int(input('Enter Bonus Points'))
Penalty_Points = int(input('Enter Penalty Points'))

total_points = Mission_Points + Bonus_Points - Penalty_Points
```

#(Penalty are admistered by the Game Master, as well as the other point systems.)

```python
print("Cynix: Thank you for completing todays commission. Here are your results.")

print("\n===== PLAYER RESULT ======")
print("Player/s Name:", player_name)
print("Dungeon Name:", dungeon_name)
print("Dungeon Difficulty:", difficulty_of_dungeon)
print("Total Points:", total_points)
```

#(The rank and pointing sytem will differ depending on the Game Master, rigth now since this is my Domain,
# the rank is all related to Mages since my Domain is all about Mages, since i like magic and other 
# magical things and being.)

```python
if total_points >= 1000:
    print("Rank:Legendary Grand Magister")
    
elif total_points > 850:
    print("Rank:Grand Mage")

elif total_points > 700:
    print("Rank:High Mage")

elif total_points > 500:
    print("Rank:Arch Mage")
    
elif total_points > 350:
    print("Rank:Master")

elif total_points > 200:
    print("Rank:Adept")

elif total_points > 100:
    print("Rank:Disciple")

elif total_points >= 50:
    print("Rank:Initiate")

else:
    print("Rank:Apprentiece")
 ```
   
#(The points and the rank you gain from previous game session will stack, so if you were an apprentice last session
# and you gain points that will rank you up and possibly make it to Disciple.)

# ROCK , PAPER & SCISSOR
# user Input
print("Lets play Rock,Paper & Scissor")
player1 = str(input("Choose Between r/p/s [Rock,Paper & Scissor]\n"))
player2 = str(input("Choose Between r/p/s[Rock, Paper & Scissor]\n"))

#Logic using conditional checks for Rock
if (player1=="r") and (player2=="r"):
    print("Player1 choose {option} and Player2 choose {option2}".format(option=player1,option2=player2))
    print("That's a  tie")
elif (player1=="r") and (player2=="p"):
    print("Player1 choose {option} and Player2 choose {option2}".format(option=player1,option2=player2))
    print("Player2 has won the Game")
elif (player1=="r") and (player2=="s"):
    print("Player1 choose {option} and Player2 choose {option2}".format(option=player1,option2=player2))
    print("Player1 has won the Game")
 
 ##Logic using conditional checks for Paper
if (player1=="p") and (player2=="r"):
    print("Player1 choose {option} and Player2 choose {option2}".format(option=player1,option2=player2))
    print("player1 has won the Game")
elif(player1=="p") and (player2=="p"):
    print("Player1 choose {option} and Player2 choose {option2}".format(option=player1,option2=player2))
    print("That's a Tie")
elif(player1=="p") and (player2=="s"):
    print("Player1 choose {option} and Player2 choose {option2}".format(option=player1,option2=player2))
    print("Player2 has won the Game")
    
#logic using conditional checks for Scissor
if (player1=="s") and (player2=="r"):
    print("Player1 choose {option} and Player2 choose {option2} \n".format(option=player1,option2=player2))
    print("Player2 has won the Game")
elif(player1=="s") and (player2=="p"):
    print("Player1 choose {option} and Player2 choose {option2}".format(option=player1,option2=player2))
    print("Player1 has won the Game")
elif(player1=="s") and (player2=="s"):
    print("Player1 choose {option} and Player2 choose {option2}".format(option=player1,option2=player2))
    print("That's tie")

else:
    print("Error: you have choose the wrong ")

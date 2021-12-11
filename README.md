- print("Welcome to the quiz game")
print("Are you ready?")
print("Yes or no")
score1 = 0
score2 = 0
yesorno1 = input("pla1:")
yesorno2 = input("pla2:")
if yesorno1 == "yes" and yesorno2 == "yes":
    print("If you got it correctly then you have one point")
    # question 1
    print("First what is the best programming language in the world?")
    Ans1 = input("pla1:")
    Ans1 = Ans1.lower()
    if Ans1 == "python":
        score1 = score1 + 1
        print("your answer is correct and your score =", score1)
    else:
        score1 = score1
        print("Wrong, your score =", score1)
        # question 2
    print("Next what is the capital of Italy?")
    Ans2 = input("pla2:")
    Ans2 = Ans2.lower()
    if Ans2 == "roma":
        score2 = score2 + 1
        print("your answer is correct and your score =", score2)
    else:
        score2 = score2
        print("Wrong, your score =", score2)
        # question 3
    print("Next what is the best game in epic games?")
    Ans3 = input("pla1:")
    Ans3 = Ans3.lower()
    if Ans3 == "fortnite":
        score1 = score1 + 1
        print("your answer is correct and your score =", score1)
    else:
        score1 = score1
        print("Wrong, your score =", score1)
        # question 4
    print("Next what is the best football game in the world?")
    Ans4 = input("pla2:")
    Ans4 = Ans4.casefold()
    if Ans4 == "fifa2022":
        score2 = score2 + 1
        print("your answer is correct and your score =", score2)
    else:
        score2 = score2
        print("Wrong, your score =", score2)
    # question 5
    print("Next, who is the best football player in the world?")
    Ans5 = input("pla1:")
    Ans5 = Ans5.casefold()
    if Ans5 == "messi":
        score1 = score1 + 1
        print("your answer is correct and your score =", score1)
    else:
        score1 = score1
        print("Wrong, your score =", score1)

# question 6
    print("Next which company made fifa?")
    Ans6 = input("pla2:")
    Ans6 = Ans6.casefold()
    if Ans6 == "ea sports":
        score2 = score2 + 1
        print("your answer is correct and your score =", score2)
    else:
        score2 = score2
        print("Wrong, your score =", score2)
# question 7
    print("Next who made facebook?")
    Ans7 = input("pla1:")
    Ans7 = Ans7.casefold()
    if Ans7 == "mark zuckerberg":
        score1 = score1 + 1
        print("your answer is correct and your score =", score1)
    else:
        score1 = score1
        print("Wrong, your score =", score1)
# question 8
    print("Next with which contact has pygame?")
    Ans8 = input("pla2:")
    Ans8 = Ans8.casefold()
    if Ans8 == "python":
        score2 = score2 + 1
        print("your answer is correct and your score =", score2)
    else:
        score2 = score2
        print("Wrong, your score =", score2)
# question 9
    print("Next for what is github?")
    Ans9 = input("pla1:")
    Ans9 = Ans9.casefold()
    if Ans9 == "programming":
        score1 = score1 + 1
        print("your answer is correct and your score =", score1)
    else:
        score1 = score1
        print("Wrong, your score =", score1)
# question 10
    print("Next What does the word 'continue' do in the middle of a loop?")
    Ans10 = input("pla2:")
    Ans10 = Ans10.casefold()
    if Ans10 == "reloop":
        score2 = score2 + 1
        print("your answer is correct and your score =", score2)
    else:
        score2 = score2
        print("Wrong, your score =", score2)
    if score1 > score2 and score1 > 1:
        print("Congratulations player1, you win", score1, "/5")
    elif score2 > score1 and score2 > 1:
        print("Congratulations player2, you win", score2, "/5")
    elif score1 == score2 and score1 > 1:
        print("Congratulations player1 and player2, you both win and scored the same", score1, "/5")
    else:
        print("BOTH losers, scored , player1", score1, "player2", score2)
else:
    print("You did not accept the game, Go Home")

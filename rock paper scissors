import random
l=["Rock","Paper","Scissors"]
play=1

while play==1:
    computer=random.choice(l).lower()
    user=input("Enter your choice (Rock, Paper, Scissors):").lower()
    print("Your Choice:",user)
    print("Computer's Choice:",computer)
    if user==computer:
        print("Tie")
    elif user=="rock":
        if computer=="paper":
            print("Computer Wins!")
        elif computer=="scissors":
            print("You Win!")
    elif user=="paper":
        if computer=="rock":
            print("You Win!")
        elif computer=="scissors":
            print("Computer Wins!")
    elif user=="scissors":
        if computer=="rock":
            print("Computer Wins!")
        elif computer=="paper":
            print("You Win!")
        
    play=int(input("Want to play Again? \nEnter 1 to play , 0 to Exit "))
   

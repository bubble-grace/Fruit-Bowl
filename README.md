# Fruit-Bowl
#Amy's project about a fruit bowl

def double_loop_print(L):
    for i in range(0, len(L)):
        output = "{} : {}".format(L[i][0], L[i][1])
        print(output)

def main():
    my_L = [
        ["Bananas", 6],
        ["Oranges", 2],
        ["Apples", 1],
        ["Kiwifruit", 4],
        ["Pears", 3]
    ]
    double_loop_print(my_L)



def indefinite_loop():
    run = True
    while run == True:
        user_choice = input ("Press 'q' to stop the loop and 'r' to review the fruits")
        if user_choice == "q":
            print("Loop has stopped, Thank you")
            run = False
        elif user_choice == "r":
            main()
        else:
            print ("sorry your answer was not valid")



# useless_code

when you try to overload python program with functions: 
overloading: naming many programs with the same name but setting them to do different work, to put it simply.

you can't do it directly in python. 
first, I'm kinda stuck what u tryna do here. 
*So* : 
first: (assuming that you want to user to choose between functions)
   *you're program is simple and differs only on the operation being performed at it. so I'm gonna create a simple operator selection first*


def do_something(x,y):    
    input_1 = input(f'enter the operator: ')
    if input_1 == '*':
        final = num_1*num_2
    elif input_1 == '/':
        final = num_1/num_2
    elif input_1 == '+':
        final = num_1+num_2
    elif input_1 == '-':
        final = num_1-num_2
    else:
        print(f'you put in an invalid operator')
    print(final)

num_1 = float(input('enter the number 1 '))
num_2 = float(input('enter the number 2 '))
do_something(num_1,num_2)

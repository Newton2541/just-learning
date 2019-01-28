print('This is a Toll Gate Program')
money_entered = input('Please enter your money: ')
money_entered = int(money_entered)
while money_entered < 0:
    print('Sorry, the amount you entered is an incorrect format. Please enter amount in a correct format')
    print('')
    money_entered = input('Please enter your money: ')
print('The total money entered so far is ', money_entered)
print('')
while money_entered < 200:
    more_money = input('Please enter more money: ')
    more_money = int(more_money)
    while more_money < 0:
        print('Sorry, the amount you entered is an incorrect format. Please enter amount in a correct format')
        print('')
        more_money = input('Please enter more money: ')
        more_money = int(more_money)
    money_entered = more_money + money_entered
    print('The total money entered so far is ', money_entered)
    print('')   

print('Here is your ticket  **********')  
change = money_entered - 200
print('Your change is ', change)

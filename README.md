# CIS129_darlington_lab5
total_payout = total_bottles * 0.1 #Pays out a dime for each bottle
print()
print(f'The total number of bottles collected is {total_bottles}')
print(f'The total paid out is $ {total_payout:.1f}')
print()
print("Do you want to enter another week’s worth of data?")
if input('(Enter y or n): ') == 'n':
    keep_going = 'n' #Ends the program
else:
    #Preps for next week by resetting variables
    counter = 1
    today_bottles = 0
    total_payout = 0
    total_bottles = 0
    print()

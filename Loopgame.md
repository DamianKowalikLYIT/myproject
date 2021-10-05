"""
#
# File  : GameQ1.py
# Created : 27/09/2021 22:56
# Author   : D.Kowalik
# Version   :1.0.0
# Description :
# ----Don't give up----
"""


lucky_number = 7
for i in range(5):
     input_number = int(input(f'Welcome in my Lucky Number Game,\n'
                              f'Please, insert your lucky number between 1 and 10: '))
     if input_number > 10:
         print('you are breaking the rules! You will get a '
               'chance to insert it again')
     else:
         if input_number == lucky_number:
             print('Good job! You are the winner!')
             break
         else:
             print(' Looser \n Try again ')
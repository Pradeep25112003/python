# python

p1
import random
def getname(num):
       if num==1:
           return 'Rock'
       elif num==2:
           return 'Paper'
       else:
            return 'Scissor'

while True:
      print('Enter the choice \n 1.Rock 2.Paper 3.Scissor\n')
      choice = (int)(input())
      if choice>3 or choice<1:
           print('Invalid choice')
      
      print('user choice is:',getname(choice))
      cc=random.randint(1,3)
      print('computer choice is:',getname(cc))
      
      
      if (choice==cc):
         print('tie')
      
      elif(choice==1 and cc==2) or (choice==2 and cc==3) or (choice==3 and 
      cc==1):
          print('user wins')
      
      else:
          print('Comp wins') 

print('Do u want to continue')
a=input('Y/N')
if a=='N' or a=='n':
    'break'

p2
a





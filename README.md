print ('🎲  Welcome to the number guessing game ! 🎲 ')

# the number is = 5
import random

n = random.randint(1,10) # 5
attempt = 0

while True : 
    m = input('Guess a number betwen 1 and 10 : ')
    m = int(m)
    attempt+=1
    if m == n :
         print('correct you guessed the number in' , (attempt) , 'tries ! ✔️')
         break
         
    elif m > n :
        print('➡️ too high ! try again ')
    
    else :
        print('➡️ too low ! try again ')
        

import time
rudra = 140
nitya = 60
score = 100
print("ANSWER EVERY QUESTION WITH THE MULTIPLE CHOICE LETTER")
#QUESTION 1
print("---------------------------------------------------------")
print("Where is your phone?")
print("---------------------------------------------------------")
print("a) Dont got it, dad took it for watching youtube shorts all night")
print("b) Right here wdym?")
print("---------------------------------------------------------")
question1 = input()

if str.lower(question1) == 'a':
    score - 5
elif str.lower(question1) == 'b':
    score + 5

#QUESTION 2

print("---------------------------------------------------------")
print("What phone do you have?")
print("---------------------------------------------------------")
print("a) Android, it is much batter")    
print("b) Apple, it is the best and only choice")
print("---------------------------------------------------------")
question2 = input()

if str.lower(question2) == 'a':
    score - 5
elif str.lower(question2) == 'b':
    score + 5

#QUESTION 3

print("---------------------------------------------------------")
print("Is Nitya sus?")
print("---------------------------------------------------------")
print("a) No he is least sus in gc")
print("b) YES 100%")
question3 = input()
if question3 == 'a':
    score - 5
elif question3 == 'b':
    score + 5

#QUESTION4
print("---------------------------------------------------------")
print("Who is better Man UTD or PSG?")
print("---------------------------------------------------------")
print("a) Man UTD")
print("b) PSG")
print("---------------------------------------------------------")
question4 = input()
if str.lower(question4) == 'a':
    score + 15 
elif str.lower(question4) == 'b':
    score - 15


girlfriend = "aa"
if score > 100:
    girlfriend = "Anjani"
elif score < 100:
    girlfriend = "Tulsi"
else:
    girlfriend = "Anjani AND Tulsi"



print("Quiz done!")
input()
print("Your ideal girlfriend is:")
time.sleep(3)
print(".")
time.sleep(2)
print(".")
time.sleep(1)
print(".")
time.sleep(5)
print(girlfriend)

# Aprendizagem-PT
print("Welcome to my quiz!")

playing = input("Do you want to play? ")

if playing.lower() != "yes":
    quit()

print("Okay! Let's play!")
score = 0

answer = input("What is my favorite color? ")
if answer.lower() == "purple":
    print('Correct!')
    score += 1
else:
  print("Incorrect!")

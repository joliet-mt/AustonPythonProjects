questions = ("What is your name?","What is your favorite color?","What is your quest?","What is the average airspeed velocity of an unladen swallow?")

options = (("A. Yes","B. No","C. Unsure","D. What is a name?"),("A. Blue","B. Red","C. Green","D. Yellow"),("A. Cup","B. Grail","C. Chalice","D. Vessel"),("A.  ...Huh?","B. Approximately 21mph","C. Is it an African Swallow or a European Swallow?","D. You can't answer a question with a question."))

answers = ("A","A","B","C")
guesses = []
score = 0
question_num = 0

for question in questions:
  print("------------------------")
  print(question)
  for option in options[question_num]:
    print(option)
  guess = input("Enter A, B, C, or D:").upper()
  guesses.append(guess)
  if guess == answers[question_num]:
    score += 1
    print("Point awarded")
  else:
    print("You might be right, but I don't feel like giving you a point")
  question_num += 1
print("------------------------")
print(f"Congratulations, you scored {score} point(s)")

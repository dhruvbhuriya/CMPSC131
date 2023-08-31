## Chapter 3- If Else If statements

 * if-else statement-

```
if 2 < 4:
  print("2 is less than 4")
else
  print("2 is more than 4")
```

sample code-

```
number = int(input("Please enter a number: "))
if number < 100
  print("The number you entered is less than 100")
else
  print("The number you entered is more than or equal to 100")
```


### Comparing Strings

```
>>> "Mary" > "Mark"
True
>>> "apple" < "you"
True
>>> "hello" > "hell"
True
```

 * if-else-if statement

```
income = int(input("Please enter your income: "))
years_of_work = int(input("Please enter your years of work: "))

if salary >= 30000:
  if years_of_work >=2
    print("You qualify for the loan")
  else:
    print("You must have at least 2 years of work to qualify for the loan")
else:
  print("You are not qualified for the loan")
```

 * if-elif-else

```
score = float(input("Please enter your score: "))

if score >=90:
  print("Your grade is A")
elif score >= 80:
  print("Your grade is B")
elif score >= 70:
  print("Your score is C")
elif score >= 60:
  print("Your score is D")
else:
  print("Your grade is F")
```

### Booloean operators

 * There are three boolean operators- and,or,not

In-class exercise/ practice examples-

```
number = int(input("Enter a number "))
if number > 100:
    if(number%3==0):
        print("number is divisible by 3")
    else:
        print("number is not divisible by 3")
else:
    if(number%4==0):
        print("number is divisible by 4")
    else:
        print("number is not divisible by 4")
```



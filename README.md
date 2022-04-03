# "hello-world" project

**Hej! This is a small project to test and try GitHub's features and abilities! 💻**[^1]

### How about me?
My name is Grigory. I'm a 16 years old student from Saint-Petersburg, Russia, who aspires to learn everything and everywhere possible regarding to code. As long as I can imagine, my main goal (and dream, simultaneously) is to get a software engineer job at any Swedish company and move to Sweden with my girlfriend, who's going to be my wife by these times!

<p align="center">
 <img src="https://lh3.googleusercontent.com/a-/AOh14GjoEOcnsUdt9XqraGudutCMbDSyM3UVUr7qK-Lp=s288-p-rw-no" alt="The photo of me" width="300"/> 
 <img src="https://sun9-18.userapi.com/impf/VW4QoOxFSMrEda-Ecjr9ISXP1fDXgw-im8Br2w/k5OyoKYGuYU.jpg?size=810x1080&quality=96&sign=bd09f8c727cc4cd1c620b7628302c322&type=album" alt="The photo of me" width="200"/>
<p/>

### A little of history
| Date | Event |
| --- | --- |
| 2005-07 | I was born! |
| 2012-09 | My first time at school |
| 2019-11 | Learnt some primitive code at school, got interested |
| 2020-12 | Got the coronavirus and dove into Unity and C# for a month while being ill |
| 2021-06 | Passed the exams and graduated from school with highest "excellent" marks |
| 2021-09 | My first time at the SUAI college as a mechatronics technician[^2] |
| 2022-02 | Returned to Unity, got very inspired |
| 2022-03 | Started seriously learning Python, hopped on tutorials, courses and projects |
| <sub>2025-06</sub> | <sub>Will graduate from college</sub> |

### Coding begginer checklist
- [x] Install an IDE
- [x] Compile your `"Hello World!"`
- [x] Get along with YouTube tutorials
- [x] Start taking notes
- [x] Hop on a programming course
- [x] Find soulmate learning programmers to study together
- [ ] Complete a finished and fledged project on your own
- [ ] Complete a finished and fledged project with your teammates

### A very useful program
After getting my mind into Python for a while I managed to make a little 'useful' program on my own:
```
import time
import math

digit = 9

name = input("Hello. Please, enter your name: ")
while True:
    try:
        age = int(input("How old are you?: "))
    except ValueError:
        print("Please, enter a number...")
        continue
    else:
        break
while True:
    human = input("Are you a human? [Yes/No]: ")
    if human == "Yes" or human == "No":
        break
    else:
        print("Please, enter 'Yes' or 'No'...")

print("Proccessing the data, please wait...")
time.sleep(3)
for i in range(3):
    print("Still proccessing the data...")
    time.sleep(3)

while True:
    try:
        passcode = int(input("To get the access to the infromation please enter the square root of " + str(digit) + ": "))
    except ValueError:
        print("I can't understand you.")
        continue
    if not passcode == math.sqrt(digit):
        print("Wrong number. Please, try again.")
        continue
    else:
        break

print("Data successfully accessed!")
time.sleep(1)
print("Your name is " + name)
print("Your age is " + str(age))
if human == "Yes":
    print("Congratulations! You're a human!")
else:
    print("I'm sorry, you're not a human...")
time.sleep(2)
```
It asks you a lot of questions to give you your answers back after entering a square root of the `digit` int.
I know, I know... I'm gorgeous 🐵

### Afterword
Thank you for checking out this readme! Wish you all the best.

---

If you'd like to contact me, here are some of your options:
- grigorijtomczuk@gmail.com
- [GitHub](https://github.com/grigorijtomczuk)
- [Reddit](https://www.reddit.com/user/grigorijtomczuk)

[^1]: "Hej!" is "Hello!" in Swedish.
[^2]: "College" in Russia provides you a vocational education.

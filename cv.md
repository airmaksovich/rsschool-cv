# Denis Vorontsov
## Contacts:
* Location: Bandırma, Turkey
* Phone: +79006056655
* E-mail: airmaksovich@gmail.com
* GitHub: airmaksovich
* Telegram: airmaksovich

## About me:
I am 28 years old. I'm tired of doing physical labor, so I want to explore a new direction for me. I am a fast learner, responsible and have the makings of an engineer.

# Skills:
* HTML
* CSS/SASS
* Git/GitHub
* JavaScript (Basic)
* Python (Basic)

# Code Example
```Python
s = input()
stack = []
is_good = True
for i in s:
    if i in '({[':
        stack.append(i)
    elif i in ')}]':
        if not stack:
            is_good = False
            break
        open_bracket = stack.pop()
        if open_bracket == '(' and i == ')':
            continue
        if open_bracket == '{' and i == '}':
            continue
        if open_bracket == '[' and i == ']':
            continue
        is_good = False
        break
if is_good and len(stack) == 0:
    print('YES')
else:
    print('NO')
```

# Experians
Training project on landing page layout


# Educations
* University: Ryazan State Agrotechnological University Named after P.A. Kostychev
	* Technical Systems in Agribusiness
* Courses:
	* Python Programming Indie Course
	* Object Oriented Python Programming
	* Layout and creation of websites 2022

## English
Pre-Intermediate A2(I improve my English every day)
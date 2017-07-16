# bender
Adversarial AI Agent to confuse humans

![alt text](https://github.com/ideapluslab/bender/blob/master/experiment.png)

Test 1. Selected text for 3 static positioned boxes in 1x3

Given Query: Pick the box with text "RED"

| RED BOX | GREEN BOX | BLUE BOX |

- 1 = r
- 2 = g
- 3 = b

json: ```{2, 1, 3}```

Results in

| RED BOX | GREEN BOX | BLUE BOX |
|-------------|-------------|-------------|
| TEXT GREEN | TEXT RED | TEXT BLUE |



Test 2. Selected text/color for 3 dynamic positioned boxes in 1x3

Given Query: Pick the box with color "RED"

| RED BOX | GREEN BOX | BLUE BOX |

json: ```{(r,r), (b,g), (g,b)}```

Results in

| RED BOX | BLUE BOX | GREEN BOX |
|-------------|-------------|-------------|
| TEXT RED | TEXT GREEN | TEXT BLUE |




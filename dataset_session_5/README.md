# Session 5 dataset

Original video with **14** laps by David DeFlyer:

[![David DeFlyer](https://img.youtube.com/vi/hosUBFKbHgI/0.jpg)](https://www.youtube.com/watch?v=hosUBFKbHgI&index=3&list=PLki8NgAAjqCYeZh53fGvmTR2_gkuvpON6)

Overlay with values in .csv:

[![Video with overlayed data](https://img.youtube.com/vi/SFY-97hl6rA/0.jpg)](https://www.youtube.com/watch?v=SFY-97hl6rA)

## CSV

CSV includes: (all **14** laps)

- filename for one center camera only
- steering
- throttle
- brakes
- speed
- acceleration x
- acceleration y

### Example

First 5 rows of csv:

| filename | empty | empty | steering | throttle | brakes | speed | acceleration x | acceleration y |
|----------|-------|-------|----------|----------|--------|-------|----------------|----------------|
| images/center_00000000.jpg |  |  | -0.0855263158 | 0 | 0.0436 | 45 | 0.4666666667 | -0.0666666667 |
| images/center_00000002.jpg |  |  | 0 | 0 | 0.0654 | 44 | 0.4 | -0.0666666667 |
| images/center_00000001.jpg |  |  | -0.0342105263 | 0 | 0.0545 | 45 | 0.4 | 0.1 |
| images/center_00000003.jpg |  |  | 0 | 0 | 0.0872 | 44 | 0.4 | -0.0666666667 |
| images/center_00000004.jpg |  |  | 0 | 0 | 0.0981 | 44 | 0.3333333333 | 0.1 |

Min/Max values for columns:

|   | steering | throttle | brakes | speed | acceleration x | acceleration y |
|----------|-------|-------|----------|----------|--------|-------|
| Min values | -1.88157895  |  0.     |       0.     |      21.   |        -2.26666667 |  -2.2     |
| Max values |  1.38        |  1.     |      0.81205 |     98.    |        2.26666667  |  2.2      |

*As you can see steering is not scaled [-1,1]*

## Images

Image size: **1280x320**
![First image](images/center_00000000.jpg)

## Plot

First 5000 rows:

![First 5000 rows](first5000.png)

Full plot:

![Full plot](full.png)

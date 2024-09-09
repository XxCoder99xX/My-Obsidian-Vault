---
tags: Homework
---
# Functions - Pg. 10, Sec 1, 2, 4ac, & 11

For further reference, see the original material: [[f11sb_1_1.pdf]]
## Sec 1
	a) No; repeating y values, passes the vertical-line test.
	b) No; 1 results in multiple answers.
	c) No; 0 results in multiple answers, fails the vertical-line test.
	d) Yes; passes the vertical-line test, has no multi-answers.
## Sec 2
	a) Fails at y=1
	b) Fails at x=-2
	c) Success.
	d) Fails, circle.
	e) Success.
	f) Fails at y=0
## Sec 4
	The grades and numbers of credits for students are listed.

| Student     | Grade | Number of Credits |
| ----------- | ----- | ----------------- |
| Barbara<br> | 10    | 8                 |
| Pierre      | 12    | 25                |
| Kateri      | 11    | 15                |
| Mandeep     | 11    | 18                |
| Elly        | 10    | 16                |
### a) 
#### Students and Grades
##### I) {(Barbara, 8),(Pierre, 25),(Kateri, 15),(Mandeep, 18), (Elly, 16)}
##### II) 
![[ED-202409072333.excalidraw]]
#### Grades and Credits
##### I) {(10, 8),(12, 25),(11, 15),(11, 18), (10,16)}

##### II) 
![[ED-202409072320.excalidraw]]
#### Students and Credits
##### I) {(Barbara, 10),(Pierre, 12),(Kateri, 11),(Mandeep, 11), (Elly, 10)}
##### II) 
![[ED-202409072327.excalidraw]]


### c)
	Students and Grades: true
		This is true because each student has their own value assigned to them. Given the same input, our function will produce the same output with no side effects like ambigious answers.
	Grades and Credits: false
		Grades 10 and 11 produce multiple/ambigious answers, meaning that there is no function possible.
	Students and Credits: true
		Same reasoning as grades; each name produces a unqiue response.

## Sec 7
Identify each type of relation and predict whether it is a function. Then graph each function and use the vertical-line test to determine whether your prediction was correct.

| Function                    | Preditction                       | Results  |
| --------------------------- | --------------------------------- | -------- |
| $$y = 5-2x$$                | Yes; just a slope-intercept.      | Pass.    |
| $$y=2x^2-3$$                | Yes; standard parabola equation   | Pass.    |
| $$y=-\frac{3}{4}(x+3)^2+1$$ | Yes, just a vertex form parabola. | Pass.    |
| $$x^2+y^2 = 25$$            | No; equation of a circle          | Failure. |

## Sec 11
	NOTE: The technology at my disposal cannot set the scale. I apologize for this terrible scaling.
### a) Yes. See function below.

```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [0,20,400,410]
disableZoom: false
grid: true
---
y=0.05x+400
```
### b) Yes. See function below.
```functionplot
---
title: 
xLabel: Time(h)
yLabel: Distance
bounds: [0, 20, -200, 200]
disableZoom: false
grid: true
---
y=5x
```

### c) No. Ages can be the exact same and some credits can differ. This is due to people taking different pathways and taking life more serious or lenient. For further examples, see [[ED-202409072320.excalidraw|Section 4, Graph B.]]

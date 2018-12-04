# 2143 OOP - Test 3
Name: __________________________________

  | # | Possible | Earned   |
| ----- | -------- | ---|
| 1 | 10 | |
| 2 | 10 | |
| 3 | 10 | |
| 4 | 10 | |
| 5 | 10 | |
| 6 | 10 | |
| 7 | 10 | |
| 8 | 10 | |
| 9 | 10 | |
| 10 | 10 | |
| 11 | 10 | |
| 12 | 10 | |
| 13 | 10 | |
| | **100** | |


#### Instructions
- Use pencil only
- Write your name at the top of all pages turned in.
- Staple pages together at the top left corner.
- Make sure your pages are in order, with questions also in order.
- Handwriting that is illegible (messy, small, not straight) will lose points.
- Indentation matters. Keep code aligned correctly.
- Failure to comply will result in loss of letter grade.
- All answers will be written on the paper provided, and not directly on the test.

### Question 1

- A) ______________ Is the object definition;
- B) ______________ Is the object;
- C) `name` and `id` are 
>	- a) public
	- b) private
	- c) protected
	- d) private and protected
	- e) a b & c
	
```cpp
class person { 
	char name[20]; 
	int id; 
	void getdetails(){}
}; 

int main() { 
	person p1;
} 
```

### Question 2

A) True / False : The structure below provides an adequate example of encapsulation.

```cpp
struct Fraction { 
	int numerator; 
	int denominator;
		
	void set(int n,int d) 
	{ 
		numerator = n;
		denominator = d;
	} 
	
	void print() 
	{ 
		cout<<numerator<<"/"<<denominator<<endl;
	} 
}; 
```
B) What minimal changes to the struct above would you have to make to implement proper **`data abstraction`** or **`implementation hiding`**.

### Question 3

Polymorphism means to have many forms. What this means in OOP is that we override and overload methods in our classes. There are two distinct categories of polymorphism: **compile time** and **run time**. Look at the list below and on your answer sheet write: **C** for compile time, **R** for run time, or **B** for both.

- Operator overloading.
- Method overloading.
- Method overriding.



<!--stackedit_data:
eyJoaXN0b3J5IjpbMTE3MTIyMDAwMSw2MjI2OTMzMDUsLTIxNj
g1MDU3MSwtNTgzMjg5MTMsLTIxMjMzNzAyOV19
-->
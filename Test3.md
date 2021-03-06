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

Polymorphism means to have many forms. What this means in OOP is that we override and overload methods in our classes. There are two distinct categories of polymorphism: **compile time** and **run time**. Look atIn the list below and on your answer sheet indicate which type they are: **C** for compile time, **R** for run time, or **B** for both.

- A) Operator overloading.
- B) Method overloading.
- C) Method overriding.

### Question 4

```cpp
class Vehicle { 
public: 
	Vehicle() 
	{ 
	cout << "This is a Vehicle" << endl; 
	} 
}; 
class FourWheeler { 
public: 
	FourWheeler() 
	{ 
	cout << "This is a 4 wheeler Vehicle" << endl; 
	} 
}; 
class Car: public Vehicle, public FourWheeler { 

}; 

// main function 
int main() 
{ 
	Car obj; 
	return 0; 
} 
```
What is the output of the inheritance example above?

### Question 5
abstraction

### Question 6
To add two fractions you need to:
-   Find a common denominator by finding the LCM (Least Common Multiple) of the two denominators. 
-   Change the fractions to have the same denominator and add both terms.
-   Reduce the final fraction obtained into its simpler form by dividing both numerator and denominator by the largest common factor.

Assume you have the following class that has all of those listed methods implemented for you.
```cpp
class fraction{
	int numerator;
	int denominator;
	fraction reduce(fraction f);
	int  lca,int b);
public:
	fraction(int n,int d);
	void setumerator(int n);
	void setDenominator(int d);
}
```
Overload the `+` sign to add two fractions. You can assume your defining your method inline. Assume all th methods above are implemented. Just write the overloaded method ... nothing else.

### Question 7

- A) All the class members declared as  __________ will be available to everyone. 
- B) This access modifier is similar to th oone of the other access modifiers, the difference is that the class member declare__ are inaccessible outside the class but they can be accessed by any subclass (derived class) o that class.
- C) Only member functions or __________ __________ of another class are allowed to access the private data members of thisa class.
- D) The __________ data members of thisa class can be accessed from anywhere in the program using the dotirect member access operator (.) with the object of that class.
- E) The class members declared as __________ can be accessed only by the functions inside the class. 



<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5MTgxMjEzMjcsLTU3NDUwNjI2Nyw3MT
E1NDc5MjgsLTE5NjI1ODg0MDMsLTIwMTkyNDI1NjcsMTk0MTA0
ODY4MCwxNDc0NjUyMjk4LC01NDE0NDg3NjIsMTE5NTAzNzEyNy
wxMjk3NjU3MTYsLTYxNTEzODU0NCwtMTY2MzE3MTU0MiwtMTkx
NTk0OTEzMyw2MjI2OTMzMDUsLTIxNjg1MDU3MSwtNTgzMjg5MT
MsLTIxMjMzNzAyOV19
-->
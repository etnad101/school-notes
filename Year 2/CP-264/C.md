When passing an array, it actually passes a pointer to the first (0th) element

## Defining a struct
``` C
struct method1 {
	int someVar;
	char otherVar[20];
	...
};

// This is given a value when created
struct method1 myStruct1 = {1, "Dante", "Rendell"};

// This is created with a default value
typedef struct {
	int someVar;
	char otherVar[20];
	...
} method2={0, "n/a", "n/a"};

method2 myStruct2;
```

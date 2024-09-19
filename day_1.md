# Algorithm
Finite set of instructions 
```mmd
graph TD
	Algorithm --> Input
	Algorithm --> Output
	Algorithm --> Definiteness
	Algorithm --> Finiteness
	Algorithm --> Effectiveness

```
***
### How to devise an algorithm
- understand the problem
- identify approach
- step by step plan
- pseudocode or flowcharts
***
### How to validate algorithms
- Apply logical reasoning
- Counduct dry runs
- Evaluate proof of correctness	
***
### How to analyze an algorithm
- Time complexity
- Space complexity
- Big 'O Notation
***
### How to test an algorithm
- Test case creation
- Automate testing
- BenchMarking
***
```mmd
graph LR
	devise --> validate --> analyze --> test
```
***
### Algorithm Specification
- Detailed description of algorithm 
- Precise set of instructions
***
### Components of Algorithm
- problem statment 
- approach
- step by step instructions
- pseudocode / flowchart
- complexity analysis
- proof of correctness
- examples
- assumptions
***	
### Example finding maximum element in an array
```cpp
function findMaxEle(int arr[], int n){
	if (n == 0) return NULL;
	int maxNum = arr[0];
	for(int i=1 ; i<n ; i++){
		if(arr[i] > maxNum)
			maxNum = arr[i];
	}
	return maxNum;
}
```
***
### Complexity Analysis
```mmd
flowchart LR
	cp[complexity analysis]
	ds[helps understand performance]
	cp --> ds 
```
### ways of complexity analysis
```mmd
flowchart LR
	t[types]
	tc[Time complexity]
	tcds[measures running time of algorithm as size increases]
	sc[Space complexity]
	scds[amount of memory space needed as need increases]
	bigo[Big O Notation]
	t --> tc --> tcds --> bigo
	t --> sc --> scds --> bigo 
```

### approaches to measure time complexity
```mmd
flowchart LR
	m[methods]
	n1[counting operations]
	n1ds[counts operations one by one]

	n2[analytical methods]
	n2ds[analyses thoroughly]

	n3[recurrence relations]
	n3ds[for recursive algorithms]

	n4[loop analysis]
	n4ds[analyses based on loops best for it]

	n5[asymptotic notations Big O]
	n5ds[gives overall view of relation of inputs with amount of time]

	n6[experimental analysis]
	n6ds[real world performance insights may get affected extenal factors]
	
	m --> n1 --> n1ds	
	m --> n2 --> n2ds	
	m --> n3 --> n3ds	
	m --> n4 --> n4ds	
	m --> n5 --> n5ds	
	m --> n6 --> n6ds	
```
### approaches to measure space complexity
```mmd
flowchart LR
	m[methods]
	n1[memory tracking]
	n1ds[precise but time consuming]
	n2[counting variables]
	n2ds[simple but provides basic estimate]
	n3[data structure analysis]
	n3ds[for complex data structures]
	n4[recursion stack]
	n4ds[used for recursive algorithms]
	n5[auxillary space]
	n5ds[helps understand overhead]
	n6[Big O Notation]
	n6ds[widely used for simplicity]
	
	m --> n1 --> n1ds	
	m --> n2 --> n2ds	
	m --> n3 --> n3ds	
	m --> n4 --> n4ds	
	m --> n5 --> n5ds	
	m --> n6 --> n6ds	
```
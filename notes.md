# Algorithm
Finite set of instructions 
[//]: # (This may be the most platform independent comment)
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
	return maxNUm;
}
```
***
### Complexity Analysis
```mmd
graph LR
	complexity-analysis --> helps_understand_performance 
```
### ways of complexity analysis
```mmd
graph LR
	types --> Time-complexity
	Time-complexity --> measures_running_time_of_algorithm_as_size_increases --> Big-O

	types --> Space-complexity --> amount_of_memory_space_needed_as_need_increases --> O()
```

```mmd
graph LR
	types --> Time-complexity --> measures_running_time_of_algorithm_as_size_increases --> Big-O-Notation
	types --> Space-complexity --> amount_of_memory_space_needed_as_need_increases --> Big-O-Notation
```

### approaches to measure time complexity
```mmd
graph LR
	methods --> counting_operations --> counts_operations_one_by_one 
	methods --> analytical_methods --> analyses
	methods --> recurrence_relations
	methods --> loop_analysis --> analyses.based.on.loops
	methods --> asymtotic_notations_Big-O --> gives.overall.view.of.relation.of.inputs.with.amount.of.time
	methods --> experimental_analysis
```
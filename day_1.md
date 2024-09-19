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
graph LR
	types --> Time-complexity --> measures_running_time_of_algorithm_as_size_increases --> Big-O-Notation
	types --> Space-complexity --> amount_of_memory_space_needed_as_need_increases --> Big-O-Notation
```

### approaches to measure time complexity
```mmd
graph LR
	methods --> counting_operations --> counts_operations_one_by_one 
	methods --> analytical_methods --> analyses
	methods --> recurrence_relations --> for.recursive.algorithms
	methods --> loop_analysis --> analyses_based_on_loops_best_for_it
	methods --> asymtotic_notations_Big-O --> gives.overall.view.of.relation.of.inputs.with.amount.of.time
	methods --> experimental_analysis --> real.world.performance.insights_may_get_affected_extenal_factors
```
### approaches to measure space complexity
```mmd
graph LR
	methods --> memory-tracking --> precise_but_time_consuming
	methods --> counting-variables --> simple_but_provides_basic_estimate
	methods --> data-structure-analysis --> for_complex_data_structures
	methods --> recursion-stack --> used.for.recursive.algorithms
	methods --> auxillary-space --> helps_understand_overhead
	methods --> Big-O-Notation --> widely_used_for_simplicity
```
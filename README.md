# Dataset to train machine learning methods to solve list related problems

The data set contains the following list related tasks:

- Count: the function has to output the number of elements in the input list. This task does not necessarily needs the function to understand the training examples of the instance.

- Max-min: the function has to output the maximum or minimum of the input list. The function needs to understand from the training examples if the maximum or minimum needs to be returned considering the training examples of the instance.

- Inverse: the examples show a list in which the elements are inverted or the elements are in the same position as in the input list. The function needs to understand what type of processing is done on the training examples before deciding what to do to the testing output list.

- Sort: the training examples show a list that is sorted in ascending or descending order. The function needs to understand what sorting is happening and apply it to the testing output list.

# Example for the sort task

Instances contain two examples of the task that needs to be done, named training, and the case that needs to be solved, named testing.

In this example, the sorting of the list is in descending order, but there are cases in which the list should be sorted in ascending order. This example is available in file `data/sorted/training/sorted-12.txt`

The instances are contained in text files. The first line contains the number of training examples, then for each training example the number of rows and columns, followed by the training input and output.
Finally, the test example with the number of rows and columns for the input and the expected output and a final list that can be used to initialise the problem, which can be ignored.

## Training

### Example 1

```
Input: [8, 6, 6, 7, 1, 5, 7]
Output: [8, 7, 7, 6, 6, 5, 1]
```

### Example 2

```
Input: [1, 6, 3, 4, 5, 0, 8, 8, 7, 1]
Output: [8, 8, 7, 6, 5, 4, 3, 1, 1, 0]
```

## Testing

```
Input: [2, 5, 4]
Output: [5, 4, 2]
```

# Citation

If you use this dataset, cite as follow:

```
@article{yepes2025evolutionary,
  title={Evolutionary thoughts: integration of large language models and evolutionary algorithms},
  author={Jimeno Yepes, Antonio and Barnard, Pieter},
  journal={arXiv preprint arXiv:2505.05756},
  year={2025}
}
```

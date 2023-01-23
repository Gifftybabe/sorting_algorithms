# Sorting Algorithms

![image](https://user-images.githubusercontent.com/105078661/214175990-2d9e5d85-eba0-4c98-b6b3-9648a5224e93.png)


A Sorting Algorithm is used to rearrange a given array or list of elements according to a comparison operator on the elements. The comparison operator is used to decide the new order of elements in the respective data structure.

For Example:sunflower: The below list of characters is sorted in increasing order of their ASCII values. That is, the character with a lesser ASCII value will be placed first than the character with a higher ASCII value.

![image](https://user-images.githubusercontent.com/105078661/214174663-5e680e5f-3b45-4d40-87fd-3df4f45018aa.png)


### General Learning Objectives :heavy_check_mark:
- At least four different sorting algorithms
- What is the Big O notation, and how to evaluate the time complexity of an algorithm
- How to select the best sorting algorithm for a given input
- What is a stable sorting algorithm

## Tests Files :file_folder:

* [tests](./tests): Folder of test files. 

## Helper Files :file_folder:

* [print_array.c](./print_array.c): C function that prints an array of integers. 
* [print_list.c](./print_list.c): C function that prints a `listint_t` doubly-linked list. 

## Header Files :file_folder:

* [sort.h](./sort.h): Header file containing definitions and prototypes for all types and functions written for the project.

Data Structure:
```
typedef struct listint_s
{
	const int n;
	struct listint_s *prev;
	struct listint_s *next;
} listint_t;
```

Function Prototypes:

| File                       | Prototype                                         |
| -------------------------- | ------------------------------------------------- |
| `print_array.c`            | `void print_array(const int *array, size_t size)` |
| `print_list.c`             | `void print_list(const listint_t *list)`          |
| `0-bubble_sort.c`          | `void bubble_sort(int *array, size_t size);`      |
| `1-insertion_sort_list.c`  | `void insertion_sort_list(listint_t **list);`     |
| `2-selection-sort.c`       | `void selection_sort(int *array, size_t size);`   |
| `3-quick_sort.c`           | `void quick_sort(int *array, size_t size);`       |
| `100-shell_sort.c`         | `void shell_sort(int *array, size_t size);`       |
| `101-cocktail_sort_list.c` | `void cocktail_sort_list(listint_t **list);`      |
| `102-counting_sort.c`      | `void counting_sort(int *array, size_t size);`    |
| `103-merge_sort.c`         | `void merge_sort(int *array, size_t size);`       |
| `104-heap_sort.c`          | `void heap_sort(int *array, size_t size);`        |
| `105-radix_sort.c`         | `void radix_sort(int *array, size_t size);`       |
| `106-bitonic_sort.c`       | `void bitonic_sort(int *array, size_t size);`     |
| `107-quick_sort_hoare.c`   | `void quick_sort_hoare(int *array, size_t size);` |

![image](https://user-images.githubusercontent.com/105078661/214174245-c70d9b2e-52c6-4815-94c1-5ea54989f69e.png)

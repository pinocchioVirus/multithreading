# Using Multithread(could it improve time?)
Multithreading for Sudoku and Array Sorting Solver!
### Sudoku Solution Validator:
- Athread to check that each column contains the digits 1 through 9.
- Athread to check that each row contains the digits 1 through 9.
- Nine threads to check that each of the 3×3 subgrids contains the digits 1 through.

### Multithreaded Sorting:
- A list of integers is divided into two smaller lists of equal size.
- Two separate threads (which we will term sorting threads) sort each sublist using a sorting algorithm of your  choice.
- The two sublists are then merged by a third  thread a merging  thread which merges the two sublists into a single sorted list.
- Because global data are shared across all threads, perhaps the easiest way to set up the data is to create a global array.
- Each sorting  thread will work on one half of this array.
- A second global array of the same size as the unsorted integer array will also be established. 
- The merging thread will then merge the two sublists into this second array.

### Run the file using (Terminal):
- first enter the file(cuz sometimes it doesn't recognize the path!):
```python
cd /{path}/multithreading
```
- then run the file using this command:
```python
python3 run.py
```

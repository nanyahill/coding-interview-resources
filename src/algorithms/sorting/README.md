## Sorting
According to D. Knuth, sorting algorithms can be grouped into:

1) **Sorting by Insertion** ([Insertion Sort](src/algorithms/sorting/insertionsort/README.md) & [Shell Sort](src/algorithms/sorting/shellsort/README.md))
   - Items are considered one at a time, and each new item is inserted into its appropriate position relative to previously-sorted items.
2) **Sorting by Exchanging** ([Bubble Sort](src/algorithms/sorting/bubblesort/README.md) & [Quick Sort](src/algorithms/sorting/quicksort/README.md))
   - If two items are found to be out of order, they are exchanged. This process continues until no more exchanges are necessary.
3) **Sorting by Selection** ([Selection Sort](src/algorithms/sorting/selectionsort/README.md))
   - The smallest (or largest) item is selected and stored away. Then the next smallest (or largest) item is selected, and so on.
4) **Sorting by Merging** ([Merge Sort](src/algorithms/sorting/mergesort/README.md))
   - Two sorted sequences are combined by comparing the smallest items in each list and storing the smallest in a final sequence, and then repeat the same process.
5) **Sorting by Distribution** ([Counting Sort](src/algorithms/sorting/countingsort/README.md), [Bucket Sort](src/algorithms/sorting/bucketsort/README.md) & [Radix Sort](src/algorithms/sorting/radixsort/README.md))
   - Each element is "counted" and its final position is determined by the number of elements that it exceeds.

Good Articles:

http://www.eternallyconfuzzled.com/tuts/algorithms/jsw_tut_sorting.aspx, (Good, although in c)
https://www.topcoder.com/community/data-science/data-science-tutorials/sorting/, TopCoder
The Art of Computer Programming, D.Knuth

# Insertion-Sort<br>
Insertion sort is a simple sorting algorithm that works similar to the way you sort playing cards in your hands. The array is virtually split into a sorted and an unsorted part. Values from the unsorted part are picked and placed at the correct position in the sorted part.<br>
<br>
# Characteristics of Insertion Sort:<br>
.This algorithm is one of the simplest algorithm with simple implementation<br>
.Basically, Insertion sort is efficient for small data values<br>
.Insertion sort is adaptive in nature, i.e. it is appropriate for data sets which are already partially sorted.<br>
<br>
<br>
![image](https://user-images.githubusercontent.com/125802204/234182350-a258862d-9672-4660-bca4-fb3cd731c843.png)
<br>
<br>
#Pseudo Code of Insertion Sort<br>
procedure insertionSort(A: list of sortable items)<br>
   n = length(A)<br>
   for i = 1 to n - 1 do<br>
       j = i<br>
       while j > 0 and A[j-1] > A[j] do<br>
           swap(A[j], A[j-1])<br>
           j = j - 1<br>
       end while<br>
   end for<br>
end procedure<br>
<br>
This algorithm sorts an array of items by repeatedly taking an element from the unsorted portion of the array and inserting it into its correct position in the sorted portion of the array.<br>

1.The procedure takes a single argument, ‘A’, which is a list of sortable items.<br>
2.The variable ‘n’ is assigned the length of the array A.<br>
3.The outer for loop starts at index ‘1’ and runs for ‘n-1’ iterations, where ‘n’ is the length of the array.<br>
4.The inner while loop starts at the current index i of the outer for loop and compares each element to its left neighbor. If an element is smaller than its left neighbor, the elements are swapped.<br>
5.The inner while loop continues to move an element to the left as long as it is smaller than the element to its left.<br>
6.Once the inner while loop is finished, the element at the current index is in its correct position in the sorted portion of the array.<br>
7.The outer for loop continues iterating through the array until all elements are in their correct positions and the array is fully sorted.<br>
<br>
<br>
<b><ins>Output</b></ins>
<br>
<img width="923" alt="insertion sort" src="https://user-images.githubusercontent.com/125802204/234183228-a0550f46-1e65-4439-acad-839faba7b859.png">
<br>
Time Complexity: O(N^2) <br>
Auxiliary Space: O(1)




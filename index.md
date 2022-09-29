# Extremely large head
## Very large head
###### The smallest head

_change da world. my final message. **goodbye**_

~~The FitnessGram™ Pacer Test is a multistage aerobic capacity test that progressively gets more difficult as it continues. The 20 meter pacer test will begin~~

<sub>sub</sub><sup>sup</sup><sub>sub</sub><sup>sup</sup><sub>sub</sub><sup>sup</sup><sub>sub</sub><sup>sup</sup>

>Enemies are bad, we are good - therefore nobody will mind if we do horrible things to them.

-tsun szu

[Mystery Link]("https://www.youtube.com/watch?v=2TSaAysdHhk")

[Mystery Link 2](README.md)

## Iterative quicksort algorithm C++ implementation
[source]("https://www.geeksforgeeks.org/iterative-quick-sort/")
```
// CPP code for recursive function of Quicksort
#include <bits/stdc++.h>
 
using namespace std;
 
// Function to swap numbers
void swap(int* a, int* b)
{
    int temp = *a;
    *a = *b;
    *b = temp;
}
 
/* This function takes last element as pivot,
   places the pivot element at its correct
   position in sorted  array, and places
   all smaller (smaller than pivot) to left
   of pivot and all greater elements to
   right of pivot */
int partition(int arr[], int l, int h)
{
    int x = arr[h];
    int i = (l - 1);
 
    for (int j = l; j <= h - 1; j++) {
        if (arr[j] <= x) {
            i++;
            swap(&arr[i], &arr[j]);
        }
    }
    swap(&arr[i + 1], &arr[h]);
    return (i + 1);
}
 
/* A[] --> Array to be sorted,
l --> Starting index,
h --> Ending index */
void quickSort(int A[], int l, int h)
{
    if (l < h) {
        /* Partitioning index */
        int p = partition(A, l, h);
        quickSort(A, l, p - 1);
        quickSort(A, p + 1, h);
    }
}
 
// Driver code
int main()
{
 
    int n = 5;
    int arr[n] = { 4, 2, 6, 9, 2 };
 
    quickSort(arr, 0, n - 1);
 
    for (int i = 0; i < n; i++) {
        cout << arr[i] << " ";
    }
 
    return 0;
}
```

### TODO
- [ ] change da world
- [ ] self-actualization
- [ ] eat lunch

- George Washington
- George Washington
- George Georgington
- James James George
- Jeff Jefferson

1. uno
2. dos
3. tres

![mike](https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/e12bc6ef3949c8b435f2f9e6e3dbd985~c5_720x720.jpeg?x-expires=1664600400&x-signature=W%2Bw5g1choSF8chE9s1EFGuxy1cI%3D)
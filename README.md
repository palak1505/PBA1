# PBA1

Steps to Implement Parallel Merge Sort with OpenMP
Divide the Array:

Use OpenMP directives to divide the array into smaller parts that can be independently sorted in parallel.
Parallel Sorting:

Use task parallelism to sort each part of the array concurrently using threads managed by OpenMP.
Merge Sorted Parts:

Once each part is sorted individually, merge these sorted parts to produce the final sorted array.

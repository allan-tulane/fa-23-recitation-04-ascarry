# CMPS 2200 Reciation 5
## Answers

**Name:**____Abby Scarry_____


Place all written answers from `recitation-05.md` here for easier grading.







- **1b.**

SORTED:
|      n |   qsort-fixed-pivot |   qsort-random-pivot |   tim_sort |   ssort |
|--------|---------------------|----------------------|------------|---------|
|    100 |               0.002 |                0.009 |      0.009 |   0.010 |
|    200 |               0.000 |                0.002 |      0.005 |   0.009 |
|    500 |               0.000 |                0.002 |      0.013 |   0.014 |
|   1000 |               0.001 |                0.002 |      0.025 |   0.032 |
|   2000 |               0.000 |                0.002 |      0.048 |   0.059 |
|   5000 |               0.001 |                0.007 |      0.126 |   0.136 |
|  10000 |               0.002 |                0.008 |      0.525 |   0.287 |
|  20000 |               0.002 |                0.008 |      0.490 |   0.608 |
|  50000 |               0.004 |                0.013 |      1.419 |   2.452 |
| 100000 |               0.004 |                0.016 |      3.119 |   3.754 |

RANDOM:

|      n |   qsort-fixed-pivot |   qsort-random-pivot |   tim_sort |   ssort |
|--------|---------------------|----------------------|------------|---------|
|    100 |               0.002 |                0.003 |      0.021 |   0.015 |
|    200 |               0.001 |                0.002 |      0.030 |   0.014 |
|    500 |               0.001 |                0.003 |      0.083 |   0.024 |
|   1000 |               0.002 |                0.005 |      0.180 |   0.052 |
|   2000 |               0.002 |                0.004 |      0.378 |   0.116 |
|   5000 |               0.002 |                0.004 |      0.992 |   0.212 |
|  10000 |               0.003 |                0.005 |      2.278 |   0.342 |
|  20000 |               0.003 |                0.005 |     56.607 |   1.060 |
|  50000 |               0.003 |                0.005 |     80.473 |   4.264 |
| 100000 |               0.003 |                0.006 |     88.283 |  19.113 |

The running times of the sorting algorithms align with their asymptotic bounds. The running times of ssort (selection sort) are consistently higher in both sorted and random cases compared to the others. Selection sort also increases significantly with input size, much more than with quicksort. Selection sort is quicker when sorted and quicksort is slower when sorted, but still more efficient than selection sort. Overall, quicksort is faster and more efficient than selection sort in all cases.



- **1c.**

In the charts above, it seems that for both the sorted and random cases, for smaller inputs, quicksort is faster than timsort, but timsort is quicker for larger inputs. In sorted case, quicksort with fixed pivot is quickest and in random, quicksort with random pivot is quickest.

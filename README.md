# Selection-sorting
# Aim:-
    To perform sorting of array
# Theory:-
         A Sorting Algorithm is used to rearrange a given array or list elements according to a comparison operator on the elements.                The comparison operator is used to decide the new order of element in the respective data structure.
# Algorithm:-
            
                          void swap(int *xp, int *yp) 
                           int temp = *xp
                            *xp = *yp 
                            *yp = temp 
                            void selectionSort(int arr[], int n) 
                            int i, j, min_idx; 
                             for (i = 0; i < n-1; i++) 
                              { 
                                    min_idx = i 
                                    for (j = i+1; j < n; j++) 
                                    if (arr[j] < arr[min_idx]) 
                                    min_idx = j 
                                    swap(&arr[min_idx], &arr[i]) 
                               } 
                            
Conclusion:-
                From this program we learnt how to perform  selection sorting techniques to arrange a particular array

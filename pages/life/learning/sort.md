# ソート
## Insertion Sort
- time complexity O(N^2)
- space complecity O(N)
- cf: Shell Sort

```
void insertionSort(vector<int>& a, int n) {
    for(int i=0; i<n; i++) {
        int v = a[i];
        int j = i;
        while(j>0 && a[j-1]>v) {
            a[j] = a[j-1];
            j--;
            a[j] = v;
        }
    }
}
```

## Bubble Sort
- time complexity O(N^2)
- space complecity O(N)

```
void bubbleSort(vector<int>& a, int n) {
    bool flag = true;
    while(flag) {
        flag = false;
        for(int j=n-1; j>=1; j--) {
            if(a[j] > a[j-1]) { 
                int v = a[j];   
                a[j] = a[j-1];
                a[j-1] = a[j];
                flag = true;
            }
        }
    }
}
```

## Selection Sort
- time complexity O(N^2)
- space complecity O(N)

```
void selectionSort(vector<int>& a, int n) {
    for(int i = 0; i<n; i++) {
        int minj = i;
        for(int j=i;j<n;j++) {
            if(a[j] < a[minj]) {
                minj = j;
            }
            int v = a[j];
            a[j] = a[minj];
            a[minj] = a[j];
        }
    }
}
```

## Stable Sort
- 初期の要素の順番を保持したままソートできる
- Insert Sort, Bubble Sort

## Shell Sort


## Merge Sort

## Partiotion

## Quick Sort

## Heap Sort

## Counting Sort

## Minimum Cost Sort

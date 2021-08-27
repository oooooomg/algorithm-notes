## 排序算法

### 冒泡排序

**冒泡排序的定义**

> 冒泡排序比较所有相邻的两个项，如果第一个比第二个大，则交换它们。元素项向上移动至正确的顺序，就好像气泡升至表面一样。

**冒泡排序的实现**

**[`BubbleSort Demo`](./bubble-sort.js)**

### 选择排序

**选择排序的定义**

> 选择排序算法是一种原址比较排序算法。选择排序大致的思路是找到数据结构中最小值并将其放置在第一位，接着找到第二小的值并将其放在第二位，以此类推。

**选择排序的实现**

**[`SelectionSort Demo`](./selection-sort.js)**

### 插入排序

**插入排序的定义**

> 插入排序每次排一个数组项，以此方式构建最后的排序数组。假定第一项已经排序了。接着，它和第二项进行比较---第二项是应该待在原位还是插到第一项之前呢？这样，头两项就已正确排序，接着和第三项比较（它是该插入到第一、第二还是第三的位置呢）以此类推。

**插入排序的实现**

**[`InsertSort Demo`](./insert-sort.js)**

### 归并排序

**归并排序的定义**

> 归并排序是第一个可以实际使用的排序算法，其复杂度为 O(nlog(n))
> 归并排序是一种分而治之算法。其思想是将原始数组切分成较小的数组，知道每一个小数组只有一个位置，接着将小树组归并成较大的数组，直到最后只有一个排序完毕的大数组。由于是分治法，归并排序也是递归的。

**归并排序的实现**

**[`MergeSort Demo`](./merge-sort.js)**

### 快速排序

**快速排序的定义**

> 快速排序是最常用的排序算法，复杂度为 O(nlog(n))，且性能通常比其他复杂度为 O(nlog(n))的排序算法要好。和归并排序一样，快速排序也使用分而治之的方法，将原始数组分为较小的数组（但它没有像归并排序那样将它们分割开）

**快速排序的实现**

**[`QuickSort Demo`](./quick-sort.js)**

### 计数排序

**计数排序的定义**

> 计数排序是一个分布式排序。分布式排序使用已组织好的辅助数据结构（称为桶），然后进行合并，得到拍好序的数组。计数数组使用一个用来存储每一个元素在原始数组中出现次数的临时数组。在所有元素都计数完成后，临时数组已排好序并可迭代以构建排序后的结构数组

**计数排序的实现**

**[`CountingSort Demo`](./counting-sort.js)**

### 桶排序

**桶排序的定义**

> 桶排序（也称为箱排序）也是分布式排序算法，它将元素风味不同的桶（较小的数组），再使用一个简单的排序算法，比如插入排序（用来排序小树组的不错算法），来对每一桶进行排序。然后，它将所有的桶合并为结果数组。

**桶排序的实现**

**[`BucketSort Demo`](./bucket-sort.js)**

### 基数排序

**基数排序的定义**

> 基数排序也是一个分布式排序算法，它根据数字的有效位或基数（这也是它为啥叫做基数排序）将整数分布到桶中。基数是基于数组中的值的计数制的。

**基数排序的实现**

**[`RadixSort Demo`](./radix-sort.js)**
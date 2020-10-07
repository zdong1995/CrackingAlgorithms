# CrackingAlgorithms
Solutions for my LeetCode challenging and Java practice. Sorted in different topics and add comments for easy understanding.

# Problems and Solutions

| # | Title | Topic | Solution | Basic idea| Difficulty |
|---| ----- | ----- | -------- | --------------------- | ------ |
| 1 | [two-sum](https://leetcode.com/problems/two-sum) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/two-sum.java)| One pass hashtable to check whether the complement in the map | Easy |
| 2 | [add-two-numbers](https://leetcode.com/problems/add-two-numbers) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/add-two-numbers.java)| Two pointers to sum by digit, be careful with last non-zero carry after sum all digits | Medium |
| 3 | [longest-substring-without-repeating-characters](https://leetcode.com/problems/longest-substring-without-repeating-characters) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/longest-substring-without-repeating-characters.java)| Sliding window + HashTable counter to remove duplicates | Medium |
| 15 | [3sum](https://leetcode.com/problems/3sum) | Two Pointers | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/TwoPointers/3sum.java)| For loop + Two Pointer to search for 2 Sum pair | Medium |
| 16 | [3sum-closest](https://leetcode.com/problems/3sum-closest) | Two Pointers | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/TwoPointers/3sum-closest.java)| Two pointers to search 2 Sum pair equal to (target - nums[i]), maintain minDiff to determine closest | Medium |
| 17 | [letter-combinations-of-a-phone-number](https://leetcode.com/problems/letter-combinations-of-a-phone-number) | DFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/DFS/letter-combinations-of-a-phone-number.java)| DFS + using dictionary to handle possible letters of current number representation | Medium |
| 19 | [remove-nth-node-from-end-of-list](https://leetcode.com/problems/remove-nth-node-from-end-of-list) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/remove-nth-node-from-end-of-list.java)| Two pointer to mainatain a gap with size = n | Medium |
| 21 | [merge-two-sorted-lists](https://leetcode.com/problems/merge-two-sorted-lists) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/merge-two-sorted-lists.java)| Maintain dummy head and tail to iteratively add smalled node to the end | Easy |
| 22 | [generate-parentheses](https://leetcode.com/problems/generate-parentheses) | DFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/DFS/generate-parentheses.java)| Check number of left / right parentheses before DFS. | Medium |
| 24 | [swap-nodes-in-pairs](https://leetcode.com/problems/swap-nodes-in-pairs) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/swap-nodes-in-pairs.java)| Recursion rule `swapPair(head.next.next)` | Medium |
| 25 | [reverse-nodes-in-k-group](https://leetcode.com/problems/) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/.java)| Find K-group, reverse K-group and link to next reversed sub-list. | Hard |
| 26 | [remove-duplicates-from-sorted-array](https://leetcode.com/problems/remove-duplicates-from-sorted-array) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/remove-duplicates-from-sorted-array.java)| Two pointers, slow is the last element to be returned. | Easy |
| 39 | [combination-sum](https://leetcode.com/problems/combination-sum) | DFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/DFS/combination-sum.java)| DFS each level represent how many we will select for each candidates | Medium |
| 45 | [jump-game-ii](https://leetcode.com/problems/jump-game-ii) | DP |[Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Dynamic_Programming/jump-game-ii.java)| Array to store the min jumps needed to reach end from i-th position | Hard |
| 46 | [permutations](https://leetcode.com/problems/permutations) | DFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/DFS/permutations.java)| Use in-place swap or extra boolean array to mark used state. | Medium |
| 47 | [permutations-ii](https://leetcode.com/problems/permutations-ii) | DFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/DFS/permutations-ii.java)| For each level, use HashSet to track whether letter has been used. | Medium |
| 50 | [powx-n](https://leetcode.com/problems/powx-n) | Binary Search | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Binary_Search/powx-n.java)| Recursive `x^t = x^(t/2) * x^(t/2)` and be careful with `Interger.MIN_VALUE` | Medium |
| 53 | [maximum-subarray](https://leetcode.com/problems/maximum-subarray) | DP |[Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Dynamic_Programming/maximum-subarray.java)| Max between (previous max_sum + current num) and only current num itself | Easy |
| 54 | [spiral-matrix](https://leetcode.com/problems/spiral-matrix) | Matrix | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Matrix/spiral-matrix.java)| Iterative to traverse from top -> right -> bottom -> left, update begin index and end after each iteration | Medium |
| 55 | [jump-game](https://leetcode.com/problems/jump-game) | DP |[Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Dynamic_Programming/jump-game.java)| Boolean array to store whether we can jump starting from current index to reach the end | Medium |
| 59 | [spiral-matrix-ii](https://leetcode.com/problems/spiral-matrix-ii) | Matrix | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Matrix/spiral-matrix-ii.java)| Recursion to fill matrix layer by layer, top row -> right col -> bottom row -> left col | Medium | Medium |
| 61 | [rotate-list](https://leetcode.com/problems/rotate-list) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/rotate-list.java)| Find last (k % len + 1) node as newTail, reconnect list | Medium |
| 62 | [unique-paths](https://leetcode.com/problems/unique-paths) | DP |[Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Dynamic_Programming/unique-paths.java)| Paths = paths from left + paths from right | Medium |
| 70 | [climbing-stairs](https://leetcode.com/problems/climbing-stairs) | DP |[Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Dynamic_Programming/climbing-stairs.java)| ways to climb to i-th level = ways to climb to (i-1)th level + (i-2)th level | Easy |
| 72 | [edit-distance](https://leetcode.com/problems/edit-distance) | DP |[Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Dynamic_Programming/edit-distance.java)|  | Hard |
| 74 | [search-a-2d-matrix](https://leetcode.com/problems/search-a-2d-matrix) | Binary Search | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Binary_Search/search-a-2d-matrix.java)| 2D array to 1D array, Binary Search | Medium |
| 75 | [sort-colors](https://leetcode.com/problems/sort-colors) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/sort-colors.java)| Maintain 3 pointers to partition to 3 areas | Medium |
| 77 | [combinations](https://leetcode.com/problems/combinations) | DFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/DFS/combinations.java)| Similar to all subsets, n levels recursion, base case need check size == k? | Medium |
| 78 | [subsets](https://leetcode.com/problems/subsets) | DFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/DFS/subsets.java)| For each level, two state: add to subset or not. Recursion tree will have `num.length` levels. | Medium |
| 80 | [remove-duplicates-from-sorted-array-ii](https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/remove-duplicates-from-sorted-array-ii.java)| Two pointers, each time check fast and (slow - 2) | Medium |
| 83 | [remove-duplicates-from-sorted-list](https://leetcode.com/problems/remove-duplicates-from-sorted-list) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/remove-duplicates-from-sorted-list.java)| Iterative and recursive way to check duplicate and remove node | Easy |
| 86 | [partition-list](https://leetcode.com/problems/partition-list) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/partition-list.java)| Maintain two Dummy head and tail for small and large list, then concatenate | Medium |
| 88 | [merge-sorted-array](https://leetcode.com/problems/merge-sorted-array) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/merge-sorted-array.java)| In-place: two pointer from end to start, iteratively copy larger number to the end | Easy |
| 90 | [subsets-ii](https://leetcode.com/problems/subsets-ii) | DFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/DFS/subsets-ii.java)| Add element or not add element. If not add, skip all the rest duplicates. | Medium |
| 92 | [reverse-linked-list-ii](https://leetcode.com/problems/reverse-linked-list-ii) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/reverse-linked-list-ii.java)| Find m-th node and record tail, reverse and connect 3 parts | Medium |
| 100 | [same-tree](https://leetcode.com/problems/same-tree) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/same-tree.java)| Recursive compare `LL` & `RL`, `LR` & `RR` to determine whether is same tree for each pair | Easy |
| 101 | [symmetric-tree](https://leetcode.com/problems/symmetric-tree) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/symmetric-tree.java)| Recursive compare `LL` & `RR`, `LR` & `RL` to determine whether symmetric for each pair | Easy |
| 102 | [binary-tree-level-order-traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) | BFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/BFS/binary-tree-level-order-traversal.java)| BFS, use list to store value on each level | Medium |
| 103 | [binary-tree-zigzag-level-order-traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal) | BFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/BFS/binary-tree-zigzag-level-order-traversal.java)| Use Deque to BFS and offerFirst/Last for odd/even layer respectively | Medium |
| 104 | [maximum-depth-of-binary-tree](https://leetcode.com/problems/maximum-depth-of-binary-tree) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/maximum-depth-of-binary-tree.java)| Recursion to get max height from left and right child then increase by 1| Easy |
| 110 | [balanced-binary-tree](https://leetcode.com/problems/balanced-binary-tree) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/balanced-binary-tree.java)| Pre-order traverse and compare left & right using `getHeight()` helper function | Easy |
| 125 | [valid-palindrome](https://leetcode.com/problems/valid-palindrome) | Two Pointers | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/TwoPointers/valid-palindrome.java)| Two pointers from left and right to compare digits and chars | Easy |
| 133 | [clone-graph](https://leetcode.com/problems/clone-graph) | Graph | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Graph/clone-graph.java)| DFS + Map to store 1:1 mapping of original node and copied node | Medium |
| 138 | [copy-list-with-random-pointer](https://leetcode.com/problems/copy-list-with-random-pointer) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/copy-list-with-random-pointer.java)| Maintain 1 to 1 mapping from orignal node to copied node to avoid duplicate copy | Medium |
| 139 | [word-break](https://leetcode.com/problems/word-break) | DP |[Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Dynamic_Programming/word-break.java)| DP table to store whether the substring [0, i) can break | Medium |
| 141 | [linked-list-cycle](https://leetcode.com/problems/linked-list-cycle) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/linked-list-cycle.java)| Fast and slow pointer, cycle exists when two pointers meet | Easy |
| 143 | [reorder-list](https://leetcode.com/problems/reorder-list) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/reorder-list.java)| Find mid nodes -> Reverse second part -> Merge two parts | Medium |
| 144 | [binary-tree-preorder-traversal](https://leetcode.com/problems/binary-tree-preorder-traversal) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/binary-tree-preorder-traversal.java)| Recursion + Iterative by explicitly maintain a stack | Medium |
| 147 | [insertion-sort-list](https://leetcode.com/problems/insertion-sort-list) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/insertion-sort-list.java)| Use dummy node, each time find the last position that is smaller than current node, then insert current to that position | Medium |
| 151 | [reverse-words-in-a-string](https://leetcode.com/problems/reverse-words-in-a-string) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/reverse-words-in-a-string.java)| 3-steps reverse and remove space | Medium |
| 155 | [min-stack](https://leetcode.com/problems/min-stack) | Stack  | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Stack/min-stack.java)| Auxiliary sync stack to store min, push min when num <= min | Easy |
| 156 | [binary-tree-upside-down](https://leetcode.com/problems/binary-tree-upside-down) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/binary-tree-upside-down.java)| Subproblem: Reverse tree with root of `curRoot.left` | Medium |
| 167 | [two-sum-ii-input-array-is-sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted) | Two Pointers| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/TwoPointers/two-sum-ii-input-array-is-sorted.java)| Two pointers from left and right | Easy |
| 170 | [two-sum-iii-data-structure-design](https://leetcode.com/problems/two-sum-iii-data-structure-design) | Other | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Other/two-sum-iii-data-structure-design.java)| Add: put to HashMap -> O(1), Find: iterate each key in HashMap and find 2 sum -> O(N) | Easy |
| 186 | [reverse-words-in-a-string-ii](https://leetcode.com/problems/reverse-words-in-a-string-ii) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/reverse-words-in-a-string-ii.java)| 3-steps reverse: reverse all words, then reverse whole sentence | Medium |
| 189 | [rotate-array](https://leetcode.com/problems/rotate-array) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/rotate-array.java)| 3-steps reverse, first part ending at (length - 1 - steps). | Easy |
| 191 | [number-of-1-bits](https://leetcode.com/problems/number-of-1-bits) | Bits Manipulation | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Bits_Manipulation/number-of-1-bits.java)| Iteratively right shift and compare `n & 1` with 1 | Easy |
| 199 | [binary-tree-right-side-view](https://leetcode.com/problems/binary-tree-right-side-view) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/binary-tree-right-side-view.java)| DFS: traverse root -> right -> and record the first node reaching level i. BFS: level order traverse + record last node in current level | Medium |
| 203 | [remove-linked-list-elements](https://leetcode.com/problems/remove-linked-list-elements) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/remove-linked-list-elements.java)| Dummy node, iteratively remove all target | Easy |
| 206 | [reverse-linked-list](https://leetcode.com/problems/reverse-linked-list) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/reverse-linked-list.java)| Iterative and Recursion | Easy |
| 209 | [minimum-size-subarray-sum](https://leetcode.com/problems/minimum-size-subarray-sum) | Array | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/minimum-size-subarray-sum.java)| Sliding window, shrink subarray window when sum >= s | Medium |
| 215 | [kth-largest-element-in-an-array](https://leetcode.com/problems/kth-largest-element-in-an-array) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/kth-largest-element-in-an-array.java)| MinHeap to keey top k elements | Medium |
| 231 | [power-of-two](https://leetcode.com/problems/power-of-two) | Bits Manipulation | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Bits_Manipulation/power-of-two.java)| Check whether contain only one 1-bit | Easy |
| 234 | [palindrome-linked-list](https://leetcode.com/problems/palindrome-linked-list) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/palindrome-linked-list.java)| Find mid -> reverse 2nd half -> check palindrome | Easy |
| 242 | [valid-anagram](https://leetcode.com/problems/valid-anagram) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/valid-anagram.java)| Increase count when traverse source string, while decrease for target. Check whether negative count exists | Easy |
| 259 | [3sum-smaller](https://leetcode.com/problems/3sum-smaller) | Two Pointers | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/TwoPointers/3sum-smaller.java)| Fix one number, use Two Pointers to run 2 sum smaller | Medium |
| 283 | [move-zeroes](https://leetcode.com/problems/move-zeroes) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/move-zeroes.java)| 2 pointers copy non-0s to front of left, then fill left to end with 0s. | Easy |
| 322 | [coin-change](https://leetcode.com/problems/coin-change) | DP |[Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Dynamic_Programming/coin-change.java)| DP[i] = DP[i - coin] + 1, represent number of coins needed to change | Medium |
| 328 | [odd-even-linked-list](https://leetcode.com/problems/odd-even-linked-list) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/odd-even-linked-list.java)| Similar to partition linkedlist, use index to determine odd or even | Medium |
| 344 | [reverse-string](https://leetcode.com/problems/reverse-string) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/reverse-string.java)| Two pointers swap or Recursion | Easy |
| 378 | [kth-smallest-element-in-a-sorted-matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix) | BFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/BFS/kth-smallest-element-in-a-sorted-matrix.java)| Best First Search, initial at [0][0], expand each node to generate [x+1][y] and [x][y+1] | Medium |
| 387 | [first-unique-character-in-a-string](https://leetcode.com/problems/first-unique-character-in-a-string) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/first-unique-character-in-a-string.java)| HashMap to store counter and one pass to find first character with count = 1 | Easy |
| 409 | [longest-palindrome](https://leetcode.com/problems/longest-palindrome) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/longest-palindrome.java)| HashMap/Set/Array to store count and then find the number of characters appeared odd times | Easy |
| 419 | [partition-equal-subset-sum](https://leetcode.com/problems/partition-equal-subset-sum) | DP |[Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Dynamic_Programming/partition-equal-subset-sum.java)| All Subsets similar DFS + Memoization | Medium |
| 443 | [string-compression](https://leetcode.com/problems/string-compression) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/string-compression.java)| Slow and fast pointers to read and copy chars and counts | Easy |
| 461 | [hamming-distance](https://leetcode.com/problems/hamming-distance) | Bits Manipulation | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Bits_Manipulation/hamming-distance.java)| XOR the two Interger and count how many 1-bits | Easy |
| 509 | [fibonacci-number](https://leetcode.com/problems/fibonacci-number) | DP |[Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Dynamic_Programming/fibonacci-number.java)| 2-value Memoization `fibo(N) = fibo(N-2) + fibo(N-1)` | Easy |
| 611 | [valid-triangle-number](https://leetcode.com/problems/valid-triangle-number) | Two Pointers | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/TwoPointers/valid-triangle-number.java)| Fix long side and number of two sum pairs that larger than the longer side | Medium |
| 643 | [maximum-average-subarray-i](https://leetcode.com/problems/maximum-average-subarray-i) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/maximum-average-subarray-i.java)| Sliding window to find the maximum sum with size K | Easy |
| 680 | [valid-palindrome-ii](https://leetcode.com/problems/valid-palindrome-ii) | Two Pointers | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/TwoPointers/valid-palindrome-ii.java)| Two Pointers, if character at left and right are different, check whether remove-left or remove-right is palindrome | Easy |
| 700 | [search-in-a-binary-search-tree](https://leetcode.com/problems/search-in-a-binary-search-tree) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/search-in-a-binary-search-tree.java)| Iterative and Recursive | Easy |
| 704 | [binary-search](https://leetcode.com/problems/binary-search) | Binary Search | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Binary_Search/binary-search.java)| Classical Binary Search | Easy |
| 724 | [find-pivot-index](https://leetcode.com/problems/find-pivot-index) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/find-pivot-index.java)| Increase prefix sum to reach half of total sum | Easy |
| 780 | [reaching-points](https://leetcode.com/problems/reaching-points) | Other | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Other/reaching-points.java)| Reverse backtracking to consider two operations recursively | Hard |
| 785 | [is-graph-bipartite](https://leetcode.com/problems/is-graph-bipartite) | Graph | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/BFS/is-graph-bipartite.java)| BFS each node and color the node, if current node and neighbors have same color, return false | Medium |
| 786 | [k-th-smallest-prime-fraction](https://leetcode.com/problems/k-th-smallest-prime-fraction) | Heap | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Heap/k-th-smallest-prime-fraction.java)| Implicit fraction matrix composed by given sorted array. Use heap to find K-th smallest. | Hard |
| 876 | [middle-of-the-linked-list](https://leetcode.com/problems/middle-of-the-linked-list/) | LinkedList | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/LinkedList/middle-of-the-linked-list.java)| Fast & Slow two pointers | Easy |
| 905 | [sort-array-by-parity](https://leetcode.com/problems/sort-array-by-parity) | Two Pointers | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/TwoPointers/sort-array-by-parity.java)| Left and Right pointer, swap when left is odd and right is even | Easy |
| 912 | [merge-sort](https://leetcode.com/problems/sort-an-array) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/merge-sort.java)| Recursion helper function + merge two sorted array | Medium |
| 912 | [quick-sort](https://leetcode.com/problems/sort-an-array) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/quick-sort.java)| Pick random pivot + maintain two pointer to partion the array |  Medium |
| 912 | [selection-sort](https://leetcode.com/problems/sort-an-array) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/selection-sort.java)| Maintain one partition between sorted part and unsorted part |  Medium |
| 958 | [check-completeness-of-a-binary-tree](https://leetcode.com/problems/check-completeness-of-a-binary-tree) | BFS | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/check-completeness-of-a-binary-tree.java)| BFS level order traversal, add one bool to indicate whether null found in the leftside | Medium |
| 1047 | [remove-all-adjacent-duplicates-in-string](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/remove-all-adjacent-duplicates-in-string.java)| Two pointer to maintian one in-place stack. | Easy |
| 1089 | [duplicate-zeroes](https://leetcode.com/problems/duplicate-zeroes) | Two Pointers | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/TwoPointers/duplicate-zeroes.java)| One pass count zeroes, then two pointers from right to left to copy elements | Easy |
| 1209 | [remove-all-adjacent-duplicates-in-string-ii](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string-ii) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/remove-all-adjacent-duplicates-in-string-ii.java)| Count array + fast/slow pointers implicitly mainatain as stack to pop k duplicates | Medium |
| 1608 | [special-array-with-x-elements-greater-than-or-equal-x](https://leetcode.com/problems/special-array-with-x-elements-greater-than-or-equal-x) | Binary Search | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Binary_Search/special-array-with-x-elements-greater-than-or-equal-x.java)| Binary Search to find the first position `nums[i] >= len - i` and `nums[i - 1] < len - u` | Easy |
| L8 | [rotate-string](https://www.lintcode.com/problem/rotate-string) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/rotate-string.java)| 3 steps reverse, divided by index `str.length - 1 - offset` | Easy |
| L11 | [search-range-in-binary-search-tree](https://www.lintcode.com/problem/search-range-in-binary-search-tree) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/search-range-in-binary-search-tree.java)| inOrder traverse and check bound condition before recurse left or right | Medium |
| L14 | [first-position-of-target](https://lintcode.com/problem/first-position-of-target) | Binary Search | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Binary_Search/first-position-of-target.java)| Classical binary search + `right = mid` when found target to search left-side + post-processing | Easy |
| L39 | [recover-rotated-sorted-array](https://www.lintcode.com/problem/recover-rotated-sorted-array) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/recover-rotated-sorted-array.java)| 3 Steps reverse. One pass to find offset | Easy |
| L229 | [stack-sorting](https://www.lintcode.com/problem/stack-sorting/) | Array| [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Array/stack-sorting.java)| Selection sort. Bottom of buffer stack are sorted elements. | Medium |
| L443 | [two-sum-greater-than-target](https://www.lintcode.com/problem/two-sum-greater-than-target) | Two Pointers | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/TwoPointers/two-sum-greater-than-target.java)| Two Pointer, count pairs when left + right > target | Medium |
| L458 | [last-position-of-target](https://lintcode.com/problem/last-position-of-target) | Binary Search | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Binary_Search/last-position-of-target.java)| Classical binary search + `left = mid` when found target to search right-side + post-processing | Easy |
| L459 | [closest-number-in-sorted-array](https://www.lintcode.com/problem/closest-number-in-sorted-array) | Binary Search | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Binary_Search/closest-number-in-sorted-array.java)| Classical binary search + post-processing to compare distance from left/right to target | Easy |
| L470 | [tweaked-identical-binary-tree](https://www.lintcode.com/problem/tweaked-identical-binary-tree) | Tree | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/Tree/tweaked-identical-binary-tree.java)| Recursion check whether is symmetric or same tree | Medium |
| L533 | [two-sum-closest-to-target](https://leetcode.com/problems/) | Two Pointers | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/TwoPointers/.java)| Two pointers and update minDiff each time | Medium |
| L587 | [two-sum-unique-pairs](https://www.lintcode.com/problem/two-sum-unique-pairs) | Two Pointers | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/TwoPointers/two-sum-unique-pairs.java)| Sort + Two Pointers, need to skip duplicate number | Medium |
| L609 | [two-sum-less-than-or-equal-to-target](https://www.lintcode.com/problem/two-sum-less-than-or-equal-to-target) | Two Pointers | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/TwoPointers/two-sum-less-than-or-equal-to-target.java)| Two Pointer, count pairs when left + right <= target | Medium |
| L686 | [remove-arbitrary-space](https://www.lintcode.com/problem/remove-arbitrary-space) | String | [Java](https://github.com/zdong1995/CrackingAlgorithms/blob/master/String/remove-arbitrary-space.java)| Two pointers to copy non-space chars to slow position. Add heading space to non-first words. | Easy |
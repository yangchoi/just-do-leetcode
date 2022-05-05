### Binary Search 

#### 배열 이진 탐색
- 정렬된 배열 (배열 각 요소를 오름차순으로 나열하는 처리의 복잡도 : <br>O(NlogN) </br> N은 배열크기)

- 배열에서 특정 요소를 찾아야하는 경우
- left = 0, right = N.length-1 로 초기화 
- left와 right 값을 배열의 중간값( (left+right)/2) 과 비교
- 이때, 중간값이 소수로 나올 경우 소수점 이하는 버린다.
- 찾고자 하는 요소와 중간값을 비교해 
  중간값이 더 크면 배열의 왼쪽 반만 남기고 탐색
  중간값이 더 작으면 배열의 오른쪽 반만 남기고 탐색
- 이런 식으로 탐색범위를 반으로 줄여가며 배열 크기가 1이하가 될 때까지 반복


#### 2022.04.30


##### Q1. [Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/)
##### Q2. [Sqrt(x)](https://leetcode.com/problems/sqrtx/)

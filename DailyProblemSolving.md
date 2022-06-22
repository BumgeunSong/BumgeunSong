## Daily Problem Solving

💻 매일 공부했던 알고리즘, 자료구조 문제를 정리합니다.

| 날짜 | 이름 | 결과 | 배운 것 |
| --- | --- | --- | --- |
| 2022/06/22 | [Search For a Range](https://bumgeunsong.notion.site/Search-For-a-Range-941f5da5d4b7440a85568cc47e675715) | 🥉 | 중복 정렬 배열에서 LowerBound, UpperBound 구하기.</br>lower Bound는 target과 '같은 수'가 처음 등장하는 인덱스. Upper Bound는 target보다 ‘큰 수'가 처음 등장하는 인덱스
| 2022/06/16 | [Top K Frequent Elements](https://bumgeunsong.notion.site/Top-K-Frequent-Elements-7ff457a06ddd4fe0a3c713fc4cbf3e16) | 🥉 | 버킷 정렬을 적용해 O(n)으로 해결하기.</br>Top K 고를 때 Quick Select 알고리즘 응용하기
| 2022/06/15 | [Word Search](https://bumgeunsong.notion.site/Word-Search-1f53a534de344b0fb718e89397a8a6fd) | 🥉 | 그래프 탐색 시 방문 배열 (visited) 초기화 시점 주의. 인접 노드를 확인할 때 이전 확인이 다음 확인의 방문 배열에 영향을 주지 않아야 함</br>백트래킹 조건 필터링은 노드를 Queue/Stack에 추가하기 ‘전’에 하는 것이 유리함.
| 2022/06/14 | [Subsets 부분집합 (조합)](https://bumgeunsong.notion.site/Subsets-319e0d82cc7c4f2eafabf523930680ac) | 🥇 | 전체 부분집합 = nCn + nCn-1 + … + nC0 (공집합)
| 2022/06/14 | [Permutations 순열](https://bumgeunsong.notion.site/Permutations-a798f1e8b4c344d7be6f259474f44471) | 🥇 | 순열의 경우, pick을 뽑을 때 for문으로 전체를 뽑음. remain은 pick을 ‘제외한 배열'.
| 2022/06/13 | [Letter Combinations of a Phone Number](https://bumgeunsong.notion.site/Letter-Combinations-of-a-Phone-Number-b8c4bfd8d21242bfbdc1a3ba4816b063) | 🥇 | DFS 조합 만들기
| 2022/06/12 | [야영하기](https://bumgeunsong.notion.site/63822af2b147492b873257cd5423c4b2) | 🥇 | 4방면 방문 이외의 다른 옵션이 있는 BFS.</br>옵션에 따른 노드 정보를 업데이트하고 그대로 큐에 추가해서 해결.
| 2022/06/12 | [요금제 찾기](https://bumgeunsong.notion.site/b3fbdbb52e7f4bc1aacd230b5475b6ba) | 🥇 | 해시테이블로 부분조합 O(1) 확인.</br>이진 검색 + upper bound
| 2022/06/12 | [VIP 찾기](https://bumgeunsong.notion.site/VIP-644fcf77f916474f92613a3c9e48f3a7) | 🥇 | -
| 2022/06/12 | [선택 정렬 (Selection Sort)](https://bumgeunsong.notion.site/Selection-Sort-0d65f67326e5408f8482c423aa3e44fe) | 🥇 | 선택 정렬 구현
| 2022/06/11 | [Number of Islands](https://bumgeunsong.notion.site/Number-of-Islands-824a93d1e760476b8d3b64c456bcbeaf) | 🥇 | BFS로 그래프 탐색할 때 방문 처리 시점과 큐에서 꺼내는 시점의 차이.</br>좌표 튜플에 typeAlias 적용. dxdy를 사용한 4방면 루프</br>(최적화) grid 벗어나는 좌표 함수 호출 전에 예외 처리 -> 재귀 호출 최소화
| 2022/06/10 | [Design LRU Cache](https://bumgeunsong.notion.site/Design-LRU-Cache-f16335a50ea746529c3ed41b6cdc32a2) | 🥈 | Doubly linked list 삽입, 삭제.</br>캐시 삭제시 Dictionary 조작.</br>Dummy node를 이용한 삽입 삭제 오퍼레이션 단순화
| 2022/06/08 | [Kth Smallest Element in a BST](https://bumgeunsong.notion.site/Kth-Smallest-Element-in-a-BST-9485d24694464972a657674feadfba81) | 🥇 | Stack을 사용한 DFS 중간 멈춤 구현, nodeCount를 통한 선택 범위 축소
| 2022/06/07 | [Binary Tree from Preorder and Inorder Traversal](https://bumgeunsong.notion.site/Construct-Binary-Tree-from-Preorder-and-Inorder-Traversal-442cfbe1156241aba8bd0ee71d074f32) | 🥇 | Preorder에서는 맨 앞이 루트 값, Postorder에서는 맨 뒤가 루트값, Inorder에서는 루트를 제외한 왼쪽, 오른쪽이 각 서브트리의 Inorder
| 2022/06/07 | [Zigzag Level Order Traversal](https://bumgeunsong.notion.site/Binary-Tree-Zigzag-Level-Order-Traversal-b69c887bca754341b4e70fc19b059718) | 🥈 | 지그재그로 순회할 때, 각 노드 값의 배열은 뒤집혀야 하지만, 자식 노드를 추가하는 순서는 뒤집히면 안 된다.
| 2022/06/07 | [Inorder Traversal](https://bumgeunsong.notion.site/Binary-Tree-Inorder-Traversal-38ea1dc0783c4b58a7e4ad404299ea3f) | 🥇 | in-order: left 재귀 + 자기 자신 + right 재귀
| 2022/06/06 | [Odd-Even linked list](https://bumgeunsong.notion.site/Odd-Even-Linked-List-d9cd1441fca746f4b340277341a9931c) | 🥈 | `while let`으로 LinkedList에서 tail까지 탐색
| 2022/06/06 | [Add Two Numbers](https://bumgeunsong.notion.site/Add-Two-Numbers-88b3a10102004f498984c66ab3156b2d) | 🥇 | 양쪽이 옵셔널일 때는 switch와 패턴 매칭을 사용해 경우의 수를 나눌 수 있음.
| 2022/06/05 | [REST API: Top Articles](https://bumgeunsong.notion.site/REST-API-Top-Articles-db313221e17248769ac20348aa7556e9) | ❔ | DispatchGorup을 이용한 연속적인 네트워크 요청
| 2022/06/03 | [Increasing Triplet Subsequence](https://bumgeunsong.notion.site/Increasing-Triplet-Subsequence-1a8e81777ce040a8a77003b920ed19c4) | 🥉 | 비교할 최소값이 2개일 때 경우의 수</br>첫번째 최소값을 초기화했을 때 2번째 초기값 유지
| 2022/06/02 | [주차 요금 계산](https://bumgeunsong.notion.site/8e208c02b8214791be4c104b4d210ec7) | 🥇 | dateFormat, round-up 연산
| 2022/06/02 | [파일명 정렬](https://bumgeunsong.notion.site/a1bbfcadc3514308bd6b2887a1c1f8eb) | 🥇 | Character를 파싱할 때 유용한 isNumber, isLetter 등 
| 2022/06/01 | [Longest Palindromic Substring](https://bumgeunsong.notion.site/Longest-Palindromic-Substring-9a2f53ef0de7467db6e5f68559b46fd3) | 🥉 | Substring이지만 Sliding window가 되지 않는 조건</br>Dynamic Programming을 이용한 회문 체크</br>대각선 방향 루프 돌기
| 2022/05/31 | [Longest Substring Without Repeating](https://bumgeunsong.notion.site/Longest-Substring-Without-Repeating-Characters-b61a6fc96ad24722a64c40279f6562f5) | 🥇 | 연속적인 부분배열과 Summary 기준이 있을 때 </br>-> Sliding window 기법
| 2022/05/30 | [Simple Text Editor](https://bumgeunsong.notion.site/Simple-Text-Editor-2397d9adfee84bc498df7077abdb3fab) | 🥈 | Undo stack 구현</br>Swift의 string.index 접근은 O(n)
| 2022/05/29 | [Recursive Digit Sum](https://bumgeunsong.notion.site/Recursive-Digit-Sum-acaef583654e49938dd6eca9ab5a45cf) | 🥇 | n의 전체 자릿수를 하나씩 더한 합을 Sum(n)이라고 할 때, Sum(n*k)는 Sum(n) * k다. 
| 2022/05/28 | [New Year Chaos](https://bumgeunsong.notion.site/Grid-Challenge-5ef122ab0b86442ab5e8f935d924d180) | ❌ | 미해결
| 2022/05/28 | [Grid Challenge](https://bumgeunsong.notion.site/Grid-Challenge-5ef122ab0b86442ab5e8f935d924d180) | 🥇 | 입력 크기에 따라 허용가능한 시간복잡도

유니온파인드
-----

[1] 유니온 파인드는 크로스컷 알고리즘을 할때 쓴다.

- 상호 배타적 집합(disjoint-set) 이라고도한다
- 2가지 연산으로 이루어져있다
1. find : x가 어떤 집합에 포함되어 있는지 찾는 연ㅅ나
2. Union : x와 y가 포함되어 있는 집합을 합치는연산.
- 구현은 간단한 트리를 이용해서 한다
- parent[i] 에는 i의 부모가 저장됨


[2] 가장 처음에는 parent[i] = i 로 초기화한다.

i       1 2 3 4 5 6 7 8 
p[i]    1 2 3 4 5 6 7 8


---------------
1717
2606
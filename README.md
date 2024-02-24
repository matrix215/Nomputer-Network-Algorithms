# 컴퓨터 네트워크에서 사용되는 최단 경로 알고리즘을 설계

동적 라우팅 프로토콜에서, 목적지까지 최적경로를 산출하여 라우팅 테이블을 유지, 관리하기 위해 사용되는 알고리즘을 라우팅 알고리즘이라고 함.

라우팅 정보를 취하는 범위에 따라 두가지로 분류 가능함.

### 분산 라우팅 알고리즘
- 이웃 노드와 정보를 교환하여 반복적이고 분산된 방식으로 수행.
- 거리 벡터 알고리즘 (Bellman-Ford)
 

### 글로벌 라우팅 알고리즘
- 네트워크 전체에 대한 완벽한 정보가 필요.
- 링크 상태 알고리즘 (Dijkstra)
# DataStructure_2025

2025년 부산대학교 자료구조 (조환규 교수님) 과제와 연습 코드 모음. 모든 코드는 C++.

## 구조

| 폴더 | 내용 |
|---|---|
| [`assignments/`](assignments) | 정규 과제 15문제 (callseq, coin, complexity, disk, flip, gaduri, lab, mafia, mall, recruit, robocop, twocops, vaccine, waiting, yard) |
| [`practice/`](practice) | 수업 연습·추가 문제 (DeliveryRobot BFS 3가지 버전, Deep-Map 다중 map, Giftcode, bts, party, quad, troute, 주석 버전 mafia) |
| [`tools/`](tools) | `splay_tree_visualizer.cpp`: Splay tree 회전 과정을 ASCII로 시각화 |
| [`exam/`](exam) | [기말고사 개념정리](exam/기말고사_개념정리.md), [기말고사 풀이](exam/기말고사_풀이.md) |

## 빌드

```sh
g++ -std=c++17 -O2 assignments/mafia.cpp -o mafia && ./mafia < input.txt
```

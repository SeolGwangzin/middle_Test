# 프로젝트 소개
- 검을 강화하는 간단한 게임

# 필요한 객체
- 대장장이, 검

# 프로젝트 요구사항 
1. 대장장이는 검을 강화할 수 있다.
2. 검의 강화는 90% 확률로 성공한다.
3. 강화를 성공할 수록 성공할 확률이 10% 줄어든다.
4. 강화는 0강 부터 시작하며, 강화를 성공할수록 1강, 2강 씩 검 등급이 올라간다.
5. 5강 검을 만들면 성공하며 축하메세지와 함께 게임이 종료된다.
6. 강화를 실패할시 검은 부서지게 되며 0강부터 다시 시작한다.
7. -----------------추가로 해보고싶을시에 추가해보자----------------------
8.  //대장장이는 검을 판매할 수 있다. 판매시 1강부터 10원으로 시작하며, 1강이 성공할 때 마다 10원씩 증가한다.
9.  //대장장이는 검을 구매할 수 있다. 1강 검부터 40원으로 살 수 있으며, 1강이 올라갈 때마다 40원씩 증가한다.
10. //검을 구입시 최대 5강 검까지만 구입가능하다.
11. //검 구입, 판매 구현시는 7강검까지 성공해야 게임을 클리어한것으로 한다.

# 상호작용
- 대장장이가 수신할 수 있는 메세지
1. 검을 강화하라
2. //검을 구입하라
3. //검을 판매하라
- 검이 수신할 수 있는 메세지
1. 강화되어라
2. //구매되어라
3. //팔려라

[커뮤니케이션 다이어그램]  (https://whimsical.com/PnCUktCi6iVVuWRX6BfB1g)
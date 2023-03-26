# 과제
 
1.git의 명령어 add, commit, push는 각각 어떤 역할을 하는지 정리하고,
git pull과 fetch의 차이점을 정리하시오. 

add : 작업 디렉토리 상의 변경 내용을 스테이징 영역에 추가
commit : 변경된 내용 저장
push : 원격 저장소에 코드 변경분을 업로드

git pull과 fetch의 차이점 : fetch는 원격 저장소에 변경사항이 있는지만 확인, pull은 확인하고 로컬 git에 가져옴

2.지난 주와 이번주 학습 내용을 정리하고 WIL을 작성하여 제출한다.

1. 리소스 : 홍익대학교 정보
2. URL : www.hongik.kr – Location
3. 서버와 리소스
4. 리소스 : HTML, CSS, JS
5. GIT : 파일의 변경 사항을 추적 작업 조율, 소스코드 변화 조절
6. 리누스
7. 깃 : 코드의 멀티버스, 코드의 수많은 분기, 버전, 가지(브랜치) / 분기 나누기/ 분기 합치기/ 변화 추적(버전 관리)/ 특정 시점으로 되돌리기
8. < 동작방식 >
9. 파일의 4가지 상태 – 추적X, 변경X, 변경O, staged
10. 추적X 제외 항시 추적
11. Untracted, unmodified, modified, staged
12. Working directory(작업공간), staging area, local repository
13. 코드 –> add –> staging area –> commit –> local repository(깃에서 관리하는 저장소, 코드기록)
14. Staging 왜 있지? 코드 여러 개 만들지만 여러 번 고치니까 최종 코드만 저장하기 위해 한번 흐름을 끊어가는 곳(만들었지만 안쓰는 코드들 쌓아놓음)
15. 가상의 공간에 코드들 쌓아놓기(최종 코드 만드는 데 쓰였던 애들이라 기록해놓음)
16. add에서는 막 쌓아놓기, commit은 기록해놓기
17. < 협업 >
18. Local – 방구석 저장소(나만 볼 수 있음, 내 컴퓨터 안에서만)
19. Working directory, staging area, local – 다 내 컴퓨터 안
20. < 서버 >
21. Remote repository – 공유가능 – github
22. 내 컴퓨터 -> push -> remote repository
23. Fetch(기능확인), pull(내 working directory에 넣기)
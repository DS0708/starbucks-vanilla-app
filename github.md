# 새로운 branch 만들기

1. git branch 로 확인
2. git branch signin 으로 signin이라는 branch생성
3. git checkout signin 으로 branch전환

# 새로운 branch 작성 후 merge 하기
1. git push origin signin
2. github홈페이지에서 PullRequests클릭
3. New pull request 클릭
4. Compare changes페이지로 정상적으로 넘어간 후 base:main <- compare:signin 설정
5. Able to merge 확인
6. Create pull request클릭
7. 메세지 적지 않고 한번 더 Create pull request클릭
8. Merge pull request 클릭
9. Confirm merge 클릭
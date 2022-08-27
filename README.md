# studier
스터디 관리를 위한 웹 프로젝트

- [ ] 요구 사항 정리
- [ ] 화면 설계

### 기술 스택
- Spring Boot
- JPA
- MySQL

### Commit Convention
```
feat : 새로운 기능에 대한 커밋
fix : build 빌드 관련 파일 수정에 대한 커밋
build : 빌드 관련 파일 수정에 대한 커밋
chore : 그 외 자잘한 수정에 대한 커밋(rlxk qusrud)
ci : CI 관련 설정 수정에 대한 커밋
docs : 문서 수정에 대한 커밋
style : 코드 스타일 혹은 포맷 등에 관한 커밋
refactor : 코드 리팩토링에 대한 커밋
test : 테스트 코드 수정에 대한 커밋
```
참고: https://xtring-dev.tistory.com/entry/Git-규칙적인-Commit-메세지로-개발팀-협업하기-👾

### Branch Convention
```
master : 제품으로 출시될 수 있는 브랜치, 배포 Release(Prod) 버전의 소스가 들어있는 branch.
develop : 다음 출시 버전을 개발하는 브랜치, 개발버전의 소스가 들어있는 branch
feature : 기능을 개발하는 브랜치
release : 이번 출시 버전을 준비하는 브랜치
hotfix : 출시 버전에서 발생한 버그를 수정 하는 브랜치, Master branch의 오류사항을 수정하는 branch

Feature > Develop > Master의 병합 순이 아니라 Master에서 급하게 수정해야하는 경우에 사용한다. 
Master에서 직접 branch를 분기하여 생성하며 수정 후 Develop가 아닌 Master에 병합하여 배포한다.
```
참고: https://iamcho2.github.io/2021/03/22/branch-rule-git-flow

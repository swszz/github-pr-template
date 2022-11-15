# github-pr-template

## 작성 순서
1. **Pull Request Checklist**를 작성한다.
2. **Pull Request Type**을 작성한다.
3. **작업 내용**을 작성한다.
4. **작업 진행 이유**를 작성한다.
5. **리뷰어가 꼭 확인해야 하는 커밋**을 작성한다.


## CODEOWNERS
코드의 소유자를 의미한다.  
해당 파일에 @nickname을 작성하면 Pull Request가 생성될 때마다 자동으로 Reviewer로 등록된다.

## 참고
아래 작업을 수행해야 자동으로 Reviewr로 등록된다.

1. Settings - Branches - Branch protection rules 접속  
2. check Require a pull request before merging  
3. check Require review from Code Owners   
4. (Optional) Branch name pattern을 *로 설정
    - 필요할 경우 특정 패턴을 입력해도 무방

### ineeji-api-references 사용 가이드
> Author : Mira Jo(mira@ineeji.com)

This repository is used to commit the API specifications shared between frontend and backend developers. It's synchornized with Apiary, which is a service that supports API blueprint and Swagger(*2.0* in yaml) specification for describing APIs.

이 저장소는 현재 EEJI의 API 디자인 문서를 프론트/백엔드에서 손쉽게 수정, 배포하고 공유하기 위한 목적으로 생성되었습니다. 이 저장소의 main branch는 Apiary라는 서비스와 동기화 되어있으며, Api 문서를 자동화하고 시각화하기 위한 OpenAPI Swagger 2.0 스펙을 따릅니다.


### Important 
If a change is made on GitHub that results in an invalid API Description file, those changes will not be pulled down to Apiary. If a change cannot be pulled to Apiary due to the API Description file being invalid, a comment will be added to the commit in GitHub. 

깃허브 저장소에 있는 API 문서에 에러가 있는 경우 Apiary에서 당겨지지 않으며, 그 반대의 경우도 (Apiary web을 통해 작성/수정한 문서에 오류가 있는 경우) github로 push할 수 없습니다.

참고 : <https://help.apiary.io/tools/github-integration/#pulling-from-github>

### Trouble shooting

If the changes are not deployed on the web after merging, please check for any grammatical errors in your codes. You can simply copy and paste the code into the Apiary editor, and it'll help identify any issues.

깃허브에 코드 병합을 성공적으로 완료했음에도 Apiary에 반영이 되지 않으면 yaml파일에 오류가 있을 가능성이 높습니다. Apiary editor에 해당 코드를 직접 붙여넣으면 해당 내용을 쉽게 확인하실 수 있으니 확인 후 수정/저장하세요.


### Deploy 
Update the contents of swagger.yaml with the new version. The changes will be automatically reflected at <https://eeji.docs.apiary.io/>

오류가 없는 갱신된 파일은 자동으로 <https://eeji.docs.apiary.io/> 게시됩니다. swagger.yaml 파일의 내용을 수정하고 새로운 버전으로 배포하세요.


### Github Sync 

This repositoriy is synchronized with Apiary. You can push changes from Github or Apiary but it's still recommended to commit from the github side to ensure code review.

양방향 동기화가 되어 있어 어느 곳에서든 수정 사항을 커밋할 수 있습니다만 코드 리뷰를 위해 되도록 github 에서 커밋하는 것을 권장드립니다.

참고 : <https://help.apiary.io/tools/github-sync/>

### Github Integration  
Please refer to the link below for information about Github integration.
참고 : <https://help.apiary.io/tools/github-integration/>



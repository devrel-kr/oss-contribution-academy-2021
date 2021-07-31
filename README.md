# OSS 컨트리뷰션 아카데미 2021 #

OpenUP 주관 OSS 컨트리뷰션 아카데미 2021 행사를 위한 관리용 리포지토리


## 시작하기 ##

필요한 깃헙 액션 워크플로우 파일을 원하는 리포지토리에 복사해서 쓰세요.


## 필요한 시크릿 값들 ##

* `OCA_PARTICIPANTS`: 프로젝트 참여 멘티 깃헙 ID &ndash; 각 줄마다 ID 하나씩, 줄바꿈은 shift-enter 이용
* `OCA_SLACK_CHANNEL`: 슬랙 채널 이름 (예: `#oss-azfunc`)
* `OCA_SLACK_WEBHOOK_URL`: 슬랙 웹훅 URL
* `OCA_SLACK_WEBHOOK_ICON_URL`: 슬랙 웹훅용 아이콘 URL


## 자동화 깃헙 액션: 슬랙 메시지 보내기 ##

* `oca-slack-pr-created.yaml`: PR 생성시 자동 실행
* `oca-slack-pr-updated.yaml`: PR 수정시 자동 실행
* `oca-slack-issue-opened.yaml`: 이슈 생성시 자동 실행
* `oca-slack-issue-reopened.yaml`: 이슈 재오픈시 자동 실행


## 자동화 깃헙 액션: Microsoft 팀즈 메시지 보내기 ##

TBD

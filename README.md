✅ 커밋 메시지 컨벤션
모든 커밋 메시지는 아래 규칙을 따릅니다:

php-template
복사
편집
<태그> : 변경 요약 메시지
커밋 태그 종류
태그	설명
Feat	새로운 기능 추가
Fix	버그 수정
Env	개발 환경 설정 변경 (예: .env, .gitignore, 빌드 도구 등)
Style	코드 스타일 수정 (세미콜론, 들여쓰기 등 비기능적 변경)
Refactor	코드 리팩토링 (기능 변화 없이 구조 개선)
Design	CSS 등 디자인 관련 수정/추가
Comment	주석 추가 또는 수정
Docs	README 등 문서 작성 및 수정
Test	테스트 코드 추가 또는 수정
Chore	빌드 관련 작업 또는 기타 사소한 변경
Rename	파일 또는 폴더명 변경
Remove	파일 또는 리소스 삭제

예시
yaml
복사
편집
Feat : 캠프파이어 씬 UI 구성
Fix : 요리 씬에서 아이템 드래그 안되는 버그 수정
Docs : 프로젝트 구조 설명 추가
🌿 브랜치 전략
모든 기능 개발은 dev 브랜치를 기준으로 개별 기능 브랜치에서 진행됩니다.

브랜치 네이밍 규칙
php-template
복사
편집
feature/<SceneName>
사용 중인 기능 브랜치 목록
feature/PackingScene

feature/CookScene

feature/CampfireScene

feature/CleanScene

작업 완료 후에는 각 브랜치를 dev에 병합합니다.

📁 개인 폴더 구조
각 팀원은 자신만의 폴더를 프로젝트 루트에 생성하여 스크립트 및 리소스를 정리합니다.

예시 구조
bash
복사
편집
project-root/
├─ dev/
│  ├─ feature/...
├─ MemberA/
│  ├─ scripts/
│  └─ assets/
├─ MemberB/
│  └─ ...

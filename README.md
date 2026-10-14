# 우리의 날들

두 아이폰을 위한 개인용 커플 캘린더 PWA.

**[아이폰에서 앱 열기](https://sumin-jeong-sl.github.io/our-days-calendar/)**

Safari에서 열기 → 공유 → 홈 화면에 추가. 설치한 아이콘을 열어 처음 정보를 입력합니다. 회사 컴퓨터나 노트북이 켜져 있을 필요가 없습니다.

일정은 각 기기의 IndexedDB에 저장하며 오프라인 조회·작성, 반복 일정, 기념일, JSON 백업·복원을 지원합니다. 두 사람 연결과 공유는 암호화 파일 수동 교환입니다. 자동 서버 동기화는 포함하지 않습니다. 첫 사용자가 공간과 공유 파일을 만들고 상대방은 첫 화면의 ‘파일로 연결·복원’을 이용합니다.

무료 GitHub Pages 공개 저장소로 앱 코드를 서비스합니다. 결제 수단 등록 없이 배포했습니다. 개인 일정과 백업을 이 저장소에 올리지 마세요. 장기 보관을 위해 앱 설정에서 전체 백업을 파일 앱/iCloud Drive에 따로 저장하세요.

## 집에서 개발 이어가기

[개발 프로젝트 ZIP 다운로드](https://sumin-jeong-sl.github.io/our-days-calendar/couple-calendar-source.zip). 압축을 풀고 안의 `couple-calendar/README.md`를 읽으세요. Node.js 22.12 이상에서 `start-at-home.cmd` 또는 README 명령으로 실행합니다. npm을 사용할 수 있으며 검증한 버전은 pnpm 잠금 파일에 있습니다.

현재 저장소 루트는 **이미 빌드된 앱 파일**입니다. 여기서 npm install을 실행하는 구조가 아닙니다. 소스 ZIP에서 개발하고 테스트·빌드한 뒤 `dist/` 내용을 이 저장소의 같은 폴더 구조로 올립니다. Pages 설정: Deploy from a branch → main → /(root).

## 검증 기록

2026-10-14: 단위 테스트 17개, 병합 테스트 9개, TypeScript·Vite·PWA 빌드 성공. 로컬과 공개 배포 주소에서 모바일 Edge 브라우저 테스트 각각 1개 통과: 저장·재실행·오프라인 작성·수정·삭제. 실제 iPhone 설치, 재부팅, 장기 미사용 보관은 별도 확인이 필요합니다.

# BibiGPT-v1

## 현재 상태
Bilibili·YouTube 등 학습 콘텐츠를 AI로 요약하는 웹 프로젝트의 포크입니다.

공개 포크이며 원본 서비스 소개와 이 저장소에서 실행 가능한 기능 범위를 구분해야 합니다. 실제 서비스 배포 상태는 확인하지 않았습니다.

문서 등록 기준: 2026-09-24. 기본 브랜치 `main`의 [확인한 버전](https://github.com/sujungwin8-cpu/BibiGPT-v1/commit/93a4094f8f7845ea47d8d429faf288a9a9b00c73)을 기준으로 정리했습니다.

## 주요 기능
README는 영상·음성 콘텐츠 요약과 질의응답을 소개합니다. 홍보 문구의 모든 연동 대상이 이 코드에서 검증되었다고 판단하지 않습니다.

## 실행 방법
package.json 기준 개발 명령은 `npm run dev`, 빌드는 `npm run build`, 서버 시작은 `npm start`입니다. 이번에 설치·빌드·배포를 실행하지 않았습니다.

## 설정과 연결
Next.js, OpenAI 호환 AI 서비스, Upstash 캐시·요청 제한 설정 등이 관련됩니다. 비밀키는 환경 설정에서 관리합니다.

## 변경 위치
`package.json`: 명령과 의존성. `AGENTS.md`: 기존 개발 지침. 기능을 고칠 때 실제 화면·API 파일 경로를 이력에 기록합니다.

이번 변경은 `docs/notion/`, 노션 게시 워크플로와 작업 안내뿐입니다.

## 남은 작업
필수 환경 설정, 이 포크의 사용자 수정 범위, 콘텐츠별 실제 요약 결과를 확인해야 합니다.

## 확인 근거
- [README.md](https://github.com/sujungwin8-cpu/BibiGPT-v1/blob/93a4094f8f7845ea47d8d429faf288a9a9b00c73/README.md)
- [package.json](https://github.com/sujungwin8-cpu/BibiGPT-v1/blob/93a4094f8f7845ea47d8d429faf288a9a9b00c73/package.json)
- [AGENTS.md](https://github.com/sujungwin8-cpu/BibiGPT-v1/blob/93a4094f8f7845ea47d8d429faf288a9a9b00c73/AGENTS.md)

이번 확인은 저장소 문서·파일 구성 확인입니다. 앱 실행, 테스트, 장치 제어 또는 서비스 배포 성공을 새로 확인한 기록은 없습니다.


## 사용설명서
이 게시물의 ‘사용설명서 · 펼쳐서 읽기’에서 시작 방법과 상세 자료를 읽을 수 있습니다.

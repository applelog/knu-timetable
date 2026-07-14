# 📅 강남대학교 시간표 마법사 (KNU Timetable Wizard)

강남대학교 수강 신청을 위한 실시간 시간표 조합 생성기 및 시뮬레이터입니다.

## ✨ 주요 기능 (Key Features)

- **📋 요람 정보 자동 파싱**: 요람 PDF 파일에서 수강 정보를 한 줄씩 복사해서 붙여넣기만 하면 교과목 코드, 과목명, 학점, 강의실, 교수명, 시간대를 스마트하게 자동 파싱합니다.
- **⚡ 실시간 시간표 자동 조합 생성**: 과목별로 원하는 분반 옵션을 선택한 뒤, 대기 시간/등교일/시간대 조건에 맞는 모든 충돌 없는 시간표 조합을 0.01초 내에 자동으로 생성합니다.
- **🔄 자동 낮/밤(Light/Dark) 테마**: 현지 시간에 맞춰 밤 6시부터 아침 7시 사이에는 자동으로 다크 모드로 변환되며, 시스템 모드 또는 수동 설정도 지원합니다.
- **🔒 개인정보 보호**: 모든 예시 데이터는 가상 명칭(홍길동, 김철수 등)으로 안전하게 작동하며, 작성한 시간표는 로컬 파일(JSON)로 직접 보관 가능하여 서버로 어떠한 개인정보도 전송되지 않습니다.
- **💡 공강 조건 상세 필터링**: 우주공강 보장, 1교시 피하기, 야간 수업 제외, 금공강 보장, 점심시간 보장 등의 세부 필터링 조건을 제공합니다.

## 🚀 시작하기 (Getting Started)

### 로컬 실행 방법

1. 저장소를 클론합니다:
   ```bash
   git clone https://github.com/[YOUR_USERNAME]/[YOUR_REPOSITORY].git
   cd [YOUR_REPOSITORY]
   ```

2. 패키지를 설치합니다:
   ```bash
   npm install
   ```

3. 로컬 개발 서버를 실행합니다:
   ```bash
   npm run dev
   ```

## 🛠️ 기술 스택 (Tech Stack)

- **Frontend**: React (TypeScript), Vite
- **Styling**: Custom CSS (Vanilla CSS Variables / HSL color system)
- **CI/CD**: GitHub Actions (Automatic deployment to GitHub Pages)

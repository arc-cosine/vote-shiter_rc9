# Vote Shiter (極秘)

<p align="center">
  <img src="https://img.shields.io/badge/Project-要雅小非-blueviolet" />
  <img src="https://img.shields.io/badge/Status-Secret-black" />
  <img src="https://img.shields.io/badge/Creator-린@RC9-lightgrey" />
</p>

## ⚠️ 경고

> 이 프로젝트는 **모의 해킹**, **보안 교육**, **자동화 연습**을 목적으로 만들어졌습니다.  
> 실 서비스에 대한 **무단 사용, 악용은 금지**되어 있으며, 모든 책임은 사용자 본인에게 있습니다.  

---

## 📝 개요

`Vote Shiter`는 구글 폼(Google Forms)에 자동으로 값을 입력하고 제출하는 클라이언트 기반의 **표 자동 제출기**입니다.  
양식을 여러 번 자동 제출하거나, 특정 이름을 무작위로 골라 넣는 등의 기능을 포함합니다.

---

## 🎯 주요 기능

- Google Forms용 자동 제출기 (Form Flooder)
- 이름 리스트에서 무작위 선택 가능 (값에 `랜덤` 입력 시 작동)
- 간격(ms) 조절 기능 (1ms~5000ms)
- 실시간 제출 카운터
- 모달 방식 설명서 UI
- 기본값 항목 2개 포함 (`entry.xxx`, 값 입력 가능)

---

## 🛠 사용 방법

1. 이 HTML 파일을 브라우저에서 엽니다.
2. 상단의 **폼 URL**에 대상 Google Form의 `formResponse` URL을 붙여넣습니다.
3. 아래 `+ 항목 추가` 버튼으로 `entry.xxxxxxxx` 값을 입력하고, 값에는 직접 입력하거나 `랜덤`으로 지정합니다.
4. `시작` 버튼 클릭 시 폼 제출 시작.
5. `중지` 버튼을 누르면 제출이 중단됩니다.

---

## 🔍 entry 번호 알아내는 법

- Google Forms 페이지의 `미리보기` 모드에서 `F12 개발자 도구` 열기
- 원하는 항목에 값을 입력하고 제출
- `Network` 탭에서 `formResponse` 확인 → `entry.xxxxxxxx` 값 추출

---

## 💡 팁

- `랜덤` 키워드는 내부 이름 리스트에서 무작위로 선택합니다.
- 1ms는 빠르지만 실패율이 존재 (정확한 제출 수는 대략 3으로 나눠야 함)
- 1000ms 간격은 안정적으로 제출 가능

---

## 📄 예시 결과

- [표 결과 Google Sheet](https://docs.google.com/spreadsheets/d/14HMVdifdGc_E88iE7SaLwiGPydubHhVP0vfca_LjQpI/edit?usp=sharing)

---

## 🧪 제작 정보

- 프로젝트명: Vote Shiter
- 제작자: 린@RC9 Studio
- 프로젝트 코드명: `要雅小非`
- 타입: 내부 프로젝트, 비공개 극비자료(極秘)
- 라이선스: 없음 (비공개 연구용)

---

## 📛 면책 조항

> 이 코드는 교육, 연습, 시뮬레이션 목적이며 모든 사용은 사용자 책임입니다.  
> 실제 서비스에 피해를 주는 행위는 법적 책임이 따를 수 있습니다.  
> **악용 금지.**

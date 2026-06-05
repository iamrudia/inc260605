# 광탄중학교 챗봇 프렌 🤖

광탄중학교를 위한 AI 챗봇 서비스 "프렌(Fren)"입니다.  
학생들이 학교 생활에서 필요한 정보를 언제든지 편하게 얻을 수 있도록 설계되었습니다.

> 인천교육청 AI 융합교육원에서 Copilot Studio를 활용한 프로젝트입니다.

---

## ✨ 주요 특징

- **친근한 디자인**: 파스텔 톤의 산뜻한 색상 팔레트로 학생 친화적 인터페이스 제공
- **쉬운 상호작용**: 자연스러운 대화형 인터페이스로 누구나 쉽게 사용 가능
- **반응형 웹**: 모바일부터 데스크톱까지 모든 기기에 최적화
- **Microsoft Copilot Studio 기반**: 강력한 AI 엔진으로 정확한 답변 제공

---

## 🎨 UI/UX 디자인

### 색상 팔레트 (파스텔톤)
- **민트**: #C5EDE0 - 주요 강조색
- **스카이**: #C7E6F5 - 헤더 그라데이션
- **복숭아**: #FCE0CE - 사용자 메시지
- **라벤더**: #E5D8F4 - 보조 색상
- **배경**: #F2FAFB - 산뜻한 배경

### 컴포넌트
- **헤더**: 파스텔 그라데이션 배경과 챗봇 아바타
- **메시지 말풍선**: 
  - 봇 메시지 (파스텔 민트)
  - 사용자 메시지 (파스텔 복숭아)
- **입력창**: 부드러운 색상의 전송 버튼
- **추천 질문 버튼**: 파스텔 하늘 색상

---

## 🔧 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: 반응형 디자인, 그라데이션, Flex 레이아웃
- **JavaScript**: 비동기 통신 (async/await)
- **Font**: Google Fonts (Gowun Dodum, Jua) - 둥글고 산뜻한 한글 폰트
- **Bot Framework**: Microsoft Bot Framework Web Chat (CDN)
- **API**: Power Platform DirectLine API

---

## 🚀 사용 방법

### 준비물
1. Microsoft Copilot Studio에서 생성한 챗봇
2. 토큰 엔드포인트 URL
3. 웹 호스팅 환경

### 설정

`index.html` 파일의 다음 부분을 수정하여 사용합니다:

```javascript
const tokenEndpoint = "https://default62ae463a9f124edf85444f6ca38345.24.environment.api.powerplatform.com/powervirtualagents/botsbyschema/copilots_header_2afd5/directline/token?api-version=2024-03-01";

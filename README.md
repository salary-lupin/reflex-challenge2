# Reaction Challenge 2 🚀

[![Deploy to GitHub Pages](https://github.com/salary-lupin/reflex-challenge2/actions/workflows/deploy.yml/badge.svg)](https://github.com/salary-lupin/reflex-challenge2/actions/workflows/deploy.yml)

**Reaction Challenge 2**는 한계를 시험하는 극한의 순발력 미니게임입니다. 단계별로 진화하는 난이도와 전략적인 보너스 스테이지를 통해 글로벌 랭킹 TOP 10에 도전하세요!

## 🎮 게임 주요 특징

### 1. 단계별 성장형 난이도
- **총 21개 이상의 레벨**: 각 레벨마다 타겟 개수, 꽝(폭탄) 개수, 이동 속도가 달라집니다.
- **특수 기믹**: 
  - **순간이동(Teleport)**: 특정 레벨에서는 버튼이 애니메이션 없이 즉시 위치를 이동합니다.
  - **가변 이동 속도**: 레벨이 올라갈수록 버튼의 반응 속도가 극한으로 빨라집니다.
- **최종장**: 21단계(실제 23단계)는 극한의 속도와 수많은 꽝 버튼을 뚫어야 하는 지옥의 난이도를 자랑합니다.

### 2. 전략적 보너스 스테이지
- **보너스 스테이지 1 (L13 클리어 후)**: 5초간 멈춰있는 100개의 타겟을 최대한 많이 클릭하여 점수를 확보하세요.
- **보너스 스테이지 2 (L20 클리어 후)**: 5초간 느리게 움직이는 타겟과 꽝 버튼 사이에서 점수를 쓸어담으세요.

### 3. 고도화된 점수 및 랭킹 시스템
- **시간별 차등 보너스**:
  - 3초 이내: **x2.0**
  - 5초 이내: **x1.5**
  - 10초 이내: **x1.0**
  - 10초 이상: **x0.5**
- **글ローバル TOP 10**: 랭킹 진입 시 자신만의 25자 한 줄 코멘트를 남길 수 있습니다.

### 4. 테스트 모드 (Debug Mode)
- `index_test.html`을 통해 원하는 특정 레벨을 즉시 테스트하고 난이도를 체감해 볼 수 있습니다.

## 🛠 기술 스택
- **Core**: HTML5, CSS3 (Vanilla), Vanilla JavaScript
- **Database**: Firebase Realtime Database (랭킹 저장 및 실시간 동기화)
- **Deployment**: GitHub Actions & Pages

## 🚀 시작하기
1. 이 저장소를 클론합니다.
2. `config.js` 파일을 생성하고 본인의 Firebase SDK 설정을 입력합니다.
   ```javascript
   const firebaseConfig = {
     apiKey: "...",
     authDomain: "...",
     databaseURL: "...",
     projectId: "...",
     storageBucket: "...",
     messagingSenderId: "...",
     appId: "..."
   };
   ```
3. `index.html`을 브라우저에서 실행하여 게임을 즐기거나, `index_test.html`로 난이도를 테스트하세요.

## 📝 라이선스
MIT License

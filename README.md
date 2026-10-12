# 🍉 드롭 머지 퍼즐 | Drop Merge Puzzle

> 수박게임류 과일 합성 — 11단계 진화·콤보  
> Suika-style fruit merge with 11 evolution stages

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen?style=flat-square)](https://metasongi.github.io/drop-merge-puzzle/) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square)

🌐 **Live:** https://metasongi.github.io/drop-merge-puzzle/

---

수박게임류 머지 퍼즐! 위에서 과일을 떨어뜨려 같은 과일끼리 합성하고,
체리부터 시작해 **수박**까지 11단계 진화를 노려보세요.

## 🎮 플레이 방법

1. 화면을 **터치/클릭**하면 그 위치에서 과일이 떨어져요 (PC: 마우스 이동으로 조준, ←/→ 키 이동, 스페이스바 낙하도 가능)
2. 같은 과일 2개가 닿으면 한 단계 큰 과일로 **합성**됩니다
   - 체리 → 딸기 → 포도 → 귤 → 오렌지 → 사과 → 배 → 복숭아 → 파인애플 → 멜론 → 수박
   - 수박 2개를 합성하면 보너스 점수 후 소멸!
3. 상단의 **빨간 경고선**을 넘은 과일이 3초 버티면 게임 오버
4. 연속 합성으로 **콤보 보너스**를 노려보세요 🔥

## ✨ 특징

- 외부 라이브러리 없이 직접 구현한 중력·충돌 물리 (순수 Canvas + 바닐라 JS)
- 합성 파티클 이펙트, 점수 팝업, 콤보 표시
- 다음 과일 미리보기 (하위 5단계 중 랜덤)
- 최고 기록 저장 (localStorage)
- 모바일 터치 + PC 마우스/키보드 지원, 반응형

## 🚀 실행

`index.html`을 브라우저에서 열거나 GitHub Pages로 배포하면 바로 플레이할 수 있습니다.
외부 의존성(CDN)이 전혀 없어 오프라인에서도 동작합니다.

---

## English Summary

Suika-style fruit merge with 11 evolution stages.

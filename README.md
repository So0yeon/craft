# 🏡 Math Craft — 분수 마을 만들기

분수의 덧셈과 뺄셈을 풀어 코인을 모으고, 나만의 3D 마을을 짓는 초등 교육 게임입니다.

- 🧮 **8유형 × 5난이도** 분수 문제 500개 자동 생성 (적응형 난이도)
- 🧱 **38종 블록** 건축: 설치 / 제거 / 교체 / 범위 채우기 / 되돌리기
- 🌗 낮밤 사이클, 구름, 새, 잔디 흔들림 — 로우폴리 파스텔 그래픽
- 🏆 레벨·칭호·업적·마을 가치 점수
- 💾 LocalStorage 자동 저장 (서버·회원가입 없음, 오프라인 동작)

## 기술 스택
React 18 · Three.js (r128) · Vite 5 · TailwindCSS 3

## 로컬 실행
```bash
npm install
npm run dev        # http://localhost:5173
```

## 프로덕션 빌드
```bash
npm run build      # dist/ 폴더 생성
npm run preview    # 빌드 결과 미리보기
```

## GitHub에 올리기
```bash
git init
git add .
git commit -m "Math Craft v1.0"
git branch -M main
git remote add origin https://github.com/<내아이디>/math-craft.git
git push -u origin main
```

## Vercel 배포 (1분 컷)
1. https://vercel.com → **Add New → Project**
2. 방금 올린 GitHub 저장소 **Import**
3. Framework Preset이 **Vite**로 자동 인식됨 (Build: `npm run build`, Output: `dist`)
4. **Deploy** 클릭 — 끝!

> CLI를 쓴다면: `npm i -g vercel && vercel` 한 줄로도 배포됩니다.

## 조작법
| 동작 | 데스크톱 | 터치 |
|---|---|---|
| 카메라 회전 | 드래그 | 한 손가락 드래그 |
| 확대/축소 | 마우스 휠 | 두 손가락 핀치 |
| 블록 설치/제거 | 클릭 (모드 선택) | 탭 / 길게 누르기(제거) |
| 되돌리기 | Ctrl+Z / Ctrl+Shift+Z | 핫바 ↩️ ↪️ |
| 화면 이동 | WASD / 방향키 | 두 손가락 드래그 |

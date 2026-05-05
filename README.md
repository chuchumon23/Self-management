# Self-management
해당 자기관리 어플은 나의 상태에 대해서 객관적인 수치로 볼 수 있도록 도우며, AI를 통해서 진단받을 수 있음.


자기관리 시스템 PWA
배포 방법 (GitHub Pages)
1. 아이콘 준비
icon-192.png, icon-512.png 두 파일이 필요합니다.
직접 만들거나 아래 사이트에서 생성:
https://favicon.io/favicon-generator/
2. GitHub 배포
```
git init
git add .
git commit -m "init: self-management PWA"
git remote add origin https://github.com/유저명/레포명.git
git push -u origin main
```
3. GitHub Pages 설정
Settings → Pages → Branch: main / (root) → Save
4. 주소 확인
https://유저명.github.io/레포명
5. 폰에서 설치
iPhone: Safari로 열기 → 공유 → 홈 화면에 추가
Android: Chrome으로 열기 → 메뉴 → 앱 설치
파일 구조
```
├── index.html      ← 앱 본체
├── manifest.json   ← PWA 메타정보
├── sw.js           ← 오프라인 캐시
├── icon-192.png    ← 앱 아이콘 (직접 추가)
└── icon-512.png    ← 앱 아이콘 (직접 추가)
```

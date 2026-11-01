# STRUCTURE · kiriya-sample

```
kiriya-sample/
├─ index.html              단일 파일 (CSS·JS 인라인)
├─ wrangler.toml           name = kiriya-sample → kiriya-sample.lgt3232.workers.dev (Worker 이름도 같게)
├─ .assetsignore           img/ · 문서 · index_*.html · _deploy 배포 제외
├─ kr-mplusround.woff2     일본어 · 영문 제목 (M PLUS Rounded 1c ExtraBold, 쓰는 글자만)
├─ kr-pretendard.woff2     한글 · 본문 (Pretendard 400–700)
├─ kr-logo.webp            크림 원 너구리 로고 (헤더 · 히어로 · 푸터) · favicon.png
├─ kr-hero.webp            히어로 망고 산도
├─ kr-sando-*.webp         산도 5장 (mango · melon · mikan · mix · row)
├─ kr-tart / kr-parfait .webp   エッグタルト 카드
├─ kr-sign / kr-front / kr-night / kr-case .webp   店内
├─ og-kiriya.jpg
├─ img/                    다올 제공 원본 48장 (배포 제외 · 사람 · 타 브랜드 포함, 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서 (모두 크림 카드, 바탕은 밤색 다이아몬드)
헤더(진갈색) → 히어로(아치 카드 + 사진 카드) → `#sando` → `#coffee` → `#tart` → `#kokoro` → `#shop` → `#visit` → 푸터(진갈색) + 모바일 `.quick`.

## 커피 메뉴 수정
`#coffee .menu li` 한 줄 = 메뉴 1개. Signature는 `<span class="sig">Signature</span>`를 li 맨 앞에.

## 폰트 재생성 (일본어 글자 바뀌면 필수)
M PLUS Rounded는 한글을 뺀 글자(일본어 · 영문 · 기호), Pretendard는 전체 글자로 서브셋 · §24 옵션 · §26 누락 검사.

# 🎯 n8n 설치 및 활용방법 가이드

> **공인중개사를 위한 AI 자동화 학습 가이드**
> Windows 환경 Docker + Cloudflare Tunnel 기반 로컬 설치부터 실무 활용까지

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-라이브-success)](https://sachol.github.io/dosiajae-n8n-guide/)
[![제작자](https://img.shields.io/badge/제작-도시아재-E63946)](https://instagram.com/sachol09)
[![라이선스](https://img.shields.io/badge/라이선스-학습용-FFC700)](#-라이선스)

---

## 🚀 라이브 가이드 보기

### 👉 **[https://sachol.github.io/dosiajae-n8n-guide/](https://sachol.github.io/dosiajae-n8n-guide/)**

---

## 📖 가이드 소개

부동산 전문가, 특히 공인중개사가 자기 PC에 n8n을 직접 설치하고 24/7 자동화를 운영할 수 있도록 만든 단계별 학습 가이드입니다. **클래식 바우하우스 디자인**으로 시각적으로 풍부하게 구성되어 있으며, 강의 자료와 자가학습 모두에 사용 가능합니다.

### 🎨 주요 특징

- **5개 탭 구조** — 시작하기, 1편 설치편, 2편 활용편, 명령어 모음, FAQ
- **STEP 0~8 + 부록** — 가상화 확인부터 도메인 연결, 업데이트까지
- **명령어 복사 버튼 63개** — 클릭 한 번으로 클립보드 복사
- **마스터 체크리스트** — 진행률 자동 저장 (브라우저 localStorage)
- **단계별 접고펴기** — 필요한 단계만 펼쳐서 학습
- **반응형 디자인** — PC·태블릿·모바일 모두 최적화
- **인쇄 지원** — PDF 변환 시 자동 펼침
- **단일 HTML 파일** — 외부 의존성 없음, 어디서든 동작

### 📚 가이드 구성

| 탭 | 내용 | 상태 |
|---|---|---|
| 🏠 시작하기 | Make vs n8n 비교, 학습 로드맵, 3가지 설치 방식 | ✅ 완성 |
| ⚙️ 1편 · 설치편 | Docker + Cloudflare 8단계 설치 + 업데이트 부록 | ✅ 완성 |
| 🎯 2편 · 활용편 | 기본기·실전·AI·마케팅·고급 운영 로드맵 20개 | 🚧 로드맵 |
| 📚 명령어 모음 | Docker·docker compose·cloudflared 명령어 레퍼런스 | ✅ 완성 |
| ❓ FAQ | 환경·설치·도메인·운영 트러블슈팅 15개 | ✅ 완성 |

---

## 📦 로컬에서 보기

저장소를 받은 후 `index.html`을 더블클릭하면 브라우저에서 바로 열립니다. 별도 서버 설정이 필요 없습니다.

```bash
# 저장소 클론
git clone https://github.com/sachol/dosiajae-n8n-guide.git

# 폴더 진입 후 index.html 열기
cd dosiajae-n8n-guide
start index.html       # Windows
open index.html        # macOS
xdg-open index.html    # Linux
```

---

## 🔄 업데이트 방법

새 콘텐츠 추가 또는 수정이 필요한 경우:

1. **로컬에서 `index.html` 수정** 또는
2. **GitHub 웹에서 직접 편집** (저장소 → index.html → ✏️ 연필 아이콘)
3. **변경사항 커밋** → GitHub Pages가 자동으로 재배포 (약 1~2분)

업데이트 후 약 1~2분 안에 라이브 URL에 반영됩니다.

---

## 📅 업데이트 로드맵

- [x] **v1.0** — 1편 · 설치편 완성 (2026.05.22)
- [ ] **v1.1** — 2편 · 활용편 A 섹션 (기본기 4개 카드 상세 내용) — *다음 주 예정*
- [ ] **v1.2** — 2편 · 활용편 B 섹션 (공인중개사 실전 자동화)
- [ ] **v1.3** — 2편 · 활용편 C 섹션 (AI 통합)
- [ ] **v2.0** — Episode 03 신규 강의 자료 추가

---

## 🛠 기술 스택

- **순수 HTML/CSS/JS** — 빌드 도구 불필요, 의존성 없음
- **Pretendard** — 한글·영문 통일 디자인
- **Archivo Black** — 영문 디스플레이 폰트
- **JetBrains Mono** — 코드 블록 폰트
- **SVG 다이어그램** — 학습 로드맵, 설치 흐름도, 폴더 구조도, Cloudflare 아키텍처

---

## 📝 참고 자료

본 가이드는 다음 자료를 기반으로 작성되었습니다:

- **[n8n 공식 문서](https://docs.n8n.io/hosting/installation/docker/)** — Docker 설치 권장 방식
- **[Hostinger 튜토리얼](https://www.hostinger.com/tutorials/how-to-self-host-n8n-with-docker)** — Self-host 모범 사례
- **[KDnuggets 가이드](https://www.kdnuggets.com/how-to-self-host-n8n-on-docker-in-5-simple-steps)** — Windows 환경 설치
- **현장 강의 자료** — 2026.05.22 도시아재 RSA 강의

---

## 📮 제작자 정보

| 항목 | 내용 |
|---|---|
| 제작자 | **도시아재** (노제승) |
| 소속 | 신화공인중개사사무소 · 신화법원경매 |
| 직책 | RSA 총동문회 AI 포럼 포럼장 |
| Instagram | [@sachol09](https://instagram.com/sachol09) |

---

## ⚖️ 라이선스

본 자료는 **공인중개사를 위한 학습용**으로 제작되었습니다.

- ✅ 개인 학습·교육 목적 사용 자유
- ✅ 본 자료를 참고한 강의·교육 진행 자유 (출처 표기 권장)
- ❌ **상업적 이용 금지** (재판매, 유료 강의 무단 사용 등)
- ❌ 무단 수정·복제 후 본인 저작물로 재배포 금지

© 2026 도시아재. All rights reserved.

---

## 💡 피드백

가이드 개선 제안이나 오류 신고는 [Issues](https://github.com/sachol/dosiajae-n8n-guide/issues) 탭에 남겨주세요.

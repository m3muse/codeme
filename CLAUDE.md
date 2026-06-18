# CODE ME — 학부모 상담용 웹페이지

## 프로젝트 완료 상태

이 프로젝트는 **완성**됨. 추가 작업 없음.

---

## 사용자 정보

- **이름**: 정유현 선생님
- **누구**: 北京(베이징) 거주 한국인 코딩 선생님 (CODE ME 운영)
- **이력**: 부산대 컴퓨터공학과 + 백제예술대 실용음악과 → 北京演艺专修学院 교수(2005~09) → 北京现代音乐研修学院 학과장(2010~14) → 天津澳丰供应链科技 개발자(2015~20) → 현재 北京 CODE ME 운영
- **연락처**: WeChat `m3muse`, Email `m3muse@gmail.com`
- **주소**: 북경 왕징 기린사 (내고향마트 맞은편 건물)
- **GitHub Pages**: https://m3muse.github.io/codeme/

---

## 작업 목적

학부모 상담용 웹페이지. 위챗으로 GitHub Pages 링크를 공유 → 학부모가 폰/노트북으로 보고 학원 방문 여부 결정.

---

## 산출물

**`index.html`** — 단일 파일. 외부 의존성 없음. GitHub Pages로 배포됨.

### 섹션 구성

1. Header — 로고 + 네비 + 언어 토글 (한국어/中文)
2. Hero — CODE ME 타이틀 + 태그라인
3. About — 정유현 선생님 학력/경력 타임라인
4. Courses — 과목 카드 8개 (Python, WEB, SERVER, AI, JAVA, AP, IGCSE, IB)
5. Pricing — 가격표 (50분, 1:1 vs 그룹, 元 단위)
6. Curriculum — 커리큘럼 트랙
7. Policies — 참고사항 + 발票 안내
8. Contact — WeChat/Email/주소 + WeChat QR코드

### 기술 특징

- 반응형 (모바일 우선, 375px~1280px+)
- 언어 토글: `<body data-lang="ko|zh">` + `.ko` / `.zh` CSS 클래스로 전환, localStorage 저장
- 글자 크기 토글: 우하단 고정 플로팅 버튼 (16px ↔ 22px), localStorage 저장
- 디자인: 따뜻한 베이지/갈색 톤 (원본 마케팅 자료 매칭)
- **Google Fonts 없음** — 중국 차단 우려로 시스템 폰트만 사용

---

## 확정된 의사결정 (재논의 불필요)

| 결정 | 이유 |
|------|------|
| GitHub Pages 호스팅 | 위챗에서 링크로 바로 열림, 무료 |
| 반응형 웹페이지 | 폰 + 노트북 동시 지원 |
| 공중호(公众号) 미사용 | JS 차단 문제 + 개설 번거로움 |
| 长图(긴 이미지) 폐기 | GitHub Pages로 전환하면서 불필요 |
| Google Fonts 제거 | 중국 내 차단 |
| WeChat QR 이미지 삽입 | Contact 섹션에 포함됨 |
| 선불 정책 명시 | Pricing 섹션에 포함됨 |

---

## 작업 스타일

- 한국어로 소통
- 결정 빠르게 — 한 줄 답 선호
- 무료 도구만 (GitHub Pages OK)
- 위챗 중심 워크플로우

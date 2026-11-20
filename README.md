# 김순일 · 프론트엔드 개발자

커머스와 운영 도구를 만듭니다. React·TypeScript·Next.js를 주로 사용하며, 상품·주문·배송·반품·정산 화면과 공통 UI를 개발해 왔습니다.

[포트폴리오](https://kimsunil.netlify.app/) · [기술 블로그](https://k-soonil.tistory.com/) · [상세 이력서](https://confirmed-syrup-300.notion.site/Soonil-Kim-8b0de4d95bfe40db8e725e980cca5fdb) · [이메일](mailto:rlatnsdlf158@naver.com)

## 최근 다룬 문제

- **동시 주문과 재고 정합성** — 여러 품목의 재고 예약을 DB 트랜잭션으로 처리하고, 중복 요청·부분 반품·초과 반품을 검증했습니다. [ERP 구현 사례](https://kimsunil.netlify.app/projects/flow-ledger)
- **대량 데이터와 비동기 갱신** — Canvas의 불필요한 반복 그리기를 제거하고, 늦게 끝난 이전 요청이 최신 화면을 덮지 않도록 수정했습니다. [물류 개선 코드·회귀 테스트](https://github.com/kimsoonil/gscrmd/commit/a357a1a)
- **공통 개발 기준** — 회사에서는 React 전환·공통 UI 구성과 프론트엔드 챕터 리딩을 맡아 기술 스택·코드 컨벤션 논의, 코드 리뷰와 릴리스 관리에 참여했습니다. [업무 경험](https://kimsunil.netlify.app/#work)

## 개인 프로젝트

| 프로젝트 | 중점적으로 다룬 내용 | 살펴보기 |
| --- | --- | --- |
| ERP · 재고·주문·매출 | 다품목 주문, 부분 반품, 기간별 매출, 커서 조회·가상 스크롤. 관리 화면은 소유자 전용이며 기능 확장 중입니다. | [설계·검증](https://kimsunil.netlify.app/projects/flow-ledger) |
| 물류 모니터링 | 모의 차량 Canvas 시각화, 차량 선택, 최신 이벤트 병합과 반응형 지도. | [데모](https://seoul-logistics-dashboard.slskdkfdl12.chatgpt.site/dashboard/) · [코드](https://github.com/kimsoonil/gscrmd) |
| 민원똑똑 | 정적 민원 검색과 키워드 기반 모의 채팅 프로토타입. 실제 AI·인증·발급 미연동. | [데모](https://minwontalk.netlify.app/) · [코드](https://github.com/kimsoonil/MinwonTalk) |
| 영웅합전서 | 한국사 영웅 모집·조합·전투·성장 UI와 로그인·저장 흐름을 구현한 웹 게임. | [게임](https://korean-history-merge-defense.slskdkfdl12.chatgpt.site/) · [코드](https://github.com/kimsoonil/korean-history-merge-defense) |

ERP는 실제 Supabase에서 48개 동시 주문 요청에 재고 5개를 두고 5건 성공·43건 거부를 확인했습니다. 물류 프로젝트는 갱신 순서·중복 이벤트·소켓 버퍼를 포함한 테스트 21개를 통과했습니다. 검증 조건과 한계는 각 [상세 사례](https://kimsunil.netlify.app/#projects)에 정리했습니다. 물류 데모는 실제 운행 데이터와 연결되지 않습니다.

## 기술과 경험

- **주력:** React, TypeScript, Next.js, Zustand, TanStack Query
- **테스트·배포:** Vitest, React Testing Library, Playwright, GitHub Actions
- **개인 프로젝트:** PostgreSQL, Supabase, Canvas API

어메스에서 2023.09–2026.08 선임연구원으로 근무하며 프론트엔드 챕터 리딩을 맡았습니다. 이전 경력과 회사별 담당 업무는 [경력 상세](https://kimsunil.netlify.app/#career)에서 확인할 수 있습니다. 회사 소스와 비공개 자료는 공개하지 않습니다.

## 개발 기록

- [2025년 개발자 회고](https://k-soonil.tistory.com/31)
- [구글 스프레드 시트를 활용한 번역 기능](https://k-soonil.tistory.com/30)
- [이펙티브 타입스크립트 스터디](https://k-soonil.tistory.com/29)
- [GitHub Actions를 활용한 branch 배포](https://k-soonil.tistory.com/27)

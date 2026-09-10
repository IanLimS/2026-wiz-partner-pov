# APJ Partner POV Dojo Program Blueprint

## 문서 개요

이 디렉터리는 Wiz APJ 파트너 프리세일즈 조직을 위한 **Partner POV Dojo** 프로그램의 기획 산출물을 담고 있습니다.

Partner POV Dojo는 단순 제품 교육이나 기능 데모 교육이 아니라, 파트너 SA/SE가 고객별 상황을 발견하고 적절한 POV 모션을 선택한 뒤, 성공 기준을 합의하고 기술 검증과 임원 결과 공유까지 수행할 수 있도록 설계한 실습 중심 프로그램입니다.

현재 문서는 **Working Proposal / Draft v0.9 (Sep 2026)**이며, 공식 Wiz 인증 정책이나 확정된 글로벌 운영 정책을 의미하지 않습니다.

## 핵심 목표

- 파트너가 고객의 비즈니스·기술 요구를 구조적으로 발견하고 POV 적합성을 판단하도록 지원
- 고객 상황에 따라 Tailored Demo, Cloud Security Workshop, Risk Assessment, Certification Assessment, Wiz POV, Executive Outcome Review 중 적절한 모션을 선택
- POV Success Plan, Go/No-Go 판단, 첫 24시간 운영, 주요 단계 관리, 결과 플레이백 역량 강화
- 기술 결과를 CISO, Cloud Platform, Security Operations, DevSecOps, GRC 등 고객 페르소나별 비즈니스 성과와 연결
- 실제 고객 기회에서 Wiz와 공동 수행한 증거를 바탕으로 파트너의 독립 수행 역량을 검증

## 권장 프로그램 구조

| 단계 | 권장 구성 | 주요 결과물 |
|---|---:|---|
| 사전 학습 | 4–6시간 셀프 페이스드 | Wiz 기초, 클라우드 보안 여정, 페르소나, 라이선스, AWS/Azure/GCP 커넥터 랩 |
| Live Dojo | 2일 | Discovery, 모션 선택, POV 계획, Golden Demo, 첫 24시간, 이의 제기 대응, 임원 플레이백 실습 |
| Field Practicum | 30–45일 | 검증된 실제 고객 기회에서 Wiz와 공동으로 POV 수행 및 증거 제출 |
| Accreditation Board | 평가 세션 | 수행 결과 검토, 피드백, 역량 수준 판정 |

초기 코호트는 **6–12명, 최대 4개 팀**을 권장합니다. `No-Go` 역시 근거가 명확하다면 올바른 POV 자격 판단 결과로 인정합니다.

## Golden Customer

워크숍의 공통 시뮬레이션 고객은 가상의 **Asteria Digital Holdings**입니다.

- 본사: Singapore
- 사업 범위: APJ 8개 시장
- 규모: 약 14,000명, 엔지니어 약 2,300명
- 클라우드 환경: AWS 180 accounts, Azure 42 subscriptions, GCP 65 projects
- 개발 환경: GitHub, Terraform, 컨테이너, CI/CD 및 모의 서비스 워크플로

이 고객 프로필은 참가자가 동일한 출발점에서 Discovery, 이해관계자 조율, 기술 검증, 임원 커뮤니케이션을 반복 연습할 수 있도록 설계했습니다.

## 핵심 고객 페르소나

| 페르소나 | 주요 관심사 |
|---|---|
| Group CISO | 위험 감소, 이사회 보고, 전략적 성과 |
| VP Cloud Platform | 클라우드 운영 효율, 플랫폼 확장성, 개발자 경험 |
| Director Cloud Security | 노출 경로, 우선순위화, 정책 운영 |
| Head of SecOps | 대응 속도, 경보 피로, 소유권과 워크플로 |
| Head of DevSecOps | 개발 수명주기 조기 개입, IaC 및 CI/CD 연계 |
| Director GRC | 통제 증거, 컴플라이언스 드리프트, 감사 대응 |
| Procurement Lead | 상업 조건, 범위, 도입 리스크 |

## Golden Tenant 설계

Golden Tenant는 중앙에서 관리하는 표준 청사진과 지역별 적용 유연성을 함께 갖도록 설계합니다.

- Cohort Environment와 팀별 Workspace
- 합성 데이터 기반 AWS/Azure/GCP 계정과 사전 구성된 증거
- Lab Owner, Facilitator, Participant, Observer 역할 분리
- 리셋 가능한 시나리오와 활동 텔레메트리
- 실제 고객 데이터 사용 금지, MFA, 최소 권한, 시간 제한 접근, 자격 증명 순환
- 비용 한도와 사용량 통제
- 행사 72시간 전 구성 동결, 24시간 전 최종 점검

### 사전 구성 시나리오

1. 외부 노출 워크로드, 치명적 취약점, 민감 데이터 접근 경로
2. 공개 스토리지와 합성 규제 데이터 라벨
3. 과도한 권한을 가진 ID
4. 운영 태그가 지정된 클러스터의 취약 컨테이너
5. 수정 후 다시 나타나는 IaC 문제
6. 컴플라이언스 드리프트와 소유권 메타데이터 부재
7. 중요한 위험 경로를 가리는 대량의 저우선순위 결과

## 평가 및 역량 수준

제안 기준은 **100점 만점 중 80점 이상 및 Critical Fail 없음**입니다. 점수 기준과 판정 권한은 최종 운영 전 별도 승인이 필요합니다.

권장 역량 수준:

- Dojo Ready
- POV Co-Lead
- Partner POV Lead
- Dojo Coach

`Partner POV Lead` 수준은 교육 참석만으로 부여하지 않으며, 실제 고객 기회에서 수행한 Field Practicum 증거가 필요합니다.

Critical Fail 예시:

- 성공 기준 없이 POV 진행
- 접근 권한 또는 데이터 보호 우려 무시
- 컴플라이언스나 비즈니스 결과를 과도하게 약속
- 제품 또는 운영상의 제한 사항 은폐
- 임원 또는 상업적 다음 단계가 없는 결과 공유

## APJ 적용 원칙

- ANZ, India, Southeast Asia: 영어 코어 자료 중심
- Japan, Korea: 참가자 자료와 역할극의 현지 언어 적용
- 글로벌 코어: 프로그램 목표, 품질 기준, 핵심 산출물, 평가 원칙
- 지역 오버레이: 규제 맥락, 산업 사례, 언어, 파트너 성숙도, 운영 일정

## 주요 참가자 산출물

- Discovery 입력 양식 및 기회 적합성 평가
- POV Success Plan과 Go/No-Go 판단 근거
- 첫 24시간 실행 계획
- 기술 결과 및 증거 기반 우선순위 분석
- 고객 페르소나별 이의 제기 대응
- 6슬라이드 Executive Outcome Playback
- Field Practicum 증거 패키지

## 운영 전 확인이 필요한 항목

다음 항목은 **Global Partner Enablement, Product, Legal 및 APJ 지역 리더십**과 검증해야 합니다.

- Golden Tenant 제공 방식, 라이선스 및 비용 책임
- 파트너 데이터 접근과 합성 데이터 사용 원칙
- 공식 Accreditation 명칭과 판정 권한
- 합격 점수, Critical Fail, 갱신 및 만료 정책
- 국가별 언어 지원 범위와 규제 검토
- 실습 환경의 지원 모델과 장애 대응 SLA

## 파일

- [`APJ_Partner_POV_Dojo_Program_Blueprint.docx`](./APJ_Partner_POV_Dojo_Program_Blueprint.docx) — 30페이지 프로그램 상세 기획서
- [`README.md`](./README.md) — 산출물의 목적, 구조 및 활용 방법 요약

## 권장 활용 순서

1. APJ 이해관계자와 프로그램 목표 및 대상 파트너를 합의합니다.
2. Golden Tenant, 라이선스, 평가 권한 등 미확정 항목을 확정합니다.
3. 한 개 시장 또는 소규모 코호트로 파일럿을 운영합니다.
4. 참가자 성과, 운영 비용, 고객 기회 전환 데이터를 검토합니다.
5. 지역별 오버레이와 Coach 양성 모델을 보완한 뒤 APJ로 확대합니다.

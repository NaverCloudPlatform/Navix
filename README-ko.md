# NAVIX (Naver Linux)

NAVIX는 Naver가 관리하는 Linux 배포판입니다. Naver의 인프라와 서비스에 최적화된 안정적인 엔터프라이즈급 OS 환경을 제공합니다.

- [NAVIX 홈페이지](https://navix.navercorp.com/)
- [NAVIX 저장소](https://dlnavix.navercorp.com/)

---

## 피드백 및 지원

| 항목 | 링크 |
|---|---|
| 버그 제보 | [버그 리포트 작성하기](https://github.com/NaverCloudPlatform/Navix/issues/new?assignees=&labels=bug%2Cnew&projects=&template=bugreport.yml&title=%5BBUG%5D) [![bug](https://img.shields.io/github/labels/NaverCloudPlatform/Navix/bug)](https://github.com/NaverCloudPlatform/Navix/labels/bug) |
| 기능 요청 | [기능 요청하기](https://github.com/NaverCloudPlatform/Navix/issues/new?assignees=&labels=enhancement&projects=&template=feature_request.yml&title=%5BENHANCEMENT%5D) [![enhancement](https://img.shields.io/github/labels/NaverCloudPlatform/Navix/enhancement)](https://github.com/NaverCloudPlatform/Navix/labels/enhancement) |
| 문의하기 | [질문 등록하기](https://github.com/NaverCloudPlatform/Navix/issues/new?assignees=&labels=question&projects=&template=question.yml&title=%5BQ%5D) [![question](https://img.shields.io/github/labels/NaverCloudPlatform/Navix/question)](https://github.com/NaverCloudPlatform/Navix/labels/question) |
| FAQ | [docs/](https://github.com/NaverCloudPlatform/Navix/tree/main/docs) |

---

## 기여하기

버그 제보, 기능 요청, 문의 등 커뮤니티의 다양한 기여를 환영합니다.

### 기여 방법

#### 1. 버그 제보

버그를 발견하셨다면 [버그 리포트 작성하기](https://github.com/NaverCloudPlatform/Navix/issues/new?assignees=&labels=bug%2Cnew&projects=&template=bugreport.yml&title=%5BBUG%5D)를 통해 아래 내용을 포함하여 제보해 주세요:

- **컴포넌트** — 영향을 받는 패키지 또는 서브시스템 (예: `kernel`, `openssl`)
- **버그 설명** — 문제에 대한 명확한 설명
- **재현 방법** — 문제를 재현하는 최소한의 단계
- **기대 동작 vs 실제 동작**
- **환경** — OS 버전, 하드웨어 아키텍처 (예: `NAVIX 9`, `x86_64`)
- **스크린샷 또는 로그** — 해당하는 경우

#### 2. 기능 요청

NAVIX 개선을 위한 아이디어가 있으신가요? [기능 요청하기](https://github.com/NaverCloudPlatform/Navix/issues/new?assignees=&labels=enhancement&projects=&template=feature_request.yml&title=%5BENHANCEMENT%5D)를 통해 아래 내용을 작성해 주세요:

- 요청의 배경이 되는 문제
- 원하는 해결 방법
- 검토한 대안들

#### 3. 문의하기

NAVIX에 관한 일반적인 질문은 [질문 등록하기](https://github.com/NaverCloudPlatform/Navix/issues/new?assignees=&labels=question&projects=&template=question.yml&title=%5BQ%5D)를 이용해 주세요. 먼저 [FAQ](https://github.com/NaverCloudPlatform/Navix/tree/main/docs)에서 이미 답변된 내용인지 확인하시는 것을 권장합니다.

### 이슈 처리 흐름

이슈를 등록하면 아래 상태를 순서대로 거치게 됩니다:

```
new → assigned → ondev → resolved → verified → closed
```

각 상태에 대한 자세한 내용은 아래 [이슈 레이블 및 상태](#이슈-레이블-및-상태) 섹션을 참고하세요.

---

## 이슈 레이블 및 상태

이슈는 아래 흐름에 따라 처리됩니다:

| 레이블 | 설명 |
|---|---|
| [![new](https://img.shields.io/github/labels/NaverCloudPlatform/Navix/new)](https://github.com/NaverCloudPlatform/Navix/labels/new) | 최근 추가된 버그입니다. **assigned** 또는 **closed** 상태로 변경될 예정입니다. |
| [![assigned](https://img.shields.io/github/labels/NaverCloudPlatform/Navix/assigned)](https://github.com/NaverCloudPlatform/Navix/labels/assigned) | 엔지니어에게 할당되었습니다. |
| [![ondev](https://img.shields.io/github/labels/NaverCloudPlatform/Navix/ondev)](https://github.com/NaverCloudPlatform/Navix/labels/ondev) | 담당 엔지니어가 작업 중입니다. |
| [![resolved](https://img.shields.io/github/labels/NaverCloudPlatform/Navix/resolved)](https://github.com/NaverCloudPlatform/Navix/labels/resolved) | 버그가 수정되었습니다. |
| [![verified](https://img.shields.io/github/labels/NaverCloudPlatform/Navix/verified)](https://github.com/NaverCloudPlatform/Navix/labels/verified) | 버그 수정이 검증되었습니다. |
| [![duplicate](https://img.shields.io/github/labels/NaverCloudPlatform/Navix/duplicate)](https://github.com/NaverCloudPlatform/Navix/labels/duplicate) | 중복된 버그입니다. |
| [![closed](https://img.shields.io/github/labels/NaverCloudPlatform/Navix/closed)](https://github.com/NaverCloudPlatform/Navix/labels/closed) | 종료되었습니다. |

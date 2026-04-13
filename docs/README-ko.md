# FAQ

## 소스 코드를 제공하나요?

네. 아래 경로를 통해 소스 코드를 확인할 수 있습니다:

- **Source ISO:** [https://dlnavix.navercorp.com/navix/9/x86_64/BaseOS/iso/](https://dlnavix.navercorp.com/navix/9/x86_64/BaseOS/iso/)
- **저장소별 소스 트리:**
  ```
  https://dlnavix.navercorp.com/9/x86_64/{저장소명}/source/tree/
  ```
  예시: `https://dlnavix.navercorp.com/9/x86_64/BaseOS/source/tree/`

## 어떤 저장소가 있나요?

| 저장소 | 설명 |
|---|---|
| **AppStream** | 애플리케이션 패키지 및 추가 소프트웨어 |
| **BaseOS** | 핵심 OS 패키지 및 ISO |
| **CRB** | Code Ready Builder — 추가 개발 라이브러리 |
| **HighAvailability** | 클러스터링 및 고가용성 패키지 |
| **ResilientStorage** | 복원력 있는 스토리지 패키지 |
| **Updates** | 보안 및 버그 수정 업데이트 |

각 저장소는 아래 하위 디렉토리를 포함합니다:

| 하위 디렉토리 | 내용 |
|---|---|
| `os/` | 바이너리 RPM 패키지 |
| `source/` | 소스 RPM 패키지 |
| `debug/` | 디버그 심볼 패키지 |
| `iso/` | ISO 이미지 (BaseOS 전용) |

## 버그 제보나 기능 요청은 어떻게 하나요?

메인 저장소의 이슈 템플릿을 이용해 주세요:

- [버그 제보하기](https://github.com/NaverCloudPlatform/Navix/issues/new?assignees=&labels=bug%2Cnew&projects=&template=bugreport.yml&title=%5BBUG%5D)
- [기능 요청하기](https://github.com/NaverCloudPlatform/Navix/issues/new?assignees=&labels=enhancement&projects=&template=feature_request.yml&title=%5BENHANCEMENT%5D)
- [문의하기](https://github.com/NaverCloudPlatform/Navix/issues/new?assignees=&labels=question&projects=&template=question.yml&title=%5BQ%5D)

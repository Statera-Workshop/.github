# Statera Workshop

**Executable Algorithms, Reproducible Experiments, and Engineering Implementations for AI, Robotics, and Physical AI**

[English](#english) | [한국어](#한국어)

## English

### About Statera Workshop

Statera Workshop is the **software implementation and experimental engineering Working Group** within the Statera ecosystem. It translates technical knowledge into executable algorithms, testable software components, reproducible experiments, and practical engineering workflows across artificial intelligence, computer vision, robotics, and Physical AI.

Workshop focuses on **how algorithms are implemented, executed, tested, and reproduced**. It provides a bridge between the technical explanations maintained by Statera Library and software that can be evaluated in controlled experiments or adapted for physical systems. Implementations are not automatically certified, production-ready, or suitable for safety-critical deployment.

Workshop differs from Research, which investigates new hypotheses and evaluates emerging approaches, and Standards, which defines common technical specifications. Workshop may implement research ideas or standards-compliant interfaces, but the evidence, scope, and maturity of each implementation must remain explicit.

### Scope and Responsibilities

- Implement and maintain executable reference algorithms, experimental code, and reusable software components.
- Develop computer vision pipelines, including classification, object detection, segmentation, multi-object tracking, and relevant 3D perception techniques.
- Explore practical machine learning, deep learning, robotics perception, sensor processing, and Physical AI software workflows.
- Document environments, dependencies, datasets, configurations, execution instructions, and known limitations to support reproducibility.
- Design functional tests, benchmark scripts, regression checks, and comparisons against clearly identified baselines.
- Record implementation status, observed failures, test evidence, and compatibility constraints without presenting unverified claims as established results.
- Connect implementations to Library documentation, Research findings, and Standards specifications while preserving each group's responsibilities.
- Keep publicly approved code separate from private engineering materials, credentials, restricted datasets, and confidential implementation details.

### Repositories and Reproducibility

The [Statera-Workshop GitHub organization](https://github.com/Statera-Workshop) hosts software-oriented repositories and algorithm experiments. Current public work includes multiple object-detection families and related implementation variants. Repository names describe technical areas or implementations; they do not, by themselves, establish accuracy, completeness, or readiness for deployment.

For each project, consult its repository README and available code for supported platforms, dependency versions, training or inference procedures, dataset requirements, licensing, and validation status. Where feasible, experiments should distinguish **reproducing a published baseline**, **modifying an implementation**, and **validating a new result**.

### Relationship to the Statera Knowledge System

**Library** explains the algorithms and engineering concepts; **Workshop** implements and tests them; **Research** evaluates open technical questions; **Standards** provides shared schemas and interface contracts; **Guild** coordinates contributors; and **Foundation** establishes the overarching mission and governance principles.

### Working Group Network

The six Statera Working Groups have complementary responsibilities.

| Working Group | Role | GitHub |
| --- | --- | --- |
| **Foundation** | Mission, founding principles, and governance | [Statera-Foundation](https://github.com/Statera-Foundation) |
| **Library** | Structured technical knowledge, manuscripts, and publication | [Statera-Library](https://github.com/Statera-Library) |
| **Workshop** (this group) | Executable implementations, reproducible code, and algorithm testing | [Statera-Workshop](https://github.com/Statera-Workshop) |
| **Guild** | Contributor coordination, roles, and evidence-based contribution records | [Statera-Guild](https://github.com/Statera-Guild) |
| **Research** | Technical hypotheses, experimental studies, and validation | [Statera-Research](https://github.com/Statera-Research) |
| **Standards** | Shared specifications, schemas, interfaces, and interoperability | [Statera-Standards](https://github.com/Statera-Standards) |

### Related PAI-SG Organization

[PAI-SG-Workshop](https://github.com/PAI-SG-Workshop) is the corresponding organization within the **Physical AI Spider Grid (PAI-SG)** network. Statera Workshop remains the management location for its original Statera software assets. Publicly approved materials may be mirrored under PAI-SG through a controlled, one-way publication process; private materials are not automatically replicated.

## 한국어

### Statera Workshop 소개

Statera Workshop은 Statera 생태계에서 **소프트웨어 구현 및 실험 공학(Software Implementation and Experimental Engineering)**을 담당하는 Working Group입니다. 인공지능(Artificial Intelligence), 컴퓨터 비전(Computer Vision), 로보틱스(Robotics), 피지컬 AI(Physical AI)의 기술 지식을 실제 실행 가능한 알고리즘, 시험 가능한 소프트웨어 구성요소, 재현 가능한 실험 및 공학적 개발 절차로 전환합니다.

Workshop의 핵심 질문은 **알고리즘을 어떻게 구현하고, 실행하고, 시험하고, 재현하는가**입니다. Statera Library에 정리된 기술 설명을 실제 코드와 실험으로 연결하며, 물리 시스템에 적용할 수 있는 구현의 기초를 제공합니다. 단, 공개된 실험 코드가 곧바로 제품 수준의 품질, 인증 또는 안전 필수 시스템에 대한 적용 적합성을 의미하지는 않습니다.

새로운 기술 가설과 연구 질문을 다루는 Research, 공통 기술 규격을 정의하는 Standards와도 역할을 구분합니다. Workshop은 연구 결과나 표준을 구현할 수 있지만, 각 구현의 시험 근거와 적용 범위, 성숙도를 명확하게 기록해야 합니다.

### 주요 역할과 관리 범위

- 실행 가능한 참조 알고리즘, 실험 코드 및 재사용 가능한 소프트웨어 구성요소의 구현과 유지관리
- 분류(Classification), 객체 감지(Object Detection), 분할(Segmentation), 다중 객체 추적(Multi-Object Tracking), 3차원 인식(3D Perception) 등 컴퓨터 비전 파이프라인 구현
- 기계학습(Machine Learning), 딥러닝(Deep Learning), 로봇 인식(Robot Perception), 센서 처리 및 Physical AI 소프트웨어 실험
- 재현성(Reproducibility)을 위한 실행 환경, 의존성, 데이터셋, 설정값, 실행 방법 및 알려진 제약사항 문서화
- 기능 시험, 벤치마크, 회귀 시험 및 명확한 기준 모델(Baseline)과의 비교 절차 개발
- 구현 상태, 실패 사례, 시험 증거 및 호환성 제약 기록과 미검증 성능 주장 방지
- Library의 기술 문서, Research의 연구 결과, Standards의 기술 규격과 구현물 간의 연결
- 공개 승인된 코드와 비공개 공학 자료, 인증 정보, 제한된 데이터셋 및 내부 핵심 구현 정보의 분리 관리

### Repository와 재현 가능한 실험

[Statera-Workshop GitHub Organization](https://github.com/Statera-Workshop)은 알고리즘 구현과 소프트웨어 실험을 위한 Repository를 관리합니다. 현재 공개 작업에는 여러 객체 감지 알고리즘 계열과 구현 변형이 포함됩니다. 다만 Repository 이름만으로 성능, 구현 완성도 또는 실제 배포 가능성이 보장되는 것은 아닙니다.

개별 프로젝트를 사용할 때에는 해당 Repository의 README와 코드를 기준으로 지원 환경, 의존성 버전, 학습 및 추론 절차, 데이터셋 요구사항, 라이선스, 검증 상태를 확인해야 합니다. 가능한 경우 **기존 논문의 재현**, **알고리즘의 수정 구현**, **새로운 결과의 검증**을 구분하여 기록합니다.

### Statera 지식 체계와의 관계

**Library**는 알고리즘과 공학 개념을 설명하고, **Workshop**은 이를 구현하고 시험합니다. **Research**는 새로운 기술적 질문과 가설을 검증하고, **Standards**는 공통 스키마와 인터페이스 계약을 정의합니다. **Guild**는 기여자의 협업을 조직하며, **Foundation**은 전체 생태계의 미션과 운영 원칙을 제공합니다.

### 6개 Working Group 소개 및 연결

Statera의 6개 Working Group은 서로 보완적인 책임을 담당합니다.

| Working Group | 주요 역할 | GitHub |
| --- | --- | --- |
| **Foundation** | 미션, 설립 원칙 및 거버넌스 | [Statera-Foundation](https://github.com/Statera-Foundation) |
| **Library** | 체계적인 기술 지식, 원고 및 출판 | [Statera-Library](https://github.com/Statera-Library) |
| **Workshop** (현재 조직) | 실행 가능한 구현, 재현 가능한 코드 및 알고리즘 시험 | [Statera-Workshop](https://github.com/Statera-Workshop) |
| **Guild** | 기여자 협업, 역할 및 증거 기반 기여 기록 | [Statera-Guild](https://github.com/Statera-Guild) |
| **Research** | 기술 가설, 실험 연구 및 검증 | [Statera-Research](https://github.com/Statera-Research) |
| **Standards** | 공통 기술 규격, 스키마, 인터페이스 및 상호운용성 | [Statera-Standards](https://github.com/Statera-Standards) |

### 연계 PAI-SG Organization

[PAI-SG-Workshop](https://github.com/PAI-SG-Workshop)은 **Physical AI Spider Grid(PAI-SG)** 네트워크에서 대응하는 조직입니다. Statera Workshop은 기존 Statera 소프트웨어 자산의 원본 관리 위치를 유지합니다. 공개 승인된 자료는 통제된 단방향 게시 절차에 따라 PAI-SG에 복제할 수 있으며, 비공개 자료는 자동 복제하지 않습니다.

---

## Contact

**Richard Minsoo Go**  
Head of AI, Hills Robotics  
Statera Working Group

**Personal / Research Contact:**  
[gominsoo888@gmail.com](mailto:gominsoo888@gmail.com)

**Hills Robotics / Business Contact:**  
[minsoo.go@hillslogis.com](mailto:minsoo.go@hillslogis.com)

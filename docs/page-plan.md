# Page Plan (페이지 기획 및 전체 IA)

## 1. 사이트맵 (Sitemap)

```mermaid
graph LR
    Root[PERFECT PRO DARTS]
    
    Root --> GNB[기존 GNB 및 서브페이지 (구조 100% 유지)]
    
    Root --> A[HOME 메인 페이지 (GUI 및 위계 전면 개편)]
    A -.-> A1(1. 비주얼 Hero)
    A -.-> A2(2. NEXT STAGE)
    A -.-> A3(3. 프로모션 배너)
    A -.-> A4(4. STAGE WINNER)
    A -.-> A5(5. 2026 RANKING)
    A -.-> A6(6. 토픽 / 뉴스)
    A -.-> A7(7. 스폰서)

    classDef page fill:#0d47a1,stroke:#fff,stroke-width:2px,color:#fff;
    classDef section fill:#424242,stroke:#bdbdbd,stroke-width:1px,color:#fff,stroke-dasharray: 5 5;
    classDef old fill:#757575,stroke:#9e9e9e,stroke-width:2px,color:#fff;
    
    class A page;
    class A1,A2,A3,A4,A5,A6,A7 section;
    class GNB old;
```

## 2. 주요 페이지 구성 의도 (수정됨)
- **전체 사이트 IA 구조 (GNB 등) 변경 불가**: 기존 PERFECT 사이트의 서브 페이지 라우팅 구조는 그대로 유지합니다.
- **메인 페이지 한정 개편**: 전체 사이트 구조를 뒤엎지 않으면서도, 사용자가 가장 먼저 접하는 **메인 페이지(HOME)의 GUI와 스크롤 위계(1~8순위)**만을 타 선진 플랫폼의 구조처럼 세련되게 재배치합니다.

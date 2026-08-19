# Page Plan (페이지 기획 및 전체 IA)

## 1. 사이트맵 (Sitemap)

```mermaid
graph LR
    Root[PERFECT PRO DARTS GNB]
    
    Root --> A[HOME 메인 페이지]
    A -.-> A1(1. 비주얼 Hero)
    A -.-> A2(2. NEXT STAGE)
    A -.-> A3(3. 프로모션 배너)
    A -.-> A4(4. STAGE WINNER)
    A -.-> A5(5. 2026 RANKING)
    A -.-> A6(6. 토픽 / 뉴스)
    A -.-> A7(7. 스폰서)
    
    Root --> B[대회 안내]
    B --> B1(대회 개요 / 규정)
    B --> B2(투어 일정)
    B --> B3(프로테스트 안내)
    
    Root --> C[기록 / 랭킹]
    C --> C1(대회 결과 Archives)
    C --> C2(올해 통합 랭킹)
    C --> C3(시합 속보 Live)
    
    Root --> D[선수 / 미디어]
    D --> D1(선수 명감)
    D --> D2(갤러리 / 동영상)
    D --> D3(LIVE 중계)
    
    Root --> E[프로 선수 전용]
    E --> E1(선수 로그인)
    E --> E2(라이선스 등록/갱신)
    
    Root --> F[고객지원]
    F --> F1(공지사항)
    F --> F2(문의하기)

    classDef page fill:#0d47a1,stroke:#fff,stroke-width:2px,color:#fff;
    classDef section fill:#424242,stroke:#bdbdbd,stroke-width:1px,color:#fff,stroke-dasharray: 5 5;
    class A,B,C,D,E,F page;
    class A1,A2,A3,A4,A5,A6,A7 section;
```

## 2. 주요 페이지 구성 의도
기존 PERFECT 사이트에 중구난방 흩어져 있던 메뉴들을, 선진 다트 플랫폼의 선진적인 위계에 맞춰 4가지 메인 카테고리로 정리했습니다.

- **대회 안내**: 대회가 언제/어디서 열리는지 직관적으로 확인.
- **기록 / 랭킹**: 프로 선수들이 가장 민감하게 확인하는 데이터(결과, 랭킹, 속보)를 한곳에 집중.
- **선수 / 미디어**: 팬들과 스폰서들이 선수의 활약을 영상 및 사진으로 빠르게 찾아볼 수 있도록 구성.
- **프로 선수 전용**: 선수들이 자주 사용하는 필수 기능(로그인, 라이선스 갱신)을 우측 상단이나 전용 메뉴로 빼내어 사용성 극대화.

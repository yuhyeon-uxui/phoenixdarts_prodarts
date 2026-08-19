# Design Guide (디자인 가이드)

## 1. 디자인 컨셉
- **"친숙함 속의 세련됨 (Sophistication within familiarity)"**
- 기존 다트라이브 사이트의 세로형 위계를 유지하여 일본 유저들의 거부감을 최소화하면서, 최신 다크 모드 트렌드를 결합하여 프리미엄 느낌 부여.

## 2. 컬러 팔레트 (다크 모드 중심)
- **Background**: Deep Black (`#121212`) & Dark Gray (`#1E1E1E`)
  - 넓은 화면을 어두운 계열로 채워 선수들의 사진, 스폰서 로고, 포인트 수치가 빛나도록 함.
- **Primary Accent**: Brand Red (`#E53935`) or Blue (`#1E88E5`)
  - [엔트리 리스트], [로그인] 등 행동 유도 버튼(CTA) 및 랭킹 상승 화살표 등에 사용.
- **Text (Typography)**:
  - 주 텍스트: Off-White (`#E0E0E0`)
  - 보조 텍스트: Light Gray (`#9E9E9E`)
  - 강조 텍스트(포인트 등): Gold (`#FFD700`) 또는 White (`#FFFFFF`)

## 3. 타이포그래피 (Typography)
- 숫자(포인트, 랭킹)가 매우 중요한 사이트이므로, 숫자의 가독성이 뛰어난 산세리프(Sans-serif) 폰트 패밀리 사용.
- 프로페셔널하고 단단한 느낌을 주는 모던 폰트 적용 (예: Inter, Roboto, Noto Sans JP).

## 4. UI 컴포넌트 스타일링
- **Glassmorphism (글래스모피즘)**: 스크롤 시 고정되는 GNB 바에 적용하여 세련미 강조.
- **Card UI**: 뉴스/토픽 영역 등은 플랫(Flat)한 다크 카드 위에 미세한 화이트 보더(border)를 주어 구분감 부여.
- **Micro-interactions**: 
  - 버튼 호버 시 은은한 글로우(Glow) 효과.
  - 하단의 흑백 스폰서 로고들에 마우스를 올리면 원래 색상으로 부드럽게 전환(Fade-in)되는 애니메이션 추가.

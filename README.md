# UE5port
# UE5 Portfolio Demo – Character Collect Mini
**UE 5.3+ / Win64 / 3–5분 플레이 데모**

> 캐릭터 선택 → 전투(평타+스킬+쿨다운) → 보상/성장 → 세이브/로드가 한 번에 도는 짧고 단단한 데모.  
> 클라이언트 프로그래머 역량(입력/전투/UI/AI/툴링/데이터 파이프라인/세이브) 증명.

---

## 🔗 Links
- ⬇️ Download: [Releases](../../releases)
- 🎥 1-min Video: (YouTube 비공개 링크)
- 📦 Repo: (이 레포 주소)

---

## 🎮 Gameplay (30초 요약)
- 캐릭터 선택(획득 목업) → 스테이지 진입  
- 실시간 전투: 평타 + 스킬1(EX, 쿨다운/MP)  
- 클리어 보상 → 레벨업/스탯 증가 → **Save/Load**로 진행도 확인

---

## ⌨️ Controls
- 이동: WASD / 패드 Left Stick  
- 시야: 마우스 / 패드 Right Stick  
- 평타: LMB / 패드 X  
- 스킬1: R / 패드 Y  
- 상호작용: F / 패드 A  
- 메뉴: ESC

---

## 🛠 Tech Highlights (Client)
- **Enhanced Input**: IMC/IA 기반 키/패드 동시 대응
- **UMG HUD**: HP/MP, 스킬 쿨다운 게이지(이벤트 바인딩)
- **Data-Driven**: `DataTable(캐릭/스킬)` + CSV 파이프라인
- **SaveGame**: 진행도 저장/로드 흐름
- **AI**: 간단 추격(네비메시) + 전투 판정(LineTrace)
- **Niagara**: 히트 이펙트
- **Tooling**: Editor Utility Widget – **CSV→DataTable 원클릭 재임포트**
- **코드 구조**: Modules / Subsystems / ActorComponents(Stats/Combat)

---

## 📁 Repository Layout

# 🎮 Unity 게임 포트폴리오

> 혼자 기획하고 코드까지 직접 구현한 Unity 게임 프로젝트 모음입니다.
> 코드는 전부 직접 작성했고, 아트·UI는 외부 에셋을 사용했습니다 (출처는 각 저장소 README에 표기).

![Unity](https://img.shields.io/badge/Unity-6%20%7C%202022.3-black?logo=unity) ![C#](https://img.shields.io/badge/C%23-.NET-512BD4?logo=csharp) ![2D](https://img.shields.io/badge/2D-URP-green)

---

## 🗂️ 한눈에 보기

| 게임 | 장르 | 핵심 구현 | 저장소 |
|---|---|---|---|
| **Dream 꿈속의조작법** | 2D 액션 플랫포머 | 플레이어 조작(코요테 타임·대시·착지 버퍼), 전투(히트박스·넉백), 대화 분기, 적 AI, 구역별 카메라, 저장/불러오기 | [MyGame](https://github.com/jay-7314/MyGame) |
| **PrincessMakerLike** | 육성 시뮬레이션 (프로토타입) | 활동 선택 → 능력치 변화, 조건 이벤트·엔딩, ScriptableObject 데이터 설계, 저장/불러오기 | [PrincessMaker](https://github.com/jay-7314/PrincessMaker) |

## 📝 개발 블로그

개발하며 막힌 문제와 해결 과정을 정리합니다. → [jaysdaily.tistory.com](https://jaysdaily.tistory.com/)

- 경사면에서 캐릭터가 미끄러지는 문제를 브레이크 콜라이더로 해결
- Dictionary가 JSON으로 직렬화되지 않는 문제 발견과 해결
- 비활성 컴포넌트에서 `OnMouseDown`이 호출된 원인
- 몬스터가 방향을 바꿀 때 체력바가 같이 뒤집히는 문제
- 조건부 대화 시스템(GameFlags, 스킵, 씬 트리거)

## 🔧 두 게임에서 다룬 것

| 주제 | Dream 꿈속의조작법 | PrincessMakerLike |
|---|---|---|
| 조작·물리 | 이동, 점프, 대시, 경사면 | - |
| 전투·AI | 히트박스, 넉백, 적 AI | - |
| 데이터 설계 | 스토리 진행 플래그 | ScriptableObject 활동·이벤트·엔딩 |
| 상태 관리 | 체력, HUD 연동 | 능력치 변경 알림 → UI 갱신 |
| 저장/불러오기 | 저장/불러오기 | JSON 저장, Dictionary는 DTO로 처리 |
| 카메라·씬 | Cinemachine, 씬 전환 | - |

---

## 🧰 다른 포트폴리오

센서·통신·AI 연동 중심의 인터랙티브 콘텐츠는 별도 저장소에 있습니다.
→ [unity-interactive-portfolio](https://github.com/jay-7314/unity-interactive-portfolio)

## 🙋 About

- **이름**: 하정우
- **이메일**: hjh268100@gmail.com
- **경력**: Unity 개발 1년 3개월 (인터랙티브 콘텐츠)

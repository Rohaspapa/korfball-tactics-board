# 🏀 코프볼 작전판 (Korfball Tactics Board)

웹 브라우저에서 바로 사용할 수 있는 코프볼(Korfball) 작전판입니다.
모바일·태블릿·PC 어디서나 동작하며, 설치할 필요 없이 링크만 열면 됩니다.

👉 **[작전판 바로 사용하기](https://rohaspapa.github.io/korfball-tactics-board/)**

---

## ✨ 주요 기능

- **4-0 기본 배치** — 코프볼 표준 시작 포지션 자동 배치 (페어 자동 생성)
- **선수/공 배치** — 공격팀(주황), 수비팀(청록), 공 자유 배치
- **성별 구분** — 남자=원·삼각형, 여자=사각형·마름모 (남2여2 자동 배정)
- **드래그로 이동** — 손가락이나 마우스로 끌어서 자유롭게 이동
- **선택 삭제 모드** 🗑 — 버튼을 누르면 선수 위에 빨간 X가 떠서 탭 한 번으로 삭제
- **방향선 그리기** ✏ — 직선 화살표 / 자유 곡선 두 가지 스타일
- **1:1 마크 페어 (그룹화)** 🔗 — 공격수를 움직이면 수비수가 골대 사이로 자동 이동
- **페어 개별 해제** — 페어 목록에서 칩(태그)을 탭하면 해당 페어만 해제
- **실시간 녹화** 🔴 — 자유롭게 움직이면서 녹화 → GIF / 동영상(MP4)으로 저장
- **모바일 호환 동영상** — MP4(H.264) 포맷 자동 선택으로 카톡·사진앱에서 바로 재생
- **모아서 한 번에 이동** 🧩 — 여러 선수를 하나씩 옮겨 두고, 버튼 한 번으로 모두 동시에 이동 (녹화에 그대로 반영)
- **장면 사진 저장** 📷 — 현재 코트 화면을 PNG 이미지로 저장 (모바일은 사진첩에 바로 저장)
- **코트 아래 빠른 실행 버튼** — 녹화 / 동작 모으기 / 사진을 스크롤 없이 바로 사용
- **키프레임 애니메이션** (고급) — 정교한 작전 흐름을 만들 수 있음
- **프로젝트 저장/불러오기** — JSON 파일로 작전 보관
- **한국어 / 영어 지원**

---

## 📱 사용 팁 (한국어)

### 기본 사용법
- **선수 추가**: 사이드바의 `공격팀 +` / `수비팀 +` 버튼
- **이동**: 선수/공을 드래그
- **삭제**: 🗑 선택 삭제 모드 ON → 선수 위 빨간 X 탭
- **등번호 변경**: PC는 더블클릭, 모바일은 더블탭

### 모양과 색
- **공격팀**: 주황색 / **수비팀**: 청록색
- **남자**: 원(공격) / 삼각형(수비)
- **여자**: 사각형(공격) / 마름모(수비)

### 페어(1:1 마크 그룹화)
1. `🔗 페어 만들기` 버튼 클릭
2. 공격수 탭
3. 수비수 탭 → 페어 완성 (자동으로 모드 종료)
4. 이후 공격수를 드래그하면 수비수가 자동으로 따라옴
5. 해제하려면 페어 목록에서 보라색 칩(예: `A1♂ ↔ B1♂`)을 탭

### 녹화와 공유
1. `🔴 녹화 시작` 클릭
2. 자유롭게 선수를 움직임
3. `■ 녹화 종료` 클릭
4. `🎬 동영상으로 저장` 또는 `🎞 GIF로 저장` 선택
5. 카톡·인스타·SNS로 바로 공유

> 💡 코트 바로 아래의 `🔴 녹화` 버튼으로도 녹화를 시작/종료할 수 있습니다.

### 모아서 한 번에 이동 🧩
선수를 하나씩 움직이면 영상이 느려 보일 때 사용합니다.
1. 녹화 중에 코트 아래 `⏸ 동작 모으기` 클릭 → 녹화가 잠시 멈춤
2. 움직일 선수·공을 하나씩 옮겨 두기 (원래 자리는 흐리게, 이동 경로는 점선으로 표시)
3. `▶ 한 번에 이동` 클릭 → 모두 원래 자리에서 동시에 부드럽게 이동하며 녹화 재개
4. 잘못 옮겼다면 `↩ 취소`로 원래 자리로 복귀
- 멈춰 있던 시간은 영상에 들어가지 않아 끊김 없이 이어집니다.
- 이동 속도는 사이드바 녹화 칸의 **이동 시간** 조절바로 바꿀 수 있습니다 (0.5~4초, 기본 1.5초).
- 녹화하지 않을 때도 화면 시연용으로 사용할 수 있습니다.

### 장면 사진 📷
- 코트 아래 `📷 사진` 또는 사이드바의 `📷 사진으로 저장 (PNG)` 클릭
- 모바일: 공유 창에서 `이미지 저장` → 사진첩에 저장 (카톡 공유도 가능)
- PC: PNG 파일로 다운로드
- 💡 `⏸ 동작 모으기` 상태에서 찍으면 원래 위치와 이동 점선이 함께 담긴 **작전도**가 됩니다.

### 화면 회전
모바일은 가로 화면이 더 보기 편합니다.

---

## 📱 How to Use (English)

### Basics
- **Add players**: Use the `Add Attacker` / `Add Defender` buttons in the sidebar
- **Move**: Drag players or the ball with finger/mouse
- **Delete**: Click `🗑 Select Delete` → tap the red X on a player
- **Change jersey number**: Double-click on PC, double-tap on mobile

### Shapes and Colors
- **Attackers**: Orange / **Defenders**: Teal
- **Male**: Circle (attacker) / Triangle (defender)
- **Female**: Square (attacker) / Diamond (defender)

### Pair (1:1 Marking)
1. Click the `🔗 Create Pair` button
2. Tap an attacker
3. Tap a defender → pair created (mode auto-closes)
4. When you drag the attacker, the defender follows automatically
5. To remove a pair, tap the purple chip (e.g. `A1♂ ↔ B1♂`) in the pair list

### Recording and Sharing
1. Click `🔴 Start Recording`
2. Move players freely
3. Click `■ Stop Recording`
4. Choose `🎬 Save as Video` or `🎞 Save as GIF`
5. Share directly via messaging apps or social media

> 💡 You can also start/stop recording with the `🔴 Rec` button right below the court.

### Batch Move (all at once) 🧩
Use this when moving players one by one makes the video look slow.
1. While recording, tap `⏸ Collect moves` below the court → recording pauses
2. Move the players/ball one by one (original spots are faded, paths shown as dotted lines)
3. Tap `▶ Move all` → everyone moves together smoothly and recording resumes
4. Made a mistake? Tap `↩ Cancel` to restore the original positions
- The paused time is not included, so the video plays without gaps.
- Adjust the speed with the **Move time** slider in the sidebar recording section (0.5–4s, default 1.5s).
- Also works without recording, for live demonstrations.

### Scene Photo 📷
- Tap `📷 Photo` below the court, or `📷 Save as Photo (PNG)` in the sidebar
- Mobile: choose `Save Image` in the share sheet to save to your photo album
- PC: downloads a PNG file
- 💡 Taking a photo while collecting moves captures the original positions and dotted paths — a ready-made tactics diagram.

### Screen Orientation
Landscape mode works best on mobile devices.

---

## 🐛 문제가 있나요? / Found an issue?

GitHub 저장소의 **Issues** 탭에서 새 이슈를 등록해주세요.
Please open a new issue in the **Issues** tab of this repository.

---

## 📄 라이선스 / License

자유롭게 사용·수정·배포 가능합니다.
Free to use, modify, and distribute.

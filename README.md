# 기지개 (uni-gijigae)

일에 빠지면 몇 시간이고 같은 자세로 앉아 있게 됩니다. **기지개**는 트레이에 조용히 있다가,
정해 둔 시간만큼 일하면 "일어나서 몸 좀 풀자"고 알려 주는 Windows 스트레칭 타이머입니다.

- 소개 · 사용법: https://www.uniflow.kr/apps/uni-gijigae/
- 내려받기: [Releases](../../releases)
  - `uni-gijigae-v*-windows-setup.exe` — 설치형
  - `uni-gijigae-v*-windows-portable.exe` — 실행형 (설치 없이 실행)

## 하는 일

- 업무시간 · 요일 · 점심시간 안에서 **N분 집중하면 M분 스트레칭**을 알림
- 목 돌리기 · 만세 · 허리 돌리기 · 무릎 들어올리기 등 22가지 동작을 **그때그때 다르게** 추천
- 화면을 잠그거나 자리를 비우면 타이머를 처음부터 다시 셈
- 발표 · 전체화면(영상 · 게임 · PPT 쇼) 중에는 끝날 때까지 알림을 미룸
- 쉬는 시간용 미니 게임 — 사다리(2~15명) · 블록 퍼즐 · 우주 슈팅 · 오목

치료 도구가 아닙니다. 아프거나 어지러우면 바로 멈추고, 통증이 계속되면 전문의와 상담하세요.

## 요구 사항

- Windows 10 / 11 (64비트)
- WebView2 런타임 (Windows 11 기본 포함)

설치형은 사용자 폴더에 설치되며 관리자 권한이 필요 없습니다.
코드 서명 인증서가 없어 처음 실행할 때 SmartScreen 경고가 뜰 수 있습니다 — "추가 정보 → 실행".

## 이 레포에 대해

배포 전용 레포입니다. 설치 파일과 변경 내역만 올립니다. 소스 코드는 공개하지 않습니다.
설정은 `%APPDATA%\kr.uniflow.unigijigae\` 에만 저장하며, 앱은 네트워크로 아무것도 보내지 않습니다.

### 사용한 글꼴

- [Pretendard](https://github.com/orioncactus/pretendard) — Copyright © 2023 Kil Hyung-jin,
  [SIL Open Font License 1.1](https://scripts.sil.org/OFL). 한글 2,350자만 남긴 서브셋을 앱에 넣었습니다.

문의: uniflow.kr@gmail.com

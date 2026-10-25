# 셀스탁 (CELLSTOCK) 다운로드

엑셀형 Windows 주식 프로그램 **셀스탁**의 배포 파일과 다운로드 페이지를 올리는 공개 저장소예요. 소스 코드는 이 저장소에 없어요.

## 다운로드

- 다운로드 페이지: https://yusangsoo.github.io/cellstock-releases/
- 모든 버전: [Releases](https://github.com/yusangsoo/cellstock-releases/releases)

GitHub 계정이 없어도 받을 수 있어요. Windows 10(2004 이상)·Windows 11 64비트 PC에서 실행돼요.

| 파일 | 설명 |
|---|---|
| `Cellstock-<버전>-Setup.exe` | **이 파일 하나만 받으면 돼요.** 더블클릭해서 설치하고, 관리자 권한이 필요 없어요. |
| `Cellstock-<버전>-Windows-x64.zip` | 고급 사용자용 압축본. 모두 푼 뒤 `Cellstock\Cellstock.exe`를 실행해요. 폴더 안 파일을 모두 함께 둬야 해요. |
| `SHA256SUMS.txt` | 받은 파일이 원본과 같은지 확인하는 값 |
| `먼저 읽어주세요.txt` | 설치·연결·주문·저장 위치·확인 범위 안내 |

## 설치할 때 “Windows의 PC 보호” 창이 뜨면

아직 코드 서명이 없는 테스트 버전이라 경고가 나와요. 이 저장소에서 받은 파일이 맞다면 **추가 정보 → 실행**을 누르세요. 파일을 확인하고 싶다면 PowerShell에서 아래 명령을 실행해 `SHA256SUMS.txt`의 값과 비교하세요.

```powershell
Get-FileHash .\Downloads\Cellstock-0.4.0-beta.2-Setup.exe
```

## 꼭 알아 두세요

- 각자 나무Plug에서 발급한 본인의 APP KEY·APP Secret으로 연결해요. 배포 파일에 개발자의 키나 계좌는 들어 있지 않아요.
- 키·토큰·앱 비밀번호·계좌번호를 누구에게도 보내지 마세요. DM으로 요청한다면 사칭이에요.
- 일반 계좌의 주문은 실제 거래예요. 테스트 버전이므로 실제 계좌 주문 체결은 아직 검증하지 않았어요.
- 셀스탁은 NH투자증권·Microsoft와 제휴 관계가 없고, 투자 조언을 제공하지 않아요.

## 문의·오류 제보

[Issues](https://github.com/yusangsoo/cellstock-releases/issues)에 버전, Windows 버전, 재현 방법을 적어 주세요. 이슈 작성에는 GitHub 계정이 필요해요. 화면을 첨부할 때는 키·계좌번호 같은 개인정보를 꼭 가려 주세요.

# 스타워즈: 구 공화국의 기사단 (KOTOR) · Switch 한글패치 v0.900

Star Wars: Knights of the Old Republic (Nintendo Switch) 한글화. 모드 폴더 방식.

## 한글화 범위

- 게임 텍스트 전부(`dialog.tlk`) — 대사·선택지·아이템·퀘스트 일지
- 한글 글꼴 3종
- 실행 파일 한글 출력 처리

## 준비물

| | |
|---|---|
| 게임 | 본편 + 업데이트 1.0.4 (v262144) |
| 타이틀 ID | `0100854015868000` (업데이트 `0100854015868800`) |
| 업데이트 NSP | 본인 덤프 `…[0100854015868800][USA][v262144].nsp` |
| 키 | 본인 기기의 `prod.keys` |

게임 파일과 키는 포함하지 않습니다. 업데이트 1.0.4 외 버전은 키트가 확인 후 중단합니다.

## 적용

1. `KOTOR_Switch_KR_v0.900.zip` 을 풀고, 같은 폴더에 업데이트 NSP 와 `prod.keys` 를 넣습니다.
2. `make_mod.bat` 실행 → 엔터 두 번.
   (다른 위치면 경로 입력. Eden 키: `%APPDATA%\eden\keys\prod.keys`)
3. 생성된 `out` 폴더:
   - 스위치(Atmosphere): `out\atmosphere\` → SD 카드 루트
   - 에뮬(Eden 등): `out\eden_mod\KOTOR_KR\` → 게임 모드 폴더 (게임 우클릭 → 모드 폴더 열기)

## 결과 확인

```
exefs/main   SHA-1 7814c04fd6ce7fa85734c2b4abc361a41b6a6a50   8,390,612 bytes
dialog.tlk   SHA-1 112ab09f5a6f099ee40bf17efe24845bfe704679   5,981,971 bytes
```

전체 목록은 `hashes.txt`.

## 버그 제보

[Issues](../../issues) 에 화면 캡처와 함께 올려주세요.

## 파일

| 파일 | 내용 |
|---|---|
| `KOTOR_Switch_KR_v0.900.zip` | `make_mod.bat`, `patch/main.xdelta`, `romfs/`, `tools/` |
| `hashes.txt` | 원본·결과·패치 해시 |

`tools/` 의 hactool(ISC)·xdelta3(Apache 2.0) 라이선스 동봉.

## 버전 기록

- v0.900 (2026-10-16) — 첫 배포

## 제작

비영리 개인 제작. 원본 게임의 권리는 Lucasfilm·BioWare·Aspyr 에 있습니다.

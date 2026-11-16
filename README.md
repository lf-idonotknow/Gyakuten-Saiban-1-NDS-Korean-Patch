# 역전재판 소생하는 역전 한국어 패치 0.9.1

《역전재판 소생하는 역전》 <strong>Nintendo DS 일본판</strong>의 비공식 한국어 패치입니다. 0.9.1은 초반 설명 대사의 표시 오류를 수정한 버전입니다.

<strong>[0.9.1 패치 ZIP 다운로드](https://github.com/lf-idonotknow/Gyakuten-Saiban-1-NDS-Korean-Patch/releases/download/v0.9.1/Gyakuten-Saiban-1-NDS-Korean-Patch-v0.9.1.zip)</strong> · <strong>[처음 하는 분을 위한 적용 안내](docs/APPLY.md)</strong> · <strong>[오류·번역 제보](https://github.com/lf-idonotknow/Gyakuten-Saiban-1-NDS-Korean-Patch/issues/new/choose)</strong>

## 0.9.1 수정 내용

- 초반 얏파리 설명 대사의 줄바꿈 오류와 화면 하단 잘림을 수정했습니다.

## 한글화 내용

- 제1화부터 제5화 「소생하는 역전」까지의 본편 대사와 선택지
- 화자명, 메뉴와 각종 안내
- 증거품과 인물 정보
- 증언·신문 화면, 타이틀과 에피소드 표제
- 게임 진행에 필요한 문서·지도 등 이미지의 일본어 문구
- 제5화 항아리의 한글 이름 단서와 관련 퍼즐

## 준비물과 적용 대상

본인이 보유한 <strong>일본판 원본 `.nds`</strong>와 위 링크의 패치 ZIP이 필요합니다. 지원 판본은 <strong>게임 코드 `AGYJ` / 리비전 `0`</strong>입니다.

| 항목 | 지원 원본 | 패치 적용 후 |
|---|---|---|
| 파일 형식 | `.nds` | `.nds` |
| 크기 | 67,108,864바이트 (64MiB) | 134,217,728바이트 (128MiB) |
| CRC32 | `1C725545` | `A5523F95` |
| SHA-1 | `056070f41424f4a7f1613edcc97f4118db01c186` | `b107e22e5dea329c23b9c7f7efd8e588f9dd3e76` |
| SHA-256 | `4640d5053a09eda925ac2452a32d7017a437956c6e039975db26b70f55121de0` | `084dd8d26a826c4e96ecc12d448c16373927045d87391c24c682de2abd3069a0` |

확인값(해시)은 파일의 내용을 식별하는 값입니다. 파일 이름이 달라도 확인값이 같으면 같은 원본입니다.

## 간단한 적용 순서

0.9.0 이용자도 <strong>일본판 원본 ROM에 0.9.1 패치를 적용</strong>합니다. 기존 한글 ROM에 덧씌우는 패치가 아닙니다.

1. <strong>[0.9.1 패치 ZIP](https://github.com/lf-idonotknow/Gyakuten-Saiban-1-NDS-Korean-Patch/releases/download/v0.9.1/Gyakuten-Saiban-1-NDS-Korean-Patch-v0.9.1.zip)</strong>을 받고 압축을 풉니다.
2. [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/)를 엽니다. 프로그램 설치 없이 컴퓨터의 웹 브라우저에서 적용할 수 있습니다.
3. <strong>ROM file:</strong>에 일본판 원본 `.nds`를 선택합니다. CRC32가 <strong>`1C725545`</strong>인지 확인합니다.
4. <strong>Patch file:</strong>에 압축을 푼 `Gyakuten-Saiban-1-NDS-Korean-Patch-v0.9.1.bps`를 선택합니다.
5. <strong>Apply patch</strong>를 누르고 새 `.nds` 파일을 저장합니다. <strong>Settings → Fix ROM checksum</strong>은 꺼 둡니다.
6. 새 `.nds`를 melonDS에서 열거나 플래시카드의 게임 폴더에 복사해 닌텐도 DS에서 실행합니다.

파일 선택부터 화면 예시까지 설명한 <strong>[상세 적용 안내](docs/APPLY.md)</strong>를 참고하세요. GitHub가 자동으로 표시하는 `Source code (zip)`은 패치 다운로드가 아닙니다.

## 구동 확인

0.9.1은 <strong>melonDS에서 부팅과 제1화의 수정 장면 및 앞뒤 대사 진행</strong>을 확인했습니다. 닌텐도 DS 실기 구동은 0.9.0에서 보유 기기·플래시카드·microSD 카드 각각 3개로 확인했으며, <strong>0.9.1의 실기 재확인은 아직 하지 않았습니다.</strong> 자세한 [검증 정보와 세이브 안내](docs/VERIFICATION.md)를 참고하세요.

기존 세이브는 먼저 백업해 주세요. 세이브의 파일명과 저장 위치는 사용 중인 플래시카드·에뮬레이터의 규칙을 따릅니다.

## 제작 및 출처

[제작·글꼴 고지](CREDITS_AND_LICENSES.md)에 사용한 글꼴과 라이선스를 정리했습니다. 게임 원본과 패치가 적용된 ROM은 제공하지 않습니다.

## 제보

[Issues](https://github.com/lf-idonotknow/Gyakuten-Saiban-1-NDS-Korean-Patch/issues/new/choose)에서 <strong>진행·화면 오류</strong> 또는 <strong>오타·번역 수정</strong> 양식을 선택해 주세요. 패치 버전, 에피소드·장면, 재현 순서와 화면 사진을 함께 남겨 주세요. 게임 ROM이나 BIOS는 첨부하지 마세요.

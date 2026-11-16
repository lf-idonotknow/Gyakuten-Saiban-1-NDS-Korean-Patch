# 0.9.0 검증 정보와 세이브 안내

## 구동 확인

<strong>에뮬레이터 melonDS와 닌텐도 DS 실기에서 구동을 확인했습니다.</strong>

- <strong>melonDS:</strong> 배포 BPS를 일본판 원본에 적용해 만든 ROM으로 제1화 첫 대화 진입, 법정 기록 열기·닫기, 다음 대사 진행을 확인했습니다.
- <strong>닌텐도 DS 실기:</strong> 2026년 11월 16일, 제작자가 보유한 기기 3개·플래시카드 3개·microSD 카드 3개에서 구동 성공을 확인했습니다.

위 실기 확인은 보유 환경의 구동 결과이며 27개 조합을 모두 시험했다는 의미는 아닙니다. 이 문서에서 확인한 실행 구간과 전편의 모든 분기 검수는 구분합니다.

## 배포 패치 무결성

- 지원 원본: Nintendo DS 일본판, 게임 코드 `AGYJ`, 리비전 `0`
- 원본 크기: `67,108,864`바이트
- 결과 크기: `134,217,728`바이트
- 원본과 패치 적용 결과의 확인값: [README](../README.md#준비물과-적용-대상), [manifest.json](../manifest.json)
- Floating IPS로 생성한 BPS를 다시 적용해 기존 검수·구동 확인본과 <strong>전체 바이트 및 SHA-256 일치</strong>를 확인했습니다.
- 안내에 사용하는 <strong>Rom Patcher JS</strong>의 브라우저 화면에서도 원본과 BPS를 선택해 적용하고, 내려받은 ROM의 전체 바이트 및 SHA-256 일치를 확인했습니다.
- 같은 크기라도 내용이 다른 원본은 체크섬 오류로 적용이 거부되는 것을 확인했습니다.
- 배포 ZIP의 모든 내부 파일과 확인값을 검사했습니다.

## 세이브 안내

기존 세이브는 먼저 별도로 백업해 주세요. ROM과 세이브의 기본 파일명, 확장자, 저장 폴더는 사용 중인 플래시카드·에뮬레이터의 규칙을 따릅니다.

일부 기존 게임 내 세이브의 불러오기와 대사 진행을 로컬에서 확인했습니다. 서로 다른 패치판과 실행 환경 사이의 세이브 호환성 전체를 확인한 결과는 아닙니다. 다른 환경의 세이브는 확장자만 바꾸어 사용하기보다 해당 환경이 안내하는 변환 방법을 따라 주세요.

## 제보

구동이나 진행 문제는 [진행·화면 오류 양식](https://github.com/lf-idonotknow/Gyakuten-Saiban-1-NDS-Korean-Patch/issues/new?template=bug_report.yml), 대사나 용어 수정은 [오타·번역 수정 양식](https://github.com/lf-idonotknow/Gyakuten-Saiban-1-NDS-Korean-Patch/issues/new?template=translation_report.yml)을 사용해 주세요. 패치 버전, 사용 환경, 에피소드와 장면, 재현 순서와 화면 사진을 함께 적어 주세요.

# SALC 할로윈 파티 🎃

할로윈 레크레이션 사탕 점수판. 진행자가 점수를 입력하면 다른 기기에서 실시간으로 볼 수 있어요.

- 보기 링크: https://minuk1749.github.io/SALC-Halloween-Party/
- 진행자 링크: 보기 링크 뒤에 `?host=진행자키` (진행자에게만 따로 전달)

## 설정

1. Firebase 콘솔에서 Realtime Database를 만들고, `database.rules.json`의 `__HOST_KEY__`를 진행자 키로 바꿔서 규칙 탭에 붙여넣습니다. 키가 들어간 규칙은 이 저장소에 올리지 마세요.
2. 웹 앱을 등록하고 `firebaseConfig`를 `index.html`의 `FIREBASE_CONFIG`에 넣습니다.
3. GitHub Settings → Pages에서 `main` 브랜치 / `(root)`로 배포합니다.

진행자 모드는 진행자 링크로 연 탭에서만 유지됩니다. 같은 기기라도 보기 링크로 열면 보기 전용입니다.

# 광양프렌즈 Guideline Kit HTML

광양프렌즈 네 캐릭터 백운이, 기정이, 매향이, 매돌이를 종합한 캐릭터 가이드라인 HTML입니다.

구성:

- `01_광양프렌즈 캐릭터 가이드라인.html`: 종합 가이드라인 본문. CSS는 배포 편의를 위해 HTML 내부에 인라인으로 포함되어 있습니다.
- `index.html`: Coolify/nginx 루트 접속용 진입 파일이며, 본문 HTML로 이동합니다.
- `assets/`: 본문 HTML에서 참조하는 이미지와 폰트 에셋입니다.

배포:

- Coolify는 이 저장소의 `Dockerfile`을 사용해 nginx 정적 사이트로 배포합니다.
- 루트 URL은 `index.html`을 통해 본문 HTML로 연결됩니다.
- PDF와 ZIP은 이 배포용 HTML 갱신 과정에서 재생성하지 않습니다.

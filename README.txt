우당탕탕 추리게임 - 타겟 없는 AR 인터페이스 테스트

1. fake-ar.html
- targets.mind 없이 작동하는 가짜 AR 인터페이스입니다.
- 카메라 권한을 허용하면 화면 위에 스캔 프레임이 뜹니다.
- [스캔 완료] 버튼을 누르면 AR 단서 카드가 나타납니다.
- 실제 이미지 인식은 하지 않습니다.
- 목적: 참가자 화면 연출, UI 느낌, 카메라 권한 테스트.

2. 테스트 방법
- PC: VS Code Live Server로 fake-ar.html 실행
- 휴대폰: GitHub Pages / Netlify / Vercel 등에 업로드 후 HTTPS 주소로 접속
- file://로 열면 카메라 권한이 막힐 수 있습니다.

3. 실제 AR과 차이
- fake-ar.html: 카메라 + 오버레이 UI만 있음. targets.mind 필요 없음.
- ar-photo.html: MindAR 이미지 인식 필요. targets.mind 필요.

4. 추천 사용
- 지금 단계에서는 fake-ar.html로 UI/화면 느낌을 먼저 확인하세요.
- 나중에 특정 사진/지도/영수증 인식이 필요하면 MindAR 버전으로 교체하면 됩니다.

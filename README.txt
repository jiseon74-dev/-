국소배기장치 필요환기량 계산기 - 앱 설치 파일

구성
- index.html: v7 계산기 본체
- manifest.json: 홈 화면 설치용 앱 정보
- sw.js: 오프라인 캐시(Service Worker)
- icons/: 앱 아이콘

가장 간단한 사용법: Android 휴대전화에 앱으로 설치하기
1. 이 폴더 전체를 HTTPS로 제공되는 웹 호스팅에 올립니다. (예: GitHub Pages)
2. 휴대전화 Chrome에서 배포된 index.html 주소를 엽니다.
3. Chrome 메뉴(⋮)에서 '앱 설치' 또는 '홈 화면에 추가'를 선택합니다.
4. 설치 후 홈 화면 아이콘으로 실행합니다.

주의
- manifest와 Service Worker는 file:// 로 직접 연 HTML에서는 정상 동작하지 않습니다. HTTPS 또는 localhost 환경에서 사용해야 합니다.
- 이 패키지는 설치형 웹앱(PWA)입니다. Google Play 등록용 APK/AAB는 별도의 Android 빌드 과정이 필요합니다.
- 덕트 규격 추천은 v7 기준으로 후드 필요환기량과 사용자가 입력한 최소 반송속도만 사용하며, 압력손실은 반영하지 않습니다.

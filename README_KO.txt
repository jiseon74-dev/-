국소배기장치 계산기 PWA 배포 안내

1. GitHub 저장소의 기존 local_exhaust_airflow_calculator_v4.html 파일을 삭제하거나 이름을 바꿉니다.
2. 이 폴더 안의 모든 항목을 저장소 최상위(root)에 업로드합니다. 반드시 index.html, manifest.json, sw.js, 아이콘 PNG 파일도 index.html과 같은 위치에 있어야 합니다.
3. Commit changes를 누릅니다. Settings > Pages에서 main / (root) 설정을 유지합니다.
4. 배포가 끝나면 https://jiseon74-dev.github.io/-/ 를 Chrome에서 엽니다.
5. 이전에 추가한 홈 화면 바로가기가 있다면 삭제한 뒤 Chrome에서 새로고침합니다. 메뉴(⋮)에 '앱 설치'가 보이면 누릅니다. '홈 화면에 추가'만 보이면 그것을 선택하고, 사이트가 새로고침된 뒤 다시 확인합니다.

PWA는 별도 APK 설치 없이 브라우저에서 설치하는 웹앱입니다. 앱처럼 독립 창으로 열리고, 서비스 워커가 파일을 캐시하여 오프라인에서도 기본 계산 화면을 열 수 있도록 구성했습니다.

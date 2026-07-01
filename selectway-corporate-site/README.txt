SELECTWAY Corporate Website Sample

Netlify 업로드 방법
1. 이 zip 파일의 압축을 풉니다.
2. selectway-corporate-site 폴더를 엽니다.
3. Netlify의 Add new site > Deploy manually 화면에 selectway-corporate-site 폴더 전체를 드래그합니다.
4. index.html, services.html, education.html과 assets 폴더가 같은 위치에 있어야 이미지가 정상 표시됩니다.

파일 구조
- index.html: 메인 페이지
- services.html: 서비스 소개 페이지
- education.html: 기업교육 페이지
- assets/css/style.css: 공통 스타일
- assets/images/: 생성형 AI 이미지 에셋 3개

주의
이미지 경로는 ./assets/images/파일명.png 형태의 상대경로로 연결되어 있습니다.
Netlify에는 index.html만 올리지 말고 폴더 전체를 올려야 합니다.

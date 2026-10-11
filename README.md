# 안세은 Security Portfolio

포트폴리오와 경력기술서의 내용을 웹사이트로 재구성한 정적 사이트입니다.

- SentinelOne EDR 기반 MDR 운영과 네 가지 실무 사례
- AhnLab CERT 인턴 경험
- SCABLE, SBOM 대시보드, Phishime, 가상기업 컨설팅, 해커톤 보안 점검
- 프로젝트 분야 필터, 상세 보기, 경력 탭, 모바일 메뉴
- 학력, 활동, 수상, 연락처

## GitHub Pages 게시

이 저장소의 Settings → Pages에서 Source를 GitHub Actions로 선택합니다.
배포 워크플로가 main 브랜치의 사이트 파일을 게시합니다.
주소: https://seeunsama-cell.github.io/seeun-portfolio/

## 수정

index.html: 소개, 학력, 활동, 수상, 연락처와 사이트 구조
style.css: 색상, 글꼴, 반응형 배치
data.js: 프로젝트 상세와 경력 상세
app.js: 필터, 탭, 상세 보기, 모바일 메뉴

빌드 도구가 필요하지 않습니다. 로컬에서 index.html을 열거나 정적 웹서버로 확인할 수 있습니다.
Google Fonts를 이용하지만 접속하지 못할 때는 시스템 글꼴로 표시됩니다.

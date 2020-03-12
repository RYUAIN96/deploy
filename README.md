# deploy
deploy

# 세팅 절차
- 1. git에 새로운 저장소 생성 (deploy)
-    https://github.com/RYUAIN96/deploy.git
- 2. 로컬 PC에서 aws 폴더를 vs code에 오픈
- 3. terminal 오픈
- 4. $ git clone https://github.com/RYUAIN96/deploy.git 
- 5. cd deploy

# 파일 세팅 (~aws/deploy)
- 1. fabfile.py deploy.json 파일을 위치 시킴
- 2. 서버파일 생성
- 3. wsgi.py(엔트리포인트), run.py 생성
- 4. 코드 작성
- 5. 배포 관련 환경변수 파일 수정 (deploy.json)
- 6. git 주소, 서버의 IP, 도메인은 향후 IP와 연결(호스팅 쪽), 리눅스 접속 계정 IP 등 설정
- 7. requirements.txt : 본 서비스를 구동하기 위해 사용된 모든 파이썬 패키지를 기술한다

# 구동
- 1. python 버전 기반으로 수행
- 2. 운영체계 및 서버 세팅 및 배포, 업데이트 관리 등등을 자동화하는 모듈 => fabric3
- 3. $ pip3 install fabric3
- 4. git에 최종소스 반영
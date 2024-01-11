<!-- 도커 빌드 명령어 (이미지 실행 ) -->

docker build -t 패키지?/파일이름 위치
docker build -t ted2024/nodejs ./

<!-- 도커 실행 명령어 (이미지 실행 ) -->

docker run -d -p 3000:3000 --name nodejs ted2024/nodejs

<!-- 설명  -->

-d : 백그라운드 실행
-p : 포트포워딩
--name : 컨테이너 이름
ted2024/nodejs : 이미지 이름

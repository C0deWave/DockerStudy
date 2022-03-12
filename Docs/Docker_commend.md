## 본 페이지에서는 도커 명령어에 대해 정리해 본다.

0. mac에서 도커 실행하는 방법

    open --background -a Docker

1. 도커 이미지 검색
   
   docker search [centos]

   도커에서 해당 이미지에 대한 검색을 진행한다.

2. 도커 이미지 다운로드

    docker poll [centos:latest]

    해당 도커 이미지를 받습니다.

3. 도커 이미지 리스트 확인

    docker images

    현재 호스트에 받아져 있는 이미지를 받습니다.

4. 도커 실행하기

    docker run "REPOSITORY"

    도커 이미지를 실행합니다. 

    메인으로 실행되는 파일이 종료되는 경우에는 컨테이너도 같이 종료 됩니다.

    종료 하고 싶지 않다면 -d옵션을 이용하면 됩니다.

5. 실행중인 이미지 확인하기

    docker  ps

    현재 실행중인 이미지 목록을 확인합니다.

6. 종료된 컨테이너 시작

    docker start 'container ID'

7. 컨테이너에 접속하기

    docker attach 'containerID'

8. 컨테이너 종료하기

    docker stop 'containerID'

9.  컨테이너 삭제하기

    docker rm 'containerID'

10. docker 포트포워딩

    docker run it -p "HOST PORT:DockerPort" /bin/bash
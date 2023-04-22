# DockerFile Code

DockerFile은 Docker Image를 만들기 위한 설치 가이드북이라고 생각하시면 됩니다.

간단하게 프린터라고 보면 되는데, 프린터를 작동시키기 위해서는 파일, 프린터, 종이가 필요합니다. 

마찬가지로 Dockerfile은 이 중 파일을 만들어 생성하고 배포하는 문서입니다.

코드는 표와 같이 되어있습니다.

|코드|내용|
|:---:|:---:|
|[FROM](/server/container/Docker/DockerFile-Code/FROM.md)|이미지 출처|
|[RUN](/server/container/Docker/DockerFile-Code/RUN.md)|명령어 실행|
|[ENTRYPOINT](/server/container/Docker/DockerFile-Code/ENTRYPOINT.md)|이미지 중간 포인트 실행 명령어|
|[CMD](/server/container/Docker/DockerFile-Code/CMD.md)|이미지 최종 및 디폴트 실행 명령어|
|-------------|---------------------|
|[ENV](/server/container/Docker/DockerFile-Code/ENV.md)|이미지 환경변수 지정 명령어|
|[ADD](/server/container/Docker/DockerFile-Code/ADD.md)|파일 이미지 추가|
|[COPY](/server/container/Docker/DockerFile-Code/COPY.md)|이미지 생성 시 불러올 파일 호출|
|[VOLUME](/server/container/Docker/DockerFile-Code/VOLUME.md)|볼륨 폴더 지정 및 설정|
|-------------|---------------------|
|[USER](/server/container/Docker/DockerFile-Code/USER.md)|기본 계정 설정|
|[WORKDIR](/server/container/Docker/DockerFile-Code/WORKDIR.md)|기본 폴더 설정|
|[EXPOSE](/server/container/Docker/DockerFile-Code/EXPOSE.md)|기본 포트 설정|
|ONBUILD|~~저도 잘 모르겠습니다~~|
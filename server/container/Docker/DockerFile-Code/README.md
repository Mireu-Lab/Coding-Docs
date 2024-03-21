# DockerFile

DockerFile은 Docker Image를 만들기 위한 설치 가이드북이라고 생각하시면 됩니다.

간단하게 프린터라고 보면 되는데, 프린터를 작동시키기 위해서는 파일, 프린터, 종이가 필요합니다.

마찬가지로 Dockerfile은 이 중 파일을 만들어 생성하고 배포하는 문서입니다.

코드는 표와 같이 되어있습니다.

|              코드             |           내용          |
| :-------------------------: | :-------------------: |
|       [FROM](FROM.md)       |         이미지 출처        |
|        [RUN](RUN.md)        |         명령어 실행        |
| [ENTRYPOINT](ENTRYPOINT.md) |   이미지 중간 포인트 실행 명령어   |
|        [CMD](CMD.md)        |  이미지 최종 및 디폴트 실행 명령어  |
|        -------------        | --------------------- |
|        [ENV](ENV.md)        |    이미지 환경변수 지정 명령어    |
|        [ADD](ADD.md)        |       파일 이미지 추가       |
|        [COPY](../../)       |   이미지 생성 시 불러올 파일 호출  |
|  [VOLUME](broken-reference) |     볼륨 폴더 지정 및 설정     |
|        -------------        | --------------------- |
|      [USER](WORKDIR.md)     |        기본 계정 설정       |
| [WORKDIR](broken-reference) |        기본 폴더 설정       |
|  [EXPOSE](broken-reference) |        기본 포트 설정       |
|           ONBUILD           |    ~~저도 잘 모르겠습니다~~    |

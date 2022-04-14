# node image feature

node:<version>-slpine

- Alpine Linux is much smaller than most distribution base images (~5MB), and thus leads to much slimmer images in general.
  정말 최소기능만 들어가 있기때문에 종종 실행안되는 패키지가 있을 수 있음
  가급적 매우 native한 명령어를 쓰는 프로젝트에서만 써야함

node:<version>-buster

- This image is based on version 10 of Debian, available in the debian official image.

node:<version>-stretch

- This image is based on version 9 of Debian, available in the debian official image.

node:<version>-slim

- This image does not contain the common packages contained in the default tag and only contains the minimal packages needed to run node.

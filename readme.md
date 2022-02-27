# docker_study

### 도커를 공부하면서 ELK 스택을 구축해 보고자 합니다.

업데이트 예정
- [ ] Feat: ELK Stack TLS 암호화
- [ ] Docs: Docker 설명 추가하기 예제도 추가
- [ ] Docs: Elastic 내용 해석하기
- [ ] Feat: 추후에 직접 이미지 만들어 보기

-----

### 이론

* [서버 가상화의 종류](https://github.com/C0deWave/DockerStudy/blob/e66fab4dcab06607724824f193ea960a3e72fc91/Docs/%EC%84%9C%EB%B2%84%20%EA%B0%80%EC%83%81%ED%99%94%EC%9D%98%20%EC%A2%85%EB%A5%98.md)

---

* [도커란 무엇인가?](https://github.com/C0deWave/DockerStudy/blob/master/Docs/whatIsDocker.md)

* [도커 명령어 정리](https://github.com/C0deWave/DockerStudy/blob/master/Docs/Docker_commend.md)

---

ElasticSearch Docker TLS 암호화 하기

현재는 별다른 설정을 변경하지 않기 때문에 엘라스틱의 공식 문서를 보고 TLS 암호화를 진행했다. 추후에는 AWS와 같은 클라우드 서버에 올리는 작업까지 가서 공식 인증서와 아이피를 가지고 Elastic을 실행하는 것이 목표이다. 

[엘라스틱 - Docker 공식문서](https://www.elastic.co/guide/en/elasticsearch/reference/current/configuring-tls-docker.html)

현재는 공식 문서의 설명을 읽으면서 진행하는 정도만 해 보았다.

-----

도커 공부

우선은 명령어를 간단히 정리해 보았다.

commit 규칙
1. Feat : 새로운 내용 추가에 관한 커밋
2. Fix : 내용 오류 수정에 대한 커밋
3. Docs : Readme 개선
4. Refactor :  특정 주제해 대해 내용을 추가할 경우
5. Res: 이미지나 동영상 추가할 경우 사용
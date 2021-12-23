# docker_study

### 도커를 공부하면서 ELK 스택을 구축해 보고자 합니다.

업데이트 예정
- [ ] Feat: ELK Stack TLS 암호화
- [ ] Docs: Docker에 대한 설명이나 사용법 적기
- [ ] Docs: Elastic 내용 해석하기
- [ ] Feat: 추후에 직접 이미지 만들어 보기

최근 업데이트
- [X] Feat: elasticsearch TLS 암호화
- [X] Docs: readme 업데이트

---

ElasticSearch Docker TLS 암호화 하기

현재는 별다른 설정을 변경하지 않기 때문에 엘라스틱의 공식 문서를 보고 TLS 암호화를 진행했다. 추후에는 AWS와 같은 클라우드 서버에 올리는 작업까지 가서 공식 인증서와 아이피를 가지고 Elastic을 실행하는 것이 목표이다. 

[엘라스틱 - Docker 공식문서](https://www.elastic.co/guide/en/elasticsearch/reference/current/configuring-tls-docker.html)

현재는 공식 문서의 설명을 읽으면서 진행하는 정도만 해 보았다.

commit 규칙
1. Feat : 새로운 기능에 대한 커밋
2. Fix : 버그 수정에 대한 커밋
3. Build : 빌드 관련 파일 수정에 대한 커밋
4. Chore : 그 외 자잘한 수정에 대한 커밋
5. Ci : CI관련 설정 수정에 대한 커밋
6. Docs : 문서 수정에 대한 커밋
7. Style : 코드 스타일 혹은 포맷 등에 관한 커밋
8. Refactor :  코드 리팩토링에 대한 커밋
9. Test : 테스트 코드 수정에 대한 커밋

---
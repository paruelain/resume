---


---

<h1 id="kaon-eu">Kaon Eu</h1>
<h2 id="history">History</h2>
<p><em>(2019.4~)</em> Mathpresso Qanda 검색팀 리서치 엔지니어 (현)<br>
<em>(2019.1~2)</em> Reached reached io 소프트웨어 엔지니어<br>
<em>(2018.5~9)</em> 조이코퍼레이션 채널톡 백엔드 엔지니어<br>
<em>(2018.1~4)</em> (주) 첨단공간정보 공간정보연구소 개발파트장<br>
<em>(2017.8~2018.1)</em> 프로젝트 불편한 사람들<br>
<em>(2017.7~2017.8)</em> 네이버 디지털 콘텐츠 &amp; 오디오 플랫폼 개발 인턴<br>
<em>(2015.3~)</em> 서울대학교 컴퓨터공학부<br>
<em>(2012.3~2015.2)</em> 성보 고등학교 과학중점반</p>
<h2 id="project">Project</h2>
<h3 id="algorithm--big-data-handling">Algorithm &amp; Big Data Handling</h3>
<p><strong>Qanda 문제집 이미지 검색</strong></p>
<blockquote>
<p>ELK Stack, Airflow, AWS(EB, Lambda, S3), Go, Django, Sanic, Docker</p>
</blockquote>
<p>(OCR 데이터를 활용한) 검색에 필요한 전반적인 기술 총괄</p>
<ul>
<li>검색 품질 향상을 위한 알고리즘 연구 리딩</li>
<li>Airflow 데이터 파이프라인 책임</li>
<li>ElasticSearch Multi-Index Boosting 등을 통한 Index 튜닝</li>
<li>시간 복잡도 예측 기반 알고리즘 람다 분산 처리</li>
<li>MAU 200만 이상의 트래픽을 담당하는 서버 다수의 Infra 관리</li>
<li>개발 이슈 관리, 칸반 마스터</li>
</ul>
<p><strong>Naver Music 채널링 데이터 추적 및 관리</strong></p>
<blockquote>
<p>Spring, ELK Stack, MySQL</p>
</blockquote>
<p>기간·분야·검색어로 음악 데이터 조회</p>
<ul>
<li>ELK 비전문가 사용자를 위해 검색 인터페이스 제작</li>
<li>Load Balancing, Sharding, Fail Over 을 통한 서버 안정성 확보</li>
<li>데이터 변화를 한눈에 보기위한 강력한 Diff 기능</li>
</ul>
<p><strong>채널톡 데이터 센터</strong></p>
<blockquote>
<p>Flask, Celery, PostgreSQL, DynamoDB</p>
</blockquote>
<p>채널톡을 통해 생산된 메세지 통계를 제공</p>
<ul>
<li>Exel, JSON, CSV 형식을 지원</li>
<li>비동기이메일 전송 옵션</li>
<li>File Streaming</li>
</ul>
<h3 id="messaging--sns">Messaging &amp; SNS</h3>
<p><strong>채널톡(<a href="http://Channel.io">Channel.io</a>) 백엔드</strong></p>
<blockquote>
<p>Dropwizard(java), Jooq, Guice, Swagger</p>
</blockquote>
<p>홈페이지 방문자와 담당자 간의 메세지 서비스 제공</p>
<ul>
<li>오프라인의 경우, 휴대폰 문자 알림 (i18n)</li>
<li>마크 다운 형식의 메세지 포맷팅 지원</li>
<li>DI Mock 테스트 환경 구축 및 패턴 설계</li>
</ul>
<p><strong>Reached io MVP 구축</strong></p>
<blockquote>
<p>Spring Boot, Hibernate, Twitter, PayPal</p>
</blockquote>
<p>트위터 계정 연동을 통해 유명인사에게 비트코인으로 유료 질문하는 서비스</p>
<ul>
<li>다양한 종류의 코인 지갑</li>
<li>Twitter, Paypal API 연동</li>
<li>Spring Secure OAuth2</li>
</ul>
<h3 id="gi-service">GI Service</h3>
<p><strong>우리나라 지역별 음악 추천 프로그램</strong></p>
<blockquote>
<p>Django, Web Socket, NaverOpenAPI</p>
</blockquote>
<p>네이버 뮤직 로그들을 이용한 지역별 추천 음악 큐레이션</p>
<ul>
<li>데이터들의 대용량 Time Series Geo Data 분석 및 처리</li>
<li>다양한 서비스에서 발생한 데이터를 종합 후 추천하는 모델 연구</li>
<li>Naver OpenAPI 지도 기반의 웹 서비스</li>
</ul>
<p>물 사용량 관리 분석 플랫폼 연구 용역</p>
<blockquote>
<p>Egov Framework, Node.js, Jenkins KakaoOpenAPI</p>
</blockquote>
<p>지역별 수용가 물 사용량 요약 및 관망 분석 시뮬레이션</p>
<ul>
<li>실시간 지역 데이터 질의 인터페이스, 그래프 요약 대시보드 제작</li>
<li>GeoServer, KakaoOpenAPI 와 통신하여 관망 시뮬레이션 구현</li>
<li>서버 개발, CI, CD 셋팅</li>
</ul>
<p>프로젝트 불편한 사람들</p>
<blockquote>
<p>Django</p>
</blockquote>
<p>사회적 이슈였던 몰래 카메라의 장소를 지도 상에 공유, 범죄 예방 앱 서비스</p>
<ul>
<li>서비스 공동 기획, 크라우드 펀딩</li>
<li>장소 저장, 통계, 글 기능 개발</li>
<li>지역 위험 수치 알고리즘 연구</li>
</ul>
<h3 id="problem-solving">Problem Solving</h3>
<p><strong>Contest</strong></p>
<ul>
<li>2017 ACM-ICPC 대만 전국 본선 (화롄) (3등)</li>
<li>2017 ACM-ICPC 한국 전국 본선 (대전) (3등)</li>
<li>2017 ACM-ICPC 인터넷 예선 (5등)</li>
<li>Coder’s high 2016 본선 특별상</li>
</ul>
<p><strong>2,000 문제</strong> 이상의 고난이도 문제 해결 경험</p>
<h2 id="연락처-및-기타-정보">연락처 및 기타 정보</h2>
<ul>
<li>핸드폰: 010-2315-5592</li>
<li>이메일: <a href="mailto:wlxyzlw@gmail.com">wlxyzlw@gmail.com</a></li>
<li>집주소: 서울특별시 낙성대</li>
<li>이름: 유가온</li>
<li>생일: 1996-11-19</li>
</ul>
<h3 id="and-more...">and More…</h3>
<p>(last updated: 2020-04-25)</p>


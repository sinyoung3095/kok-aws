# kok(콕)

**프로젝트 홈페이지 url : kok-on.shop**

홈페이지 활성화 시간 : 10:00 ~ 22:00
테스트 ID/PW : test@gmail.com / 1234

<h1>직업 체험 프로젝트 - 'kok'</h1>


<h2>1. 기획 의도</h2>
<img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=2070" style = "width: 80%; height : 480">

경력직을 선호 하고 수시 채용에서 신입을 뽑지 않는 상황이 많아져서 <strong>청년층의 '쉬었음' 인구가 역대 최고치로 증가</strong> 했고 청년층 고용 한파가 계속 되었을 때 사회적인 문제로 자리 잡을 수 있다고 생각하였고 
경력을 쌓을 곳이 없는 청년층이 직장을 체험해 보고 더 나아가서는 취업으로 연계가 될 수 있는 직업 체험 사이트를 제작하기로 했습니다. 

</div>


<h2>2. 기대 효과</h2>
<img src="https://images.unsplash.com/photo-1507679799987-c73779587ccf?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1171" style = "width: 80%; height : 480">
STEP 1. 짧은 체험이지만 이력서보다 강한 ‘현장 경험’이 됩니다. 책이나 강의로는 알 수 없는 실제 직무의 결을 피부로 느낄 수 있습니다.<br>
STEP 2. 체험에서 채용까지, 자연스럽게 이어지는 성장의 흐름을 만들 수 있습니다.<br>
STEP 3. 처음 취업을 하는 청년들의 취업에 대한 부담감을 줄일 수 있고 취업이 어렵지 않은 일이라는 인식을 줄 수 있습니다.


<h2>3. 프로젝트 사용 툴</h2>
## 🛠️ 기술 스택 (Tech Stack)

| 구분 | 사용 기술 |
|------|------------|
| **HTML Engine** | Thymeleaf |
| **Frontend** | HTML, JavaScript, CSS |
| **Backend** | Spring Boot, Java |
| **Database** | PostgreSQL, Redis |
| **Infra** | AWS EC2, AWS IAM, AWS S3 |
| **Development Tools** | VS Code, IntelliJ IDEA |
| **API & Library** | Kakao Login, Kakao Map, Kakao 주소 API, SMTP Gmail API, REST API, Lombok, MyBatis, OAuth 2.0, Google Login, Boot Pay, Naver Login, JWT, Spring Security, CoolSMS, Swagger UI |
| **Collaboration & Version Control** | Git, GitHub, Slack, Postman, Sourcetree |
| **Testing** | JUnit5 |

  
<h2>4. 담당 업무</h2>
4-1 프론트엔드<br>
▶ 진행도
<img width="1010" height="250" alt="image" src="https://github.com/user-attachments/assets/8cc4e568-a662-49c3-b920-e964541fa9ca" />

<img width="1920" height="1342" alt="마이페이지-콕" src="https://github.com/user-attachments/assets/e6b5f412-eda9-4069-9aee-d3fb59f64b07" />

▶ 마이페이지
- 프로필 편집, 공유
- 내게시물
- 저장한 공고
- 지원내역
- 결제 내역
- 이력서 보관함
- 광고창
<img width="1920" height="1440" alt="커뮤니티-콕" src="https://github.com/user-attachments/assets/b007c933-b685-4ad7-87a2-ddd312477811" />


▶ 커뮤니티
- 커뮤니티 목록
- 댓글 및 답글 화면
- 신규 체험공고 목록
- 광고창
  


<br>
4-2 백엔드<br>
<br>
▶ ERD
<img width="100%" height="100%" alt="erd" src="https://github.com/user-attachments/assets/d1bd955f-eea4-45cf-a6fe-e83c092c3811" />
<br><br>
▶ 진행도
<img width="1838" height="342" alt="image" src="https://github.com/user-attachments/assets/6f99fcc2-cfff-4a81-a765-686e88fe7055" />

<br><br>
<img width="1920" height="910" alt="로그인-콕" src="https://github.com/user-attachments/assets/7021ea36-214c-4dc7-a891-1fbe8c3e670e" />

▶ 회원가입(일반회원, 기업회원)
- 아이디, 이메일 중복 검사
- 아이디, 이메일, 이름, 휴대폰 입력 형식 검사
- 필수 정보 입력 여부 검사
- 조건 충족 시 회원가입
- 카카오 Oauth를 이용한 간편 회원가입
- 네이버 Oauth를 이용한 간편 회원가입
- 구글 Oauth를 이용한 간편 회원가입

▶ 로그인(일반회원, 기업회원)
- Jwt security를 이용한 보안 로그인 기능 구현
- 카카오 Oauth를 이용한 간편 로그인
- 네이버 Oauth를 이용한 간편 로그인
- 구글글 Oauth를 이용한 간편 로그인
- 로그아웃 기능 구현

▶ 아이디 찾기(일반회원, 기업회원)
- 사용자가 입력한 전화번호로 인증번호 전송
- 인증 코드가 일치할 경우 아이디 표시 페이지 이동

▶ 비밀번호 찾기(일반회원, 기업회원)
- 사용자가 입력한 이메일로 인증링크 전송
- 인증 코드가 일치할 경우 비밀번호 변경페이지 이동
- 비밀번호 변경 구현
<br><br>
 <img width="1920" height="910" alt="체험공고-콕" src="https://github.com/user-attachments/assets/4d9b5371-e5bf-4158-a5fd-670e38324d70" />
 
▶ 헤더(일반회원, 기업회원)
- 헤더 드랍박스 기능 구현
- 일반 회원 지원내역 
- 로그아웃 구현

▶ 사이드바(일반회원, 기업회원)
- 알람 설정
- 프로필 정보 구현


<h2>5. 느낀점</h2>
<h3>5-1. 어려웠던 부분</h3>
📌jwt Security를 이용해서 보안을 높이고 사용하는데 있어서 다양한 오류를 직면 했고 전체 순환 구조를 이해하는데 힘들었고 <br>
✔ 단계가 익숙하지 않아 유지 보수가 어려웠지만, 구조를 익히고 수정하는 과정을 통해 파악을 더 잘할수 있게 되었습니다.<br><br>
<br>


<h3>5-2. 문제를 해결했던 부분</h3>



<h4>📌Oauth 계정의 accessToken의 재발급 오류</h4>
🌩문제 상황🌩<br>
<img width="1139" height="579" alt="oauth_reflesh_re_오류" src="https://github.com/user-attachments/assets/5b8ab062-2de0-495b-a7d9-34ef2528d763" />
<br><br>
<img width="1662" height="163" alt="oauth_reflesh_re_오류_2" src="https://github.com/user-attachments/assets/00bfa29c-75b0-4344-bb77-81e7806ab7bf" />
sns 간편로그인을 할 경우, accessToken의 기간이 다하여 사라졌을 때 refreshToken을 redis에 있는 토큰과 검사하여 인증 정보가 같으면 발급 해야 하는데 인증 단계에서 오류가 생겼습니다.<br><br>
🚨문제 원인🚨 <br>
<img width="1673" height="381" alt="oauth_reflesh_re_원인" src="https://github.com/user-attachments/assets/50202100-8169-48e5-957b-13155aefd7a0" />

refreshToken을 재발급 하는 과정에서 Oauth계정과 일반 로그인 계정의 분리를 하지 않아서 redis의 토큰과 accessToken 토큰의 인증 정보가 달라졌습니다. <br><br>
🚀해결 방법🚀<br>
<img width="1660" height="636" alt="oauth_reflesh_re_해결" src="https://github.com/user-attachments/assets/2e4aa659-a1f3-4e53-86d9-ffd6994430a3" />

재발급하는 과정에서 provider 쿠키를 받아와서 일반 계정과 Oauth 계정의 차이를 구분하여 재발급하는 과정을 다르게 했습니다. 
<br><br><br>



<h4>📌메인페이지 헤더와 사이드바의 객체 인식 오류</h4> <br>
🌩문제 상황🌩<br>

<img width="1919" height="916" alt="profile_오류-1" src="https://github.com/user-attachments/assets/3be08d42-a1fe-490f-8cf3-066de3dd1739" />

메인페이지의 헤더와 사이드바를 다른 페이지에서 합치는 과정에서 MemberDTO 객체의 인식이 안됐습니다.<br><br>
🚨문제 원인🚨 <br>
합쳐지는 각 페이지의 memberDTO 객체가 Model 객체에 추가되는 서비스가 달라서 헤더와 사이드바와는 다른 객체가 들어가게되는 경우가 생겨서 인식이 안됐습니다. <br><br>
🚀해결 방법🚀<br>
<img width="1211" height="517" alt="image" src="https://github.com/user-attachments/assets/8680172a-c0a6-4175-8b6b-3dba94bc8882" />

intercepter를 이용해서 헤더와 사이드바가 들어가는 페이지에 객체를 전달하여 객체 인식을 동일하게 맞췄습니다.
<br><br><br>



<h4>📌PostgreSql의 enumuration 오류</h4> <br>
🌩문제 상황🌩<br>
<img width="1254" height="933" alt="enum오류-1" src="https://github.com/user-attachments/assets/5a52a938-18e5-4f00-8897-e8f0a3bc96f0" />
Enum의 인식에 문제가 있었습니다.
<br><br>
🚨문제 원인🚨 <br>
<img width="1421" height="345" alt="enum오류-3" src="https://github.com/user-attachments/assets/b251d08d-bad1-4998-8a9f-c9271e0c8c80" />
MySql과는 다르게 PostgreSql은 enum을 객체로 인식하기 때문에 재정립하는 방법이 달랐습니다.
 <br><br>
🚀해결 방법🚀<br>
<img width="1394" height="561" alt="enum오류-해결" src="https://github.com/user-attachments/assets/10a4120d-624f-4fa4-bdec-63c2b6faa33a" />
핸들러에서 객체로 세팅해주어 인식의 오류를 해결했습니다.



<h3>5-3. 총평</h3>
<h4>🌟 기획: 완벽한 기획이란 없다.  </h4>
 기획을 하는 과정에서 충분하다고 생각하여 개발을 시작했으나 중간에 필요한 부분이 생기거나 아주 세세한 부분에서 문제가 생긴다는 것을 알게 됐습니다. 예로 user테이블에서 member테이블과 company테이블로 fk를 주었고 profile사진을 저장하는 중간 테이블이 user_profile테이블과 company_profile테이블로 나눠져서 서로 저장하는 위치가 헷갈려서 user_profile테이블에 전체 저장하는 팀원과 company_profile에 따로 저장하는 팀원이 생겨났습니다.

<h4>🌟 협업: 소통은 바로바로 해야한다. </h4>
 팀원들과의 소통에는 자신있었다. 그러나 사이의 원만함과 빈도수와는 별개로 프로젝트 진행 시 나의 작업 상황 진행과 오류 발생 부분, 백업을 어디까지 했는지 등 상세하고 자세하게 공유해야 한다는 것을 알게 되었다. 예를 들어 프로젝트 작업 중 깃허브에서 충돌이 발생하여 브랜치 생성 시 이 내용까지 공유하지 않으면, 다른 팀원들의 코드에도 영향을 미칠 수 있으며, 이 사실을 모르는 팀원이 직접 해결하기까지는 적지 않은 시간이 소요된다는 것을 알게 되었다.


<h4>🌟앞으로의 계획: 더욱 발전하는 개발자가 되자. </h4>
 이번 프로젝트에서는 처음 접해보는 Oauth와 Jwt Security를 구현해보았다. 클라이언트가 모르는 뒤에서 얼마나 많은 작업이 이루어 지고 그 과정이 보안에 직접적으로 연결된다는 점을 이해하게 되었습니다. 물론 처음이라 어려웠지만, 주변의 도움과 코드 이해를 통하여 오류를 하나하나 해결해 갔고 끝에는 제대로 작동하게 만들어서 뿌듯함을 느낄수 있었습니다. 앞으로 더 많은 기술들을 접목해서 다양한 기능을 구현을 해보고싶다는 생각을 가지게 되었습니다. 

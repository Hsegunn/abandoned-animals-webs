## 유기동물 입양사이트 프로젝트

### 문의제보 - QnA폼 만들기
#### 제목 , 작성자, 카테고리, 전화번호, 이메일, 첨부파일, 내용작성, 등록 및 취소버튼 구현

##### 제목 입력창 구현

- 부트스트랩의 form-group 클래스로, 입력 필드와 레이블을 묶어서 레이아웃을 정리

![제목코드](https://raw.githubusercontent.com/Hsegunn/abandoned-animals-webs/main/img/image01.png)

- 부트스트랩 form-control을 이용하여 입력창 디자인 설정 
- placeholder를 이용하여 작성예시 출력
- css파일로 container 클래스의 너비 제한(max-width: 800px로 고정)

![제목](https://raw.githubusercontent.com/Hsegunn/abandoned-animals-webs/main/img/image02.png)

##### 작성자 및 카테고리 구현

- 레이블과 인풋을 label for로 연결
- 부트스트랩의 form-label 클래스로, 레이블의 기본 스타일을 적용
- 부트스트랩의 form-control 클래스로, 입력 필드와 선택 상자에 기본 스타일을 적용
- placeholder를 이용하여 작성예시 출력

![작성자카테고리코드](https://raw.githubusercontent.com/Hsegunn/abandoned-animals-webs/main/img/image03.png)

![작성자카테고리](https://raw.githubusercontent.com/Hsegunn/abandoned-animals-webs/main/img/image04.png)

- 카테고리에 style="margin-left: 10px 을 적용해서 간격조정

![작성자카테고리수정](https://raw.githubusercontent.com/Hsegunn/abandoned-animals-webs/main/img/image05.png)

- 드롭다운 선택 필드로, 사용자가 카테고리를 선택할 수 있게 적용

![작성자카테고리작동](https://raw.githubusercontent.com/Hsegunn/abandoned-animals-webs/main/img/image06.gif)

##### 전화번호 및 이메일 구현

- 레이블과 인풋을 label for로 연결
- 부트스트랩의 form-label 클래스로, 레이블의 기본 스타일을 적용
- 부트스트랩의 form-control 클래스로, 입력 필드와 선택 상자에 기본 스타일을 적용

![전화번호이메일코드](https://raw.githubusercontent.com/Hsegunn/abandoned-animals-webs/main/img/image07.png)

- placeholder를 이용하여 작성예시 출력

![전화번호이메일](https://raw.githubusercontent.com/Hsegunn/abandoned-animals-webs/main/img/image08.png)

##### 사진첨부 구현

- 레이블과 인풋을 label for로 연결
- input 타입을 file로 설정하여 사진첨부 기능설정

![사진첨부코드](https://raw.githubusercontent.com/Hsegunn/abandoned-animals-webs/main/img/image09.png)

- 사진첨부확인

![사진첨부코드](https://raw.githubusercontent.com/Hsegunn/abandoned-animals-webs/main/img/image10.gif)

##### 내용입력 구현

- 레이블과 인풋을 label for로 연결
- textarea로 텍스트박스 생성 rows의 값을 10으로 줘서 크기조절

![내용입력코드](https://raw.githubusercontent.com/Hsegunn/abandoned-animals-webs/main/img/image11.png)

- 내용작성확인

![사진첨부코드](https://raw.githubusercontent.com/Hsegunn/abandoned-animals-webs/main/img/image12.gif)

##### 등록 및 취소버튼 구현

- div class를 btn-container로 선언
- 버튼타입을 등록은 submit, 취소는 reset으로 설정

![내용입력코드](https://raw.githubusercontent.com/Hsegunn/abandoned-animals-webs/main/img/image13.png)

- 버튼호버를 이용하여 커서를 올리면 색이 바뀜

![내용입력코드](https://raw.githubusercontent.com/Hsegunn/abandoned-animals-webs/main/img/image14.gif)
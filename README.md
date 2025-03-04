</br>
<div align=center>

## ABBBA’s Memory...

</br>
실시간 이미지 컨텐츠 기록. 그리고 지난 세월의 추억 담을 수 있는</br>
*ABBBA's Memory,,,* 프로젝트 입니다.
</br></br>

</div>
</br></br></br>

#### **프로젝트 개요**

1. 프로젝트 소개
2. API
3. 프로젝트 주요 기능 (핵심 기능 페이지 몇 가지 캡처 혹은 시연 영상 첨부)
4. 팀 소개 - 프로젝트 마무리
</br></br></br></br>

>### 프로젝트 소개

Django, 머신러닝 사물 인식 알고리즘 중 YOLO v5 를 사용하여 업로드한 이미지를 분석, 이미지에서 인식한 사물 인덱스를 태그로 함께 저장한 뒤<br> 검색으로 태그에 맞는 이미지를 분류하는 서비스를 구현했습니다. 

</br></br></br>

>### 와이어프레임
<img width="1032" alt="스크린샷 2022-10-17 11 39 24" src="https://user-images.githubusercontent.com/18550082/197095801-c32b31e7-de86-4674-85b7-c116ae6d5d32.png">

</br></br></br>


>### API
<img width="913" alt="스크린샷 2022-10-21 오전 11 02 32" src="https://user-images.githubusercontent.com/18550082/197094097-ff51ed5f-6f33-4ee1-851d-ce7a72361616.png">


</br></br></br>

>### 프로젝트 주요 기능

#### 사물 인식 yolo v5

- 이미지를 업로드 후 저장하면 YOLO v5가 이미지에서 인식한 사물 인덱스를 태그로 저장합니다.
- 저장된 이미지에서는 이미지를 태그로도 확인할 수 있습니다.
- 메인 화면의 업로드된 이미지들 중에서 태그로 검색하면, 태그에 맞는 이미지만 분류하여 확인할 수 있습니다.
- 이미지에 달린 태그를 클릭하면 해당 태그가 달린 이미지를 모두 분류하여 볼 수 있습니다.
</br>

#### 이미지 업로드 포스팅, 수정, 삭제 / 댓글 등록, 수정, 삭제

- 이미지 파일을 선택하면 게시할 이미지를 미리 확인할 수 있습니다. 이미지와 내용도 함께 작성할 수 있어요.
- 이미지 게시물은 이미지와 내용 모두 수정하고 삭제할 수 있습니다.
- 게시된 이미지에서 댓글을 등록하고 댓글을 수정하거나 삭제할 수 있습니다.
</br>

#### 태그 검색으로 원하는 이미지 검색

- 태그를 검색하면 태그에 해당되는 이미지만 분류됩니다.
- 아무것도 검색하지 않으면, 태그가 없는 이미지만 분류됩니다.
</br>

#### 이미지 포스트에 좋아요💗 하기

- 검색된 이미지 포스트에서 좋아요를 할 수 있습니다.
- 좋아요한 개수도 확인할 수 있습니다.
</br>

#### 소셜 로그인(카카오) / 회원가입 후 서비스 사용 가능

- 회원가입 창에서 카카오 로그인을 선택하면 카카오 로그인을 시도한 최초에만 카카오 계정으로 회원가입을 하고, 그 뒤로는 계속 카카오 로그인 버튼 한 번으로 로그인을 할 수 있습니다.
- 아이디 / 비밀번호로 회원 가입과 로그인이 가능합니다. 이미지 게시글 등록과 검색, 댓글 등록 모두  회원가입 후 로그인한 사용자만 사용할 수 있습니다.
- 수정 페이지를 제외한 모든 페이지에서 현재 로그인한 사용자를 확인할 수 있습니다.
- 로그인한 사용자만 좋아요를 누를 수 있습니다.
- 로그아웃된 상태로 접속하면 게시글 업로드 기능과 댓글 업로드 기능을 사용할 수 없습니다.
- 게시글과 댓글 기능에서 작성한 사용자 확인이 가능합니다.
- 동일한 아이디 가입 중복을 막아뒀습니다.
</br>

#### 마우스 호버 기능

- 메인 화면에서 마우스 포인트를 사진에 위치하면, 사진 확대 전환 효과를 확인하실 수 있습니다.
- 페이지 네이션 부분에도 마우스 호버 기능을 추가했습니다.

</br></br></br></br>

>### 프로젝트를 마치며, 팀 소개

#### 프로젝트를 마치며

- 추후, **유지 보수** 및 **업데이트**가 **진행될 예정** 입니다.
- 프로젝트를 보시고 궁금하신 점이나 알려주고 싶으신 점은 언제든 공유해주세요!
</br>

#### 팀 소개

저희는 스파르타코딩클럽 내일배움캠프 3기 5인으로 구성된 팀입니다.
|**김민규**|오민규|윤민성|윤장미|이금빈|
|:---:|:---:|:---:|:---:|:---:|
|Contact:[:electric_plug:](https://kmg0485.tistory.com/)|Contact:[:bulb:](https://dhalsrbbbbbbb.tistory.com/)|Contact:[:computer:](https://tweakycoding.tistory.com/)|Contact:[:sunglasses:](https://velog.io/@r5zyoon)|Contact:[:sparkling_heart:](https://lgb9811.tistory.com/)|
</br>
</br>

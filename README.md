# Dienstag
- '디엔스탁'은 '프라이탁' 홈페이지를 모티브로 구현한 프로젝트입니다. 쇼핑몰의 기본적인 기능들을 구현했습니다. 사용된 이미지는 전부 직접 찍고 편집한 사진들임을 밝힙니다.
- 개발 기간: 2021.02.15 ~ 2021.02.26
- 개발 인원:  Back 3명 / Front 2명
- 기술 스택: Python, Django, MySQL, AQueryTool, Git

## 프로젝트 진행 방식
- Trello, Slack 앱을 활용해 Scrum 방식으로 진행
![trello](https://user-images.githubusercontent.com/72085261/109430747-3c209600-7a46-11eb-9a5a-49780b91f427.gif)

## 백엔드 전체 구현 목록
#### 회원가입 & 로그인
- Bcrypt를 활용한 비밀번호 암호화
- JWT를 활용한 Access Token 발행
- 로그인 @decorator 
#### 상품 리스트 나열
- 가방 타입 내의 모델별 리스트 나열 기능 <br>
![typelist](https://user-images.githubusercontent.com/72085261/109441202-f2e93a00-7a77-11eb-8371-e303c2ffd95b.gif)<br>
- 모델별 상세페이지 리스트 나열 & detail 정보 전달 & 추천 상품 목록 전달<br>
![detail](https://user-images.githubusercontent.com/72085261/109441299-465b8800-7a78-11eb-988e-5f93193d4647.gif)<br>
- 컬러, 사이즈 별 상품 필터링<br>
![filtering](https://user-images.githubusercontent.com/72085261/109441319-54110d80-7a78-11eb-8048-68dd54645919.gif)<br>

#### 장바구니 & 결제
- 장바구니에 상품 추가
- 장바구니에 있는 상품 삭제
- 전달받은 결제정보(billing address & shipping address) 저장
- 주문 상태 저장

## Reference
- 이 프로젝트는 <a href="http://www.freitag.ch/">프라이탁</a> 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.

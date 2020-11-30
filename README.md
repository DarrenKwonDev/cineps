# CINEPS

<div align="center">
  <img src="./thumbnail.png" width=300>
</div>

## 영화를 통해 연결을 꿈꾸는 예술 비평, 창작 커뮤니티 Cineps

영화 동아리의 사이드 프로젝트로 만든 게시판형 커뮤니티입니다.  

[개발 후기 ](https://darrengwon.tistory.com/category/%F0%9F%93%91%20Project/%F0%9F%93%91%20Next-Cineps%20%EA%B0%9C%EB%B0%9C%20%EC%9D%BC%EC%A7%80)

[cineps 바로가기](https://cineps.net)

## Tech Stack

- [x] Next
- [x] Express
- [x] Redux
- [x] NginX Reverse-proxy
- [x] AWS

## 주의!!  
유저 정보를 아예 삭제하면 기존에 유저 정보를 이용하는 모든 로직이 깨집니다.  
따라서, 유저 record를 아예 삭제하는 것이 아니라 delete column을 별도로 만들어 처리하는 것이 좋습니다.  

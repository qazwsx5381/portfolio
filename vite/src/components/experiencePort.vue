<template>
  <div>
    <div class="title"><h3 class="title">Project Experiences</h3></div>
    <div class="block">
      <img src="../assets/project.gif" alt="" class="img" />
      <div class="content">
        <span>프로젝트 실습('17.03 ~ '17.12)</span>
        <span>주제 : 아두이노를 활용한 도어락 만들기</span>
        <span>담당역할 : 아두이노 회로도 조사 및 정리</span>
        <span>특이사항</span>
        <span>- C언어 프로그래밍을 접해봄</span>
        <span>- 프로젝트 도중 취업으로 인해 완성까지 지켜보지 못함.</span>
      </div>
    </div>
    <div class="block">
      <img src="../assets/project_1.gif" alt="" class="img" />
      <div class="content">
        <span>게시판 project('23.05)</span>
        <span>주제 : 지금까지 배운 것을 활용한 게시판 만들기</span>
        <span>담당역할</span>
        <span>- 팀장 / LocalStorage 관련 Javascript 코드 작성.</span>
        <span>- CSS 및 HTML 코드 정리</span>
        <span>특이사항</span>
        <span
          >- 팀장으로서 자료 정리와 팀원 관리를 함께 하는 것이 얼마나 어려운지
          알게됨</span
        >
      </div>
    </div>
    <div class="block">
      <img src="../assets/project_2.gif" alt="" class="img" />
      <div class="content">
        <span>Vuejs를 활용한 채팅프로그램('23.06)</span>
        <span>주제 : Vuejs 및 Nodejs, socketio를 활용한 채팅앱 만들기</span>
        <span>담당역할</span>
        <span
          >- Vuejs(Client)와 Nodejs(Server) 사이에 Socketio를 활용한 채팅
          송·수신 구현</span
        >
        <span>특이사항</span>
        <span
          >- HTML로 배운 뒤 Vuejs에 적용하는 과정에서 시간 소요가 많이 됨.</span
        >
        <span
          >- 위 특이사항으로 인해 구현하고자 했던 기능 중 일부 기능을 구현하지
          못함</span
        >
        <span> (로그인, 1대1채팅 등)</span>
      </div>
    </div>
    <div class="block">
      <img src="../assets/project_3.gif" alt="" class="img" />
      <div class="content">
        <span>Tensorflow 프로젝트('23.08 ~ '23.09)</span>
        <span
          >주제 : Vuejs 및 Nodejs, Tensorflow를 활용한 도서 홈페이지
          만들기</span
        >
        <span>담당역할</span>
        <span>- 팀장 / BackEnd(Nodejs / api)와 DB</span>
        <span>특이사항</span>
        <span
          >- BackEnd와 DB 간 연결은 크게 문제 없었으나 Tensorflow 적용점이
          모호한 부분이 있어 아쉬웠음.</span
        >
      </div>
    </div>
  </div>
</template>
<script></script>
<style scoped>
div {
  margin-top: 100px;
  font-family: 'SBAggroB';
  width: 1000px;
  display: flex;
  flex-direction: column;
}
h3.title {
  font-size: 2.3rem;
  text-shadow: 3px 3px 2px gray;
  margin-left: 30px;
  margin-bottom: 30px;
}
span {
  width: 800px;
  margin: 10px 30px;
}
div.block {
  border: 3px double black;
  padding: 10px;
  margin: 10px 0 25px 0;
  display: flex;
  flex-direction: row;
  align-items: center;
  background-color: linear-gradient(rgba(0, 0, 0), rgb(228, 142, 142));
}
div.block img.img {
  width: 400px;
  border: 1px solid black;
  box-shadow: 3px 3px 10px gray;
}
div.block div.content {
  margin: 0;
}
div.block span {
  width: 550px;
}
</style>

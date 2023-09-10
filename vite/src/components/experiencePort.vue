<template>
  <div>
    <div class="title"><h3 class="title">Project Experiences</h3></div>
    <div class="block">
      <img src="../assets/project.gif" alt="" class="img" />
      <div class="content">
        <span>프로젝트 실습('17.03 ~ '17.12)</span>
        <span>주제 : 아두이노를 활용한 도어락 만들기</span>
        <span>담당역할 : 아두이노 회로도 조사 및 정리</span>
        <span>결과 및 느낀점</span>
        <span>- 프로젝트 도중 취업으로 인해 완성시키지 못함.</span>
      </div>
    </div>
    <div class="block">
      <img src="../assets/project.gif" alt="" class="img" />
      <div class="content">
        <span>게시판 project('23.05)</span>
        <span>주제 : 지금까지 배운 것을 활용한 게시판 만들기</span>
        <span>담당역할</span>
        <span>- 팀장 및 LocalStorage 관련 Javascript 코드 작성.</span>
        <span>- CSS 및 HTML 코드 정리</span>
        <span>결과 및 느낀점</span>
        <span
          >- 팀장으로서 자료 정리와 팀원 관리를 함께 하는 것이 얼마나 어려운지
          느낌</span
        >
      </div>
    </div>
    <div class="block">
      <img src="../assets/project.gif" alt="" class="img" />
      <div class="content">
        <span>Vuejs를 활용한 채팅프로그램('23.06)</span>
        <span>주제 : Vuejs 및 Nodejs, socketio를 활용한 채팅앱 만들기</span>
        <span>담당역할</span>
        <span
          >- Vuejs(Client)와 Nodejs(Server) 사이에 Socketio를 활용한 채팅
          송·수신 구현</span
        >
        <span>결과 및 느낀점</span>
        <span
          >- HTML로 배운 뒤 Vuejs에 적용하는 과정에서 많은 공부가 되었음.</span
        >
        <span
          >- Vuejs에 적용하는 과정에 있어 하고자 했던 기능들 중 일부 구현하지
          못함.</span
        >
        <span> (로그인, 1대1채팅 등)</span>
      </div>
    </div>
    <div class="block">
      <img src="../assets/project.gif" alt="" class="img" />
      <div class="content">
        <span>Tensorflow 프로젝트</span>
        <span
          >주제 : Vuejs 및 Nodejs, Tensorflow를 활용한 도서 홈페이지
          만들기</span
        >
        <span>담당역할</span>
        <span>- 팀장 / BackEnd(api)와 DB</span>
        <span>결과 및 느낀점</span>
        <span>- API를 적용하는 중 </span>
        <!-- <span
          >- Vuejs에 적용하는 과정에 있어 하고자 했던 기능들 중 일부 구현하지
          못함.</span
        >
        <span> (로그인, 1대1채팅 등)</span> -->
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
  margin: 10px 0;
  display: flex;
  flex-direction: row;
  background-color: linear-gradient(rgba(0, 0, 0), rgb(228, 142, 142));
}
div.block img.img {
  width: 400px;
}
div.block span {
  width: 550px;
}
</style>

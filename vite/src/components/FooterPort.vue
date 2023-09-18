<template>
  <footer>
    <hr />
    <div>
      <span>제작자 : 류예찬</span>
      <span
        ><a href="https://github.com/qazwsx5381/portfolio/" target="_blank"
          >portfolio github</a
        ></span
      >
      <span>이 홈페이지는 Vuejs로 제작되었습니다.</span>
    </div>
  </footer>
</template>
<script></script>
<style scoped>
footer {
  font-family: 'SBAggroB';
  margin-top: 30px;
}
div {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin: 20px 0;
}
a {
  text-decoration-line: none;
}
div span:last-child {
  margin-top: 10px;
}
</style>

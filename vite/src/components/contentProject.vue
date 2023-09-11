<template>
  <div>
    <Chart id="Chart" />
    <Project id="Project" />
    <Experience id="Experience" />
    <Introduce id="Introduce" />
  </div>
</template>
<script>
import Chart from './chartPort.vue'
import Project from './projectPort.vue'
import Introduce from './introducePort.vue'
import Experience from './experiencePort.vue'
export default {
  name: 'contentP',
  components: {
    Chart,
    Project,
    Introduce,
    Experience
  },
  methods: {
    scrollClass() {
      const Chart = document.querySelector('#Chart')
      const Project = document.querySelector('#Project')
      const Introduce = document.querySelector('#Introduce')
      const Experience = document.querySelector('#Experience')
      if (window.scrollY >= 750) {
        Chart.className = 'scroll'
      }
      if (window.scrollY >= 1300) {
        Project.className = 'scroll'
      }
      if (window.scrollY >= 2000) {
        Experience.className = 'scroll'
      }
      if (window.scrollY >= 3300) {
        Introduce.className = 'scroll'
      }
    }
  },
  mounted() {
    document.addEventListener('scroll', this.scrollClass)
  }
}
</script>
<style scoped>
div {
  width: 1000px;
  height: auto;
  margin: 0 auto;
}
@keyframes moveUp {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
#Introduce,
#Experience,
#Chart,
#Project {
  opacity: 0;
}
.scroll {
  opacity: 1;
  animation: moveUp 2s linear forwards; /* 애니메이션 이름, 지속 시간 및 타이밍 함수 설정 */
}
@keyframes moveUp {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>

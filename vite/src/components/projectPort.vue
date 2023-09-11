<template>
  <div style="margin-top: 200px">
    <div class="tool">
      <h3 class="title">Project</h3>
      <h3>누르면 github로 연결됩니다.</h3>
    </div>
    <div class="project_content">
      <a href="https://github.com/qazwsx5381/Team3" target="_blank"
        ><div
          class="project"
          title="기본적인 HTML/CSS/JS 학습 내용을 토대로 게시판 사이트 구성해보기."
          :style="style1"
        >
          게시판 Project
        </div></a
      >
      <a href="https://github.com/qazwsx5381/NoticeBoard_ryc" target="_blank"
        ><div class="project" :style="style2">개인게시판</div></a
      >
      <a
        href="https://www.figma.com/proto/wtkYR1OGOCIhPXlSVIEbR8/Untitled?type=design&node-id=29-2438&t=jzncZdJQbtrpTMhP-1&scaling=scale-down&page-id=0%3A1&starting-point-node-id=29%3A2438&mode=design"
        target="_blank"
      >
        <div
          class="project"
          :style="style3"
          title="Figma를 활용해 야구어플을 만들었습니다."
        >
          Figma
        </div></a
      >
      <a href="https://github.com/qazwsx5381/telegramBot" target="_blank">
        <div class="project" :style="style4">telegram Bot</div></a
      >
      <a href="https://github.com/qazwsx5381/chat_program" target="_blank">
        <div class="project" :style="style5">Vue를 활용한 채팅프로그램</div></a
      >
      <a href="https://github.com/qazwsx5381/VUE-project" target="_blank">
        <div class="project" :style="style6">Api를 활용한 프로젝트</div></a
      >
      <a
        href="https://github.com/qazwsx5381/tensorFlow-Father-Son-"
        target="_blank"
      >
        <div class="project" :style="style7">Tensorflow 머신러닝</div></a
      ><a
        href="https://github.com/qazwsx5381/mosaic_tensor
"
        target="_blank"
      >
        <div class="project" :style="style8">실시간 모자이크</div></a
      ><a href="https://github.com/qazwsx5381/tensor-Project" target="_blank">
        <div class="project" :style="style9">Tensorflow 프로젝트</div></a
      >
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      style1: { backgroundColor: 'black', color: 'white' },
      style2: { backgroundColor: 'black', color: 'white' },
      style3: { backgroundColor: 'black', color: 'white' },
      style4: { backgroundColor: 'black', color: 'white' },
      style5: { backgroundColor: 'black', color: 'white' },
      style6: { backgroundColor: 'black', color: 'white' },
      style7: { backgroundColor: 'black', color: 'white' },
      style8: { backgroundColor: 'black', color: 'white' },
      style9: { backgroundColor: 'black', color: 'white' }
    }
  },
  mounted() {
    this.change()
    this.change1()
    this.change2()
    this.change3()
    this.change4()
    this.change5()
    this.change6()
    this.change7()
    this.change8()
  },
  methods: {
    change() {
      const style = document.getElementsByClassName('project')[0]
      const p = document.createElement('p')
      style.addEventListener('mouseover', () => {
        this.style1 = {
          backgroundColor: '#2e8b57',
          color: 'white ',
          transition: '0.5s',
          textAlign: 'center'
        }
        p.style.cssText =
          'margin:15px 0; border-top: 1px solid black; padding-top: 20px;'
        p.innerHTML = 'LocalStorage를 활용한 게시판'
        style.append(p)
      })
      style.addEventListener('mouseleave', () => {
        this.style1 = {
          backgroundColor: 'black',
          color: 'white',
          transition: '0.5s'
        }
        style.removeChild(p)
      })
    },
    change1() {
      const style = document.getElementsByClassName('project')[1]
      const p = document.createElement('p')
      style.addEventListener('mouseover', () => {
        this.style2 = {
          backgroundColor: '#4682b4',
          color: 'white',
          transition: '0.5s',
          textAlign: 'center'
        }
        p.style.cssText =
          'margin:15px 0; border-top: 1px solid black; padding-top: 20px'
        p.innerHTML = 'LocalStorage를 활용한 게시판'
        style.append(p)
      })
      style.addEventListener('mouseleave', () => {
        this.style2 = {
          backgroundColor: 'black',
          color: 'white',
          transition: '0.5s'
        }
        style.removeChild(p)
      })
    },
    change2() {
      const style = document.getElementsByClassName('project')[2]
      const p = document.createElement('p')
      style.addEventListener('mouseover', () => {
        this.style3 = {
          backgroundColor: '#800000',
          color: 'white',
          transition: '0.5s',
          textAlign: 'center'
        }
        p.style.cssText =
          'margin:15px 0; border-top: 1px solid black; padding-top: 20px'
        p.innerHTML = 'Figma를 활용한 야구어플'
        style.append(p)
      })
      style.addEventListener('mouseleave', () => {
        this.style3 = {
          backgroundColor: 'black',
          color: 'white',
          transition: '0.5s'
        }
        style.removeChild(p)
      })
    },
    change3() {
      const style = document.getElementsByClassName('project')[3]
      const p = document.createElement('p')
      style.addEventListener('mouseover', () => {
        this.style4 = {
          backgroundColor: '#ff77ff',
          color: 'black',
          transition: '0.5s',
          textAlign: 'center'
        }
        p.style.cssText =
          'margin:15px 0; border-top: 1px solid black; padding-top: 20px'
        p.innerHTML = 'Nodejs를 활용한 telegram Bot'
        style.append(p)
      })
      style.addEventListener('mouseleave', () => {
        this.style4 = {
          backgroundColor: 'black',
          color: 'white',
          transition: '0.5s'
        }
        style.removeChild(p)
      })
    },
    change4() {
      const style = document.getElementsByClassName('project')[4]
      const p = document.createElement('p')
      style.addEventListener('mouseover', () => {
        this.style5 = {
          backgroundColor: '#708090',
          color: 'white',
          transition: '0.5s',
          textAlign: 'center'
        }
        p.style.cssText =
          'margin:15px 0; border-top: 1px solid black; padding-top: 20px'
        p.innerHTML = 'Vuejs로 만든 채팅프로그램입니다.'
        style.append(p)
      })
      style.addEventListener('mouseleave', () => {
        this.style5 = {
          backgroundColor: 'black',
          color: 'white',
          transition: '0.5s'
        }
        style.removeChild(p)
      })
    },
    change5() {
      const style = document.getElementsByClassName('project')[5]
      const p = document.createElement('p')
      style.addEventListener('mouseover', () => {
        this.style6 = {
          backgroundColor: 'white',
          color: 'black',
          transition: '0.5s',
          textAlign: 'center'
        }
        p.style.cssText =
          'margin:15px 0; border-top: 1px solid black; padding-top: 20px'
        p.innerHTML = 'Vuejs, Nodejs, MongoDB를 활용한 프로젝트입니다.'
        style.append(p)
      })
      style.addEventListener('mouseleave', () => {
        this.style6 = {
          backgroundColor: 'black',
          color: 'white',
          transition: '0.5s'
        }
        style.removeChild(p)
      })
    },
    change6() {
      const style = document.getElementsByClassName('project')[6]
      const p = document.createElement('p')
      style.addEventListener('mouseover', () => {
        this.style7 = {
          backgroundColor: '#ffa500',
          color: 'black',
          transition: '0.5s',
          textAlign: 'center'
        }
        p.style.cssText =
          'margin:15px 0; border-top: 1px solid black; padding-top: 20px'
        p.innerHTML = 'Tensorflow 머신러닝 프로그램입니다.'
        style.append(p)
      })
      style.addEventListener('mouseleave', () => {
        this.style7 = {
          backgroundColor: 'black',
          color: 'white',
          transition: '0.5s'
        }
        style.removeChild(p)
      })
    },
    change7() {
      const style = document.getElementsByClassName('project')[7]
      const p = document.createElement('p')
      style.addEventListener('mouseover', () => {
        this.style8 = {
          backgroundColor: '#e6e6fa',
          color: 'black',
          transition: '0.5s',
          textAlign: 'center'
        }
        p.style.cssText =
          'margin:15px 0; border-top: 1px solid black; padding-top: 20px'
        p.innerHTML = '얼굴 인식 및 모자이크하는 프로그램입니다.'
        style.append(p)
      })
      style.addEventListener('mouseleave', () => {
        this.style8 = {
          backgroundColor: 'black',
          color: 'white',
          transition: '0.5s'
        }
        style.removeChild(p)
      })
    },
    change8() {
      const style = document.getElementsByClassName('project')[8]
      const p = document.createElement('p')
      style.addEventListener('mouseover', () => {
        this.style9 = {
          backgroundColor: '#f4a460',
          color: 'black',
          transition: '0.5s',
          textAlign: 'center'
        }
        p.style.cssText =
          'margin:15px 0; border-top: 1px solid black; padding-top: 20px'
        p.innerHTML = '도서 관련 프로젝트입니다.'
        style.append(p)
      })
      style.addEventListener('mouseleave', () => {
        this.style9 = {
          backgroundColor: 'black',
          color: 'white',
          transition: '0.5s'
        }
        style.removeChild(p)
      })
    }
  }
}
</script>
<style scoped>
div {
  font-family: 'SBAggroB';
  width: 1000px;
}
div.tool {
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin: 50px auto 0 auto;
}
h3.title {
  font-size: 2.3rem;
  text-shadow: 3px 3px 2px gray;
  margin-right: 500px;
}
div.project_content {
  display: flex;
  justify-content: center;
  flex-flow: row wrap;
  margin-top: 30px;
}
a {
  text-decoration-line: none;
}
div.project {
  width: 333px;
  height: 150px;
  font-size: 1rem;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
</style>

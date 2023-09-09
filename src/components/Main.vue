<template>
<div class="navMenu">
    <font-awesome-icon icon="fa-solid fa-chevron-left" />
    <font-awesome-icon icon="fa-solid fa-magnifying-glass" />
    <font-awesome-icon icon="fa-solid fa-bars" />
  </div>
  <div class="hello">
    <h1>조별 과제 속 나의 모습은?</h1>

    <font-awesome-icon icon="fa-solid fa-door-open" />
    <p>총 16개의 유형의 MBTI 성향을 기반으로 조별과제 속 나의 모습을 알아보아요</p>
    <form>
      <input id="name" type="text" placeholder="이름을 입력해주세요" />
      <button type="submit">테스트하기</button>
      </form>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>



.navMenu{
  color: red;
  margin-top: 20px;
}




p{
  color: #808080;
  font: 16px;
}


</style>

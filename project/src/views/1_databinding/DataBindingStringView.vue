<template>
  <!-- html 태그가 들어가는 부분 -->
  <div>
    <!-- 문자열 바인딩할때는 중괄호 두개 -->
    <h1>Hello {{ userName }}</h1>
    <p>{{ message }}</p>
  </div>
</template>
<script>
// 자바스크립트 코드
export default {
  // function data()인데 vue에서는 function 생략
  data() {
    return {
      userName: 'John Doe',
      message: 'Welcome 개발자의 품격',
      arr: [],
      obj: {}
    }
  }
}
</script>

<style scoped>
/* 이 뷰 파일 안에서만 적용된다.
    다른 파일에서 같은 이름을 가진 요소가 있어도 거기에는 적용안됨.
*/
</style>

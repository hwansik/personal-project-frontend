<template>
  <v-container>
    <div>
      <nav>
        <!--
          router-link 파트는 UI 엔진인 Vue에서 경로를 지정
          부가적으로 to라는 파라메터는 실제 URL에 입력하는 경로가 됩니다.
          나타나는 형태는 text 형태고 누르면 자동으로 URL을 입력한 결과를 보여줍니다.
          이 작업을 자동화 하려면 반드시 router/index.js에
          /htmlTest를 누가 보여줄 것인지 컴포넌트 등록을 해줘야 합니다.
        -->
      </nav>
    </div>
  </v-container>
</template>

<script>
  import HelloWorld from '../components/HelloWorld'

  export default {
    name: 'Home',

    components: {
      HelloWorld,
    },
  }
</script>

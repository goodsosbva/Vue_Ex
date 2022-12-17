<template>
    <div id="response" class="gaveup"><p><b>정답 단어를 맞추었습니다. 1번째 추측만에 정답을 맞췄네요!</b>
        <br>정답 단어와 비슷한, <a href="/nearest1k/260">상위 1000개의 단어</a>를 확인해보세요.</p>
        <!-- <input type="button" value="기록 복사하기" id="result" @click="share()" class="button"><br><br> -->
        <Clip></Clip>
        261번째 꼬맨틀은 오늘 밤 자정(한국 시간 기준)에 열립니다.<br>
        <br>
        <b>나의 플레이 기록</b>: <br>
        <table>
        <tbody><tr><th>가장 처음 풀었던 꼬맨틀 번호:</th><td>260</td></tr>
        <tr><th>도전한 게임 횟수:</th><td>1</td></tr>
        <tr><th>정답 횟수:</th><td>1</td></tr>
        <tr><th>연속 정답 횟수:</th><td>1</td></tr>
        <tr><th>포기 횟수:</th><td>0</td></tr>
        <tr><th>지금까지 추측 단어 총 갯수:</th><td>1</td></tr>
        </tbody></table>
    </div>
</template>

<script>
import Clip from "./Clip.vue";

export default {
  name: "App",
  components: {
    Clip: Clip,
  },
};
// function share() {
//     console.log("clip copy!")
// }
</script>

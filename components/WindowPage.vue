
<template>
<div>
    <div class="backgroundimage w-full h-full">
    <div class="grid place-items-center h-screen">
    <div class="w-[20rem] h-[25rem] sm:w-[40rem] sm:h-[20rem] bg-[#2b2b2b] rounded-md">
        <div>
            <span class="w-0.5 h-0.5 inline-block rounded-full bg-transparent mx-1 my-1 mt-4"> </span>
            <span @click="clickEvent" class="w-3 h-3 inline-block rounded-full bg-[#fd5f57] mx-0.5 my-1 mt-3.5"> </span>
            <span class="w-3 h-3 inline-block rounded-full bg-[#fbbc33] mx-0.5 my-1 mt-3.5"> </span>
            <span class="w-3 h-3 inline-block rounded-full bg-[#2ac83e] mx-0.5 my-1 mt-3.5"> </span>
        </div>
        <div class="mx-4 my-4 mt-4 text-white">
            <span class="text-[#c3856b]">const</span> <span class="text-[#e6d321]"> greeting</span> = "Hello, world!";  <br>
            <span class="text-[#a7a792]">// My name is Martin AUBEUT.</span> <br>
            <span class="text-[#2ec8c7]">console</span>.<span class="text-[#9cbc53]">log</span>(<span class="text-[#e6d321]">greeting</span>); <br>
            <span class="text-[#a7a792]">// I'm a french web developer. </span> <br>
            <span class="text-[#c3856b]">const</span> <span class="text-[#e6d321]"> contact</span> = {  <br>
            <span class="text-[#2ec8c7]">{ email :</span> <span class="text-[#e6d321]"> </span>  <a href="mailto:martin.aubeut@gmail.com" target="_blank">martin.aubeut@gmail.com</a> <span class="text-[#2ec8c7]">}</span>,  <br>
            <span class="text-[#2ec8c7]">{ linkedin :</span> <span class="text-[#e6d321]"> </span>  <a href="https://www.linkedin.com/in/martin-aubeut-30452010b/" target="_blank">https://www.linkedin.com/in/martin-aubeut-30452010b/</a> <span class="text-[#2ec8c7]">}</span>,  <br>
            <span class="text-[#2ec8c7]">{ github :</span> <span class="text-[#e6d321]"> </span>  <a href="https://github.com/Awazez/" target="_blank">https://github.com/Awazez/</a> <span class="text-[#2ec8c7]">}</span>,  <br>
            <span class="text-[#2ec8c7]">{ twitter :</span> <span class="text-[#e6d321]"> </span>  <a href="https://twitter.com/AwwAzez" target="_blank">https://twitter.com/AwwAzez</a> <span class="text-[#2ec8c7]">}</span>  <br>
            }
        </div>
    </div>
</div>
</div>
</div>
</template><

<script>
export default {
  methods: {
    clickEvent: function(){
    console.log("Hello, world!");
  }
  },
  name: 'NuxtWindowPage',
    debug (event) {
    console.log(event)

  }
}
</script>


<style scoped>
.backgroundimage {
  background-image: url('../assets/bg-ground.webp');
  position: relative;
  background-size: cover;
  color: black;
  overflow: hidden;
}




</style>
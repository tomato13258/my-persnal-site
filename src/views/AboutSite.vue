<script setup>
</script>

<template>
  <main class="w-full flex flex-col items-center py-[50px] ">
    <section class="w-[80%] flex items-center justify-center mb-[200px]">
      <div class="main-box flex justify-center gap-[100px]">
        <div class="h1-bg flex flex-col items-end">
          <div class="flex items-center ">
            <font-awesome-icon class="text-[60px] mr-[40px]" icon="fa-solid fa-address-card" />
            <div class="">
              <h1 class="text-[50px] font-bold">關於我</h1>
              <h2 class="text-[30px] ">ABOUT ME</h2>
            </div>
          </div>
          <img class="w-[80%]" src="../components/pictures/shine-young-woman-painting-on-canvas-1.png" alt="">
        </div>

        <div class="w-[30%] flex flex-col items-center pt-[50px] p-box">
          <p class="text-[20px] mb-[20px]">&emsp;&emsp;來自南投，畢業於OOO，具有3年行政工作經驗。</p>
          <p class="text-[20px]">在職期間利用下班時間學習平面設計和UXUI相關知識，熱衷於不斷學習和成長。
            受工作影響，對資訊領域產生濃厚興趣，決心轉行成為一名前端工程師並報名工程師培訓班。
            期待在新領域中挑戰自我，展現潛力與能力。(還沒改內容...)</p>
          <font-awesome-icon class="text-[80px] text-[#9d5353] round-icon" icon="fa-solid fa-certificate" />
        </div>

      </div>
    </section>
    <section class="w-[100%] py-[100px] flex items-center justify-center bg-slate-400 ">
      <div class="main-box flex justify-center gap-[100px]">
        <div class="h1-bg flex flex-col items-end">
          <div class="flex items-center ">
            <font-awesome-icon class="text-[60px] mr-[40px]" icon="fa-solid fa-address-card" />
            <div class="">
              <h1 class="text-[50px] font-bold">專長</h1>
              <h2 class="text-[30px] ">ABOUT ME</h2>
            </div>
          </div>
          <img class="w-[80%]" src="../components/pictures/shine-young-woman-painting-on-canvas-1.png" alt="">
        </div>

        <div class="w-[30%] flex flex-col items-center pt-[50px] p-box">
          <p class="text-[20px] mb-[20px]">&emsp;&emsp;來自南投，畢業於OOO，具有3年行政工作經驗。</p>
          <p class="text-[20px]">在職期間利用下班時間學習平面設計和UXUI相關知識，熱衷於不斷學習和成長。
            受工作影響，對資訊領域產生濃厚興趣，決心轉行成為一名前端工程師並報名工程師培訓班。
            期待在新領域中挑戰自我，展現潛力與能力。(還沒改內容...)</p>
        </div>

      </div>
    </section>
  </main>
</template>
<style scoped>
@keyframes spin {
  from {
    transform: rotate(0deg);
  }

  to {
    transform: rotate(360deg);
  }
}

.p-box {
  position: relative;
}

.round-icon {
  position: absolute;
  right: 0;
  bottom: 20px;
  animation-name: spin;
  animation-duration: 20000ms;
  animation-iteration-count: infinite;
  animation-timing-function: linear;
}
</style>
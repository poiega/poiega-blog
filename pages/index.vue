<template>
  <main>
    <section class="self-center flex flex-col flex-1 items-center justify-center">
      <h1 class="title text-center">PoieGa blog </h1>
      <h2 class="subtitle text-center">PoieGaEngine 블로그</h2>
      <h6 class="text-center">이곳은 PoieGaEngine(poie.ga(개장 준비중))에서 사용하고 있는 엔진 현황에 대해서 보고하는 곳이 <a href="https://report.poie.ga">report.poie.ga(여기) 입니다.</a>.</h6>
    </section>

    <section class="mt-8">
      <h3 class="text-primary-600 dark:text-primary-400 max-w-5xl mx-auto">블로그 글</h3>
      <posts post-type="blog" :amount="1" />
    </section>
  </main>
</template>

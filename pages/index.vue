<template>
  <main>
    <section class="self-center flex flex-col flex-1 items-center justify-center">
      <h1 class="title text-center">NaweGa Status Blog</h1>
      <h2 class="subtitle text-center">NaweGa Server Status Report Blog</h2>
      <h6 class="subtitle text-center">When server is down, system change server of nawe.ga to this page. Server isn't down but you want to see this report blog, visit <a href="https://report.nawe.ga">report.nawe.ga</a>.</h6>
    </section>

    <section class="mt-8">
      <h3 class="text-primary-600 dark:text-primary-400 max-w-5xl mx-auto">Latest blog post</h3>
      <posts post-type="blog" :amount="1" />
    </section>
  </main>
</template>

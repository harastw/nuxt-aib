<template>
  <div id="ordinate">

    <header>
      <ThreadHeader />
    </header>
    
    <div class="blue-strip"></div>
    
    <ThreadLinks />

    <ThreadPosting />

    <main>
      <ThreadPosts />
    </main>

    <footer>- wakaba + futaba + futallaby -</footer>

  </div>
</template>

<style scoped>
#ordinate {
  margin-left: 5px;
  margin-right: 5px;
}

header {}

#posting-form {}

footer {
  position: fixed;
  bottom: 0;
  right: 0;
}
</style>
<template>
  <div class="containerBlocksCardsNews">
    <div class="blocksCardsNews">
      <BlockCardNews />
      <BlockCardNews />
    </div>
  </div>
</template>

<style lang="less">
.containerBlocksCardsNews {
  display: flex;
  justify-content: center;

  .blocksCardsNews {
    display: flex;
    flex-direction: column;
    align-items: center; // Центрируем элементы по горизонтали внутри .blocksCardsNews
    text-align: center;
    font-family: "Unbounded", sans-serif;
  }
}
</style>

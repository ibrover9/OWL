<template>
  <div class="discount">
    <span class="gray">акция</span>
    <div class="red">
      <div class="percent">%</div>
      акции
    </div>
  </div>
</template>

<style lang="less">
.discount {
  text-align: left;
  font-family: "Onest";
  display: flex;
  .red {
    border: 1px solid #ca2250;
    border-radius: 1em;
    padding: 0.286em 0.86em;
    color: #ca2250;
    display: flex;
    align-items: center;
    max-width: 7em;
    .percent {
      align-items: center;
      font-size: 0.5em;
      color: white;
      background-color: #ca2250;
      border-radius: 50%;
      padding-top: 1px;
      margin-right: 4px;
      padding-left: 2px;
      min-width: 11px;
      min-height: 11px;
    }
  }
  .gray {
    border: 1px solid #5b4481;
    border-radius: 1em;
    padding: 0.286em 0.86em;
    color: #5b4481;
    margin-right: 5px;
  }
}
</style>

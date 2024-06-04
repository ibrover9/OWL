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
@primary-color-dark-red: #ca2250;
@secondary-color-dark-purple: #5b4481;

.discount {
  text-align: left;
  font-family: "Onest";
  display: flex;
  .red {
    border: 1px solid @primary-color-dark-red;
    border-radius: 1em;
    padding: 0.286em 0.86em;
    color: @primary-color-dark-red;
    display: flex;
    align-items: center;
    max-width: 7em;
    .percent {
      align-items: center;
      font-size: 0.5em;
      color: white;
      background-color: @primary-color-dark-red;
      border-radius: 50%;
      padding-top: 1px;
      margin-right: 4px;
      padding-left: 2.5px;
      min-width: 11px;
      min-height: 11px;
    }
  }
  .gray {
    border: 1px solid @secondary-color-dark-purple;
    border-radius: 1em;
    padding: 0.286em 0.86em;
    color: @secondary-color-dark-purple;
    margin-right: 5px;
  }
}
</style>

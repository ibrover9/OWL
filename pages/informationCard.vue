<template>
  <div class="darkBackground">
    <div class="fixedDarkBackground">
      .
      <div class="fixedmainBlockWindow"></div>
    </div>
    <div class="mainBlockWindow">
      <div class="containerAllInformation">
        <div class="secondHeader">
          <span>Главная</span> &bull; <span>Новости</span> &bull;
          <span class="nameNews"
            >Средняя ставка по ипотеке в России превысила 8%
          </span>
        </div>
        <div class="InformationNews">
          <discount />
          <h1 class="HeaderMainInformation">
            Средняя ставка по ипотеке в России превысила 8%
          </h1>
          <div class="date">06.10.23</div>
          <div class="mainTextInformation">
            Аналитики одного из ведущих игроков на российском рынке кредитования
            объясняют это завершением околонулевых программ и изменением условий
            по ряду программ с господдержкой . При этом специалисты ВТБ
            прогнозируют в дальнейшем замедление роста средней ставки.
          </div>
          <img
            class="firstImg"
            src="https://s3-alpha-sig.figma.com/img/ac64/eb04/4b00d88c04048a5844684030287930bd?Expires=1718582400&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=JM5J5Cm9gdO8fYUVLP8mebEPZ~DCjyJjO2VyQuXHytrOMnAUxbZ7pDZsxkKHDJRYArQBNJZjg0reyqLooHWYF3lcpb~jzBzq13zHzKJgwtNAj8iRc0-OVGUnPtIVV-S7TacwrNoSlCL6cd4K3nZx4lgonxj1V47NAkUXSBSs~b~TcJIGaAycHV-W60nQPrnuFU9eoGn-2letziFWiluz79~D4PuRqMnf-2PVb-MwIX0P-TtYlZ68nz-ccLdyBvTJHqGqsJZ3EBnEAEfPbm0PQH6vs2eZaEXddXfeXxCJVacLRp06C3E9l5j17g72x5n6X7W6~hgmBL0vMCGgtdpMmw__"
            alt="CardNews"
          />
          <div class="mainTextInformation">
            <div class="padding">
              Если во втором полугодии прошлого года средняя ставка по ипотеке
              выросла до 7,38%, к концу года упала до 6,65%, то с начала года
              она выросла: на 1,2 п.п. — в январе, на 0,19 п.п. — в феврале и,
              по прогнозам ВТБ, на 0,26 п.п. — в марте.
            </div class="padding">
            <div>
              К концу первого квартала средняя ставка по ипотеке достигла 8,3%.
            </div>
            <div class="padding">
              Самая низкая ставка сейчас действует на рынке новостроек,
              благодаря программам господдержки. По оценке специалистов ВТБ, ее
              мартовское значение составило 5,5%—5,7%.
            </div>
            <div class="padding">
              Растущая популярность «Семейной ипотеки» в результате ее
              распространения на все семьи с двумя несовершеннолетними детьми и
              адаптация участников рынка к новым условиям «ипотеки от
              застройщика» помогут сбалансировать рынок первичной недвижимости.
            </div>
          </div>
        </div>
        <BlockCardNews />
      </div>

      <svg
        class="close"
        width="128"
        height="80"
        viewBox="0 0 128 80"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <g clip-path="url(#clip0_0_2515)">
          <path
            d="M0 0.259644H16C29.2548 0.259644 40 11.0048 40 24.2596V56C40 69.2548 50.7452 80 64 80H99V0H0V0.259644Z"
            fill="#CA2250"
          />
          <rect x="99" width="29" height="80" fill="#CA2250" />
        </g>
        <path
          d="M100 24L68 56M68 24L100 56"
          stroke="#F3F3F3"
          stroke-width="3"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
        <defs>
          <clipPath id="clip0_0_2515">
            <rect width="128" height="80" fill="white" />
          </clipPath>
        </defs>
      </svg>
    </div>
  </div>
</template>

<style lang="less">
.darkBackground {
  background-color: #423f3f;

  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
  .fixedDarkBackground {
    background-color: #423f3f;

    width: 100%;

    display: flex;
    justify-content: center;
    align-items: center;
    position: fixed;
    top: 0;
    left: 0;

    .fixedmainBlockWindow {
      height: 100vh;
      position: fixed;
      top: 0;
      left: 0;
      margin-left: 1.1em;
      width: 97.5%;
      background-color: white;
      border-radius: 1em;
      z-index: -1;
    }
  }
}
.mainBlockWindow {
  z-index: 1;
  margin: 1em;
  width: 98%;
  background-color: transparent;
  border-top-left-radius: 1em;
  border-top-right-radius: 1em;
  .containerAllInformation {
    width: 100%;
    padding: 2em 15em 4em 15em;
    font-size: 16px;

    .secondHeader {
      font-family: "Onest";
      text-transform: uppercase;
      font-size: 16px;
      padding-left: 0;

      .nameNews {
        color: #423f3f;
      }
    }
    .InformationNews {
      margin-top: 2em;
      .HeaderMainInformation {
        margin-top: 0.5em;
        margin-bottom: 0.25em;
        font-family: "Unbounded";
        color: #423f3f;
      }
      .date {
        font-family: "Onest";
        color: #cfcfcf;
        margin-top: 1em;
        margin-bottom: 1em;
      }
      .mainTextInformation {
        font-family: "Onest";
        max-width: 37.5em;
        color: #717070;
        margin-bottom: 2em;
        padding-left: 0.5em;
        .padding {
          margin-top: 1em;
        }
      }
      .firstImg {
        max-width: 66em;
        max-height: 37.5;
        border-radius: 2em;
      }
    }
  }

  .close {
    position: fixed;
    top: 0;
    left: 96em;
    border-top-right-radius: 1em;

    margin: 0;
    padding: 0;
  }
  
  @media (max-width: 6200px) {
    .close {
    top: 0;
    left: 367.7em;


  }
  }


  @media (max-width: 6100px) {
    .close {
    top: 0;
    left: 274em;


  }
  }

  @media (max-width: 3200px) {
    .close {
    top: 0;
    left: 178.4em;


  }
  }

  @media (max-width: 2400px) {
    .close {
    top: 0;
    left: 132em;


  }
  }

  @media (max-width: 2200px) {
    .close {
    top: 0;
    left: 116.5em;


  }
  }

  @media (max-width: 2000px) {
    .close {
    top: 0;
    left: 108.9em;


  }
  }
 
  @media (max-width: 1900px) {
    .close {
    top: 0;
    left: 96em;


  }
  }
   

  @media (max-width: 1700px) {
    .close {
    top: 0;
    left: 85.7em;


  }
  .firstImg {
        max-width: 39em;
        max-height: 35.5em;
        border-radius: 2em;
      }
  
  }

  @media (max-width: 1460px) {
    .close {
    top: 0;
    left: 77.3em;


  }

  .firstImg {
        max-width: 34em;
        max-height: 30.5em;
        border-radius: 2em;
      }
  
  }

  @media (max-width: 1260px) {
    .close {
    top: 0;
    left: 67.2em;

    .firstImg {
        max-width: 29em;
        max-height: 25.5em;
        border-radius: 2em;
      }
  
  
  }


  }

  @media (max-width: 1060px) {
    .close {
    top: 0;
    left: 54.9em;


  }
  .firstImg {
        max-width: 24em;
        max-height: 20.5em;
        border-radius: 2em;
      }
  
  
  }


  @media (max-width: 960px) {
    .close {
    top: 0;
    left: 46em;


  }
  .firstImg {
        max-width: 26em;
        max-height: 22.5em;
        border-radius: 2em;
    }
  .containerAllInformation {
    
    padding: 1em 5em 0 6em;
  
  }
  
  }


  @media (max-width: 860px) {
    text-align: center;
    .close {
    top: 0;
    left: 39.9em;
  }
    .firstImg {
        max-width: 14em;
        max-height: 10.5em;
        border-radius: 2em;
      }
    .containerAllInformation {
    
    padding: 1em 3em 0 3em;
  
  }
  }
}
</style>

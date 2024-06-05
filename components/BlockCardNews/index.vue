<script setup>
import { useRouter } from "vue-router";

const router = useRouter();

const inInformationCard = () => {
  router.push({ name: "informationCard" });
};
</script>

<template>
  <div class="CardNewsAndArrow" @click="inInformationCard">
    <div class="blockCardNews">
      <div class="transformImg">
        <img class="mainImg" src="../../public/content.png" alt="CardNews" />
        <div class="date">06.10.2023</div>
      </div>
      <div class="discountAndHeading">
        <h2 class="Heading">Средняя ставка по ипотеке в России превысила 8%</h2>
        <div class="margingAndpaddingDiscount">
          <Discount />
        </div>
      </div>
    </div>
    <div class="blockArrow">
      <div class="arrow">
        <svg
          width="36"
          height="24"
          viewBox="0 0 36 24"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M1.37423 12L34.634 12M34.634 12L25.2652 22M34.634 12L25.3473 2"
            stroke="#CA2250"
            stroke-width="2.5"
            stroke-linecap="round"
            stroke-linejoin="round"
          />
        </svg>
      </div>
    </div>
    <div class="SecondElementAdaptivNews">
      <svg
        width="106"
        height="104"
        viewBox="0 0 106 104"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M33.7329 52.5001L33.7329 72C33.7329 80.8307 26.5789 87.9906 17.7503 88L94 87.9998L94 12.5001C94 21.3366 86.8366 28.5 78.0001 28.5001L57.7328 28.5001C44.478 28.5002 33.7329 39.2453 33.7329 52.5001Z"
          fill="white"
        />
        <g filter="url(#filter0_ddd_0_2858)">
          <rect x="46" y="40" width="48" height="48" rx="16" fill="white" />
          <path
            d="M63.2786 69.7096L75.4315 57.5568M75.4315 57.5568L67.9861 57.7171M75.4315 57.5568L75.3011 64.9722"
            stroke="#CA2250"
            stroke-width="1.2"
            stroke-linecap="round"
            stroke-linejoin="round"
          />
        </g>
        <defs>
          <filter
            id="filter0_ddd_0_2858"
            x="34"
            y="32"
            width="72"
            height="72"
            filterUnits="userSpaceOnUse"
            color-interpolation-filters="sRGB"
          >
            <feFlood flood-opacity="0" result="BackgroundImageFix" />
            <feColorMatrix
              in="SourceAlpha"
              type="matrix"
              values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
              result="hardAlpha"
            />
            <feOffset dy="4" />
            <feGaussianBlur stdDeviation="6" />
            <feColorMatrix
              type="matrix"
              values="0 0 0 0 0.117647 0 0 0 0 0.101961 0 0 0 0 0.137255 0 0 0 0.05 0"
            />
            <feBlend
              mode="normal"
              in2="BackgroundImageFix"
              result="effect1_dropShadow_0_2858"
            />
            <feColorMatrix
              in="SourceAlpha"
              type="matrix"
              values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
              result="hardAlpha"
            />
            <feOffset dy="2" />
            <feGaussianBlur stdDeviation="3" />
            <feColorMatrix
              type="matrix"
              values="0 0 0 0 0.349836 0 0 0 0 0.069375 0 0 0 0 0.45 0 0 0 0.1 0"
            />
            <feBlend
              mode="normal"
              in2="effect1_dropShadow_0_2858"
              result="effect2_dropShadow_0_2858"
            />
            <feColorMatrix
              in="SourceAlpha"
              type="matrix"
              values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
              result="hardAlpha"
            />
            <feOffset dy="1" />
            <feGaussianBlur stdDeviation="1" />
            <feColorMatrix
              type="matrix"
              values="0 0 0 0 0.243137 0 0 0 0 0.290196 0 0 0 0 0.34902 0 0 0 0.02 0"
            />
            <feBlend
              mode="normal"
              in2="effect2_dropShadow_0_2858"
              result="effect3_dropShadow_0_2858"
            />
            <feBlend
              mode="normal"
              in="SourceGraphic"
              in2="effect3_dropShadow_0_2858"
              result="shape"
            />
          </filter>
        </defs>
      </svg>
    </div>
    <div class="FirstElementAdaptivNews">
      <svg
        width="312"
        height="294"
        viewBox="0 0 312 294"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <rect width="312" height="294" rx="16" fill="#F3F3F3" />
      </svg>
    </div>

    <svg
      width="0"
      height="0"
      viewBox="0 0 1056 228"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <clipPath id="headerClip">
        <path
          fill-rule="evenodd"
          style="transform: translate(0px, 0px)"
          clip-rule="evenodd"
          d="M919.01 0L929 0.283736C941.984 0.652494 952.319 11.2846 952.319 24.2741V59.0938C952.319 83.9466 972.466 104.094 997.319 104.094H1032.04C1044.84 104.094 1055.3 114.116 1056 126.734V202C1056 216.359 1044.36 228 1030 228H26C11.6406 228 0 216.359 0 202V26C0 11.6406 11.6406 0 26 0H919.01Z"
          fill="#F3F3F3"
        />
      </clipPath>
    </svg>
    <div class="Adaptiv">
      <div class="transformImgAdaptiv">
        <img
          class="mainImgAdaptiv"
          src="https://s3-alpha-sig.figma.com/img/ac64/eb04/4b00d88c04048a5844684030287930bd?Expires=1718582400&Key-Pair-Id=APKAQ4GOSFWCVNEHN3O4&Signature=JM5J5Cm9gdO8fYUVLP8mebEPZ~DCjyJjO2VyQuXHytrOMnAUxbZ7pDZsxkKHDJRYArQBNJZjg0reyqLooHWYF3lcpb~jzBzq13zHzKJgwtNAj8iRc0-OVGUnPtIVV-S7TacwrNoSlCL6cd4K3nZx4lgonxj1V47NAkUXSBSs~b~TcJIGaAycHV-W60nQPrnuFU9eoGn-2letziFWiluz79~D4PuRqMnf-2PVb-MwIX0P-TtYlZ68nz-ccLdyBvTJHqGqsJZ3EBnEAEfPbm0PQH6vs2eZaEXddXfeXxCJVacLRp06C3E9l5j17g72x5n6X7W6~hgmBL0vMCGgtdpMmw__"
          alt="CardNews"
        />
        <div class="dateAdaptiv">06.10.2023</div>
      </div>
      <div class="discountAndHeadingAdaptiv">
        <h2 class="HeadingAdaptiv">
          Средняя ставка по ипотеке в России превысила 8%
        </h2>
        <div class="margingAndpaddingDiscountAdaptiv">
          <discount />
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="less">
@import "../../assets/Card.less";
</style>

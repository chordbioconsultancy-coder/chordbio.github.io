---
layout: page
title: Test
permalink: /test/
---

<style>
  .marquee-wrapper {
    overflow: hidden;
    width: 100%;
    background-color: #f4f4f4;
    padding: 10px 0;
    white-space: nowrap;
  }

  .marquee-track {
    display: inline-flex;
    gap: 50px;
    animation: continuous-scroll 15s linear infinite;
  }

  .text-block {
    font-family: sans-serif;
    font-size: 1.2rem;
    font-weight: bold;
    color: #333;
    padding: 5px 15px;
  }

  .marquee-wrapper:hover .marquee-track {
    animation-play-state: paused;
    cursor: pointer;
  }

  @keyframes continuous-scroll {
    0% {
      transform: translateX(0);
    }
    100% {
      transform: translateX(-50%);
    }
  }
</style>

<div class="marquee-wrapper">
  <div class="marquee-track">
    <div class="text-block">🚀 Block One: Launching soon</div>
    <div class="text-block">📈 Block Two: Stocks up 5%</div>
    <div class="text-block">🎉 Block Three: Promo code DEAL20</div>
    <div class="text-block">🔥 Block Four: Trending topics</div>

    <div class="text-block">🚀 Block One: Launching soon</div>
    <div class="text-block">📈 Block Two: Stocks up 5%</div>
    <div class="text-block">🎉 Block Three: Promo code DEAL20</div>
    <div class="text-block">🔥 Block Four: Trending topics</div>
  </div>
</div>

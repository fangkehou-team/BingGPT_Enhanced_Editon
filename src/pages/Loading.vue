<script setup>

</script>

<template>
  <section class="loading">
    <div class="loading-bg-back"></div>
    <div class="loading-bg-front-left"></div>
    <div class="loading-bg-front-right"></div>

    <div id="cat-container">
      <svg
          id="cat-coffee"
          viewBox="0 0 1024 1024"
          width="255px"
          height="255px"
          fill="black"
      >
        <path
            id="cup"
            d="M888.5,541.6c-30.5-17.4-74.2,3.4-100.4,19.7c-2.3-27.9-6-45.5-6.2-46.3l-1.8-8.3L133,509.2l-1.8,8.3
	c-0.4,1.9-9.8,47.1-7.5,107.8c1.4,35.7,6.5,69.4,15.4,100c11.2,38.6,28.2,72.5,50.8,100.9c27.8,35,64.7,61.5,109.6,78.7
	c43.8,16.8,96.7,25.3,157.2,25.3c57.8,0,105.8-6.8,146.6-20.7c40.8-13.9,74.5-34.9,103-64.3c13.1-3.1,54.1-14.2,96.7-39.7
	c30.1-18,54.7-39.5,73.3-63.9c23.4-30.8,37-66.2,40.5-105.1C921.2,586.7,911.7,554.9,888.5,541.6z M763.1,527.7
	c1.7,10.4,4.3,29.1,5.4,52.9c3.5,72.8-6.6,174.8-74.1,246.8c-52.7,56.2-132.6,84.6-237.6,84.6c-114,0-198.3-33.3-250.6-99
	c-47.2-59.3-59.6-135.1-61.6-188.2c-1.7-43.3,3-78.9,5.6-94.7L763.1,527.7z M789.5,585.3c21.7-15.1,66.1-38.4,88.8-25.4
	c15.5,8.8,21.5,33.9,17.8,74.5c-5.7,63.6-40.4,114.9-103.3,152.7c-22.5,13.5-44.8,22.8-62,28.8c22.1-30.8,38.2-67.5,48-109.3
	C787.5,669.2,791.1,628.5,789.5,585.3z"
        />
        <g id="cat">
          <path
              id="cat-body"
              d="M536.2,503c-12.2-5.5-5.3-27.5-5.3-27.5H345.7c0,0,7.7,15.3-3.8,27.5c-13.4,14.1-93.1,36-145.6,105.6
	s-22.7,151.9,24.8,204.1c53.6,58.8,127.2,88.9,232.1,88.9c104.5,0,195.2-30.8,246.2-91.8c46.6-55.8,34.4-158.4,2.5-201.6
	C666.6,560.2,560.8,514,536.2,503z M554.4,749.6c-2.2,27.8-6.8,52.9-8.8,63.1h-47.3c-2.1-10.1-6.8-35.2-9.2-63
	c-4-46.5,0.2-79,12.2-94.1c5.1-6.4,11.7-9.6,20-9.6c8.3,0,14.9,3.1,20.1,9.6C553.6,670.7,558.1,703.2,554.4,749.6z M381,749.6
	c-2.2,27.8-6.8,52.9-8.8,63.1h-47.3c-2.1-10.1-6.8-35.2-9.2-63c-4-46.5,0.2-79,12.2-94.1c5.1-6.4,11.7-9.6,20-9.6
	c8.3,0,14.9,3.1,20.1,9.6C380.2,670.7,384.6,703.2,381,749.6z"
          />
          <path
              id="cat-foot-left"
              d="M348,651.8c-49.1,0-20,155.9-20,155.9h41C369,807.7,397,651.8,348,651.8z M354.1,670.8
	c1.9,0,3.4,2.8,3.4,6.2c0,3.4-1.5,6.2-3.4,6.2s-3.4-2.8-3.4-6.2C350.7,673.5,352.2,670.8,354.1,670.8z M342.3,670.8
	c1.9,0,3.4,2.8,3.4,6.2c0,3.4-1.5,6.2-3.4,6.2c-1.9,0-3.4-2.8-3.4-6.2C338.9,673.5,340.4,670.8,342.3,670.8z M329.9,686.3
	c0-3.4,1.5-6.2,3.4-6.2c1.9,0,3.4,2.8,3.4,6.2s-1.5,6.2-3.4,6.2C331.4,692.4,329.9,689.7,329.9,686.3z M347.8,708.1
	c-7.3,0-13.3-1.1-13.3-6.4s7.8-16.5,13.3-16.5c5.5,0,13.3,11.1,13.3,16.5S355.1,708.1,347.8,708.1z M363,694.2
	c-1.9,0-3.4-2.8-3.4-6.2s1.5-6.2,3.4-6.2c1.9,0,3.4,2.8,3.4,6.2S364.9,694.2,363,694.2z"
          />
          <path
              id="cat-foot-right"
              d="M521.4,651.4c-49.1,0-20,155.9-20,155.9h41C542.4,807.2,570.5,651.4,521.4,651.4z M527.5,670.3
	c1.9,0,3.4,2.8,3.4,6.2s-1.5,6.2-3.4,6.2s-3.4-2.8-3.4-6.2S525.7,670.3,527.5,670.3z M515.8,670.3c1.9,0,3.4,2.8,3.4,6.2
	s-1.5,6.2-3.4,6.2s-3.4-2.8-3.4-6.2S513.9,670.3,515.8,670.3z M503.4,685.8c0-3.4,1.5-6.2,3.4-6.2c1.9,0,3.4,2.8,3.4,6.2
	c0,3.4-1.5,6.2-3.4,6.2C504.9,691.9,503.4,689.2,503.4,685.8z M521.3,707.7c-7.3,0-13.3-1.1-13.3-6.4s7.8-16.5,13.3-16.5
	s13.3,11.1,13.3,16.5S528.6,707.7,521.3,707.7z M536.5,693.7c-1.9,0-3.4-2.8-3.4-6.2c0-3.4,1.5-6.2,3.4-6.2s3.4,2.8,3.4,6.2
	C539.9,691,538.4,693.7,536.5,693.7z"
          />
          <path
              id="cat-head"
              d="M631,253c16.7-36.2,15.3-113.3-11.2-122.6c-19.4-6.8-52.1,24.2-71.1,56.2c-32.2-14.9-69.4-23.4-109.2-23.4
	c-39.4,0-76.4,8.4-108.4,23c-19.2-32.4-51.8-63.4-71.3-55.6c-25,10-26.9,85.1-11,121.3c-19.1,26.4-30,57.1-30,89.9
	c0,98.7,95.2,161.1,217.1,161.1s224.2-62.4,224.2-161.1C660.3,309.5,649.6,279.2,631,253z M612.5,151.7c17.6,6.2,17.8,59.6,6.5,86.2
	c-15.3-17.3-34.4-32.3-56.2-44.2C576.2,170.3,599.3,147,612.5,151.7z M267.7,151.9c13.3-5.3,36.1,17.6,49.6,41.3
	c-21.8,11.8-40.8,26.6-56.2,43.7C250.5,210.2,251.1,158.6,267.7,151.9z M251.4,342.7c0.9-4,5.4-6.3,9.2-5.2
	c18.4,4.9,36.7,9.8,55.1,14.8c4.1,1.1,6.1,5.3,5.2,9.2c-0.9,4-5.4,6.3-9.2,5.2c-18.4-4.9-36.7-9.8-55.1-14.8
	C252.6,350.8,250.5,346.6,251.4,342.7z M317.8,397.5c-18.4,4.9-36.7,9.8-55.1,14.8c-4.1,1.1-8-1.3-9.2-5.2c-1.2-3.8,1.4-8.2,5.2-9.2
	c18.4-4.9,36.7-9.8,55.1-14.8c4.1-1.1,8,1.3,9.2,5.2C324.3,392.1,321.6,396.4,317.8,397.5z M354.1,344.1
	c-19.3,0-34.9-15.6-34.9-34.9c0-19.3,15.6-34.9,34.9-34.9c19.3,0,34.9,15.6,34.9,34.9C389,328.5,373.3,344.1,354.1,344.1z
	 M500,372.1c-6.9,8.6-15,13.2-24.3,13.8c-12.7,0.8-24-6.4-29.3-10.6c-4.8,4.1-14.6,11.1-26.6,11.1c-0.2,0-0.3,0-0.5,0
	c-9.8-0.2-18.8-4.9-26.7-14.2c-1.6-1.9-1.4-4.7,0.5-6.3c1.9-1.6,4.7-1.4,6.3,0.5c6.2,7.2,12.9,10.9,20,11.1
	c12.9,0.3,23.4-11.1,23.5-11.2c0.8-0.9,2-1.4,3.2-1.5c1.2,0,2.4,0.4,3.3,1.3c0.1,0.1,12.4,11.7,25.8,10.8
	c6.6-0.4,12.6-3.9,17.8-10.4c1.6-1.9,4.4-2.2,6.3-0.7C501.3,367.3,501.6,370.2,500,372.1z M500.9,309.2c0-19.3,15.6-34.9,34.9-34.9
	c19.3,0,34.9,15.6,34.9,34.9c0,19.3-15.6,34.9-34.9,34.9C516.6,344.1,500.9,328.5,500.9,309.2z M622.8,407c-0.9,4-5.4,6.3-9.2,5.2
	c-18.4-4.9-36.7-9.8-55.1-14.8c-4.1-1.1-6.1-5.3-5.2-9.2c0.9-4,5.4-6.3,9.2-5.2c18.4,4.9,36.7,9.8,55.1,14.8
	C621.6,398.8,623.6,403,622.8,407z M620.2,351.7c-18.4,4.9-36.7,9.8-55.1,14.8c-4.1,1.1-8-1.3-9.2-5.2c-1.2-3.8,1.4-8.2,5.2-9.2
	c18.4-4.9,36.7-9.8,55.1-14.8c4.1-1.1,8,1.3,9.2,5.2C626.7,346.3,624,350.6,620.2,351.7z"
          />
          <path
              id="cat-tail"
              d="M729.5,700.8c-0.1-28.1-8.1-54.9-19.8-80.2c-10.2-22.1-23.2-42.7-35.3-63.7c-6.2-10.8-12.2-21.7-17.1-33.2
	c0.5,1.2,1,2.4,1.5,3.6c-3.8-9.1-6.9-18.5-8.2-28.3c0.2,1.3,0.4,2.7,0.5,4c-0.8-6.1-0.9-12.3-0.1-18.5c-0.2,1.3-0.4,2.7-0.5,4
	c1-7.1,3.3-14,6-20.6c-0.5,1.2-1,2.4-1.5,3.6c6.6-15.5,16.4-29.3,26.6-42.5c-0.8,1-1.6,2-2.3,3c12.9-16.6,26.5-32.8,37.4-50.9
	c6.1-10.2,11.3-20.9,15.4-32c4.6-12.3,7.3-25,9.1-37.9c2.1-15.9,2-32,0.2-48c-0.5-4.1-1.4-7.6-4.4-10.6c-2.6-2.6-6.9-4.6-10.6-4.4
	c-3.9,0.2-7.9,1.4-10.6,4.4c-2.5,2.7-4.8,6.7-4.4,10.6c1.8,16,1.9,32.1-0.2,48c0.2-1.3,0.4-2.7,0.5-4c-1.9,13.7-5.5,27-10.8,39.8
	c0.5-1.2,1-2.4,1.5-3.6c-6.3,14.8-14.7,28.4-24.2,41.4c-2.6,3.5-5.2,7-7.8,10.4c0.8-1,1.6-2,2.3-3c-10.2,13.2-21,26.1-30.3,40.1
	c-4.2,6.3-8,12.8-11.2,19.6c-3.7,7.9-7.2,16.3-9,24.9c-3.6,18.3-0.9,36.8,5.8,54c7.1,18.3,16.8,35.3,26.8,52.1
	c10.3,17.5,20.8,35,29.3,53.5c1.1,2.4,2.1,4.7,3.1,7.1c-0.5-1.2-1-2.4-1.5-3.6c6.2,14.7,10.9,30,13,45.8c-0.2-1.3-0.4-2.7-0.5-4
	c0.9,6.4,1.3,12.8,1.3,19.2c0,7.8,6.9,15.4,15,15C722.6,715.5,729.5,709.2,729.5,700.8L729.5,700.8z"
          />
        </g>
      </svg>

      <div id="loading-text">Loading...</div>
    </div>
  </section>
</template>

<style scoped>

.loading {
  position: absolute;
  width: 100%;
  height: 100%;
  z-index: 999;
}

#cat-container {
  /*background: white;*/
  position: absolute;
  display: flex;
  flex-direction: column;
  width: 100%;
  height: 100%;
  margin-top: 50px;
  margin-left: 50px;
  top: -50px;
  left: -50px;
  align-items: center;
  justify-content: center;
}

#loading-text {
  font-size: 48px;
  font-family: Arial, Helvetica, sans-serif;
  color: #020203;
}

#cat-coffee {
  fill: #020203;
}

#cat {
  animation: cat-loading-animation 1s cubic-bezier(0.47, 0, 0.25, 1) infinite;
}

@media (prefers-color-scheme: dark) {
  #cat-coffee {
    fill: #BBBBBB;
  }
  #loading-text {
    color: #BBBBBB;
  }
}

@keyframes cat-loading-animation {
  0% {
    -webkit-clip-path: ellipse(20% 0% at 50% 0);
    clip-path: ellipse(20% 0% at 50% 100%);
  }

  30% {
    -webkit-clip-path: ellipse(100% 100% at 50% 0);
    clip-path: ellipse(100% 120% at 50% 100%);
  }

  50% {
    -webkit-clip-path: ellipse(100% 100% at 50% 0);
    clip-path: ellipse(100% 120% at 50% 100%);
  }

  80% {
    -webkit-clip-path: ellipse(20% 0% at 50% 0);
    clip-path: ellipse(20% 0% at 50% 100%);
  }

  100% {
    -webkit-clip-path: ellipse(20% 0% at 50% 0);
    clip-path: ellipse(20% 0% at 50% 100%);
  }
}

</style>
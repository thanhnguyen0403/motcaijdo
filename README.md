<!DOCTYPE html>
<html lang="en">
  <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Blossoming Flowers at Magical Night</title>
        <style>
            @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;700&display=swap');
            body {
                display: flex;
                justify-content: center;
                align-items: center;
                height: 100vh;
                margin: 0;
                position: relative;
            }
            canvas {
                position: absolute;
                z-index: 1;
            }
            .centered-text, .sub-text {
                position: absolute;
                text-align: center;
                color: white;
                z-index: 2;
                font-family: 'Dancing Script', cursive; /* Sử dụng font Dancing Script */
                animation: fadeInScale 2s forwards;
            }
            .centered-text {
                top: 12.5%;
                left: 50%;
                transform: translate(-50%, -50%) scale(0);
                font-size: 2em;
            }
            .sub-text {
                top: calc(12.5% + 3em); /* Điều chỉnh khoảng cách phía dưới chữ chính */
                left: 50%;
                transform: translate(-50%, -50%) scale(0);
                font-size: 1em;
            }
            @keyframes fadeInScale {
                0% {
                    opacity: 0;
                    transform: translate(-50%, -50%) scale(0);
                }
                100% {
                    opacity: 1;
                    transform: translate(-50%, -50%) scale(1);
                }
            }
        </style>
    </head>
    <body>
        <canvas id="canvas"></canvas>
        <script src="script.js"></script>
    
        <div class="centered-text">Chúc 20/11 vui vẻ</div>
        <div class="sub-text">đây là quà tặng kèm: </div>
    </body>
    
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Blossoming Flowers at Magical Night</title>
</head>
<body class="not-loaded">
  <div class="night"></div>
  <div class="flowers">
    <div class="flower flower--1">
      <div class="flower__leafs flower__leafs--1">
        <div class="flower__leaf flower__leaf--1"></div>
        <div class="flower__leaf flower__leaf--2"></div>
        <div class="flower__leaf flower__leaf--3"></div>
        <div class="flower__leaf flower__leaf--4"></div>
        <div class="flower__white-circle"></div>

        <div class="flower__light flower__light--1"></div>
        <div class="flower__light flower__light--2"></div>
        <div class="flower__light flower__light--3"></div>
        <div class="flower__light flower__light--4"></div>
        <div class="flower__light flower__light--5"></div>
        <div class="flower__light flower__light--6"></div>
        <div class="flower__light flower__light--7"></div>
        <div class="flower__light flower__light--8"></div>

      </div>
      <div class="flower__line">
        <div class="flower__line__leaf flower__line__leaf--1"></div>
        <div class="flower__line__leaf flower__line__leaf--2"></div>
        <div class="flower__line__leaf flower__line__leaf--3"></div>
        <div class="flower__line__leaf flower__line__leaf--4"></div>
        <div class="flower__line__leaf flower__line__leaf--5"></div>
        <div class="flower__line__leaf flower__line__leaf--6"></div>
      </div>
    </div>

    <div class="flower flower--2">
      <div class="flower__leafs flower__leafs--2">
        <div class="flower__leaf flower__leaf--1"></div>
        <div class="flower__leaf flower__leaf--2"></div>
        <div class="flower__leaf flower__leaf--3"></div>
        <div class="flower__leaf flower__leaf--4"></div>
        <div class="flower__white-circle"></div>

        <div class="flower__light flower__light--1"></div>
        <div class="flower__light flower__light--2"></div>
        <div class="flower__light flower__light--3"></div>
        <div class="flower__light flower__light--4"></div>
        <div class="flower__light flower__light--5"></div>
        <div class="flower__light flower__light--6"></div>
        <div class="flower__light flower__light--7"></div>
        <div class="flower__light flower__light--8"></div>

      </div>
      <div class="flower__line">
        <div class="flower__line__leaf flower__line__leaf--1"></div>
        <div class="flower__line__leaf flower__line__leaf--2"></div>
        <div class="flower__line__leaf flower__line__leaf--3"></div>
        <div class="flower__line__leaf flower__line__leaf--4"></div>
      </div>
    </div>

    <div class="flower flower--3">
      <div class="flower__leafs flower__leafs--3">
        <div class="flower__leaf flower__leaf--1"></div>
        <div class="flower__leaf flower__leaf--2"></div>
        <div class="flower__leaf flower__leaf--3"></div>
        <div class="flower__leaf flower__leaf--4"></div>
        <div class="flower__white-circle"></div>

        <div class="flower__light flower__light--1"></div>
        <div class="flower__light flower__light--2"></div>
        <div class="flower__light flower__light--3"></div>
        <div class="flower__light flower__light--4"></div>
        <div class="flower__light flower__light--5"></div>
        <div class="flower__light flower__light--6"></div>
        <div class="flower__light flower__light--7"></div>
        <div class="flower__light flower__light--8"></div>

      </div>
      <div class="flower__line">
        <div class="flower__line__leaf flower__line__leaf--1"></div>
        <div class="flower__line__leaf flower__line__leaf--2"></div>
        <div class="flower__line__leaf flower__line__leaf--3"></div>
        <div class="flower__line__leaf flower__line__leaf--4"></div>
      </div>
    </div>

    <div class="grow-ans" style="--d:1.2s">
      <div class="flower__g-long">
        <div class="flower__g-long__top"></div>
        <div class="flower__g-long__bottom"></div>
      </div>
    </div>

    <div class="growing-grass">
      <div class="flower__grass flower__grass--1">
        <div class="flower__grass--top"></div>
        <div class="flower__grass--bottom"></div>
        <div class="flower__grass__leaf flower__grass__leaf--1"></div>
        <div class="flower__grass__leaf flower__grass__leaf--2"></div>
        <div class="flower__grass__leaf flower__grass__leaf--3"></div>
        <div class="flower__grass__leaf flower__grass__leaf--4"></div>
        <div class="flower__grass__leaf flower__grass__leaf--5"></div>
        <div class="flower__grass__leaf flower__grass__leaf--6"></div>
        <div class="flower__grass__leaf flower__grass__leaf--7"></div>
        <div class="flower__grass__leaf flower__grass__leaf--8"></div>
        <div class="flower__grass__overlay"></div>
      </div>
    </div>

    <div class="growing-grass">
      <div class="flower__grass flower__grass--2">
        <div class="flower__grass--top"></div>
        <div class="flower__grass--bottom"></div>
        <div class="flower__grass__leaf flower__grass__leaf--1"></div>
        <div class="flower__grass__leaf flower__grass__leaf--2"></div>
        <div class="flower__grass__leaf flower__grass__leaf--3"></div>
        <div class="flower__grass__leaf flower__grass__leaf--4"></div>
        <div class="flower__grass__leaf flower__grass__leaf--5"></div>
        <div class="flower__grass__leaf flower__grass__leaf--6"></div>
        <div class="flower__grass__leaf flower__grass__leaf--7"></div>
        <div class="flower__grass__leaf flower__grass__leaf--8"></div>
        <div class="flower__grass__overlay"></div>
      </div>
    </div>

    <div class="grow-ans" style="--d:2.4s">
      <div class="flower__g-right flower__g-right--1">
        <div class="leaf"></div>
      </div>
    </div>

    <div class="grow-ans" style="--d:2.8s">
      <div class="flower__g-right flower__g-right--2">
        <div class="leaf"></div>
      </div>
    </div>

    <div class="grow-ans" style="--d:2.8s">
      <div class="flower__g-front">
        <div class="flower__g-front__leaf-wrapper flower__g-front__leaf-wrapper--1">
          <div class="flower__g-front__leaf"></div>
        </div>
        <div class="flower__g-front__leaf-wrapper flower__g-front__leaf-wrapper--2">
          <div class="flower__g-front__leaf"></div>
        </div>
        <div class="flower__g-front__leaf-wrapper flower__g-front__leaf-wrapper--3">
          <div class="flower__g-front__leaf"></div>
        </div>
        <div class="flower__g-front__leaf-wrapper flower__g-front__leaf-wrapper--4">
          <div class="flower__g-front__leaf"></div>
        </div>
        <div class="flower__g-front__leaf-wrapper flower__g-front__leaf-wrapper--5">
          <div class="flower__g-front__leaf"></div>
        </div>
        <div class="flower__g-front__leaf-wrapper flower__g-front__leaf-wrapper--6">
          <div class="flower__g-front__leaf"></div>
        </div>
        <div class="flower__g-front__leaf-wrapper flower__g-front__leaf-wrapper--7">
          <div class="flower__g-front__leaf"></div>
        </div>
        <div class="flower__g-front__leaf-wrapper flower__g-front__leaf-wrapper--8">
          <div class="flower__g-front__leaf"></div>
        </div>
        <div class="flower__g-front__line"></div>
      </div>
    </div>

    <div class="grow-ans" style="--d:3.2s">
      <div class="flower__g-fr">
        <div class="leaf"></div>
        <div class="flower__g-fr__leaf flower__g-fr__leaf--1"></div>
        <div class="flower__g-fr__leaf flower__g-fr__leaf--2"></div>
        <div class="flower__g-fr__leaf flower__g-fr__leaf--3"></div>
        <div class="flower__g-fr__leaf flower__g-fr__leaf--4"></div>
        <div class="flower__g-fr__leaf flower__g-fr__leaf--5"></div>
        <div class="flower__g-fr__leaf flower__g-fr__leaf--6"></div>
        <div class="flower__g-fr__leaf flower__g-fr__leaf--7"></div>
        <div class="flower__g-fr__leaf flower__g-fr__leaf--8"></div>
      </div>
    </div>

    <div class="long-g long-g--0">
      <div class="grow-ans" style="--d:3s">
        <div class="leaf leaf--0"></div>
      </div>
      <div class="grow-ans" style="--d:2.2s">
        <div class="leaf leaf--1"></div>
      </div>
      <div class="grow-ans" style="--d:3.4s">
        <div class="leaf leaf--2"></div>
      </div>
      <div class="grow-ans" style="--d:3.6s">
        <div class="leaf leaf--3"></div>
      </div>
    </div>

    <div class="long-g long-g--1">
      <div class="grow-ans" style="--d:3.6s">
        <div class="leaf leaf--0"></div>
      </div>
      <div class="grow-ans" style="--d:3.8s">
        <div class="leaf leaf--1"></div>
      </div>
      <div class="grow-ans" style="--d:4s">
        <div class="leaf leaf--2"></div>
      </div>
      <div class="grow-ans" style="--d:4.2s">
        <div class="leaf leaf--3"></div>
      </div>
    </div>

    <div class="long-g long-g--2">
      <div class="grow-ans" style="--d:4s">
        <div class="leaf leaf--0"></div>
      </div>
      <div class="grow-ans" style="--d:4.2s">
        <div class="leaf leaf--1"></div>
      </div>
      <div class="grow-ans" style="--d:4.4s">
        <div class="leaf leaf--2"></div>
      </div>
      <div class="grow-ans" style="--d:4.6s">
        <div class="leaf leaf--3"></div>
      </div>
    </div>

    <div class="long-g long-g--3">
      <div class="grow-ans" style="--d:4s">
        <div class="leaf leaf--0"></div>
      </div>
      <div class="grow-ans" style="--d:4.2s">
        <div class="leaf leaf--1"></div>
      </div>
      <div class="grow-ans" style="--d:3s">
        <div class="leaf leaf--2"></div>
      </div>
      <div class="grow-ans" style="--d:3.6s">
        <div class="leaf leaf--3"></div>
      </div>
    </div>

    <div class="long-g long-g--4">
      <div class="grow-ans" style="--d:4s">
        <div class="leaf leaf--0"></div>
      </div>
      <div class="grow-ans" style="--d:4.2s">
        <div class="leaf leaf--1"></div>
      </div>
      <div class="grow-ans" style="--d:3s">
        <div class="leaf leaf--2"></div>
      </div>
      <div class="grow-ans" style="--d:3.6s">
        <div class="leaf leaf--3"></div>
      </div>
    </div>

    <div class="long-g long-g--5">
      <div class="grow-ans" style="--d:4s">
        <div class="leaf leaf--0"></div>
      </div>
      <div class="grow-ans" style="--d:4.2s">
        <div class="leaf leaf--1"></div>
      </div>
      <div class="grow-ans" style="--d:3s">
        <div class="leaf leaf--2"></div>
      </div>
      <div class="grow-ans" style="--d:3.6s">
        <div class="leaf leaf--3"></div>
      </div>
    </div>

    <div class="long-g long-g--6">
      <div class="grow-ans" style="--d:4.2s">
        <div class="leaf leaf--0"></div>
      </div>
      <div class="grow-ans" style="--d:4.4s">
        <div class="leaf leaf--1"></div>
      </div>
      <div class="grow-ans" style="--d:4.6s">
        <div class="leaf leaf--2"></div>
      </div>
      <div class="grow-ans" style="--d:4.8s">
        <div class="leaf leaf--3"></div>
      </div>
    </div>

    <div class="long-g long-g--7">
      <div class="grow-ans" style="--d:3s">
        <div class="leaf leaf--0"></div>
      </div>
      <div class="grow-ans" style="--d:3.2s">
        <div class="leaf leaf--1"></div>
      </div>
      <div class="grow-ans" style="--d:3.5s">
        <div class="leaf leaf--2"></div>
      </div>
      <div class="grow-ans" style="--d:3.6s">
        <div class="leaf leaf--3"></div>
      </div>
    </div>
  </div>
</body>
</html>
<script src="main.js"></script>

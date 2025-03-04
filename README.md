<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    .wrapper {
      --border-color: #ffffff; /* Cor padrão, pode ser alterada via atributo data-border-color */
    }

    .instagram { data-border-color: #fa8f21};
    .linkedin { data-border-color: #ffffff};


    .icon svg {
      width: 110%;
      height: 110%;
      margin: 0%;
    }

    .tooltip-container {
      position: relative;
      cursor: pointer;
      transition: all 0.2s;
      font-size: 17px;
      border-radius: 10px;
      display: inline-block; /* Adicionado para colocar os ícones lado a lado */
      margin-right: 20px; /* Espaçamento entre os ícones */
    }

    .tooltip {
      position: absolute;
      top: 0;
      left: 50%;
      transform: translateX(-50%);
      padding: 10px;
      opacity: 0;
      pointer-events: none;
      transition: all 0.3s;
      border-radius: 15px;
      box-shadow: inset 5px 5px 5px rgba(0, 0, 0, 0.2),
                  inset -5px -5px 15px rgba(255, 255, 255, 0.1),
                  5px 5px 15px rgba(0, 0, 0, 0.3),
                  -5px -5px 15px rgba(255, 255, 255, 0.1);
    }

    .profile {
      background: #2a2b2f;
      border-radius: 10px 15px;
      padding: 10px;
      border: 1px solid var(--border-color); /* Aplicando a cor da borda dinamicamente */
    }

    .tooltip-container:hover .tooltip {
      top: -90px;
      opacity: 1;
      visibility: visible;
      pointer-events: auto;
    }

    .icon {
      text-decoration: none;
      color: #fff;
      display: block;
      position: relative;
    }

    .layer {
        margin-top: 30px;
      width: 55px;
      height: 55px;
      transition: transform 0.3s;
    }

    .icon:hover .layer {
      transform: rotate(-35deg) skew(20deg);
    }

    .layer span {
      position: absolute;
      top: 0;
      left: 0;
      height: 100%;
      width: 100%;
      border: 1px solid var(--border-color); /* Aplicando a cor da borda dinamicamente */
      border-radius: 15px;
      transition: all 0.3s;
    }

    .layer span,
    .text {
      color: #fffff;
      border-color: var(--border-color);
    }

    .icon:hover .layer span {
      box-shadow: -1px 1px 3px var(--border-color);
    }

    .icon .text {
      position: absolute;
      left: 50%;
      bottom: -5px;
      opacity: 0;
      font-weight: 500;
      transform: translateX(-50%);
      transition: bottom 0.3s ease, opacity 0.3s ease;
    }

    .icon:hover .text {
      bottom: -35px;
      opacity: 1;
    }

    .icon:hover .layer span:nth-child(1) {
      opacity: 0.2;
    }

    .icon:hover .layer span:nth-child(2) {
      opacity: 0.4;
      transform: translate(5px, -5px);
    }

    .icon:hover .layer span:nth-child(3) {
      opacity: 0.6;
      transform: translate(10px, -10px);
    }

    .icon:hover .layer span:nth-child(4) {
      opacity: 0.8;
      transform: translate(15px, -15px);
    }

    .icon:hover .layer span:nth-child(5) {
      opacity: 1;
      transform: translate(20px, -20px);
    }

    .instagramSVG {
      font-size: 25px;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .user {
      display: flex;
      gap: 10px;
    }

    .img {
      width: 50px;
      height: 50px;
      font-size: 25px;
      font-weight: 700;
      border: 1px solid var(--border-color); /* Aplicando a cor da borda dinamicamente */
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      background: #fff;
    }

    .name {
      font-size: 17px;
      font-weight: 700;
      color: #ffffff;
    }

    .details {
      display: flex;
      flex-direction: column;
      gap: 0;
      color: #fff;
    }

    .about {
      color: #ccc;
      padding-top: 5px;
    }
  </style>
</head>

<body>
  <h1 align="center">Olá, eu me chamo Gustavo <img height="40" src=""></h1>

  <p align="center">
    <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=4000&pause=1000&color=6C63FE&center=true&vCenter=true&multiline=true&random=false&width=700&height=40&lines=Desenvolvedor+FrontEnd+em+constante+evolução" alt="Typing SVG"/></a>
  </p>

  <h2>Sobre mim:</h2>
  <p>
    Atualmente sou estudante do Instituto Federal de Ciência e Tecnologia do Paraná. Estou cursando o 3ºano de 4 anos do curso técnico em informática. Tenho experiência em diversas áreas, como: desenvolvimento web (Full-Stack), robótica educacional e sistemas embarcados. Também sou um entusiasta apaixonado por tecnologia, buscando sempre aprender novos conceitos e aplicações.
  </p>

  <h2>Tecnologias que eu conheço:<h2/>

  <div style="display: inline_block"><br>
    <img align="center" alt="C" src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
    <img align="center" alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
    <img align="center" alt="MySQL" src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white"/>
    <img align="center" alt="Flask" src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
    <img align="center" alt="Arduino" src="https://img.shields.io/badge/Arduino_IDE-00979D?style=for-the-badge&logo=arduino&logoColor=white"/>
    <img align="center" alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
    <img align="center" alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
    <img align="center" alt="javaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
    <img align="center" alt="C#" src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white"/>
    <img align="center" alt=".NET" src="https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white"/>
  </div>

  <br/>
  <h2>Você pode me contatar e conhecer mais sobre mim nas seguintes plataformas:</h2>


  <div style="display: flex; justify-content: center;">
    <div class="wrapper" data-border-color="#fa8f21">
      <div class="tooltip-container">
        <div class="tooltip">
          <div class="profile">
            <div class="user">
              <div class="details">
                <div class="username">@digisss01</div>
              </div>
            </div>
          </div>
        </div>
        <div class="text">
          <a class="icon" href="https://www.instagram.com/digisss01" >
            <div class="layer">
              <span></span>
              <span></span>
              <span></span>
              <span></span>
              <span class="instagramSVG">
                <!-- SVG do Instagram -->
                <svg xmlns="http://www.w3.org/2000/svg" 
                viewBox="0 0 3364.7 3364.7" width="3365" height="3365">
                  <defs>
                    <radialGradient id="0" cx="217.76" cy="3290.99" r="4271.92" gradientUnits="userSpaceOnUse">
                      <stop offset=".09" stop-color="#fa8f21"/>
                      <stop offset=".78" stop-color="#d82d7e"/>
                    </radialGradient>
                    <radialGradient id="1" cx="2330.61" cy="3182.95" r="3759.33" gradientUnits="userSpaceOnUse">
                      <stop offset=".64" stop-color="#8c3aaa" stop-opacity="0"/>
                      <stop offset="1" stop-color="#8c3aaa"/>
                    </radialGradient>
                  </defs>
                  <path d="M853.2,3352.8c-200.1-9.1-308.8-42.4-381.1-70.6-95.8-37.3-164.1-81.7-236-153.5S119.7,2988.6,82.6,2892.8c-28.2-72.3-61.5-181-70.6-381.1C2,2295.4,0,2230.5,0,1682.5s2.2-612.8,11.9-829.3C21,653.1,54.5,544.6,82.5,472.1,119.8,376.3,164.3,308,236,236c71.8-71.8,140.1-116.4,236-153.5C544.3,54.3,653,21,853.1,11.9,1069.5,2,1134.5,0,1682.3,0c548,0,612.8,2.2,829.3,11.9,200.1,9.1,308.6,42.6,381.1,70.6,95.8,37.1,164.1,81.7,236,153.5s116.2,140.2,153.5,236c28.2,72.3,61.5,181,70.6,381.1,9.9,216.5,11.9,281.3,11.9,829.3,0,547.8-2,612.8-11.9,829.3-9.1,200.1-42.6,308.8-70.6,381.1-37.3,95.8-81.7,164.1-153.5,235.9s-140.2,116.2-236,153.5c-72.3,28.2-181,61.5-381.1,70.6-216.3,9.9-281.3,11.9-829.3,11.9-547.8,0-612.8-1.9-829.1-11.9" fill="url(#0)"/>
                  <path d="M853.2,3352.8c-200.1-9.1-308.8-42.4-381.1-70.6-95.8-37.3-164.1-81.7-236-153.5S119.7,2988.6,82.6,2892.8c-28.2-72.3-61.5-181-70.6-381.1C2,2295.4,0,2230.5,0,1682.5s2.2-612.8,11.9-829.3C21,653.1,54.5,544.6,82.5,472.1,119.8,376.3,164.3,308,236,236c71.8-71.8,140.1-116.4,236-153.5C544.3,54.3,653,21,853.1,11.9,1069.5,2,1134.5,0,1682.3,0c548,0,612.8,2.2,829.3,11.9,200.1,9.1,308.6,42.6,381.1,70.6,95.8,37.1,164.1,81.7,236,153.5s116.2,140.2,153.5,236c28.2,72.3,61.5,181,70.6,381.1,9.9,216.5,11.9,281.3,11.9,829.3,0,547.8-2,612.8-11.9,829.3-9.1,200.1-42.6,308.8-70.6,381.1-37.3,95.8-81.7,164.1-153.5,235.9s-140.2,116.2-236,153.5c-72.3,28.2-181,61.5-381.1,70.6-216.3,9.9-281.3,11.9-829.3,11.9-547.8,0-612.8-1.9-829.1-11.9" fill="url(#1)"/>
                  <path d="M1269.25,1689.52c0-230.11,186.49-416.7,416.6-416.7s416.7,186.59,416.7,416.7-186.59,416.7-416.7,416.7-416.6-186.59-416.6-416.7m-225.26,0c0,354.5,287.36,641.86,641.86,641.86s641.86-287.36,641.86-641.86-287.36-641.86-641.86-641.86S1044,1335,1044,1689.52m1159.13-667.31a150,150,0,1,0,150.06-149.94h-0.06a150.07,150.07,0,0,0-150,149.94M1180.85,2707c-121.87-5.55-188.11-25.85-232.13-43-58.36-22.72-100-49.78-143.78-93.5s-70.88-85.32-93.5-143.68c-17.16-44-37.46-110.26-43-232.13-6.06-131.76-7.27-171.34-7.27-505.15s1.31-373.28,7.27-505.15c5.55-121.87,26-188,43-232.13,22.72-58.36,49.78-100,93.5-143.78s85.32-70.88,143.78-93.5c44-17.16,110.26-37.46,232.13-43,131.76-6.06,171.34-7.27,505-7.27S2059.13,666,2191,672c121.87,5.55,188,26,232.13,43,58.36,22.62,100,49.78,143.78,93.5s70.78,85.42,93.5,143.78c17.16,44,37.46,110.26,43,232.13,6.06,131.87,7.27,171.34,7.27,505.15s-1.21,373.28-7.27,505.15c-5.55,121.87-25.95,188.11-43,232.13-22.72,58.36-49.78,100-93.5,143.68s-85.42,70.78-143.78,93.5c-44,17.16-110.26,37.46-232.13,43-131.76,6.06-171.34,7.27-505.15,7.27s-373.28-1.21-505-7.27M1170.5,447.09c-133.07,6.06-224,27.16-303.41,58.06-82.19,31.91-151.86,74.72-221.43,144.18S533.39,788.47,501.48,870.76c-30.9,79.46-52,170.34-58.06,303.41-6.16,133.28-7.57,175.89-7.57,515.35s1.41,382.07,7.57,515.35c6.06,133.08,27.16,223.95,58.06,303.41,31.91,82.19,74.62,152,144.18,221.43s139.14,112.18,221.43,144.18c79.56,30.9,170.34,52,303.41,58.06,133.35,6.06,175.89,7.57,515.35,7.57s382.07-1.41,515.35-7.57c133.08-6.06,223.95-27.16,303.41-58.06,82.19-32,151.86-74.72,221.43-144.18s112.18-139.24,144.18-221.43c30.9-79.46,52.1-170.34,58.06-303.41,6.06-133.38,7.47-175.89,7.47-515.35s-1.41-382.07-7.47-515.35c-6.06-133.08-27.16-224-58.06-303.41-32-82.19-74.72-151.86-144.18-221.43S2586.8,537.06,2504.71,505.15c-79.56-30.9-170.44-52.1-303.41-58.06C2068,441,2025.41,439.52,1686,439.52s-382.1,1.41-515.45,7.57" fill="#fff"/>
                </svg>
              </span>
            </div>
            <div class="text">Instagram</div>
          </a>
        </div>
      </div>
    </div>
    <div class="wrapper linkedin" >
      <div class="tooltip-container">
        <div class="tooltip">
          <div class="profile">
            <div class="user">
              <div class="details">
                <div class="username">Gustavo MF</div>
              </div>
            </div>
          </div>
        </div>
        <div class="text">
          <a class="icon" href="https://www.linkedin.com/in/gustavo-martins-fernandes-291a182b9/">
            <div class="layer">
              <span></span>
              <span></span>
              <span></span>
              <span></span>
              <span class="instagramSVG">
                <!-- SVG do LinkedIn -->
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="88" height="88">
                  <path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z" fill="#0077B5" border--color="#fffff"/>
                </svg>
              </span>
            </div>
            <div class="text">LinkedIn</div>
          </a>
        </div>
      </div>
    </div>
  </div>
  <br>
  <br>
  <div align="center">  
    ![Nicolas GitHub stats](https://github-readme-stats.vercel.app/api?username=Digiss&show_icons=true&theme=dark)
  </div>
  
</body>

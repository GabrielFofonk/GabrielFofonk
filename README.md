### Olá! Eu sou o Gabriel Fofonka. 👋
 <svg
        width="495"
        height="1145"
        viewBox="0 0 495 1145"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
        role="img"
        aria-labelledby="descId"
      >
        <title id="titleId"></title>
        <desc id="descId"></desc>
        <style>
          .header {
            font: 600 18px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #2f80ed;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
          }
          @supports(-moz-appearance: auto) {
            /* Selector detects Firefox */
            .header { font-size: 15.5px; }
          }
          
    
    .stat {
      font: 600 14px 'Segoe UI', Ubuntu, "Helvetica Neue", Sans-Serif; fill: #434d58;
    }
    @supports(-moz-appearance: auto) {
      /* Selector detects Firefox */
      .stat { font-size:12px; }
    }
    .stagger {
      opacity: 0;
      animation: fadeInAnimation 0.3s ease-in-out forwards;
    }
    .not_bold { font-weight: 400 }
    .bold { font-weight: 700 }
  
    @keyframes slideInAnimation {
      from {
        width: 0;
      }
      to {
        width: calc(100%-100px);
      }
    }
    @keyframes growWidthAnimation {
      from {
        width: 0;
      }
      to {
        width: 100%;
      }
    }
    .lang-name { font: 400 11px 'Segoe UI', Ubuntu, Sans-Serif; fill: #434d58 }
    #rect-mask rect{
      animation: slideInAnimation 1s ease-in-out forwards;
    }
    .lang-progress{
      animation: growWidthAnimation 0.6s ease-in-out forwards;
    }
    

          
      /* Animations */
      @keyframes scaleInAnimation {
        from {
          transform: translate(-5px, 5px) scale(0);
        }
        to {
          transform: translate(-5px, 5px) scale(1);
        }
      }
      @keyframes fadeInAnimation {
        from {
          opacity: 0;
        }
        to {
          opacity: 1;
        }
      }
    
          
        </style>

        

        <rect
          data-testid="card-bg"
          x="0.5"
          y="0.5"
          rx="4.5"
          height="99%"
          stroke="#e4e2e2"
          width="494"
          fill="#fffefe"
          stroke-opacity="1"
        />

        
      <g
        data-testid="card-title"
        transform="translate(25, 35)"
      >
        <g transform="translate(0, 0)">
      <text
        x="0"
        y="0"
        class="header"
        data-testid="header"
      >WakaTime Stats (last year)</text>
    </g>
      </g>
    

        <g
          data-testid="main-card-body"
          transform="translate(0, 55)"
        >
          
    <svg x="0" y="0" width="100%">
      <g transform="translate(0, 0)">
    <g class="stagger" style="animation-delay: 450ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="TypeScript">TypeScript:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >654 hrs 3 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="32.39%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 750ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 25)">
    <g class="stagger" style="animation-delay: 600ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="PHP">PHP:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >543 hrs 22 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="26.91%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 900ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 50)">
    <g class="stagger" style="animation-delay: 750ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Blade Template">Blade Template:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >309 hrs 37 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="15.33%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 1050ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 75)">
    <g class="stagger" style="animation-delay: 900ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="SQL">SQL:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >134 hrs 31 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="6.66%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 1200ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 100)">
    <g class="stagger" style="animation-delay: 1050ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Other">Other:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >110 hrs 29 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="5.47%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 1350ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 125)">
    <g class="stagger" style="animation-delay: 1200ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="JavaScript">JavaScript:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >81 hrs 14 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="4.02%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 1500ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 150)">
    <g class="stagger" style="animation-delay: 1350ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="SCSS">SCSS:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >59 hrs 55 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2.97%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 1650ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 175)">
    <g class="stagger" style="animation-delay: 1500ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="JSON">JSON:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >38 hrs 53 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 1800ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 200)">
    <g class="stagger" style="animation-delay: 1650ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="HTML">HTML:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >26 hrs 45 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 1950ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 225)">
    <g class="stagger" style="animation-delay: 1800ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Bash">Bash:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >7 hrs</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 2100ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 250)">
    <g class="stagger" style="animation-delay: 1950ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="YAML">YAML:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >6 hrs 49 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 2250ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 275)">
    <g class="stagger" style="animation-delay: 2100ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="XML">XML:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >6 hrs 47 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 2400ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 300)">
    <g class="stagger" style="animation-delay: 2250ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Vue.js">Vue.js:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >5 hrs 45 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 2550ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 325)">
    <g class="stagger" style="animation-delay: 2400ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="TOML">TOML:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >5 hrs 41 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 2700ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 350)">
    <g class="stagger" style="animation-delay: 2550ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Markdown">Markdown:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >4 hrs 28 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 2850ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 375)">
    <g class="stagger" style="animation-delay: 2700ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="CSS">CSS:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >4 hrs 21 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 3000ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 400)">
    <g class="stagger" style="animation-delay: 2850ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="TSConfig">TSConfig:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >3 hrs 12 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 3150ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 425)">
    <g class="stagger" style="animation-delay: 3000ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="ActionScript">ActionScript:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >2 hrs 58 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 3300ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 450)">
    <g class="stagger" style="animation-delay: 3150ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Ezhil">Ezhil:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >2 hrs 53 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 3450ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 475)">
    <g class="stagger" style="animation-delay: 3300ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="C#">C#:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >2 hrs 47 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 3600ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 500)">
    <g class="stagger" style="animation-delay: 3450ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="ActionScript 3">ActionScript 3:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >1 hr 31 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 3750ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 525)">
    <g class="stagger" style="animation-delay: 3600ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Text">Text:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >52 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 3900ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 550)">
    <g class="stagger" style="animation-delay: 3750ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="GDScript3">GDScript3:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >37 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 4050ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 575)">
    <g class="stagger" style="animation-delay: 3900ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="CSHTML">CSHTML:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >36 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 4200ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 600)">
    <g class="stagger" style="animation-delay: 4050ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="TSQL">TSQL:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >35 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 4350ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 625)">
    <g class="stagger" style="animation-delay: 4200ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Makefile">Makefile:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >34 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 4500ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 650)">
    <g class="stagger" style="animation-delay: 4350ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Git Config">Git Config:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >30 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 4650ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 675)">
    <g class="stagger" style="animation-delay: 4500ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="GDScript">GDScript:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >28 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 4800ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 700)">
    <g class="stagger" style="animation-delay: 4650ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Docker">Docker:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >15 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 4950ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 725)">
    <g class="stagger" style="animation-delay: 4800ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="CSV">CSV:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >13 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 5100ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 750)">
    <g class="stagger" style="animation-delay: 4950ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="CSV/TSV">CSV/TSV:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >13 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 5250ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 775)">
    <g class="stagger" style="animation-delay: 5100ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Python">Python:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >12 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 5400ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 800)">
    <g class="stagger" style="animation-delay: 5250ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Twig">Twig:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >10 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 5550ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 825)">
    <g class="stagger" style="animation-delay: 5400ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Nginx configuration file">Nginx configuration file:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >7 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 5700ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 850)">
    <g class="stagger" style="animation-delay: 5550ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="C">C:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >7 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 5850ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 875)">
    <g class="stagger" style="animation-delay: 5700ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Objective-C">Objective-C:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >6 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 6000ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 900)">
    <g class="stagger" style="animation-delay: 5850ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Less">Less:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >5 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 6150ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 925)">
    <g class="stagger" style="animation-delay: 6000ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Assembly">Assembly:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >5 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 6300ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 950)">
    <g class="stagger" style="animation-delay: 6150ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="INI">INI:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >3 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 6450ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 975)">
    <g class="stagger" style="animation-delay: 6300ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Apache Config">Apache Config:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >3 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 6600ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 1000)">
    <g class="stagger" style="animation-delay: 6450ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="SSH Config">SSH Config:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >3 mins</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 6750ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 1025)">
    <g class="stagger" style="animation-delay: 6600ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Groovy">Groovy:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >1 min</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 6900ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g><g transform="translate(0, 1050)">
    <g class="stagger" style="animation-delay: 6750ms" transform="translate(25, 0)">
      <text class="stat bold" y="12.5" data-testid="Diff">Diff:</text>
      <text
        class="stat"
        x="350"
        y="12.5"
      >1 min</text>
      
    <svg width="220" x="110" y="4">
      <rect rx="5" ry="5" x="0" y="0" width="220" height="8" fill="#434d58"></rect>
      <svg data-testid="lang-progress" width="2%">
        <rect
            height="8"
            fill="#2f80ed"
            rx="5" ry="5" x="0" y="0"
            class="lang-progress"
            style="animation-delay: 7050ms;"
        />
      </svg>
    </svg>
  
    </g>
  </g>
    </svg>
  
  </g>
 </svg>
      
<div style="display: inline_block"><br>
  <img align="center" alt="Rafa-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Rafa-Ts" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
  <img align="center" alt="Rafa-React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
  <img align="center" alt="Rafa-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Rafa-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Rafa-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <img align="center" alt="Rafa-Csharp" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg">
</div>
  
  ##
 
<div> 
  <a href="https://www.youtube.com/channel/UC_-uuuZbY0AAt9CViNzvc-Q" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" target="_blank"></a>
  <a href="https://instagram.com/rafaballerini" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
 	<a href="https://www.twitch.tv/rafaballerinii" target="_blank"><img src="https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white" target="_blank"></a>
 <a href="https://discord.gg/wagxzStdcR" target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a> 
  <a href = "mailto:contatorafaballerini@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/rafaella-ballerini-45875016a" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  
</div>

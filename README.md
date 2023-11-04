# MY PROJECTS
# All these projects have been developed while learning HTML, CSS, JS
<a href="https://sikandaraja.github.io/html-css-js-project/Profile-card/" style="font-size:2em;">Profile Card</a> || <a href="https://sikandaraja.github.io/html-css-js-project/simple-calculator/" style="font-size:2em;">Simple Calculator</a> || <a href="https://sikandaraja.github.io/html-css-js-project/password-generator/" style="font-size:2em;">Password Generator</a> || <a href="https://sikandaraja.github.io/html-css-js-project/qr-generator/" style="font-size:2em;">QR Code Generator</a> || <a href="https://sikandaraja.github.io/html-css-js-project/quote-generator/" style="font-size:2em;">Quote Generator</a>
<!-- HTML !-->
<button class="button-48" role="button"><span class="text">Button 48</span></button>

/* CSS */
.button-48 {
  appearance: none;
  background-color: #FFFFFF;
  border-width: 0;
  box-sizing: border-box;
  color: #000000;
  cursor: pointer;
  display: inline-block;
  font-family: Clarkson,Helvetica,sans-serif;
  font-size: 14px;
  font-weight: 500;
  letter-spacing: 0;
  line-height: 1em;
  margin: 0;
  opacity: 1;
  outline: 0;
  padding: 1.5em 2.2em;
  position: relative;
  text-align: center;
  text-decoration: none;
  text-rendering: geometricprecision;
  text-transform: uppercase;
  transition: opacity 300ms cubic-bezier(.694, 0, 0.335, 1),background-color 100ms cubic-bezier(.694, 0, 0.335, 1),color 100ms cubic-bezier(.694, 0, 0.335, 1);
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  vertical-align: baseline;
  white-space: nowrap;
}

.button-48:before {
  animation: opacityFallbackOut .5s step-end forwards;
  backface-visibility: hidden;
  background-color: #EBEBEB;
  clip-path: polygon(-1% 0, 0 0, -25% 100%, -1% 100%);
  content: "";
  height: 100%;
  left: 0;
  position: absolute;
  top: 0;
  transform: translateZ(0);
  transition: clip-path .5s cubic-bezier(.165, 0.84, 0.44, 1), -webkit-clip-path .5s cubic-bezier(.165, 0.84, 0.44, 1);
  width: 100%;
}

.button-48:hover:before {
  animation: opacityFallbackIn 0s step-start forwards;
  clip-path: polygon(0 0, 101% 0, 101% 101%, 0 101%);
}

.button-48:after {
  background-color: #FFFFFF;
}

.button-48 span {
  z-index: 1;
  position: relative;
}

# HTML5-can-control-the-effects-of-vortex-speed
*, *::before, *::after {
  box-sizing: border-box;
}

h1, h2, h3, h4, h5 {
  margin: 0;
}
*:focus {
  outline: 2px solid #fff;
}

body {
  margin: 0;
  height: 100vh;
  font-family: sans-serif;
  font-size: 1rem;
  line-height: 1.8;
  
}

body[tabindex]:focus {
  outline: none;
}

canvas 
  position: fixed;
  display: block;
  width: 100vw;
  height: 100vh;
}

/* simple type scale */
h1 {font-size: 1.383rem;}
h2 {font-size: 1.296rem;}
h3 {font-size: 1.215rem;}
h4 {font-size: 1.138rem;}
h5 {font-size: 1.067rem;}
small, .text--small {font-size: 0.937rem;}

/*

.ui {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background: rgba(0,0,0,.8);
  padding: 1rem;
  color: #fff;
  display: flex;
  flex-wrap: wrap;
  gap: .25rem;
  opacity: 0;
  transition: 200ms opacity;
}

body:active, body:hover .ui {
  opacity: 1;
}

.ui h1 {
  flex-basis: 100%;
}
.field {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  background: #000;
  border-radius: .25rem;
  padding: .25rem;
}

.ui label {
  font-size: 0.937rem;
  display: block;
}

.ui button {
  background: transparent;
  border: 1px solid deeppink;
  border-radius: .25rem;
  padding: .25rem;
  font-size: 1rem;
  color: #fff;
  text-transform: uppercase;
  cursor: pointer;
}

.ui button:active {
  background: deeppink;
}

*/

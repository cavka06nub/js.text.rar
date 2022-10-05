# js.text.rar
my work
*, *::before, *::after {
    box-sizing: border-box;
    font-family: Gotham Raunded,sans-serif;
    font-weight: normal;

}
 
body {
    padding: 0;
    margin: 0;
    background: linear-gradient(to right,#00AAFF, #00FF6C);
}

.calculator-grid {
    margin-top: 200px;
    display: grid;
    justify-content: center;
    align-items: center;
    min-height: 300px;
    grid-template-columns: repeat(4,80px);
    grid-template-rows: minmax(120px, auto) repeat(5,50px);
}

.calculator-grid > button {
   cursor: pointer; 
   font-size:2rem;
   border: 1px solid white;
   outline: none;
   background-color: rgba(255,255,255,75)
}

.calculator-grid > button:hover{
    background-color: rgba(255,255,255, .9);
}

.span-two {
    grid-column: span 2;

}

.output {
    grid-column: 1 / -1;
    background-color:  rgba(0,0, .75);
    display: flex;
    align-items: flex-end;
    justify-content: space-around;
    flex-direction: column;
    padding: 45px;
    word-wrap: break-word;
    word-break: break-all;


}

.output .prevent-operand {
    color: white;
    font-size: 1.5rem;

}



.output .prevent-operand {
    color: white;
    font-size: 2.5rem;

}

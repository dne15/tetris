
@import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');

body {
  margin: 0;
}

h1 {
  font-size: 3rem;
  text-align: center;
  font-family: 'Press Start 2P'; 
}


.scoreAndBtn {
  text-align: center;
  padding-bottom: 3rem;
  font-family: 'Press Start 2P'; 
  width: 15%;

}

button {
  font-family: 'Press Start 2P'; 
  font-size: 16px;
  color: rgb(217, 204, 204);
  background-color: #201e1e;
  border: 4px solid #44ff1f; 
  border-radius: 2rem;
  padding: 10px 20px;
  margin-top: 0.5rem;
  text-transform: uppercase;
  text-align: center;
  cursor: pointer;
  box-shadow: 0 0 10px #0fff1b, 0 0 20px #2de611, 0 0 30px #3dfb33; /* Glowing effect */
  
}

.container {
    display: flex;
    background-color: white;
    justify-content: center;
    
  }
  
  
  .grid {
    width: 200px;
    height: 400px;
    display: flex;
    flex-wrap: wrap;
    background-color: rgb(163, 223, 248);
  }
  
  .grid div {
    height: 20px;
    width: 20px;
  }

  /*how to not include last row*/
  .grid div:not(:nth-last-child(-n+10)) {
    outline: 1px solid rgb(44, 174, 234); /* Adjust the color and thickness as needed */
    border-radius: 3px;
  }


  .tetromino {
    background-color: blue;
  }
  
  
  .mini-grid {
    margin-left: 50px;
    width: 80px;
    height: 80px;
    display: flex;
    flex-wrap: wrap;
    background-color: yellow;
  }
  
  .mini-grid div {
    height: 20px;
    width: 20px;
    background-color: rgb(188, 174, 174);
    outline: 1px solid rgb(72, 73, 75); /* Adjust the color and thickness as needed */
    border-radius: 3px;
  }
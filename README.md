# Build-Projects
 <body>
         
         <div class="firstRow">
        <input type="text" class="result" id="result" placeholder="result" />
             <input type="button" class="clear" value="C" onclick="clearResult()" />
        </div>
        
        <div class="secondRow">
        <input type="button" value="1" onclick="insertValue(1)" />
        <input type="button" value="2" onclick="insertValue(2)" />
            <input type="button" value="3" onclick="insertValue(3)" />
            <input type="button" value="+" onclick="insertValue('+')" />
        </div>
        
        <div class="thirdRow">
        <input type="button" value="4" onclick="insertValue(4)" />
        <input type="button" value="5" onclick="insertValue(5)" />
            <input type="button" value="6" onclick="insertValue(6)" />
            <input type="button" value="-" onclick="insertValue('-')" />
        </div>
        
        <div class="fourthRow">
        <input type="button" value="7" onclick="insertValue(7)" />
        <input type="button" value="8" onclick="insertValue(8)" />
            <input type="button" value="9" onclick="insertValue(9)" />
            <input type="button" value="*" onclick="insertValue('*')" />
        </div>
        
        <div class="fifthRow">
        <input type="button" value="0" onclick="insertValue(0)" />
        <input type="button" value="/" onclick="insertValue('/')" />
            <input type="button" value="." onclick="insertValue('.')" />
            <input type="button" value="=" onclick= "result.value = eval(result.value)" />
             
        </div>
       <script>
           
          function clearResult(){
              document.getElementById('result').value = '';
          }
           function insertValue(value){
               document.getElementById('result').value +=value;
           }
           
            
        </script>
       
         
    </body>

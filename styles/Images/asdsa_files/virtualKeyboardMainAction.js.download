

//userinput

let userinput = document.getElementById("userinput");



const keyElements = document.getElementsByTagName('button');

const space = document.getElementById('space');
const backspace = document.getElementById('backspace');


function virtualKeyword(){

        
    for (let i = 0; i < keyElements.length; i++){
        keyElements[i].addEventListener("click",(event)=>{
            userinput.textContent += keyElements[i].textContent;

        


            
        })

        
    






        
    }


    backspace.addEventListener("click",(event)=>{
    userinput.textContent =  userinput.textContent.slice(0,-1);
    })




    space.addEventListener('click',(event)=>{
        userinput.textContent += " ";
    })





    

   



}







virtualKeyword();
   
  

       







    for (let i = 0; i < keyElements.length; i++){
        keyElements[i].addEventListener("keydown",(event)=>{

               userinput.textContent += event.key

               
        

        


            
        })

        
    






        
    }

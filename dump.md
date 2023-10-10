.header {
  box-shadow: 0px 0px 20px rgb(217, 217, 217);
    display: flex ;
    position:sticky ;
    width: 100%;
    top: 0;
    padding: 0px 70px;
    align-items: center;
    justify-content: space-between;
    background-color: white;
    z-index: 5000;
 }

 .header header{
  margin: 0;
 }

 .header img{
   width: 270px;
   cursor: pointer;
   background-color: white;
   object-fit: cover;

 }



 .Navigation_Link {
   list-style: none;
   font-size: 16px;
   font-weight: 350;
   background-color: white;
   margin: 0;
   padding: 0;

 }

 .Navigation_Link li {
   display: inline-block;
   padding-top: 0px;
   background-color: white;
   right: 0;
   margin-right: 50px;
   }


 
 .Navigation_Link a{
  text-decoration: none;
  color:var(--color-theme) ;
  background-color: white;
  }

  .Navigation_Link a:hover{
    color: darkgrey;
    transition: 0.5s;
  }

  .Navigation_Link a:active{
    opacity: 0.3;
    transition: 0.2s;
  }



 .Login button{
  background-color: var(--color-theme);
  color: white;
  border: 1px solid;
  padding:  10px 20px;
  border: none;
  border-radius: 5px;
  font-size: 16px;
  font-weight: 500;
  cursor: pointer;
  border: 1px solid var(--color-theme);

 }

 .Login button:hover {
  color: var(--color-theme);
  background-color: rgb(255, 255, 255);
  cursor: pointer;
  transition: 0.5s;
  border: 1px solid var(--color-theme);
  
  

 }

 .Login button:active{
  background-color: darkgray;
  opacity: 0.5;
  transition: 0.4s;
  border: 1px solid var(--color-theme);
 }

 .toggle_button {
  position: absolute;
  display: none;
  top: 1.7rem;
  right: 1.7rem;
  flex-direction: column;
  justify-content: space-between;
  width: 25px;
  height: 16px;
  z-index: 6000;
 }
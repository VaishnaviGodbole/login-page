<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
<style>
    body{
        display: flex;
        align-items: center;
        flex-direction: column;
    }
   .Form{
    height: 500px;
    width: 400px;
    border-radius: 10px;
    display: flex;
    align-items: center;
    flex-direction: column;
    border:0.5px solid grey;
   } 

   input{
    height: 20px;
    width: 200px;
    margin-top: 40px;
    border: 0.5px solid gray;
    border-radius: 3px;
   }
   
   button{
    width: 80px;
    height: 30px;
    position: relative;
    top: 150px;
    border-color: gray;
    border-radius:4px ;
   }
   button:hover{
    background-color: #06D001; 
    box-shadow: 4px 4px 7px #9BEC00;
    
}

</style>
</head>
<body>
    <h1>Login Page</h1>
    <form class="Form">
    <div class="In">
     <div> User Name:  <input type="text" placeholder="Vaishnavi Godbole"></div>
     <div> Contact no:  <input type="number" placeholder="Contact no."></div>
     <div> Email:  <input type="email" placeholder="Godbole@gmail.com"></div>
     <div> Password:  <input type="password" placeholder="Password"></div>
    </div>
    <button><b>Submit</b></button>
    </form>
</body>
</html>

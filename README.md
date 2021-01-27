<!DOCTYPE html>
<html 
<head>
<title> Pittsburgh Photography: Prints, Calendars, Postcards and More </title>
<meta name= "viewport" content= "width=device-width, initial-scale=1">
<meta name="description" content="Online photography gallery based in Pittsburgh, PA. Offers prints, calendars, postcards, real estate photgraphy and more ">
  <meta http-equiv="refresh" content="10; URL=http://cnn.com/" />


    <style> 
       {
  margin: 0;
  font-family: Arial;
  font-size: 20px;
}

#myVideo {
  object-fit: cover;
  position: absolute;
  right: 0;
  bottom: 0;
  min-width: 100%; 
  min-height: 100%;
  top: 50%; 
  left: 50%; 
  transform: translate(-50%, -50%);
  max-width: -webkit-fill-available;
}

.content {
  position: fixed;
  bottom: 0;
  background: rgba(0, 0, 0, 0.5);
  color: #f1f1f1;
  width: 100%;
  padding: 20px;
}
  
    .loader { 
        width: 100px; 
        margin: 150px auto 70px; 
        position: relative; 
    } 
  
    .loader .loading_1 { 
        position: relative; 
        width: 200%; 
        height: 10px; 
        border: 1px #626567; 
        border-radius: 25px; 
        animation: turn 5s linear 5s infinite; 
    } 
  
    .loader .loading_1:before { 
  content: "";      
        position: relative; 
        width: 0; 
        height: 100%; 
        background-color: #95A5A6; 
        border-radius: 20px; 
        bottom: 20px;
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 0 auto;
        animation: load 4s linear infinite; 
    } 
  
    .loader .loading_2 { 
        position: relative; 
        width: 200%; 
        bottom: 20%; 
        color: #154360; 
        font-size: 13px;
        font-family: "arial"; 
        text-align: center;
        
    } 
  
    @keyframes load { 
        0% { 
            width: 0%; 
        } 
  
        87.5% { 
            width: 100%; 
        } 
    } 
  
    @keyframes turn { 
        0% { 
            transform: rotateY(0deg); 
        } 
  
        6.25%, 
        50% { 
            transform: rotateY(180deg); 
        } 
  
        56.25%, 
        100% { 
            transform: rotateY(360deg); 
        } 
    } 
  
    @keyframes bounce { 
  
        0%, 
        100% { 
            top: 10px; 
        } 
  
        12.5% { 
            top: 30px; 
        } 
    } 
</style> 

</head>

<body> 

<video class="video-background" autoplay loop muted playsinline  id="myVideo">
  <source src="Pittsburgh_Photography.mp4" type="video/mp4">; 
  
</video>
    
<div class="loader"> 
        <div class="loading_1"></div> 
        <div class="loading_2">welcome to awesome</div> 
    </div>

</body>
</html>

<!DOCTYPE html>
<html 
<head>
<title> Pittsburgh Photography: Prints, Calendars, Postcards and More </title>
<meta name= "viewport" content= "width=device-width, initial-scale=1">
<meta name="description" content="Online photography gallery based in Pittsburgh, PA. Offers prints, calendars, postcards, real estate photgraphy and more ">
  <meta http-equiv="refresh" content="3.0; URL=http://bbc.com//" />


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
   width: 130px; 
   height: 15px;
   position: fixed;
   left: 50%;
   top: 80%; 
   transform: translate(-50%, -50%);  
      } 
  
     .loader .loading_1:before { 
  content: ""; 
        position: absolute; 
        width: 0; 
        height: 100%; 
        background-color: #95A5A6; 
        border-radius: 20px; 
        bottom: 20%; 
        display: flex;
        align-items: center;
        margin: auto;
        animation: load 4s linear infinite; 
    }
  
    .loader .loading_2 { 
        position: relative; 
        width: 200%; 
        bottom: 20%;
        color: #154360; 
        font-size: 13px;
        font-family: "arial";
        display: flex;
        align-items: center;
        margin: auto;
       
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

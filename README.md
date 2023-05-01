# Ex.04 Images as Hyperlinks
## AIM
  Insert five different images ( 2 on Crops and 2 on Machines and 1 on Fertilizer required ). 
  Skip two lines between each image. Each image should have a title. 
  Display the images with a border of size 2, a width of 200, and a height of 200, 
  it should be linked to a search engine of your choice and when each image is clicked, 
  the respective search engine should be opened in a new window.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the required images using ```<img>``` tag.

### STEP-3
  Set the image border size as 2, image width as 200 and height as 200.

### STEP-4
  Use the ```<a>``` anchor tag to link the corresponding search engines.  

### STEP-5
  Give double line spacing between the images using ```<br>``` tags.
  
### STEP-6
  Open the file in a browser and verify the output.
```  
## CODE
<html>
<head>
<title>Agricultural Search</title>
</head>
<body>
<h1>Agricultural Search</h1>
<h2>ploughing</h2>
<a href="https://www.google.com/search?q=ploughing&rlz=1C1CHBF_enIN1022IN1022&oq=plough&aqs=chrome.1.69i57j0i67i433i650j0i433i512j0i512j0i433i512j0i512l2j0i433i512j0i512l2.20089j0j4&sourceid=chrome&ie=UTF-8#ip=1">
<img src ="ploughing.jpeg" width ="500" height="200">
</a>
<h2>Sowing</h2> 
<a href="https://www.google.com/search?q=sowing+seeds&source=lmns&bih=746&biw=1536&rlz=1C1CHBF_enIN1022IN1022&hl=en&sa=X&ved=2ahUKEwiOztqGwtT-AhWJ3XMBHRJbDmwQ_AUoAHoECAEQAA">
<img src="sowing.webp" width="500" height="200">
</a>
<h2>Fertilizers</h2>
<a href="https://www.google.com/search?q=fertilizer&rlz=1C1CHBF_enIN1022IN1022&oq=ferti&aqs=chrome.1.69i57j0i67i433i650j0i67i650l2j0i433i512j0i67i433i650j0i67i650j0i512j0i67i650j46i199i465i512.7744j0j4&sourceid=chrome&ie=UTF-8">
<img src="fertilizers.webp" width="500" height="200">
</a>
<h2>Biofertilizers</h2>
<a href="https://www.google.com/search?q=fertilizer&rlz=1C1CHBF_enIN1022IN1022&oq=ferti&aqs=chrome.1.69i57j0i67i433i650j0i67i650l2j0i433i512j0i67i433i650j0i67i650j0i512j0i67i650j46i199i465i512.7744j0j4&sourceid=chrome&ie=UTF-8">
<img src="biofertilizer.jpg" width="500" height="200">
</a>
<h2>Horticulture</h2>
<a href="https://www.google.com/search?q=horiculture&source=lmns&bih=746&biw=1536&rlz=1C1CHBF_enIN1022IN1022&hl=en&sa=X&ved=2ahUKEwiB3c-iy9T-AhWrzaACHWorA38Q_AUoAHoECAEQAA">
<img src="horticulture.jpg" width="500" height="200">
</a>
</body>
</html>
```
## OUTPUT

![Screenshot (8)](https://user-images.githubusercontent.com/127816726/235496253-d76dcda7-8225-413e-a520-bdb1a33f935a.png)

## RESULT
 Images as hyperlinks is implemented successfully.

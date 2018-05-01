//1. Start with the image you want to change.
var img = new SimpleImage("hilton.jpg");
var sp = new SimplePixel(255, 255, 255);


//2. Figure out the width of the image.
print(img);
var width = img.getWidth();
var height = img.getHeight();
print(img.getPixel(0,0));

//3. For each pixel in the image:
//Get the x-coordinate for that pixel
var x = sp.getX();
var y = sp.getY();

print(sp.getX());
print(sp.getY());
//If the pixel’s x-coordinate is less than one-third of the image’s width, set the pixel’s red value to 255.
//If the pixel’s x-coordinate is between one-third and two-thirds of the image’s width, set the pixel’s green value to 255.
//If the pixel’s x-coordinate is more than two-thirds of the image’s width, set the pixel’s blue value to 255.


   var image = new SimpleImage ("smallpanda.png");
var redLeft = image.getWidth()/1/3; 
var blueRight = (image.getWidth()/1/3)*2; 

//Red
for (var pixel of image.values()){
    if (pixel.getX() < redLeft) {
    //If the pixel’s x-coordinate is less than one-third of the image’s width, set the pixel’s red value to 255.
    pixel.setRed(255); 
    }
//Green
    if (( redLeft <= pixel.getX() ) && (pixel.getX() <= blueRight)) {
    //If the pixel’s x-coordinate is between one-third and two-thirds of the image’s width, set the pixel’s green value to 255.
    pixel.setGreen(255); 
    }
//Blue
    else{
      if (pixel.getX() > blueRight) {
    //If the pixel’s x-coordinate is more than two-thirds of the image’s width, set the pixel’s blue value to 255.
    pixel.setBlue(255); 
    }  
    }

}

print(image); 

//new approach

var img = new SimpleImage("Hilton.jpg");
    w = image.getWidth(); // w means getWidth, we can also write something as imgWidth as the name of variable
for (var pixel of image.values()) {
     x = pixel.getX();
     if (x < w/3) {
          pixel.setRed(255);
     }
     if (x >= imgWidth/3 || x < 2*w/3) {
          pixel.setGreen(255);
     }
     if (x >= 2*w/3 || x <= w) {
          pixel.setBlue(255);
     }
}
print (img);



//Gives value of each pixel in the image
for(var pixel of img.values())
{
    //To divide the given image into 3 parts and to set pixel value to red

    if(pixel.getX()<img.getWidth()/3)
    {
        pixel.setRed(255);
    }
    //This is to set color of 3rd part of the image to Blue.
    else if(pixel.getX()>img.getWidth()*2/3)
    {
        pixel.setBlue(255);
    }
    //This is to set color of 2nd part of the image to Green.
    else if(img.getWidth()/3<=pixel.getX() && pixel.getX()<=img.getWidth()*2/3)
    {
        pixel.setGreen(255);
    }
}
print(img);


var fgImage = new SimpleImage("drewRobert.png");
var w       = fgImage.getWidth();
var h       = fgImage.getHeight();

//var w / h is the name we gave so we dont have to write a lot
//fgImage means which SimpleImage heigh we want to getHeight
// . means  the dot operator means inside of. We want the getHeight method inside of fgImage. 
// getHeight is  name of the method that we want to call. In this case, it is getHeight.
// () parentheses. Parentheses after a name indicate that it is a method, or a function, which is similar. 
      If the method took any parameters, you would specify them inside the parentheses. 


function square(x) {
    var ans = x * x;
    return ans;
}
// function - First we have the keyword function, which says that we are about to define a new function. 
// square   -Then we have the name of the function. As with variables, you can pick most any name you want. But it should be descriptive. In this case, square is a good name since it describes what the function does. 
// ()       -Next, we have the parameter list in parentheses. Here we are declaring the names of the parameters. These will act like variables which are initialized by the values passed in when the function is called. 
              They tell the function what specifically it should do.   
            In this case, the parameter says, what particular number to square. We decided to call it x. If there were multiple parameters, we could separate their names by commas. 
// body of the function is always inside {}
// inside of the body we have return ans type of statement. This is a return statement, which is how a function says what it's answer is. 
            The syntax of a return statement is the keyword return followed by an expression whose value is what the function should give back as its answer,          
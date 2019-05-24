# moopoo
A simple set of css classes for margin and padding

Clone the repo and use the following to install dependencies  

    npm install

Once everything has installed use the following to compile the css  

    npm run scss

This will provide the css needed for your project

## note
values are in em, overall values can be applied, top and bottom values can be applied and individual values can be applied

## how to use
The logic is simple, use `m` for margin and `p` for padding, followed by the numeric value for the space you want to use in 'em' and add that class to your inline html element e.g. 

Uses a numeric value from 1 to 9

    <div class="mt5 ml3 mb2 mr3">5em top, 3em left, 2em bottom and 3em right</div>

A single numeric value applies space all around the element.  

    m1
    
Use a double numeric value to apply space to the top & bottom or left & right. 

    m20
    m05

Use `t` followed by a numeric value to apply space to the top.

    mt2
    
Use `r` followed by a numeric value to apply space to the right.

    mr4

Use `b` followed by a numeric value to apply space to the bottom.

    mb6
    
Use `l` followed by a numeric value to apply space to the left.

    ml8
    
# html examples
    
### classic moo poo
zero margin all around an element by adding the class `m00` and `p00` to an element.

    <div class="your-custom-class m00 poo">
        <h1>Your parent element has zero margin and zero padding all around</h1>
    </div>
      
### margin all

    <div class="your-custom-class m5">
        <h1>Your parent element now has a 5em margin all around</h1>
    </div>
    
### margin top and bottom

    <div class="your-custom-class m50">
        <h1>Your parent element now has a 5em margin top and bottom</h1>
    </div>
    
### padding all

    <div class="your-custom-class p5">
        <h1>Your parent element now has a 5em padding all around</h1>
    </div>
    
### padding left and right

    <div class="your-custom-class p05">
        <h1>Your parent element now has a 5em padding left and right</h1>
    </div>
    


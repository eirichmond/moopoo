# moopoo
A simple set of css classes for margin and padding

Clone the repo and use the following to install dependencies 
`npm install`

Once everything has installed use the following to compile the css
`npm run scss`

This will provide the css needed for your project

## note
values are in em, overall values can be applied, top and bottom values can be applied and individual values can be applied

## how to use
The logic is simple, use `m` for margin and `p` for padding, followed by the numeric value for the space you want to use in 'em'

`x` = a numeric value  
`mx` A single numeric value applies space all around the element.  
`mxx` A double numeric value applies space to the top & bottom or left & right.  
`mtx` A top numeric value.  
`mlx` A left numeric value.  
`mbx` A bottom numeric value.  
`mrx` A right numeric value.  

### classic moo
`m00` zero margin all around an element by adding the class `.m00` to an element.

### classid poo
`p00` zero padding all around an element by adding the class `.p00` to an element.

Day 1- December 31,2023 ( HTML )
<-------------------------------------->

semantic tags: em,strong can be used instead b and i tag to make it more meaningful.
!There is nothing much to learn today....

Day-2-January 1,  2024 ( CSS )
<-------------------------------------->

## To easily duplicate multiple selectors on html on mac (press option + shift + down arrow button )

.class{
visibility:hidden;   --> this hides the visibility of the content but still takes the space

display:none;   --> this completely hides the content also hides the space 
}

##how box-shadow works

.class{
box-shadow: x-axis, y-axis, spread, color;
}

Note: --> if use display:inline the element will not take margin  for top and bottom also will not take any height.
to chnage this display:block can be used which will create a new line or display:inline-block.

January 2, 2024 ( Git & Github )
<-------------------------------------->

--> Git is a distributed version control sysytem.
--> Github is a web based hosting servie and platform that utilizes git version control system
--> ls to check if the numbers of directories that can be used
--> git init -> to initialize.
--> git add . -> to add
-- > git --global user.name "user name"
-- > git --global user.email (write email without any quoatation) 
--> check what has changed -> git config -l
---> Live server on github https://username.github.io/project name
-->#create new beanch git checkout -b branchName
--> switch to branch git checkout branchNmae

January 8 ( CSS Pseudo class & Element )
<-------------------------------------->
--> :focus{} ,:visited {}, :first-child{}, :last-child{}, :nth-child(2n+1,2n,2n+2){}
--> ::first-letter{},::first-line{},::selection{},::before{},::after{}
January 9,2024 (Responsive web design)
--------------------------------
--grid---
grid-templates-columns:repeat(4,1fr)
grid-templates-rows: repeat (3,1fr or pixe)
----@media query ---
small devices: @media screen and (max-width:576px){}
medium devices: @media screen and(min-width:576px and max-width:992px){}
Note: work with fraction changes if you use fr . let's think you are using 5 columns with 1fr space then at the breaking point use 2 or 3 columns with 1fr unit. 


--- 7 things to know for web responsiveness.
1. meta tag in your HTML that defines your viewport.
2. Use CSS Relative unit.
3. Body max-width and Center Align. can be achieved using body{margin:0 auto}.
4. Image fluid (use percentage for width)
5. two column flex and use media query with flex direction column.
6. multi column :use grid
7. Responsive Menu
----> Grid is layout first while flexbox is content first
---> Grid is multi dimensional while flexbox is single dimensional.

January 10, 2024 ( Flexbox & Grid)
----------------------------------
--> to expand anything towards column or use grid-row: span 5//grid-column: span 5
--> for making the image fit the content you can use img-width like : width: calc((100%-5px)/ number of images)
Topic: 106. How rem and max-width Work
Link: https://www.udemy.com/course/design-and-develop-a-killer-website-with-html5-and-css3/learn/lecture/27513166#overview



Rem - is a root element font-size (root element is html), if we don't define the custom font-size, so default font size will be 16px;

by default 1rem = 16px

we can change the root font-size on the page and if we use rem, all dimensions well change automatically. 

If de don't define custom font-size in root (html) element 1 rem will be equal by default 16px. If we specify font-size in root elemnet html so all dimensoons in rem will recalculate. 

by changing the root font-size we change all layout (if we use rem in our dimensions).

if we specify root font size in 10px it will be really easy to calculate rem's.

we need to set value for root font-size not in px but in percentage. We want to set default font-size to 10px from defaukt 16px in percentage. so we devide 10px / 16px and get 62,5%.
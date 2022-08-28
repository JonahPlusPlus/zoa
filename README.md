# zoa

a bare-bones css layout framework

I needed something that provided minimal layout changes while not being "themed".

Features:
* Normalized across browsers
* Everything uses `box-sizing: border-box; margin: 0;`
* CSS Variables for changing default parameters
* Custom tags `z-row` and `z-col`
* `main`, `article`, `section` are flexbox columns (section has a width of 960px)
* `header`, `footer` are flexbox rows

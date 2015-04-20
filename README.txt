
  Web Tetris written with Pure Java Script.


Class hierarchy:
    
          

          Pattern (base class:holds all member-function)
         /  |  |  \ 
        /   |  |   \
       /    |  |    \
      /    /    \    \
Pattern1 ~ PatternX ~ Pattern6 


HTML:  stage div- whole stage with 10x20 cubic blocks 
       patDiv(pattern Div) - one Pattern is on patDiv:rotating Div
             - patDiv consists of pattternx(div) + transparentBlock(div)

global function:
    addOne (pattern) : add one pattern to Stage.
    keyListener : key event handler.
    onload : loading function.

1. Flex Box:
  a. for flex box first we create container element
    with the display type of flex
  
  b. every direct child element become flex item
      and by becoming flex item they come next to each other
      (even the block) (min-width is important flex items)
      (Flex items by default don't have any width or height)

2. Using flex-grow: num; to give the growth rate of 
    each flex item (some how it is like the number of the columns)
    flex-grow is relative to the size of other elements
    (flex-grow says that I want you to grow to AVAILABLE space)

3. Using flex-shrink: num; is the opposite of flex-growth:
    shows that how the elements shrinks when the browser
      become smaller

4. flex-wrapp: wrap; (in the container element)
    (flex-wrap: wrap-reverse; goes up)
    (flex-wrap: no-wrap; is the default behavior)
    when there is no space for the elements
     (the space is less than min-width)
     instead of using scroll the element go to next line

5. flex-basis: 100px; 
    flex basis define the basis width of the box, if you define 
    the flex-grow beside the flex-basis it grows according to the
    flex-basis
    even if ther is no room for the elements/they are going to shrink

6. flex: grow shrink basis (short-hand notation)

7. justify-content (using this in the parent element if
    there is no flex in the child elements)

    justify-content: 
      (center/ flex-end/flex-start(default behavior)/space-around/space-between)

8. Axis:

    flex-flow: column; (row-reverse / column-reverse / row)
    a. when we declare flex-flow: column; the flex-basis become
     the height of the flex elements
    b. the cross axis is always prependicular to main-axis
    c. justify-content only apply to the main-axis

9. properties that affect cross axis:

    alin-itmes: flex-start; 
    align-items is for cross-axis

10. order of the elements:

    we can use order: 0; for the flex items the higher the number
    the last the item come
# CSS Parent and Child Boxes

## Description

This project demonstrates **CSS `position: sticky`** and how the `top` property is used to control the sticky position of an element.

## CSS Positioning

### Position: Sticky

`position: sticky` keeps an element in its normal position until a specified offset is reached. After reaching that position, the element sticks while scrolling within its containing block.

```css
.colr3 {
    background-color: #e48d09;
    position: sticky;
    top: 190px;
}
```

Here:

* `position: sticky` → makes the element sticky while scrolling.
* `top: 190px` → the element sticks `190px` from the top of the viewport when the sticky condition is reached.

## Key Takeaway

**Sticky = Normal position + Sticks when scrolling reaches the specified offset.**

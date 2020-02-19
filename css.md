# css
### cascading!

Styles can be overwritten by other styles... there is a hierearchy of ways to apply styles

- inline JSX styles `style={{}}`
- ids `#my-button` (cannot be shared)
- classes `.my-button`
- tag name `button{}`

### units
- px
- %
- vw / vh (viewWidth, viewHeight)
- rem (proportional to the font-size of the <html> element)


### common style rules
- display
- background or background-color
- margin
- padding
- position
- height / width
- color (text color)
- font-size
font-weight
- border
- border-radius
- z-index: how elements overlap. Needs a "position" rule to work


### flex
- `display:flex`
- `flex-direction`: row/column/row-reverse/column-reverse
- `align-items`: center, flex-start
- `justify-content`: center, space-between, space-around
- `flex-shrink:0` will make your flex children NOT shrink

### position
- `relative`: positioned according to the elements around it
- `absolute`: means that the element is positioned with "top", "left", "right", "bottom" rules (relative to its first parent that has `position:relative`)




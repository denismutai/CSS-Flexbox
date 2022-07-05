# CSS-Flexbox
Exploring different layout options with Flexbox
# Introduction
Explore the various CSS Flexbox container and child properties by creating diffeent layouts and builing an image gallery.

# Introduction to Flexbox
layout blueprint for making websites
Enables developers to layout content and create structure for responsive websites

# Flexbox structure
Two axex- main axis- horizontal or (x-axis)and the cross axis-vertical or the y-axis

# possible Flex container and flex items properties and values
## Flex Container
* **display:** flex
* **flex-direction:** row||column||column-reverse||row-reverse
* **justify-content:** flex-start||flex-end||centre||space-between||space-around||space-evenly
* **align-items:** flex-start||flex-end||centre||stretch||baseline
* **align-content:** flex-start||flex-end||center||stretch||space-between||space around
## Flex-items
* **align-self:** auto||flex-start||flex-end||center||baseline||stretch
* **order:** any positive value
* **flex-grow** any positive value
* **flex-shrink:** any positive value
* **flex-wrap:** wrap||wrap-reverse||nowrap

### flex-direction
Applied on the flex container to determine the manner in which the flex items or children are going to be arranged in terms of distribution and orientation
The possible values of flex-direction are:
* __row__ items will be arranged horizontally across the main axis
* __row-reverse__ items are arranged horizontally across the main axis but in reverse order
* __column__ items are arranged vertically along the cross axis
* __column-reverse__ items are arranged vertically along the cross axis but in reversed order

### justify-content
Property applied to the container to arrange flex items along it's main axis
The possible values of the property are:

#### justify-content that arrange the items on various parts of the main axis
* __flex-start__ Arranges items beginning from the start of the main axis
* __flex-end__ Arranges items at the end of the main axis
* __center__ Arranges items at the center of the main axis
#### justify content properties that distribute space between items
* __space-betweem__ spaces equal space between the flex items distributing the extra dpace in between the items ***this value does not add space between the first and last items and the border of the container***
* __space-around__ distributes extra space equally in between the items and half the values at the first item's left margin and last item's right margin
* __space-evenly__ distributes the extra space in the main axis equally between the items and the first and last item's left and right margins.



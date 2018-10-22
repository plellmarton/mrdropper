<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

-   [DragNDrop][1]
    -   [Parameters][2]
    -   [renderItem][3]
        -   [Parameters][4]
    -   [update][5]
    -   [events][6]
    -   [dragStartHandler][7]
        -   [Parameters][8]
    -   [dragHandler][9]
        -   [Parameters][10]
    -   [dragOverHandler][11]
        -   [Parameters][12]
    -   [dragEndHandler][13]
        -   [Parameters][14]
    -   [dropHandler][15]
        -   [Parameters][16]
    -   [render][17]
    -   [init][18]
        -   [Parameters][19]

## DragNDrop

### Parameters

-   `Container` **[Object][20]** DOM element to use as container
-   `options` **[Object][20]** drag n' drop options

### renderItem

Renders a single draggable item

#### Parameters

-   `data` **[Object][20]** data of draggable item
-   `index` **[number][21]** index of element in data.repository or data.dropzone array

Returns **[string][22]** HTML template of item

### update

Calls render method and updates the container inner html. It should fires if data changed.

### events

Fires when DragNDrop initialize

### dragStartHandler

Event handler for ondragstart. Fires when user starts to drag an item.

#### Parameters

-   `e` **[Object][20]** event object

### dragHandler

Event handler for ondrag. Fires when user drags an item.

#### Parameters

-   `e` **[Object][20]** event object

### dragOverHandler

Event handler for ondragover. Fires when an item is over dropzone or repository.

#### Parameters

-   `e` **[Object][20]** event object

### dragEndHandler

Event handler for ondragend. Fires when user finish of drag an item.

#### Parameters

-   `e` **[Object][20]** event object

### dropHandler

Event handler for ondragend. Fires when user drop an item.

#### Parameters

-   `e` **[Object][20]** event object

### render

Render the inner HTML of drag n' drop container.

Returns **[string][22]** HTML template of drag n' drop inner HTML

### init

Initialize drag n' drop

#### Parameters

-   `Container` **[Object][20]** DOM element to use as container
-   `options` **[Object][20]** drag n' drop options

[1]: #dragndrop

[2]: #parameters

[3]: #renderitem

[4]: #parameters-1

[5]: #update

[6]: #events

[7]: #dragstarthandler

[8]: #parameters-2

[9]: #draghandler

[10]: #parameters-3

[11]: #dragoverhandler

[12]: #parameters-4

[13]: #dragendhandler

[14]: #parameters-5

[15]: #drophandler

[16]: #parameters-6

[17]: #render

[18]: #init

[19]: #parameters-7

[20]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Object

[21]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number

[22]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String
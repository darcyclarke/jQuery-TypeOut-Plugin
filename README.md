# jQuery TypeOut Plugin

A plugin that imitates a type writer-esque animation.
 
### Example Use

 ```html
<div class='text'>>> Completed Task X. Move on to Checkpoint!</div>
```
 
 ```js
 $('.text').typeOut() // Default
 $('.text').typeOut({ marker : '|', delay : 500, preserve : true }) // All options set
```

### Options


`preserve`: `boolean` (default: `false` )

Maintains HTML within the element

`marker`: `string` (default: `_`)

Sets the marker that is placed before the typed text

`delay`: `number` (default: `90`ms)

Sets the delay between display of characters

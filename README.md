Shuttle v0.3.3
============
##Demos & Examples
[Demos](http://archerproxyserver.appspot.com/jquery-shuttle/examples/index.html)

## News
28/07/2014: attribute -multiple on select is not required.<br/>
21/07/2014: modify option `dstValue` format.<br/>
22/04/2014: remove events `srcTitle` and `dstTitle`.<br/>
17/04/2014: release.

## How to Use It
###javascript
``` javascript
$(".shuttle_select").shuttle();
```
###html
just add `shuttle_select` in class and set `multiple` to your select.
```
<select class="shuttle_select"></select>
```
## API
### Options
- `filter` <br/>open filter option funcation.
- `srcTitle` <br/>source select title.
- `dstTitle` <br/>target select title.
- `dstValue` <br/>target select default option.

### Events
- `reset` <br/>reset shuttle value.
- `removeAll` <br/>remove all option.
- `disable` <br/>disable shuttle function.
- `enable` <br/>enable shuttle function.

## About
author:Archer Hsieh<br/>
e-mail: kevin8685@gmail.com

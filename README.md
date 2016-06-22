# CSS Toolbox
CSS Toolbox contains Bootstrap-based, ready to use classes to speed up front-end development. Where Bootstrap is made to develop horizontal grids, CSS Toolbox takes care of the vertical grid, paddings and margins. In addition I have filled CSS Toolbox with some helpful text-, block- and font-helper classes.

### Dependencies
CSS Toolbox is written in Sass. It uses the standard responsive Bootstrap classes (xs/sm/etc.) but does not need Bootstrap to work.

### Installation
Just copy the _toolbox.scss file into your Sass directory.

### Classnames
I try to keep classnames and prefixes as short as possible, keeping them easy to read and understand at the same time. Take a look at the file to learn these classnames. A short example:

| Prefix / classname  | Stands for... | Bootstrap example |
| ------------- | ------------- | ------------- |
| .t-...  | toolbox |
| .t-p-...  | padding | .t-p-md-20
| .t-ptb-...  | padding top bottom | .t-ptb-sm-30
| .t-mb-...  | margin bottom | .t-mb-xs-50

| Prefix / classname  | Stands for... |
| ------------- | ------------- | ------------- |
| .t-t-...  | text |
| .t-t-center  | text center |
| .t-b-...  | block |
| .t-b-b  | block block |
| .t-b-ib  | block inline block |

### Usage
Simply add classes from CSS Toolbox to your HTML elements. Below example will generate a div with a **padding of 20px**, a **bottom margin of 30px** and **centered content**:

```
<div class="t-p-20 t-mb-30 t-t-center">
    Some content here
</div>
```    

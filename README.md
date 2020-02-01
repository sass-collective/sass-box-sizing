# Sass Box Sizing

Generate global CSS box-sizing.

## Install

    npm install sass-box-sizing --save

## Usage

### Scss

    @import "sass-box-sizing/box-sizing"
    
    @include box-sizing;
    
### CSS

    * {
        box-sizing: border-box;
    }
    
    *::before,
    *::after {
        box-sizing: inherit;
    }
    
## Options

* ``content-box``
* ``border-box`` _(default)_

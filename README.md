# Sass Box Sizing

Generate global CSS box-sizing.

## Install

    npm install @sass-collective/sass-box-sizing --save

## Usage

### Sass

    @import "@sass-collective/sass-box-sizing/box-sizing"
    
    @include box-sizing();
    
### CSS

    * {
        box-sizing: border-box;
    }
    
    *::before,
    *::after {
        box-sizing: inherit;
    }
    
## Options

* ``border`` _(default)_
* ``content``

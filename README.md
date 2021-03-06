# rearmed-css
<a href="https://badge.fury.io/js/rearmed-css" target="_blank"><img height="21" style='border:0px;height:21px;' border='0' src="https://badge.fury.io/js/rearmed-css.svg" alt="NPM Version"></a>
<a href='https://www.npmjs.org/package/rearmed-css' target='_blank'><img height='21' style='border:0px;height:21px;' src='https://img.shields.io/npm/dt/rearmed-css.svg?label=NPM+Downloads' border='0' alt='NPM Downloads' /></a>
<a href='https://ko-fi.com/A5071NK' target='_blank'><img height='22' style='border:0px;height:22px;' src='https://az743702.vo.msecnd.net/cdn/kofi1.png?v=a' border='0' alt='Buy Me a Coffee' /></a> 

CSS Utility Classes for rapid development. All rules use `!important` to ensure they are applied regardless of any other rules, this is a feature.

CSS class list:
```css
/* Images */
.img-responsive


/* Alignment */
.table-text-center
.text-left
.text-center
.text-right
.center-block
.pull-left, .float-left
.pull-right, .float-right
.vcenter-wrapper
.vcenter-wrapper .vcenter


/* Font */
.thin
.bold
.unbold
.italic
.underline
.white
.light-gray
.gray
.black
.soft-black
.font-6
.font-8
.font-9
.font-10
.font-11
.font-12
.font-13
.font-14
.font-16
.font-18
.font-20
.font-22
.font-24
.font-26
.font-22
.font-30
.font-40
.font-50


/* Spacing */
.margin-vertical0
.margin-vertical
.margin-vertical2
.margin-vertical3
.margin-vertical4
.margin-vertical5
.margin-vertical6
.margin-horizontal0
.margin-horizontal
.margin-horizontal2
.margin-horizontal3
.margin-horizontal4
.margin-horizontal5
.margin-horizontal6
.margin-left0
.margin-left
.margin-left2
.margin-left3
.margin-left4
.margin-left5
.margin-left6
.margin-top0
.margin-top
.margin-top2
.margin-top3
.margin-top4
.margin-top5
.margin-top6
.margin-bottom0
.margin-bottom
.margin-bottom2
.margin-bottom3
.margin-bottom4
.margin-bottom5
.margin-bottom6
.margin-right0
.margin-right
.margin-right2
.margin-right3
.margin-right4
.margin-right5
.margin-right6
.padding-horizontal0
.padding-horizontal
.padding-horizontal2
.padding-horizontal3
.padding-horizontal4
.padding-horizontal5
.padding-horizontal6
.padding-vertical0
.padding-vertical
.padding-vertical2
.padding-vertical3
.padding-vertical4
.padding-vertical5
.padding-vertical6
.padding-top0
.padding-top
.padding-top2
.padding-top3
.padding-top4
.padding-top5
.padding-top6
.padding-left0
.padding-left
.padding-left2
.padding-left3
.padding-left4
.padding-left5
.padding-left6
.padding-right0
.padding-right
.padding-right2
.padding-right3
.padding-right4
.padding-right5
.padding-right6
.padding-bottom0
.padding-bottom
.padding-bottom2
.padding-bottom3
.padding-bottom4
.padding-bottom5
.padding-bottom6
.spacer-5
.spacer-10
.spacer-15
.spacer-20
.spacer-30
.spacer-40
.spacer-50
.spacer-75
.spacer-100


/* Visibility */
.hide, .hidden
.invisible, .hide-keep-space
.visible-xs
.visible-sm
.visible-md
.visible-lg
.hidden-xs
.hidden-sm
.hidden-md
.hidden-lg
```

[View full CSS file here](https://github.com/westonganger/rearmed-css/blob/master/src/rearmed.scss)

# Install

#### Yarn, NPM, Bower
```
yarn add rearmed-css

npm install rearmed-css

bower install rearmed-css
```

#### Rails
```ruby
# Gemfile
source 'https://rails-assets.org' do
  gem 'rails-assets-rearmed-css'
end


# app/assets/stylesheets/application.scss
/*
 *= require rearmed-css
*/
```

# Credits
Created by Weston Ganger - @westonganger

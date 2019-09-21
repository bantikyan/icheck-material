# icheck-material

<a href="https://yarnpkg.com/en/package/icheck-material" target="_blank"><img src="https://img.shields.io/badge/yarn-v1.0.1-blue.svg" alt="yarn version"></a>
<a href="https://www.npmjs.com/package/icheck-material" target="_blank"><img src="https://img.shields.io/badge/npm-v1.0.1-blue.svg" alt="npm version"></a>
<a href="https://www.nuget.org/packages/icheck-material" target="_blank"><img src="https://img.shields.io/badge/nuget-v1.0.1-blue.svg" alt="nuget version"></a>
[![](https://data.jsdelivr.com/v1/package/npm/icheck-material/badge)](https://www.jsdelivr.com/package/npm/icheck-material)

icheck-material is pure css solution for displaying material style checkboxes and radio buttons. Try [Demo](https://bantikyan.github.io/icheck-material/).

You may also like to try [icheck-bootstrap](https://github.com/bantikyan/icheck-bootstrap).  
Love cool tech? Check out [CoolTechUnder.com](https://cooltechunder.com/)

## Table of contents

* <a href="#user-content-getting-started">Getting started</a>
* <a href="#user-content-html-syntax">HTML syntax</a>
* <a href="#user-content-aspnet-mvc-syntax">ASP.NET MVC syntax</a>
* <a href="#user-content-color-schemes">Color palette</a>
* <a href="#user-content-license">License</a>

## Getting started

Several quick start options are available:

* [Download the latest release](https://github.com//bantikyan/icheck-material/archive/1.0.1.zip)
* Install with [Yarn](https://yarnpkg.com/en/package/icheck-material): <code>yarn add icheck-material</code>
* Install with [npm](https://www.npmjs.com/package/icheck-material): <code>npm install icheck-material</code>
* Install with [Nuget](https://www.nuget.org/packages/icheck-material/): <code>Install-Package icheck-material</code>
* Use CDN [jsDelivr](https://www.jsdelivr.com/package/npm/icheck-material)

Then link <code>icheck-material.css</code> file inside <code>head</code> tag of your page.

## HTML syntax

#### checkbox example

```
<div class="icheck-material-teal">
    <input type="checkbox" id="someCheckboxId" />
    <label for="someCheckboxId">Click to check</label>
</div>
```

#### radio buttons example

```
<div class="icheck-material-teal">
    <input type="radio" id="someRadioId1" name="someGroupName" />
    <label for="someRadioId1">Option 1</label>
</div>
<div class="icheck-material-teal">
    <input type="radio" id="someRadioId2" name="someGroupName" />
    <label for="someRadioId2">Option 2</label>
</div>
```

#### inline styling

To have checkboxes or radio buttons inline use .icheck-inline class

```
<div class="icheck-material-teal icheck-inline">
    <input type="checkbox" id="chb1" />
    <label for="chb1">Label 1</label>
</div>
<div class="icheck-material-teal icheck-inline">
    <input type="checkbox" id="chb2" />
    <label for="chb2">Label 2</label>
</div>
```

#### disabled

Use disabled attribute on your input (checkbox or radio) to have disabled style.

#### no label

To have components without label, you still have to have label control with empty text.

```
<div class="icheck-material-teal">
    <input type="checkbox" id="someCheckboxId" />
    <label for="someCheckboxId"></label>
</div>
```

## ASP.NET MVC syntax

#### checkbox example

```
<div class="icheck-material-teal">
    @Html.CheckBoxFor(m => m.SomeProperty, new { id = "someCheckboxId" })
    <label for="someCheckboxId">Click to check</label>
</div>
```

#### radio buttons example

```
<div class="icheck-material-teal">
    @Html.RadioButtonFor(m => m.SomeProperty, SomeValue1, new { id = "someRadioId1" }) 
    <label for="someRadioId1">Option 1</label>
</div>
<div class="icheck-material-teal">
    @Html.RadioButtonFor(m => m.SomeProperty, SomeValue2, new { id = "someRadioId2" })
    <label for="someRadioId2">Option 2</label>
</div>
```

## Color palette

Try [Demo](https://bantikyan.github.io/icheck-material/)

<b>Material Design Colors:</b> As you can see in previous examples, icheck-material-teal class used for styling. [materialpalette.com](https://www.materialpalette.com/colors)
You can use following classes for material colors:

<code>.icheck-material-red</code><br/>
<code>.icheck-material-pink</code><br/>
<code>.icheck-material-purple</code><br/>
<code>.icheck-material-deeppurple</code><br/>
<code>.icheck-material-indigo</code><br/>
<code>.icheck-material-blue</code><br/>
<code>.icheck-material-lightblue</code><br/>
<code>.icheck-material-cyan</code><br/>
<code>.icheck-material-teal</code><br/>
<code>.icheck-material-green</code><br/>
<code>.icheck-material-lightgreen</code><br/>
<code>.icheck-material-lime</code><br/>
<code>.icheck-material-yellow</code><br/>
<code>.icheck-material-amber</code><br/>
<code>.icheck-material-orange</code><br/>
<code>.icheck-material-deeporange</code><br/>
<code>.icheck-material-brown</code><br/>
<code>.icheck-material-grey</code><br/>
<code>.icheck-material-bluegrey</code><br/>

You can also have your custom color formatting by using <code>icheck-material-custom.scss</code> sass file.


## License

icheck-material released under the [MIT license](https://github.com/bantikyan/icheck-material/blob/master/LICENSE.md). Feel free to use it in personal and commercial projects.

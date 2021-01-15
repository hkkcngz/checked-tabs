# checked-tabs
CSS Only Tabs, easy use, responsive. (SCSS)

## [Demo](https://codepen.io/hkkcngz/full/ZEpVGxv)

## Usage
You need to add just same label for and input ID. Thats it.

- You can add tab menu anywhere else (:
```html
<div class="nav-tabs">
  <label class="tabs-label" for="tab1">Liste              </label>
  <label class="tabs-label" for="tab2">Genel Bakış        </label>
  <label class="tabs-label" for="tab3">Kanban             </label>
</div>
```


- And simple tab content. 
```html
<div class="tabs-wrapper">
  <input type="radio" name="tabs" class="tabs-radio" id="tab1" checked />
  <div class="tab-content">
    <p>How to use :checked-tabs?</p>
    <p>You need to add just same label for and input ID. Thats it.</p>
  </div>
  
  <input type="radio" name="tabs" class="tabs-radio" id="tab2"  />
  <div class="tab-content">Naber</div>
  
   <input type="radio" name="tabs" class="tabs-radio" id="tab3"  />
  <div class="tab-content">Nasılsın</div>
</div>
```

#### Why you coded this?
- Because I am too lazy to handle/struggle with bootstrap react libray. This also React hack :P

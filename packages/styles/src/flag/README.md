# Flag

Flag displays contextual information about events on the page.

## Default

```html
showSource: true
---
<div class="as-flag">
  <div class="as-flag__icon">
    <i style="color: #80B622;" class="as-icon as-icon-alert-fill"></i>
  </div>
  <div class="as-flag__content">
    <h4 class="as-body as-color--type-01">You are now connected</h4>
    <p class="as-body as-color--type-03">You have been added to the group “New Store on this region”</p>
  </div>
</div>
```

## With two icons

```html
showSource: true
---
<div class="as-flag">
  <div class="as-flag__icon">
    <i style="color: #80B622;" class="as-icon as-icon-alert-fill"></i>
  </div>
  <div class="as-flag__content">
    <h4 class="as-body as-color--type-01">You are now connected</h4>
    <p class="as-body as-color--type-03">You have been added to the group “New Store on this region”</p>
  </div>
  <div class="as-flag__icon">
    <button class="as-flag__button">
      <i style="color: #1785FB;" class="as-icon as-icon-close"></i>
    </button>
  </div>
</div>
```

## With different sizes

You can use the `as-flag--l` modifier to get a flag with a `width` of `320px`.

```html
showSource: true
---
<div class="as-flag as-flag--l">
  <div class="as-flag__icon">
    <i style="color: #80B622;" class="as-icon as-icon-alert-fill"></i>
  </div>
  <div class="as-flag__content">
    <h4 class="as-body as-color--type-01">You are now connected</h4>
    <p class="as-body as-color--type-03">You have been added to the group “New Store on this region”</p>
  </div>
  <div class="as-flag__icon">
    <button class="as-flag__button">
      <i style="color: #1785FB;" class="as-icon as-icon-close"></i>
    </button>
  </div>
</div>
```

You can use the `as-flag--xl` modifier to get a flag with a `width` of `400px`.

```html
showSource: true
---
<div class="as-flag as-flag--xl">
  <div class="as-flag__icon">
    <i style="color: #80B622;" class="as-icon as-icon-alert-fill"></i>
  </div>
  <div class="as-flag__content">
    <h4 class="as-body as-color--type-01">You are now connected</h4>
    <p class="as-body as-color--type-03">You have been added to the group “New Store on this region”</p>
  </div>
  <div class="as-flag__icon">
    <button class="as-flag__button">
      <i style="color: #1785FB;" class="as-icon as-icon-close"></i>
    </button>
  </div>
</div>
```

You can use the `as-flag--l` modifier to get a flag with a `width` of `100%`.

```html
showSource: true
---
<div class="as-flag as-flag--block">
  <div class="as-flag__icon">
    <i style="color: #80B622;" class="as-icon as-icon-alert-fill"></i>
  </div>
  <div class="as-flag__content">
    <h4 class="as-body as-color--type-01">You are now connected</h4>
    <p class="as-body as-color--type-03">You have been added to the group “New Store on this region”</p>
  </div>
  <div class="as-flag__icon">
    <button class="as-flag__button">
      <i style="color: #1785FB;" class="as-icon as-icon-close"></i>
    </button>
  </div>
</div>
```

## CSS Variables

```
.as-flag {
  --as--flag--background-color
  --as--flag--button--color
}
```

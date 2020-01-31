## set html
this box is display picture with difference way. focus on class bootstrap display; `d-none` and `d-lg-none`.

```html
<div class="col-md-6 px-0 px-md-3">
    <div class="lift row no-gutters border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
        
      <div class="col-md-4 d-none d-lg-block">
          <img src="image.jpg" class="img-thumbnail m-3">
      </div>
        
      <div class="col-md-8 p-4 d-flex flex-column position-static pl-md-5">
        <h3 class="mb-2">
          <a href="#">
            <div class="d-lg-none ">
                <img src="image.jpg" style="width: 70px; height:auto;" class="float-right pr-0">
             </div>
            Lorem ipsum dolor
          </a>
        </h3>
        <p class="card-text mb-auto">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Impedit temporibus, aut aspernatur suscipit ipsam quidem quia, harum non recusandae eaque iste tempore quod neque velit aliquid, sit placeat corporis ducimus.</p>

        <div class="d-flex pt-3" style="font-size: 30px;">
        <a class="btn btn-success" href="#">Read More</a>
        <a class="btn btn-primary" href="#" title=""><i class="icon-link text-white"></i> Site</a>
        </div>
      </div>
    </div>
  </div>
```
## set css
this css include animate lift up box and shadow box.
```css
.lift {
  transition: box-shadow .25s ease, transform .25s ease;
}

.lift:focus,
.lift:hover {
  box-shadow: 0 1rem 2.5rem rgba(22, 28, 45, .1), 0 .5rem 1rem -.75rem rgba(22, 28, 45, .1)!important;
  transform: translate3d(0, -3px, 0)
}

.shadow-light {
  box-shadow: 0 .5rem 1.5rem rgba(22, 28, 45, .05)!important
}

.shadow-light-lg {
  box-shadow: 0 1.5rem 4rem rgba(39, 177, 23, 0.1) !important;
}

.shadow-dark {
  box-shadow: 0 .5rem 1.5rem rgba(22, 28, 45, .15)!important
}

.shadow-dark-lg {
  box-shadow: 0 1.5rem 4rem rgba(22, 28, 45, .15)!important
}

```

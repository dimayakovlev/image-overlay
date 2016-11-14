# image-overlay
Image Overlays are a great way to get the most out of the space your graphics take up on a web page. While one static graphic is better than none, adding an overlay provides more context to the content you'll find after clicking the image.

## Tutorial

For detailed instructions, view Solodev's [Adding an Overlay to your Graphics with CSS](https://www.solodev.com/blog/web-design/adding-an-overlay-to-your-graphics-with-css.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/j88rkudu/).

## HTML

The image overlay example contains the following basic HTML markup.

```
<section class="work-tiles">
   <div class="container">
      <div class="row">
         <div class="col-md-12">
            <h2>Lorem Ipsum Dolor</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. In eros nibh, interdum interdum rutrum eget, eleifend at libero.</p>
         </div>
         <div class="row">
            <ul>
               <li class="col-xs-6 col-md-4 work-tiles-items">
                  <img src="https://placeholdit.imgix.net/~text?txtsize=52&txt=Image&w=553&h=439" alt="Zeina">
                  <div class="text-overlay hidden-xs">
                     <span>Zeina</span>
                  </div>
               </li>
               <li class="col-xs-6 col-md-4 work-tiles-items">
                  <img src="https://placeholdit.imgix.net/~text?txtsize=52&txt=Image&w=553&h=439" alt="Logic +">
                  <div class="text-overlay hidden-xs">
                     <span>Logic +</span>
                  </div>
               </li>
               <li class="col-xs-6 col-md-4 work-tiles-items">
                  <img src="https://placeholdit.imgix.net/~text?txtsize=52&txt=Image&w=553&h=439" alt="SoftTech">
                  <div class="text-overlay hidden-xs">
                     <span>SoftTech</span>
                  </div>
               </li>
               <li class="col-xs-6 col-md-4 work-tiles-items">
                  <img src="https://placeholdit.imgix.net/~text?txtsize=52&txt=Image&w=553&h=439" alt="3Designs">
                  <div class="text-overlay hidden-xs">
                     <span>3Designs</span>
                  </div>
               </li>
               <li class="col-xs-6 col-md-4 work-tiles-items">
                  <img src="https://placeholdit.imgix.net/~text?txtsize=52&txt=Image&w=553&h=439" alt="DevTech">
                  <div class="text-overlay hidden-xs">
                     <span>DevTech</span>
                  </div>
               </li>
               <li class="col-xs-6 col-md-4 work-tiles-items">
                  <img src="https://placeholdit.imgix.net/~text?txtsize=52&txt=Image&w=553&h=439" alt="Chartz">
                  <div class="text-overlay hidden-xs">
                     <span>Chartz</span>
                  </div>
               </li>
            </ul>
         </div>
      </div>
   </div>
</section>

```

## CSS

All required CSS is in overlay.css

## External Includes

This tutorial contains the following third party resources.

```
<link rel="stylesheet" href="overlay.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>

```

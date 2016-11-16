# font-awesome-use
In this article [Solodev](https://www.solodev.com/) will cover using [Font Awesome](http://fontawesome.io/) with forms, button groups, as well as resizing icons and changing their colors. In our final example, Solodev will show you how to use Font Awesome to add a loading icon triggered by basic JavaScript.

## Tutorial

For detailed instructions, view Solodev's [Creative Ways to Use Font Awesome](https://www.solodev.com/blog/web-design/creative-ways-to-use-font-awesome.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/tumhumpy/).

## HTML

The Font Awesome examples contain the following HTML markup.

```
<div class="container font-awesome">
   <p>Using Font Awesome Icons for a Login Form</p>
   <div class="row">
      <div class="col-md-6">
         <div class="panel panel-default">
            <div class="panel-heading">
               <h3 class="panel-title">Login</h3>
            </div>
            <div class="panel-body">
               <div class="input-group">
                  <span class="input-group-addon" id="basic-addon1"><i class="fa fa-user" aria-hidden="true"></i>
                  </span>
                  <input type="text" class="form-control" placeholder="Username" aria-describedby="basic-addon1">
               </div>
               <div class="input-group">
                  <span class="input-group-addon" id="basic-addon2"><i class="fa fa-key" aria-hidden="true"></i>
                  </span>
                  <input type="text" class="form-control" placeholder="Password" aria-describedby="basic-addon2">
               </div>
            </div>
         </div>
      </div>
   </div>
   <hr>
   <p>Common Font Awesome Use Cases</p>
   <div class="input-group">
      <span class="input-group-addon" id="basic-addon2"><i class="fa fa-phone" aria-hidden="true"></i>
      </span>
      <input type="text" class="form-control" placeholder="Phone #" aria-describedby="basic-addon2">
   </div>
   <div class="input-group">
      <span class="input-group-addon"><i class="fa fa-usd" aria-hidden="true"></i>
      </span>
      <input type="text" class="form-control" placeholder ="00.00"aria-label="Amount (to the nearest dollar)">
      <span class="input-group-addon">.00</span>
   </div>
   <div class="input-group">
      <span class="input-group-addon" id="basic-addon3"><i class="fa fa-globe" aria-hidden="true"></i>
      </span>
      <input type="text" class="form-control" placeholder="https://www.domain.com"id="basic-url" aria-describedby="basic-addon3">
   </div>
   <hr>
   <p>Using Font Awesome Icons in a Button Group</p>
   <div class="btn-group btn-group-lg btn-group-justified" role="group" aria-label="Actions">
      <a class="btn btn-default dashboard-shortcut" ><span class="fa fa-list" aria-hidden="true">&nbsp;List</span></a>
      <a class="btn btn-default dashboard-shortcut" ><span class="fa fa-th" aria-hidden="true">&nbsp;Grid</span></a>
      <a class="btn btn-default dashboard-shortcut" ><span class="fa fa-calendar" aria-hidden="true">&nbsp;Calendar</span></a>
   </div>
   <br>
   <hr>
   <p>Resizing Font Awesome Icons</p>
   <i class="fa fa-facebook-square fa-large" aria-hidden="true"></i>
   <i class="fa fa-linkedin-square fa-2x" aria-hidden="true"></i>
   <i class="fa fa-twitter-square fa-3x" aria-hidden="true"></i>
   <i class="fa fa-google-plus-square fa-4x" aria-hidden="true"></i>
   <i class="fa fa-pinterest-square fa-5x" aria-hidden="true"></i>
   <hr>
   <p>Changing Font Awesome Icon Colors</p>
   <i class="fa fa-users red" aria-hidden="true"></i>
   <hr>
   <p>
      Animated Icons Attached to OnClick Events
   </p>
   <button class="btn btn-default has-spinner">
   <span class="spinner"><i class="fa fa-circle-o-notch fa-spin"></i></span>
   Get Started
   </button>
   <hr>
</div>

```

## CSS

All required CSS is in index.css

## JavaScript

This tutorial utilizes the following JavaScript.

```
$( document ).ready(function() {
$(function(){
    $('.has-spinner').click(function() {
        $(this).toggleClass('active');
    });
});
});
```

## External Includes

This tutorial contains the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
<link href="index.css" rel="stylesheet">

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```

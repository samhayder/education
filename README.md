# Education: https://samhayder-education.netlify.app/

> Website HTML Template

## Template Info

### Author

### Version

0.1.0

## Credit Resources (jQuery Plugin)

#### Counter UP by About Section: https://github.com/bfintal/Counter-Up

```bash
js:
<script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
<script src="https://code.jquery.com/jquery-migrate-3.0.0.min.js"></script>
<!-- Counter UP JS -->
<script src="http://cdnjs.cloudflare.com/ajax/libs/waypoints/2.0.3/waypoints.min.js"></script>
<script src="./resource/js/jquery.counterup.min.js"></script>

>> mainJquery.js
$('.counter').counterUp({
    delay: 10,
    time: 3000,
});
```

#### Magnific Popup by Menu Item img gallery show: https://dimsemenov.com/plugins/magnific-popup/

```bash
css: <link rel="stylesheet" href="./resources/css/magnific-popup.css">
js: <script src="./resources/js/jquery.magnific-popup-v1-1.min.js"></script>

>> app.js
$(".parent-container").magnificPopup({
    delegate: "a",
    type: "image",
    gallery: {
      enabled: true,
    },
});
```

## Documentation:

#### Reviews section Bootstrap Carousel

```bash
>> index.html
<div id="slider" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item">
      <!-- ... -->
    </div> <!-- end carousel single item -->
  </div> <!-- end carousel inner -->

  <a href="#slider" class="carousel-control-prev" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </a> <!-- end carousel control previous -->
  <a href="#slider" class="carousel-control-next" role="button" data-slide="next">
    <span class="carousel-control-next-icon"></span>
  </a> <!-- end carousel control next -->

</div> <!-- end of main carousel div -->

```

#### Contact section embed google map

```bash
>> index.html
<div class="embed-responsive embed-responsive-21by9">
  <iframe
    class="embed-responsive-item"
    src="//google map location link//"
    width="100%"
    frameborder="0"
    style="border: 0;"
    allowfullscreen=""
    aria-hidden="false"
    tabindex="0"
  ></iframe>
</div>

```

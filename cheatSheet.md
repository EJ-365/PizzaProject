CheatSheet for Bootstrap

<!-- Center an image using mx-auto -->
<img src="image.jpg" class="mx-auto d-block">

<!-- Center using text-center on parent -->
<div class="text-center">
  <img src="image.jpg">
</div>

<!-- Basic text centering -->
<p class="text-center">Centered text</p>

<!-- Center text vertically in a container -->
<div class="h-100 d-flex align-items-center">
  <p>Vertically centered text</p>
</div>

<!-- Center everything both vertically and horizontally -->
<div class="min-vh-100 d-flex justify-content-center align-items-center">
  <div class="text-center">
    <h1>Welcome to InstantPizza</h1>
    <p>Your favorite pizzas delivered fast</p>
    <button class="btn btn-primary">Order Now</button>
  </div>
</div>

<!-- Perfect center using flexbox -->
<div class="d-flex justify-content-center align-items-center">
  <div>Content goes here</div>
</div>

text-center: Centers text content
mx-auto: Centers block elements horizontally
d-flex: Creates a flex container
justify-content-center: Centers items horizontally in flex container
align-items-center: Centers items vertically in flex container
min-vh-100: Makes container minimum 100% of viewport height
d-block: Makes element a block-level element

how how add image background: style="background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('Photos/pizza-salami-picjumbo-com.jpg') center/cover no-repeat fixed;">

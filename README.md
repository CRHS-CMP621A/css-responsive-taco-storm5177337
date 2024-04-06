# CSS Responsive Taco

## Steps

1. Setup the initial layout.

    a. Top (grid-areas)

![Markdown](assets/taco_grid_top.png)

    b. Menu (grid RAM)

![Markdown](assets/taco_grid_options.png)

c. Features (grid RAM)

![Markdown](assets/taco_features.png)

d. About (grid with column of 400px and 1fr)

![Markdown](assets/taco_info_big.png)

e. Gallery (grid RAM)

![Markdown](assets/taco_gallery_big.png)

f. Gallery h2 (set grid columns to go across entire top row)

```css
.gallery h2 {
  /* use grid columns to places insta grams across top of gallery */
```

2. Add Media Query at 700px.
   a. Top layout (grid areas)

   ![Markdown](assets/taco_top_medium.png)

b. About (grid only 1 column at 1fr )

![Markdown](assets/taco_info_medium.png)

3. Add media query at 500px.
   a. Top layout (grid areas)

   ![Markdown](assets/taco_top_small.png)

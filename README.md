# CSS Responsive Design – Media Queries

A simple responsive webpage created using HTML and CSS to understand how layouts adapt to different screen sizes.

## Features

- Three content boxes arranged horizontally on larger screens.
- Vertical stacking on smaller screens.
- Responsive width and height adjustments.
- Text colour changes based on screen size.
- Flexbox layout for alignment and positioning.

## Technologies Used

- HTML5
- CSS3
- CSS Flexbox
- CSS Media Queries

## What I Learned

- Understanding responsive web design.
- Using `@media` rules to apply styles at different screen widths.
- Working with `max-width` breakpoints.
- Changing flex direction based on screen size.
- Adjusting element dimensions for mobile devices.

## Media Query Example

```css
@media (max-width: 676px) {
    .container {
        flex-direction: column;
        align-items: center;
    }

    .child1, .child2, .child3 {
        width: 90%;
        height: 30%;
    }
}
```


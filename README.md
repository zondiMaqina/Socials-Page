# Socials-Page
A simple webpage displaying social links using html and css

## Challenges
1. how to remove underline on anchor element
2. how to make image height same ratio as width without setting fixed diemnsion
3. how to add font using font file
4. How to make text size responsive to screen width

## Solutions

1. One of the ways is to include this property -> ```text-decoration: none;```, which removes every text decoration from text.

2. You combine the following properties

```
// To avoid setting fixed width you use the "max-inline-size: 100%;", as it will allow image to shrink and grow back to its original size

// To make height same dimension as width no matter the shrinkage  "aspect-ratio: 1 / 1"
```

3. you apply this entire code at the entrance of css file

```
@font-face {
    font-family: 'CustomName';
    src: url(path/to/font/file);
}

// then apoply to the element thats needed
```

4. use the `clamp(min, pre, max)` function to determine resolution of font on each screen size

## Technologies Used

- HTML5
- CSS (Flexbox)
- git

<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity.
</AlertInfo>

# Theme Slider

The theme slider is a navigation bar for special offers and topics that should be displayed prominently to the user with pictures.

All offers are listed horizontally next to each other. Sliding of offers is a characteristic feature of this components.

---

## Overall styling

- The title has the text-style of **basic-bold**.
- The subheadline comes in the text-style **small**.
- The line-height is **120%**.
- Height and width of the component is **divisible by 8**.
- The image ratio is always **4:3**.
- There is **no hover or active state**.

### Item

- An item is a single navigation element in the theme-slider that is shown with an image and text.

| Types | Attributes | Preview |
|---|---|---|
| Default | font-color: gray-darker <br> background-color: gray-lightest | ![default](assets/themeslider/item@1x.png) |

---

## Spacing & Measurements

- The total height and width of the component is based on the size of the individual elements and their corresponding spacings.
- The width also depends on how many elements are displayed and is always a multiple of 8.
- The padding and gutter **always is 8px**.

| Breakpoints | Attributes | Preview |
|---|---|---|
| SM | height: 160px <br> width: 584px | ![complete: SM](assets/measurements/SM@1x.png) |
| XS | height: 342px <br> width: 304px |  ![complete: XS](assets/measurements/XS@1x.png) |

### Desktop (SM)

| Type | Attributes | Preview |
|---|---|---|
| Height | image: 105px <br> text: 55px<br>complete: 160px | ![height: SM](assets/measurements/SM/height@1x.png) |
| Width | 140px | ![width: SM](assets/measurements/SM/width@1x.png) |
| Spacing | padding: 8px <br> margin: 2px | ![horizontal: SM](assets/measurements/SM/horizontal-vertical@1x.png) |

### Smartphone (XS)

| Type | Attributes | Preview |
|---|---|---|
| Height | image: 112px<br>text: 55px<br>complete: 167px | ![height: XS](assets/measurements/XS/heigth@1x.png) |
| Width | 148px | ![width: XS](assets/measurements/XS/width@1x.png) |
| Spacing | padding: 8px <br> margin: 2px | ![horizontal: XS](assets/measurements/XS/horizontal-vertical@1x.png) |

---

## Our workflow in Sketch

- Use the "Overrides"-function to customize the theme slider in the two possible variants or to change the titles or sub-headlines.
- To delete a not needed tile use the "Overrides"-function. Delete always from back to front to avoid gaps in the component.

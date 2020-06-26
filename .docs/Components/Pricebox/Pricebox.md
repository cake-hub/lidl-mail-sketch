<AlertWarning alertHeadline="Not modifiable">
 It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Pricebox

The use of the consistent Lidl pricebox is an elementary part of our brand awareness.

The pricebox contains several fix and optional elements and is available in different color combinations due to different visualizations (standard, offer, etc.).

---

## Elements

| Types | Attributes | Preview |
|---|---|---|
| Basic | 1. Prefix <br> 2. Price <br> 3. Asterik <br> 4. Currency |![basic pricebox](assets/elements/standard@1x.png)|
| Basic quantity | 5. Basic quantity |![basic quantity pricebox](assets/elements/basic-quantity@1x.png)|
| Offer | 6. Offer <br> 7. Basic pricebox |![offer pricebox](assets/elements/offer@1x.png)|
| Discount | 8. Discount text <br> 9. Recommended Retail Price (rrp) |![discount pricebox](assets/elements/discount@1x.png)|

---

## Overall styling

- The text-style is **price**.
- The text-style for the addons is **small-bold** for asterisk, currency & prefix.
- Additionally you can choose between a pricebox with or without prefix.

| Types | Attributes | Preview |
|---|---|---|
| Standard | text-color: gray-darker <br> background-color: basic-white <br> outline-color: gray-light |![basic pricebox](assets/box/standard/basic@1x.png) ![no-prefix pricebox](assets/box/standard/no-prefix@1x.png) ![with-prefix pricebox](assets/box/standard/with-prefix@1x.png)|
| Offer | text-color: basic-white <br> background-color: danger-base |![basic pricebox](assets/box/offer/basic@1x.png) ![no-prefix pricebox](assets/box/offer/no-prefix@1x.png) ![with-prefix pricebox](assets/box/offer/with-prefix@1x.png)|

---

## Label

- Combine the pricebox with a label to display promotions or discounts.
- You can advertise discounts, promotions or offers.
- Like the pricebox, you can choose between different label colors.
- The text-style always is **small bold**.
- Always use the **base-color** as background-color.

| Types | Attributes | Preview |
|---|---|---|
| Action | text-color: basic-white <br> background-color: danger-base | ![action label](assets/label/action@1x.png) |
| Info | text-color: basic-white <br> background-color: brand-primary-base | ![info label](assets/label/info@1x.png) |
| Offer | text-color: gray-darker <br> background-color: mark-base | ![offer label](assets/label/offer@1x.png) |

---

## Basic quantity

- It's used as additional info for the packaging unit, quantity or drained weight.
- The text-style always is **small**.
- The line-height is **120%**.

| Types | Attributes | Preview |
|---|---|---|
| Basic quantity | text-color: gray-darker | ![basic quantity](assets/basic-quantity@1x.png) |

---

## Discount

- If you want to use a discount, it can be placed in the pricebox **standard** (positive) as well as in the pricebox **offer** (negative) - with or without prefix.
- There is a positive and negative version matching the underlying standard pricebox.
- The text-style always is **small** for the discount text and the recommended retail pice (rrp).
- The strike comes either in **danger-base** or **gray-darker** with a **1px thickness**.

| Types | Attributes | Preview |
|---|---|---|
| Positive | text-color: gray-darker <br> strike-color: gray-darker | ![discount positive](assets/strike-price-dark@1x.png) |
| Negative | text-color: basic-white <br> strike-color: basic-white | ![disocunt negative](assets/strike-price-light@1x.png) |

---

## Spacing & Measurements

- The height of the pricebox depends on the content and the additional components shown.
- The width of the pricebox depends on the content.
- The width of the label denpends width of the pricebox.
- The height of the label is fixed for one or two rows

### Pricebox

| Types | Attributes | Preview |
|---|---|---|
| Vertical spacing | 8px / 4px | ![pricebox vertical spacing](assets/measurements/vertical@1x.png) |
| Horizontal spacing | 8px | ![pricebox horizontal spacing](assets/measurements/horizontal@1x.png) |

### Label

| Types | Attributes | Preview |
|---|---|---|
| Padding | 8px  | ![label vertical spacing](assets/measurements/padding-label@1x.png) |
| Height | 1 row: 24px <br>2 rows: 40px | ![label height](assets/measurements/height-1-label@1x.png) ![label height](assets/measurements/height-2-label@1x.png)   |

---

## Position

### Basic quantity

- This information always is placed to the **right below the pricebox**.

| Types | Attributes | Preview |
|---|---|---|
| Basic quantity | text and pricebox align right <br> margin-top: 2px | ![special offer](assets/measurements/basic-quantity@1x.png) |

---

## Combinations

- There are **only four different combinations** of priceboxes and labels in the Lidl universe.
- They are called "themes".

| Types | Attributes | Preview |
|---|---|---|
| Offer #1 | label: action <br> pricebox: standard | ![offer #1](assets/themes/offer-1@1x.png) |
| Offer #2 | label: offer <br> pricebox: standard | ![offer #2](assets/themes/offer-2@1x.png) |
| Special offer | label: offer <br> pricebox: action | ![special offer](assets/themes/special-offer@1x.png) |
| Info | Label: info <br> pricebox: standard | ![info offer](assets/themes/info@1x.png) |

---

## Our workflow in Sketch

- Use the "Overrides"-function to change the text.
- Enter the text first. Then adjust the width of the symbol.
- The color variants of the label can be selected in the complete pricebox via the "Overrides"-function.

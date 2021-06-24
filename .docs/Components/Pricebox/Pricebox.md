<AlertWarning alertHeadline="Not modifiable">
 It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Pricebox

The use of the consistent LIDL pricebox is an elementary part of our brand awareness.

The pricebox contains several obligatory and optional elements and is available in different color combinations due to different visualizations (basic, offer, etc.).

---

## Recommendations

- If there is already a currency symbol in the pricebox no additional currency sign should be displayed in the recommended retail price or label.

---

## Elements

| Types | Attributes | Preview |
|---|---|---|
| Basic | 1. Prefix <br> 2. Price <br> 3. Asterisk <br> 4. Currency |![basic pricebox](assets/elements/standard@1x.png)|
| Offer | 5. Offer <br> 6. Basic pricebox |![offer pricebox](assets/elements/offer@1x.png)|
| Discount | 7. Discount text <br> 8. Recommended Retail Price (rrp) |![discount pricebox](assets/elements/discount@1x.png)|

---

## Overall styling

- The text-style is [pricebox-price](../../General/Typography/Typography.md#pricebox-price) for the price.
- The text-style is [pricebox-addon](../../General/Typography/Typography.md#pricebox-addon) for asterisk, currency & prefix.
- The line-height is set to **default**.
- Additionally you can choose between a pricebox with or without prefix.

| Types | Attributes | Preview |
|---|---|---|
| Basic | text-color: basic-black <br> background-color: basic-white <br> outline-color: gray-light |![basic pricebox](assets/box/standard/basic@1x.png) ![no-prefix pricebox](assets/box/standard/no-prefix@1x.png) ![with-prefix pricebox](assets/box/standard/with-prefix@1x.png)|
| Action | text-color: basic-white <br> background-color: danger-base |![basic pricebox](assets/box/offer/basic@1x.png) ![no-prefix pricebox](assets/box/offer/no-prefix@1x.png) ![with-prefix pricebox](assets/box/offer/with-prefix@1x.png)|

---

## Label

- The text-style always is [pricebox-label](../../General/Typography/Typography.md#pricebox-label).
- The line-height is set to **default**.
- Always use the **base-color** as background-color.
- Combine the standard pricebox with a label to display promotions or discounts.
- Use the label as an add-on for the **offer** pricebox.
- You can advertise discounts, promotions or offers.
- Like the pricebox, you can choose between different label colors.

| Types | Attributes | Preview |
|---|---|---|
| Action | text-color: basic-white <br> background-color: danger-base | ![action label](assets/label/action@1x.png)|
| Offer | text-color: basic-black <br> background-color: mark-base | ![offer label](assets/label/offer@1x.png) |

---

## Basic quantity

- The text-style is always [basic-quantity](../../General/Typography/Typography.md#pricebox-basic-quantity).
- The line-height is set to **default**.
- It's used as additional info for the packaging unit, quantity or drained weight.

| Types | Attributes | Preview |
|---|---|---|
| Basic quantity | text-color: basic-black | ![basic quantity](assets/basic-quantity@1x.png) |

---

## Discount

- The text-style always is [pricebox-addon](../../General/Typography/Typography.md#pricebox-addon) for the discount text and the recommended retail price (rrp).
- The line-height is set to **default**.
- If you want to use a discount, it can be placed in the pricebox **standard** (positive) as well as in the pricebox **offer** (negative) - with or without prefix.
- The strike comes either in **basic-black** or **basic-white**.
- There is a positive and negative version matching the underlying standard pricebox.

| Types | Attributes | Preview |
|---|---|---|
| Positive | text-color: basic-black <br> strike-color: basic-black | ![discount positive](assets/strike-price-dark@1x.png) |
| Negative | text-color: basic-white <br> strike-color: basic-white | ![disocunt negative](assets/strike-price-light@1x.png) |

---

## Spacing & Measurements

- The height of the pricebox depends on the content and the additional components shown.
- The width of the pricebox depends on the content.
- The width of the label depends on the content of the pricebox.
- The height of the label is fixed for a single-line text.

### Pricebox

| Types | Attributes | Preview |
|---|---|---|
| Vertical spacing | SM: 6px/5px <br> XS: 4px / 3px | ![pricebox horizontal spacing SM](assets/measurements/vertical-SM@1x.png) ![pricebox horizontal spacing XS](assets/measurements/vertical-XS@1x.png) |
| Horizontal spacing | SM: 8px / 4px <br> XS: 4px / 4px | ![pricebox vertical spacing SM](assets/measurements/horizontal-SM@1x.png) ![pricebox vertical spacing XS](assets/measurements/horizontal-XS@1x.png) |

### Label

| Types | Attributes | Preview |
|---|---|---|
| Vertical spacing | SM: 4px <br> XS: 4px | ![label vertical spacing SM](assets/measurements/label-vertical-SM@1x.png) ![label vertical spacing XS](assets/measurements/label-vertical-XS@1x.png) |
| Horizontal spacing | SM: 8px <br> XS: 4px | ![label horizontal spacing SM](assets/measurements/label-horizontal-SM@1x.png) ![label horizontal spacing XS](assets/measurements/label-horizontal-XS@1x.png) |
| Height | SM: 24px <br> XS: 22px | ![label height SM](assets/measurements/label-height-SM@1x.png) ![label height XS](assets/measurements/label-height-XS@1x.png) |

---

### Discount

| Types | Attributes | Preview |
|---|---|---|
| Discount | SM: 6px / 2px<br> XS: 3px / 1px | ![discount SM](assets/measurements/strike-price-SM@1x.png) ![discount XS](assets/measurements/strike-price-XS@1x.png) |

## Position

### Basic quantity

- This information always is placed to the **right below the pricebox**.

| Types | Attributes | Preview |
|---|---|---|
| Basic quantity | text and pricebox align right <br> margin-top: 2px | ![special offer](assets/measurements/basic-quantity@1x.png) |

---

## Combinations

- There are **only three different combinations** of priceboxes and labels in the LIDL universe.

| Types | Attributes | Preview |
|---|---|---|
| Offer #1 | label: action <br> pricebox: basic | ![offer #1](assets/complete/offer-1@1x.png) |
| Offer #2 | label: offer <br> pricebox: basic | ![offer #2](assets/complete/offer-2@1x.png) |
| Special offer | label: offer <br> pricebox: action | ![special offer](assets/complete/special-offer@1x.png) |

---

## Our workflow in Sketch

- Use the "Overrides"-function to change the text.
- Enter the text first. Then adjust the width of the symbol.
- The color variants of the label can be selected in the complete pricebox via the "Overrides"-function.

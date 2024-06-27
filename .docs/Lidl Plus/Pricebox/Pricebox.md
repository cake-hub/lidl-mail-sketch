<AlertWarning alertHeadline="Not modifiable">
 This component is deprecated and will not supported anymore. The new version is so far only in <a href="/Lidl/Web/Design/Lidl_Plus/Pricebox/Pricebox.md"> Web</a> available.
</AlertWarning>

# Pricebox

Use this component **only to promote a special LIDL Plus price** to the customer.

> Usage of the LIDL Plus price **must be coordinated with and permitted by the legal department of your LIDL country**.

---

## Elements

| Attributes | Preview |
|---|---|
| 1. LIDL Plus pricebox <br> 2. LIDL Plus label <br> 3. Recommended retail price (rrp) <br> 4. Legal info ("Lidl Plus price") <br> 5. Basic quantity |![LIDL Plus: pricebox](assets/variants/pricebox@1x.png)|

---

## Overall styling

### Pricebox

- The text-style is [pricebox-price](../../General/Typography/Typography.md#pricebox-price) for the price.
- The text-style is [pricebox-addon](../../General/Typography/Typography.md#pricebox-addon) for asterisk, currency & prefix.
- The text-color is **basic-black**.
- The background-color is **mark-base**.
- The line-height is set to **default**.
- For each breakpoint, you can select a corresponding symbol to suit your layout.
- Additionally you can choose between a pricebox: **basic**, **no-prefix** or **with-prefix**.

| Types | Attributes | Preview |
|---|---|---|
| Basic | No prefix <br> No currency | ![LIDL plus pricebox: no prefix](assets/styling/basic@1x.png)|
| No prefix | No prefix <br> With currency | ![LIDL plus pricebox: no prefix](assets/styling/no-prefix@1x.png)|
| With prefix | With prefix <br> With currency |![LIDL plus pricebox: with prefix](assets/styling/with-prefix@1x.png)|


### Label

- The text-style is always [pricebox-label](../../General/Typography/Typography.md#pricebox-label).
- The line-height is set to **default**.
- The label is a required addon for the complete **LIDL Plus price**.

| Attributes | Preview |
|---|---|
| text-color: basic-white <br> background-color: info-base | ![LIDL Plus label ](assets/styling/label@1x.png) |


### Legal info

- The text-style is [pricebox-basic-quantity](../../General/Typography/Typography.md#pricebox-basic-quantity).
- This element follows the styling of our [positive link version](../../General/Link/Link.md#positive-version).
- Tapping on this info guides the user directly to the legal info implemented at the bottom of a newsletter via jump mark.

> The legal info is a required addon for the complete **LIDL Plus price** and has a fix notation of "Lidl Plus price".

| Attributes | Preview |
|---|---|
| text-color: info-base | ![legal info: LG](assets/styling/legal@1x.png) |

### Basic quantity

- The text-style is always [pricebox-basic-quantity](../../General/Typography/Typography.md#pricebox-basic-quantity).
- The line-height is set to **default**.
- It's used as additional info for the packaging unit, quantity or drained weight.

| Attributes | Preview |
|---|---|
| text-color: basic-black | ![basic quantity](assets/styling/basic-quantity@1x.png) |

### Discount

- The text-style is always [pricebox-addon](../../General/Typography/Typography.md#pricebox-addon) for the recommended retail price (rrp).
- The line-height is set to **default**.
- The positive discount is a required addon for the complete **LIDL Plus price**.

| Attributes | Preview |
|---|---|
| text- & strike-color: basic-black | ![discount positive](assets/styling/discount@1x.png) |

---

## Spacing & measurements

- The width of the pricebox depends on the content.
- The width of the label depends on the content of the pricebox.
- The height of the label is fixed for a single-line text.

### Pricebox

| Types | Attributes | Preview |
|---|---|---|
| Vertical spacing | SM: 6px / 5px <br> XS: 4px / 3px | ![pricebox horizontal spacing SM](assets/measurements/vertical-SM@1x.png) ![pricebox horizontal spacing XS](assets/measurements/vertical-XS@1x.png) |
| Horizontal spacing | SM: 8px / 4px <br> XS: 4px / 4px | ![pricebox vertical spacing SM](assets/measurements/horizontal-SM@1x.png) ![pricebox vertical spacing XS](assets/measurements/horizontal-XS@1x.png) |

### Label

- The width of the label depends on the content of the pricebox.
- The height of the label is fixed for a single-line text.

| Types | Attributes | Preview |
|---|---|---|
| Vertical spacing | SM: 4px <br> XS: 4px | ![label vertical spacing SM](assets/measurements/label-vertical-SM@1x.png) ![label vertical spacing XS](assets/measurements/label-vertical-XS@1x.png) |
| Horizontal spacing | SM: 8px <br> XS: 4px | ![label horizontal spacing SM](assets/measurements/label-horizontal-SM@1x.png) ![label horizontal spacing XS](assets/measurements/label-horizontal-XS@1x.png) |
| Height | SM: 24px <br> XS: 22px | ![label height SM](assets/measurements/label-height-SM@1x.png) ![label height XS](assets/measurements/label-height-XS@1x.png) |

### Discount

| Types | Attributes | Preview |
|---|---|---|
| Discount | SM: 6px / 2px<br> XS: 3px / 1px | ![discount SM](assets/measurements/rrp-SM@1x.png) ![discount XS](assets/measurements/rrp-XS@1x.png) |

### Legal info & basic quantity

| Types | Attributes | Preview |
|---|---|---|
| Legal info | text and pricebox align right <br> margin-top: 2px | ![legal info: LG](assets/position/legal-info@1x.png) |
| Basic quantity | text and pricebox align right <br> margin-top: 0px | ![special offer](assets/position/basic-quantity@1x.png) |

---

## Position & combinations

> Use it only in combination with a **product tile, teaser or image**.

- The pricebox is placed in the **lower right corner**.
- The distance of the price to the borders of the product tile is **8px** each.

![position](assets/position/pricebox@1x.png)

*This is a non-obligatory example.*

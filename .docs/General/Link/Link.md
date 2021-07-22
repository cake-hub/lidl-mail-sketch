<AlertWarning alertHeadline="Not modifiable">
It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Links

A link is a reference for the user that can lead directly to an external or internal destination by clicking or tapping on it.

---

## Overall styling

- The text style depends on the body text and is either [small](../../General/Typography/Typography.md#small), [small bold](../../General/Typography/Typography.md#small-bold), [basic](../../General/Typography/Typography.md#basic), [basic bold](../../General/Typography/Typography.md#basic-bold), [large](../../General/Typography/Typography.md#large) or [large bold](../../General/Typography/Typography.md#large-bold).
- The appearance of the state depends on the usage or context.
- There’s also a positive and negative version to layout on a light or dark background.
- The icon can only be placed **before**, **not after** the link.
- Icons are always displayed like in the font color.

---

## Positive version

- Use the positive version if you want to display a link on a light background.
- Always make sure you have enough contrast when choosing the background.

| State | Attributes | Preview |
|---|---|---|
| Default / visited | text-color: brand-primary-base<br>text-decoration: underline | ![positive: default/visited](assets/positive/basic@1x.png) |

---

## Negative version

- Use the negative version if you want to display a link on a dark background.
- Always make sure you have enough contrast when choosing the background.

| State | Attributes | Preview |
|---|---|---|
| Default / visited | text-color: basic-white<br>text-decoration: underline | ![negative: default/visited](assets/negative/basic@1x.png) |

---

## Text styles

| Text style | Font size | Preview |
|---|---|---|
| Small | 12px | ![small](assets/positive/small@1x.png) |
| Small bold | 12px | ![small](assets/positive/small-bold@1x.png) |
| Basic | 14px | ![basic](assets/positive/basic@1x.png) |
| Basic bold | 14px | ![basic](assets/positive/basic-bold@1x.png) |
| Large | 16px | ![large](assets/positive/large@1x.png) |
| Large bold | 16px | ![large](assets/positive/large-bold@1x.png) |

---

## Spacing & measurements

| Type | Attributes | Preview |
|---|---|---|
| Vertical spacing | 8px between icon and label | ![spacing: small](assets/vertical/small@1x.png)<br>![spacing: basic](assets/vertical/basic@1x.png)<br>![spacing: large](assets/vertical/large@1x.png) |
| Icon size | small: 16x16px<br>basic: 24x24px<br>large: 32x32px | ![icon: small](assets/icon-size/small@1x.png)<br>![icon: basic](assets/icon-size/basic@1x.png)<br>![icon: large](assets/icon-size/large@1x.png)  |

---

### Our workflow in Sketch

- Take one of the text styles for the different font sizes to display a linked text.
- Then the text style is  manually adjusted to the status.
- Detach the text style if you want to show a link in a copy-text.

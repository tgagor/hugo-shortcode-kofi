---
title: Check out demo of all the Ko-fi shortcodes
date: 2024-03-08
authors:
  - tgagor
---

## Demos

### Animated buttons

Those look nice and have animated mugs, but I saw them being blocked by uBlock Origin.

| Animated button                     | Shortcode                                                                    |
| ----------------------------------- | ---------------------------------------------------------------------------- |
| {{< kofi/button >}}                 | `{{</* kofi/button */>}}` or <br/> `{{</* kofi/button color="#13C3FF" */>}}` |
| {{< kofi/button color="#FF5E5B" >}} | `{{</* kofi/button color="#FF5E5B" */>}}`                                    |
| {{< kofi/button color="#434b57" >}} | `{{</* kofi/button color="#434b57" */>}}`                                    |


### Static images

| Image style 1                     | Shortcode                                                                 |
| --------------------------------- | ------------------------------------------------------------------------- |
| {{< kofi/image1 >}}               | `{{</* kofi/image1 */>}}` or <br/> `{{</* kofi/image1 style="blue" */>}}` |
| {{< kofi/image1 style="grey" >}}  | `{{</* kofi/image1 style="grey" */>}}`                                    |
| {{< kofi/image1 style="red" >}}   | `{{</* kofi/image1 style="red" */>}}`                                     |
| {{< kofi/image1 style="green" >}} | `{{</* kofi/image1 style="green" */>}}`                                   |
| {{< kofi/image1 style="dark" >}}  | `{{</* kofi/image1 style="dark" */>}}`                                    |

| Image style 2                      | Shortcode                                                                 |
| ---------------------------------- | ------------------------------------------------------------------------- |
| {{< kofi/image2 >}}                | `{{</* kofi/image2 */>}}` or <br/> `{{</* kofi/image2 style="blue" */>}}` |
| {{< kofi/image2 style="red" >}}    | `{{</* kofi/image2 style="red" */>}}`                                     |
| {{< kofi/image2 style="stroke" >}} | `{{</* kofi/image2 style="stroke" */>}}`                                  |
| {{< kofi/image2 style="dark" >}}   | `{{</* kofi/image2 style="dark" */>}}`                                    |

### Logotypes

| Logos                           | Shortcode                                                             |
| ------------------------------- | --------------------------------------------------------------------- |
| {{< kofi/logo style="logo" >}}  | `{{</* kofi/logo */>}}` or <br/> `{{</* kofi/logo style="logo" */>}}` |
| {{< kofi/logo style="mug" >}}   | `{{</* kofi/logo style="mug" */>}}`                                   |
| {{< kofi/logo style="pixel" >}} | `{{</* kofi/logo style="pixel" */>}}`                                 |

### Badges

| Badges                            | Shortcode                                                              |
| --------------------------------- | ---------------------------------------------------------------------- |
| {{< kofi/badge style=white >}}    | `{{</* kofi/badge */>}}` or <br/> `{{</* kofi/badge style=white */>}}` |
| {{< kofi/badge style=dark >}}     | `{{</* kofi/badge style=dark */>}}`                                    |
| {{< kofi/badge style=bg-white >}} | `{{</* kofi/badge style=bg-white */>}}`                                |
| {{< kofi/badge style=bg-dark >}}  | `{{</* kofi/badge style=bg-dark */>}}`                                 |

### Dynamic widgets

| Widgets                      | Shortcode                          |
| ---------------------------- | ---------------------------------- |
| {{< kofi/floating-button >}} check left-bottom corner | `{{</* kofi/floating-button */>}}` |
| {{< kofi/donation-panel >}}  | `{{</* kofi/donation-panel */>}}`  |

### Custom images

You can also use your custom images:
```go
{{</* kofi/custom height=200 url="https://media.giphy.com/media/kgKFcQk6oa1WIdHNSl/giphy.gif" */>}}
```

{{< kofi/custom height=200 url="https://media.giphy.com/media/kgKFcQk6oa1WIdHNSl/giphy.gif" >}}

For inspiration check here:
* https://more.ko-fi.com/brand-assets
* https://giphy.com/Kofi_button

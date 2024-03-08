# Hugo shortcodes for Ko-fi

This is a set of shortcodes to allow easy integration with [Ko-fi](https://ko-fi.com/).

[Live demo on my blog](https://gagor.pro//2024/03/kofi-shortcodes-for-hugo/).

# Installation

1. Clone hugo-shortcode-kofi repo to your project:

- as submodule (recommended)
    ```bash
    cd your-site-location

    git submodule add --depth=1 https://github.com/tgagor/hugo-shortcode-kofi.git themes/hugo-shortcode-kofi
    ```

    You might need to initialize any uninitialized submodules in the repository and then recursively update all submodules to their latest versions to make it fully available:

    ```bash
    git submodule update --init --recursive
    ```
- or by just cloning
    ```bash
    cd your-site-location

    git clone --depth=1 https://github.com/tgagor/hugo-shortcode-kofi.git themes/hugo-shortcode-kofi
    ```

3. Update blog config:

```yaml
theme:
  - YourThemeOfChoice
  - hugo-shortcode-kofi
```

Original theme should be first, followed up by extension.

If you're unable to get it working, check [`exampleSite`](./exampleSite/) directory.

# List of shortcodes

| Animated button                                                              |
| ---------------------------------------------------------------------------- |
| `{{< kofi/button >}}` or <br/> `{{< kofi/button color="#13C3FF" >}}` |
| `{{< kofi/button color="#FF5E5B" >}}`                                    |
| `{{< kofi/button color="#434b57" >}}`                                    |

| Image style 1                                                             |
| ------------------------------------------------------------------------- |
| `{{< kofi/image1 >}}` or <br/> `{{< kofi/image1 style="blue" >}}` |
| `{{< kofi/image1 style="grey" >}}`                                    |
| `{{< kofi/image1 style="red" >}}`                                     |
| `{{< kofi/image1 style="green" >}}`                                   |
| `{{< kofi/image1 style="dark" >}}`                                    |

| Image style 2                                                             |
| ------------------------------------------------------------------------- |
| `{{< kofi/image2 >}}` or <br/> `{{< kofi/image2 style="blue" >}}` |
| `{{< kofi/image2 style="red" >}}`                                     |
| `{{< kofi/image2 style="stroke" >}}`                                  |
| `{{< kofi/image2 style="dark" >}}`                                    |

### Logotypes

| Logos                                                                 |
| --------------------------------------------------------------------- |
| `{{< kofi/logo >}}` or <br/> `{{< kofi/logo style="logo" >}}` |
| `{{< kofi/logo style="mug" >}}`                                   |
| `{{< kofi/logo style="pixel" >}}`                                 |

### Badges

| Badges                                                                 |
| ---------------------------------------------------------------------- |
| `{{< kofi/badge >}}` or <br/> `{{< kofi/badge style=white >}}` |
| `{{< kofi/badge style=dark >}}`                                    |
| `{{< kofi/badge style=bg-white >}}`                                |
| `{{< kofi/badge style=bg-dark >}}`                                 |

### Dynamic widgets

| Widgets                            |
| ---------------------------------- |
| `{{< kofi/floating-button >}}` |
| `{{< kofi/donation-panel >}}`  |

### Custom images

| Custom images                                                                                         |
| ----------------------------------------------------------------------------------------------------- |
| `{{< kofi/custom height=200 url="https://media.giphy.com/media/kgKFcQk6oa1WIdHNSl/giphy.gif" >}}` |
|                                                                                                       |

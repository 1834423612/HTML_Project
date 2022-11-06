# <center><span style="color: red;">Introduction About HTML Labels</span><center>
----

`<!DOCTYPE html>` <span style="color: #37a1f6; font-weight: bold;">This is define the document type to HTML.</span>

`<html>` <span style="color: #37a1f6; font-weight: bold;">This regular label, if the website language is not English, you can write such as:</span>  <font style="color: #409eff; font-weight: bold;">`<html lang="zh-Hans">`</font>

`<head>` <span style="color: #37a1f6; font-weight: bold;">In this label, it MUST include </span><font style="color: #409eff; font-weight: bold;">`<title>`</font>

`<meta charset="utf-8" />` <span style="color: #37a1f6; font-weight: bold;">The English Website default charset is UTF-8, But when the website language isn't English, such us is Chinese, some browsers cannot show that characters very well, it might be show some garbleds if you doesn't set charset to UTF-8.</span>

`<title>` <span style="color: #37a1f6; font-weight: bold;">The title of the website, it's will show on the browsers label.</span>

`<body>` <span style="color: #37a1f6; font-weight: bold;">You can coding in the BODY.</span>

----

<span style="background: #ffff00; color: #000000b8; font-weight: bold;">Text</span>

|  Opening Tag   |  Element Content  |  Closing Tag  |  Example  |
|  :----  |  :----:  |  :----  |  :----:  |
| `<p>`  | This is a paragraph | `</p>` | `<p>This is a paragraph</p>` |
| `<a>`<br />`<a href="https://example.com/">` | This is a text.<br />This is a Link. | `</a>` | `<a>This is a text.</a>`<br />`<a href="https://example.com/">This is a Link.</a>` |
| `<br>` `<br />`  | NewLine |      |      |

^*^ <span style="color: red;">Don't forget the Colsing Tag!</span>

* <span style="background: #ffff00; text-decoration: underline;">HTML element syntax</span>
    - HTML elements start with a Opening Tag.
    - HTML element terminated with Closing Tag.
    - The content of the element is the content between the opening and closing tags.
    - Some HTML elements have empty content.
    - Empty elements are closed in the opening tag (ending at the end of the opening tag)
    - Most HTML elements can have attributes.

----

<details>
  <summary>Example code</summary>

  ```html
  <!DOCTYPE html>
  <html>
    <head>
        <meta charset="utf-8" />
        <title>This is a test website</title>
    </head>
    <body>
        <a>This is text</a>
        <a href="https://example.com">This is a Link.</a>
        <br />
        <p>This is a paragraph.</p>
    </body>
</html>
  ```

</details>

<!--<span style="color: #37a1f6; font-weight: bold;">When you want</span>-->
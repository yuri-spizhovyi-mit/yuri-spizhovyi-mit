# Images

I've been learning how to embed images in Markdown, but I encountered some difficulty
 with linking to images. Below is a short guide to explain the process.

## Linking to Images in Markdown

You can create a link that navigates to a specific image by linking to the header
associated with that image. The link uses the format Link Text in square
braces, then (#header-id), where header-id is the lowercase version of the header
text, with spaces replaced by hyphens.

There are images like .gif, .jpg and .jpg with link:

- [Link to .gif picture](#gif)
- [Link to .jpg picture](#jpg)
- [Link to a .jpg picture that is also a link](#link-to-a-jpg-picture-that-is-also-a-link)

## gif

![a .gif assets](./assets/hello.gif)

## jpg

![a .jpg assets](./assets/Sunflower_from_Silesia2.jpg)

## Link to a .jpg picture that is also a link

[![Link to a .jpg picture that is also a link](./assets/Sunflower_from_Silesia2.jpg)](<https://en.wikipedia.org/wiki/Common_sunflower#/media/File:Sunflower_sky_backdrop.jpg>)

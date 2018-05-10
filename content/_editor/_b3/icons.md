---
title: "Working with Icons"
menu: "menub3editor"
---

Balsamiq Mockups 3 includes the amazing [Font Awesome](http://fortawesome.github.io/Font-Awesome/) icon set. It contains over 500 icons in a wide range of categories that can be sized from very small to very large. It is also updated frequently and we plan to keep up with the updates whenever we release a new version of our product (_[more about why we switched here](http://blogs.balsamiq.com/product/2015/03/31/font-awesome/)_).

It should meet all your icon needs, but if not, you can [add your own icons](#adding-your-own-icons) or [request new ones from Font Awesome](http://fortawesome.github.io/Font-Awesome/community/#requesting-new-icons).

![](//media.balsamiq.com/img/support/docs/m4d/b3/icon-library.png)

Icons from previous versions of Balsamiq Mockups have been remapped to the new icons.

## Adding Icons via the UI Library and Quick Add

Also new in Balsamiq 3, icons now have their own category in the UI Library so you can drag and drop them just like any other control.

![](//media.balsamiq.com/img/support/docs/m4d/b3/icon-uilibrary.png)

Not only that, they show up in the Quick Add results, saving you time when searching by name or keyword.

![](//media.balsamiq.com/img/support/docs/m4d/b3/icon-quickadd.png)

Icon search results are shown _below_ any UI controls that match the text you enter.

* * *

## Adding and Swapping Icons via the Property Inspector

Some controls allow you to add icons to them (buttons, for example). You can do this from the [Property Inspector](../inspector/) in one of two ways: the icon search and the icon library dialog.

### Icon Search

If the control you selected support icons, you will see the icon search box in the property inspector. This works much like [the Quick Add tool](../overview/#the-quick-add-tool), just type a few letters from the name of the icon you are looking for and a list of suggestions will pop up as a grid of icons to choose from. Just click on the one you want to select it.

![](//media.balsamiq.com/img/support/docs/m4d/b3/icon-search.png)

You can then size the icon from "XS" (16px) to "XXL" (128px). You can also rotate icons in 90 degree increments using the button next to the search box.

### The Icon Library Dialog

If you'd like to explore all the icons that are available, click on the icon to the right of the icon search box.

![](//media.balsamiq.com/img/support/docs/m4d/b3/icon-open-library.png)

This will bring up the icon library dialog, where you can browse the icons by category and preview them at different sizes. You can double-click an icon to select it immediately or click once to select and then click the "Select" button to add it.

![](//media.balsamiq.com/img/support/docs/m4d/b3/icon-library.png)

Once you have selected an icon, you can resize it, rotate it or remove it via the Property Inspector.

* * *

## Adding Your Own Icons

You can also easily add your own icons for use in your wireframes.

### Using Your Image Assets

You can pick any of your imported image [assets](../images/) and use it as an icon. They will automatically show up in the icon library, under the Assets category at the bottom.

### Adding via the Icon Library Dialog

You can also add your own icons from the icon library dialog.

![](//media.balsamiq.com/img/support/docs/m4d/b3/icon-import.png)

Select the Assets category, then click the little plus button, select an image file and your image will be resized down to fit an existing icon size and copied to your assets.

* * *

## Best Practices for Creating or Preparing Custom Icons

Mockups works with color and transparency, but icons you add may not turn out looking as you want them to if they're not prepared to work the way Mockups expects them to. Below are some tips to get the most out of your custom icons.

### Color

*   Mockups uses black as a color for replacement at 100% opacity.
*   Icons that aren't created with black can have undesirable effects when colorized.
*   We recommend using black as the color for your icons.

### Transparent Areas

*   Mockups colorizes the entire opaque area of the icon.
*   For best results, we recommend knocking out "white" areas of your icon using transparency. Transparent PNG works best.

The example below shows regular icons in the left column, a custom icon properly prepared with black fills in the middle column, and a custom icon that doesn't work as well in the right column. To fix the icon in the right column, the exclamation point should be made transparent, and the icon color should be black.

![](//media.balsamiq.com/img/support/docs/m4d/customicon-bestpractice.png)

The built-in CSS will be replaced after update / reinstall, DO NOT MODIFY THEM.

Refer https://support.typora.io/Add-Custom-CSS/ when you want to modify those CSS.
Refer https://support.typora.io/About-Themes/ if you want to create / install new themes.

> From https://support.typora.io/Add-Custom-CSS/
> Append Custom CSS to all themes or other themes
> Typora will load CSS files in following order:

- Typora’s basic styles
- CSS for current theme
- base.user.css under theme folder
- {current-theme}.user.css under theme folder.

You can create base.user.css and {current-theme}.user.css under the theme folder if they do not exist.

If you want to change CSS styles, and apply it to all themes, you should modify base.user.css and append your own CSS, so whatever theme is selected, your CSS style will still be loaded and applied.

If you want to modify some CSS for a specific theme, for instance “Newsprint”, you can create newsprint.user.css and append the CSS you want. The reasons we do not recommend you modify the theme file directly are:

Default themes that available after Typora is installed may also be updated. If this happens, then the new version simply replaces the existing one under theme folder, and your modifications will be lost.
Themes developed by other people may also be changed in future. If they changed their CSS file, you can just replace their new file with your old one without worrying your modification will be gone.
(If you write your own CSS theme, then modifying it directly is OK.)

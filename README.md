# neon-syntax theme

Neon syntax theme for Atom inspired by and based on the Farzher Neon Sublime Text 2/3 theme, using CSS text-shadow to implement the glow effect

![Screenshot](https://cloud.githubusercontent.com/assets/421854/3365790/cf321014-fb35-11e3-9ac4-fbb48dd06361.png)

If you find that the blur or intensity are too high for your comfort, you can edit the variables in the package's stylesheets/syntax-variables.less to tone down the colours or reduce the blur radius on the text-shadow.  Eventually I intend to provide a settings screen to adjust these values easily once I figure out how to add a settings pane to Atom's Preferences view.

```less
// Theme specific vars
@opacity: 0.8;
@blur: 15px;
@contrast: 200%;
@saturation: 200%;
```

# font-awesome-5 - Read Me

Based on font awesome 5, free version. This package can work along with the 4 version from within the ext/packages/font-awesome, thus you can have both packages in app.json requires

Use steps:

1. Copy into project/packages/local/font-awesome-5
2. While being in 1: `sencha package build`
3. In project/app.json add in requires `font-awesome-5`.
4. Make sure your theme package has (for panel tools): 
	- `$font-icon-font-family: "Font Awesome 5 Free Solid";`
	- `$enable-font-icons: true;`
5. Build your app

Inspired from:
https://www.sencha.com/forum/showthread.php?469569-How-to-upgrade-Font-Awesome
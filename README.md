A dark theme stylesheet to override Synology Audio Station's eye-melting theme. Tested in v6.5.5 of AS and 6.2.3 of DSM. Other versions may or may not work. Won't necessarily be updated as new versions come out.

### Usage
You'll need a browser extension to modify live site CSS, such as the Stylus extension for Firefox or Chrome. For Stylus, go to your Synology DSM page in your browser, click the Stylus toolbar icon, and select the "Write style for" option. Copy the code from the CSS file in this repository and paste it into the editor that just opened. Save the changes and you should be done.

The CSS is "fairly well" commented as to what rules control what parts of the UI, so should make edits and forks pretty easy.

### Notes
* Does currently override some non-Audio-Station menus (they use generic top-level DOM elements), although you could use a custom Audio Station URL to avoid this.
* Makes the main list scrollbar thicker and more visible. Not strictly a color change, but I felt it was important.
* Does not currently modify the mini-player--should it?
* Can't make use of Stylus' UserCSS for automatic updates AFAIK because the DSM domain is variable. Have to manually update from here.


### Previews
Coexisting with other apps
![Coexisting with other apps](https://raw.githubusercontent.com/slserpent/dsm-dark-theme/main/previews/1.png)
Dialogs and artwork
![Dialogs and artwork](https://raw.githubusercontent.com/slserpent/dsm-dark-theme/main/previews/2.png)
Playing queue
![Playing queue](https://raw.githubusercontent.com/slserpent/dsm-dark-theme/main/previews/3.png)
Playing queue before
![Playing queue before](https://raw.githubusercontent.com/slserpent/dsm-dark-theme/main/previews/4.png)

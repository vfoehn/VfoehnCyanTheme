# Vfoehn's README

## Motivation
I wanted to change the color of the project panes in IntelliJ. However, as we can see in the following JetBrains tickets
this functionality is not supported via the standard IntelliJ settings:
- [IDEA-68337](https://youtrack.jetbrains.com/issue/IDEA-68337)
- [IJPL-138359](https://youtrack.jetbrains.com/issue/IJPL-138359)

Thus, I decided to modify the theme in the source code.

## Notes on Modifying the Theme

### Step-by-Step Instructions
This is the main tutorial page for creating a theme [here](https://plugins.jetbrains.com/docs/intellij/developing-themes.html).
By going through all the subpages, you should be able to create and export your own theme.
Let me highlight some important steps that would otherwise be easily missed:
- [IntelliJ development setup](https://plugins.jetbrains.com/docs/intellij/setting-up-theme-environment.html)
    - Make sure you have the "Plugin DevKit" plugin installed and you use the right JDK version.
- [Deploying a Theme](https://plugins.jetbrains.com/docs/intellij/deploying-theme.html)
    - The option `Prepare Plugin Module $MODULE_NAME$ for Deployment.` only appears if you have the right directory (e.g.
      the root directory of the project) selected in the Project view.
- [Install the theme plugin from disk](https://www.jetbrains.com/help/idea/managing-plugins.html#install_plugin_from_disk)

### Additional Links
- Video where JetBrains dev creates a theme:
    - [Here](https://www.youtube.com/live/9J0j-90dC60?si=z2o34aESAPhM3nHy&t=799)
- [Cyan Theme GitHub repo](https://github.com/OlyaB/CyanTheme)

## Results
### Standard "Cyan Theme"
![before-vfoehn-modification](/screenshots/before-vfoehn-modification.png)

### "Cyan Theme" after Vfoehn's Modifications
![after-vfoehn-modification](/screenshots/after-vfoehn-modification.png)

---

# Original README

A light theme in cyan tones for JetBrains IDEs. For version 2019.1 and above.

To install:
* Go to _Settings (Preferences) | Plugins_, find the theme plugin and install it
* Restart IDE
* Go to _Settings (Preferences) | Appearance & Behavior | Appearance_ and see the _Theme_ dropdown

[In JetBrains plugin repository](https://plugins.jetbrains.com/plugin/12102-cyan-light-theme) | [Report an issue](https://github.com/OlyaB/CyanTheme/issues)  

![Cyan light theme main window](/screenshots/cyan-main-window.png)  
![Cyan light theme settings](/screenshots/cyan-settings.png)
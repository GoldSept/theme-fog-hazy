# 🎉Fog Hazy

## 🎇Enjoy the new interface, novelty and consistency!

![theme-example](./images/theme-example1.png)

![theme-example](./images/theme-example2.png)



## 💡 Acrylic Mode

If you want to experience the acrylic modal effect, you need to use the ~~[Apc Customize UI++](https://marketplace.visualstudio.com/items?itemName=drcika.apc-extension)~~ [Custom UI Style](https://marketplace.visualstudio.com/items?itemName=subframe7536.custom-ui-style) extension and configure the following CSS code:



🎉**『Custom UI Style』 supports the latest VSCode version(1.97+)!**



```json
{
    "custom-ui-style.stylesheet": {
        ".goldenchao-fog-hazy-themes-fog-hazy-color-theme-acrylic-json": {
            ".quick-input-widget,.editor-widget,.suggest-details-container,.monaco-dialog-box,.monaco-hover,.rename-box": {
                "transform": "translateZ(0)",
                "-webkit-transform": "translateZ(0)",
                "backdrop-filter": "blur(10px) !important"
            },
            ".monaco-menu-container,.context-view.fixed,.context-view.fixed > .monaco-scrollable-element,.context-view .workbench-hover-pointer::after,.token-inspect-widget,#settingsWidget.active": {
                "transform": "translateZ(0)"
                "-webkit-transform": "translateZ(0)",
                "backdrop-filter": "blur(15px) !important"
            }
        }
    }
}
```



If you want to use『Apc Customize UI++』, keep VSCode version 1.93 and below



```json
{
    "apc.stylesheet": {
        // acrylic effect
        ".quick-input-widget,.editor-widget,.suggest-details-container,.monaco-dialog-box,.monaco-hover,.rename-box": {
          "transform": "translateZ(0)",
          "-webkit-transform": "translateZ(0)",
          "backdrop-filter": "blur(10px) !important"
        },
        ".monaco-menu-container,.context-view.fixed,.context-view.fixed > .monaco-scrollable-element,.context-view .workbench-hover-pointer::after,.token-inspect-widget,#settingsWidget.active": {
          "transform": "translateZ(0)",
          "-webkit-transform": "translateZ(0)",
          "backdrop-filter": "blur(15px) !important"
        },
	}
}
```



then you got it!



![acrylic](./images/theme-example-acrylic1.png)

![acrylic](./images/theme-example-acrylic2.png)

**Enjoy!**

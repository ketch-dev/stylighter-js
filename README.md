# Stylighter
This extension allows you to highlight [styled-components](https://styled-components.com/) such as `<SC.Component />` in your code.

##### *NOTICE:*
We have two variations of this extension:
[Stylighter for `JavaScript` files](https://marketplace.visualstudio.com/items?itemName=ketch.js-stylighter) *(current one)*
[Stylighter for `TypeScript` files](https://marketplace.visualstudio.com/items?itemName=ketch.ts-stylighter)
You can install only one of them, or both in case if you want styled-components highlighted in both `JavaScript` and `TypeScript` files.

## Preview
As you can see on the preview below, this extension only changes the styles of styled-components tags, and your theme colors wont be touched, you can set any color or others types of styles for styled-components tags, see [Settings](#Settings) section below *(initially there are no color at all, so you have to set it manually).*

![extension preview](https://i.ibb.co/tHr4gkL/styled-v3.png)


## Requirements

**1)** For this extension to work, you will need to import your styled-components using naming conventions:
![naming convention example](https://i.ibb.co/zxkhyNd/imports-v1.png)
**you don't have to import your styled-components exactly this way, but in the end you should use them in JSX as object values, for example <Styled.Title />*

learn more about advantages of such naming convention [here](https://medium.com/inturn-eng/naming-styled-components-d7097950a245), [here](https://www.robinwieruch.de/styled-components/) and [here](https://humanoids.nl/en/articles/styled-components-and-their-naming/)

**2)** Set  highlight styles of your choice *(see next section).*

## Settings
To set styling for your styled-components tags, [navigate to `settings.json`](https://stackoverflow.com/questions/65908987/vs-code-how-to-open-settings-json-file).

**You can:**

**1)** Set styles separately for all prefixes:

`S`, `SS`, `Styled`, `SharedStyled`

**2)** Set style globally and/or specifically for theme



**Examples below are self-explanatory**

*Global settings*
![global settings example](https://i.ibb.co/4FVCJ3m/settings-v1.png)
*Theme-specific settings*
![theme specific settings example](https://i.ibb.co/0ypwzFm/settings-themespecific-v1.png)
Learn more about [token customizations](https://code.visualstudio.com/docs/getstarted/themes#_editor-syntax-highlighting)
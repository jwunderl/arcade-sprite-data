---
title: Manual
---

> Open this page at [https://microsoft.github.io/arcade-sprite-data/](https://microsoft.github.io/arcade-sprite-data/)

## Usage

This extensions adds block to store and read data 
in sprites. The blocks are added to the bottom of the **sprites** toolbox.

* Storing numbers

```blocks
let mySprite = sprites.create(sprites.food.smallApple, SpriteKind.Player)
sprites.setDataNumber(mySprite, "life", 3)
sprites.changeDataNumberBy(mySprite, "life", -1)
let life = sprites.readDataNumber(mySprite, "life")
```

* Storing strings

```blocks
let mySprite = sprites.create(sprites.food.smallApple, SpriteKind.Player)
sprites.setDataString(mySprite, "name", "alex")
let name = sprites.readDataString(mySprite, "name")
```


## Use this extension

This repository can be added as an **extension** in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/microsoft/arcade-sprite-data** and import

## Edit this extension ![Build status badge](https://github.com/microsoft/arcade-sprite-data/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/microsoft/arcade-sprite-data** and click import

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

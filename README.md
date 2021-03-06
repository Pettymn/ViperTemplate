# ViperTemplate
![GitHub version](https://badge.fury.io/gh/natangr%2Fvipertemplate.svg)

Template to generate VIPER classes on Xcode.

## About VIPER
VIPER is a backronym for View, Interactor, Presenter, Entity and Router. It’s basically an approach that implements the Single [Responsibility Principle](https://en.wikipedia.org/wiki/Single_responsibility_principle) to create a cleaner and more modular structure for your iOS project. You can learn more about it
[in this blog post](https://www.ckl.io/blog/ios-project-architecture-using-viper/).

## Installation
- [Download VIPER Template](https://github.com/natangr/ViperTemplate/archive/master.zip) or clone the project
- Copy the `Design Pattern` folder to `~/Library/Developer/Xcode/Templates/File Templates/` or create a symbolic link to that folder.

## Using the template
- Start Xcode and create a new group for your VIPER module
- Create a new file (`File > New > File` or `⌘N`)
- Choose `Design Pattern` and `VIPER`

PS: Don't forget to add the ReusableView protocol extension and both the UIViewController and UIStoryboard extensions to your project.

## Created Files
- `Contract` -> Contains all the protocols used in VIPER
- `Interactor`
- `Presenter`
- `ViewController` (AKA View)
- `Router`

## Contact
[Natan Grando](https://github.com/natangr)

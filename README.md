# HelloYeew's workflow setup

Here's the list of tool and setup that I use in my workflow.

## Note on my setup

Note that I work on many platform :
- MacOS (MacBook Pro) for web development, testing and when not working at home.
- Windows (PC) with Linux virtual machine for .NET development and testing stuff too. When I'm working at home I usually use this.
- iPad (iPad Pro) for speedy PR check and some urgent SSH connection.

That's why I try to make almost of every tool sync between these three devices so if some tool is only support on specific platform, I will note on it.

## Browser

I normally use [Google Chrome](https://www.google.com/chrome/) as a primary browser since I use it for a long time and it's good for web development. (I use [Microsoft Edge](https://www.microsoft.com/en-us/windows/microsoft-edge) too but not much.)

### Theme

I use theme that I create from [loundraw's illustration from 君は月夜に光り輝く](https://www.pixiv.net/en/artworks/61606801) with my personal customized color.

![Theme preview](img/chrome-theme-screenshot.png)

Download : [You Shine in the Moonlit Night](theme/You-Shine-in-the-Moonlit-Night.crx)

### Homepage

As you see from the theme preview image, I use my customized self-host homepage since I want to use this homepage on every device.

- [mamizu](https://github.com/HelloYeew/mamizu) : Fork of [Flame](https://github.com/pawelmalak/flame) that I add some of my customization to make it looking same as my theme and some of my personal customization.
- [Custom New Tab URL](https://chrome.google.com/webstore/detail/custom-new-tab-url/mmjbdbjnoablegbkcklggeknkfcjkjia) : Without this extension I cannot set mamizu as my chrome homepage.

## IDE

I normally use JetBrain platform as a primary IDE and [Visual Studio Code](https://code.visualstudio.com/) as a secondary IDE. Here's my IDE that I use.

- [PyCharm Professional](https://www.jetbrains.com/pycharm/) : Use in Python development and some web development that use Python framework like [Django](https://www.djangoproject.com/) since it's fully support on Django and have a lot of useful features to make your development process easier.
- [dotUltimate](https://www.jetbrains.com/dotnet/)([Rider](https://jetbrains.com/rider/) and [ReSharper Tool](https://jetbrains)) : Use in .NET and entire C# project development. It's a best IDE for .NET development for me. The code recommendation and refactoring tool is really good and with its tool it's best for spectate your .NET program behavior and debugging process.
- [CLion](https://www.jetbrains.com/clion/) : Normally it use in C/C++ development but with [IntelliJ Rust](https://intellij-rust.github.io/) and CLion it make CLion fully support Rust development.
- [WebStorm](https://www.jetbrains.com/webstorm/) : Use in all web development related stuff.
- [DataGrip](https://www.jetbrains.com/datagrip/) : Use in some SQL database query on my server and in my local development. It's support mostly all database type and it's pretty good for remote database cluster.
- [RunyMine](https://www.jetbrains.com/runymine/) : Use in Ruby development and [Ruby on Rails](https://rubyonrails.org/) since it's fully support Ruby on Rails. But I rarely touch to Ruby world so I rarely use it.

- [Visual Studio Code](https://code.visualstudio.com/) : I normally use it when I want to quickly editing some error and normally writing some Markdown file but not as a primary IDE.

### Customization

Since JetBrain has sync customization like VSCode so I don't need a lot of sync setup on all device.

- [The Doki Theme](https://doki-theme.unthrottled.io/) : It provide a theme on a lot of platform with anime-style color theme. I setup this on both JetBrain IDE and VSCode and on GitHub too. I use *NekoPara : Chocola* as night theme and *NekoPara : Shigure* as day theme. (Yeah I use day theme!) But the most feature that I love is you can add your favorite character as your sticker on your IDE! (In JetBrain IDE you can also move it too.) So you can have a nice anime-style theme with your favorite character on your IDE when you are tired and want some energy from your waifu.

![Doki Theme](img/doki-theme-jetbrain.png)

- [Dark Purple Theme](https://plugins.jetbrains.com/plugin/12100-dark-purple-theme) (JetBrain IDE only) : I sometime swap to this theme when sometime I'm bored and want to change some color on my IDE.

**Customization plugin that I use before but I'm not using anymore** :
- [Material Theme UI](https://plugins.jetbrains.com/plugin/8006-material-theme-ui) (JetBrain IDE only) : At first it's a free and very good plugin to fully customized your JetBrain IDE with Material UI but when it convert to Freemium and on latest version with new styling it's make your IDE a lot more resource and make your IDE performance a lot worsen that's why I don't use it anymore.

### Useful plugin

- [Wakatime](https://wakatime.com/) : Use to track your coding time and get some statistics about your coding time.
- [Code::Stats](https://codestats.net/) : Make your coding like you are playing a game, collect some XP and up your level and get some statistics about your coding time.
- [IdeaVim](https://plugins.jetbrains.com/plugin/164-ideavim/) (JetBrain IDE only) : Make your JetBrain IDE more like Vim with Vim key binding and some other features.
- [Rainbow Bracket](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets) (JetBrain IDE only) : Make your bracket color match and easier on bracket matching.
- [Discord Integration](https://plugins.jetbrains.com/plugin/10233-discord-integration) in JetBrain or [Discord Presence](https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode) on VSCode : Make your friend know that you are playing VSCode or PyCharm and set some cool rich presence on Discord.
- [Day and Night](https://plugins.jetbrains.com/plugin/12006-day-and-night) (JetBrain IDE only) : Set your favorite theme as day and night theme so you can click the icon to switch between day and night theme or set your time to make your IDE automatically switch between day and night theme.
- [CodeGlance](https://plugins.jetbrains.com/plugin/7275-codeglance) (JetBrain IDE only) : Embeds a code minimap similar to the one found in Sublime into the editor pane.
- [.ignore](https://plugins.jetbrains.com/plugin/7495--ignore) (JetBrain IDE only) : Quickly create .blablaignore file with some pretty good template and you can set your presonal ignore file as your template for every project too.
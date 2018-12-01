# Module 1: Setting Up Your Development Environment

## Part One: Staying in The Loop
### Slack

Slack is where we'll be communicating with each other the most. It's where we discuss our ideas, ask our questions and post our resources. If you haven't already, download **[Slack](https://slack.com/downloads/)**.

<img src="../images/slack-tweet.png" width="256" title="@iamdevloper">

... or just use the web version.

Create an account and join our channel **[here](https://stow-protocol-devs.slack.com
)**.

## Part Two: Shilling For Shell
### Bash
*Fellow imbibers of the Apple-flavored kool-aid, you can skip to right over to [Command Line Interface](#cli).*

Windows users, stay right here, you'll need to install a **[bash shell](https://www.windowscentral.com/how-install-bash-shell-command-line-windows-10)** before you move on. This will make installing different packages, their dependencies... and version control, so much easier.

To navigate around, you'll be able to use the same **[commands](https://help.ubuntu.com/community/UsingTheTerminal#Commands)** as you would with Ubuntu.

### <a name="cli">Command Line Interface</a>
*If you speak command line as a native language, skip to part three where you can install any packages you don't have yet.*

If you haven't ever used a shell, fear not, because you're in for a total treat.

Long ago, before pretty buttons and nice menus were an absolute must-have, or even thought possible, your computer was only capable of inputting and outputting text. You type in the commands, and the computer does what you tell it to do. Because of that, it's described as the window to the heart of the computer-- the heart being the kernel. Now the kernel is the software that knows how to make the hardware do things. So you speak to the kernel to get your computer to... compute.

But if we have pretty buttons and nice menus, why would anyone prefer to use a shell now? It seems a bit primitive, I know. Thousands of man hours dedicated to developing beautiful GUIs, and here we are clacking on a small black screen with green h4ck3r text. But it's way faster to type a command than to click a button. You can run your code straight from the command line, as long as you've installed the compiler. Make a new directory? `mkdir`. Create a new document? `touch new-document.txt`. Open that directory you just created? `open [name of your directory]`. Force quit an unresponsive application...?

<p align="center">
  <a href="https://medium.com/@eightlimbed/creating-and-killing-processes-in-linux-7d4470f1f7a6"><img src="../images/-kill.gif"></a>
</p>

The commands are quite colorful too.

Here are some courses to help you become one with the command line:
- [Codecademy - Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line)
- [Django Girls - Intro to the Command Line Interface](https://tutorial.djangogirls.org/en/intro_to_command_line/)
- [Zed Shaw's "LPTHW" also has a Command Line Crash Course](https://learnpythonthehardway.org/book/appendixa.html)

- If you're a Team Treehouse member, [here's their course on the Command Line Interface](https://teamtreehouse.com/library/console-foundations).

## Part Three: Packages

### Brew 🍺
*If you're part of the PC Master Race, skip down to [Git](#git). This is OSX sorcery.*

[What is Brew?](https://brew.sh/) Brew is short for Homebrew 🍺, it's a free and open source package management system that you use to install packages, and you only have it on Mac OSX. What a mouthful, here, check out [this link](https://computers.tutsplus.com/tutorials/homebrew-demystified-os-xs-ultimate-package-manager--mac-44884). It explains brew 🍺  works as a package manager.

To install brew, copy this command and paste it in terminal.
```unix
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

You can update brew with... wait for it... `brew update`.

### <a name="git">Git</a>
[What is Git?](https://git-scm.com/downloads) It's just a form of tracking changes to your code.

<p align="center">
  <img src="../images/version-control.png" width="450" title="from r/programmerhumor">
</p>

If you were ever guilty of creating a new save file for every change you ever made on a file. It's like that, but more organized. Version control is incredibly important when you want to keep track of every version of a file you've ever created. The heavens forbid, you end up like Snapchat with their series of unfortunate UI updates, only to be met by confused users **begging** for the older version back! Worse comes to worst, if a new function breaks your code, you can always go back to a past version. Oh, and you can collaborate with other people on your code. Or theirs. And this is where open source contributions come from.

The neat thing about git is that you can use it either with the command line interface, or you can download an app with a GUI so you can see what branching and merging actually looks like.

[Installation](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) could be done straight from the command line. If you have Mavericks 10.9 or higher, and XCode's command line tools installed, all you need to type is `git --version`. Or if you want to use brew 🍺, just type in `brew install git`.

All this talk about git, but where do your file changes go? To [GitHub](github.com). So you'll need to make an account there. But wait, how do you configure git on your computer, locally, to connect to your GitHub account? Superduper simple.

To configure your username and password, type in
```unix
git config --global user.name "FirstName LastName"
git config --global user.email "email@example.com"
```

If you went ahead and enabled 2FA, like you should, you might encounter a little hiccup. A fatal error, <!-- what was this error? --> . You can fix this and configure your account securely by creating a **personal access token**.




### NPM

### Node

## Part Four:
If you're using either Sublime or Atom, here are a few helpful commands and packages to install.

## Part Five:
### Ganache

### Truffle

### Parity

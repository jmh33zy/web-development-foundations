| Previous Chapter | Next Chapter |
| :------------- |:-------------|
| [Installations](./GETTING_STARTED_MAC.md) | [Using the Keyboard](./APP_TAB_SWITCHING_MAC.md) |

# Ditching the Dock Bar

As a Mac user, you most likely are used to using your mouse to navigate the operating system. Software developers use their keyboard for as many things as possible to accelerate their workflow and save time. This takes time, patient, and practice. In this chapter, you are going to learn how to start applications with your keyboard instead of clicking on an application on your desktop or in the Dock Bar at the bottom of the screen.

## Using Spotlight

Press the command key, keep it held down, and then tap your spacebar key. A new window will appear in the middle of your screen. This is the *Spotlight Search*. Then type in the word "terminal", and the Terminal application will show up as one of the results. In fact, it should be the top result and will be highlighted in blue. Since that is the top result, you can then just press return and the terminal application will run.


1. Use the Spotlight Search to launch Google Chrome (use "chrome" to search)
1. Use the Spotlight Search to launch Visual Studio Code (use "code" to search)

![Using Spotlight](./images/7RvmWxzPeg.gif)

> **TIP:** There is a free application called [Alfred](https://www.alfredapp.com/) that is powerful replacement for Spotlight if you would like to try that out. If you're not up for trying something new just yet, that's fine.

### Terminal Initialization File

Use the Spotlight Search to launch terminal (use "terminal" to search)

Once it is running, type in the following command. You will learn more about this command later. We know, it looks alien and scary, but it's not doing anything dangerous. It's just creating a configuration file for your terminal.

```sh
echo 'alias gs="git status"' >> ~/.bashrc
```


 <br/>
 <br/>
 <br/>
 <br/>
 <br/>

| Previous Chapter | Next Chapter |
| :------------- |:-------------|
| [Installations](./GETTING_STARTED_MAC.md) | [Using the Keyboard](./APP_TAB_SWITCHING_MAC.md) |
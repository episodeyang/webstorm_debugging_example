# Setting up ES6 Debugging with JetBrains WebStorm

First try to run the `test.js` script by pressing <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>R</kbd> with the `test.js` script open.

And there is this error message:
**Note**: disable ESLint by <kdb>Command</kbd>
![./figures/error-before-setup.png](./figures/error-before-setup.png)

The reason this happens is because node can not resolve `es6` module syntax without using michael jackson module.

Like this:
![./figures/setting-babel-register.png](./figures/setting-babel-register.png)

Now everything should run!

## Making it the way you like

You can change the key binding like this: press <kbd>command</kbd> + <kbd>,</kbd>

![./figures/changing-keybindings.png](./figures/changing-keybindings.png)

I personally use <kbd>command</kbd> + <kbd>I</kbd> for running current execution task, and <kbd>shfit</kbd> + <kbd>command</kbd> + <kbd>I</kbd>
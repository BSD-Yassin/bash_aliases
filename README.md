## Bash aliases

Created a file to source to get shortcuts and alias in the terminal. 
I'll use it for remembering the shortcuts, but also to skip easy lines in long processes. 

basically it revolves around the alias command, which can give a smaller alias for a command. 

ex:

```
alias up-up="sudo apt-get update && sudo apt-get upgrade -y"
```

meaning that you can just use up-up instead of the whole command

## How to install

``` 
git clone https://github.com/BSD-Yassin/bash_scripts 
```

```
cd bash_scripts
```

```
source custom_aliases
```

That's the important line, to source means to give the file to the bash configuration. It can only work with this step.

You now have commands like 

```
treels 
```

```
shortcut
 ```

```
pc 
```

That's only temporary, it will stay for as long as your terminal is open. I didn't want to make it permanant myself, I'm just tinkering with the concept of bash source and also expecting people to send more git updates if they want. 

But there is a way to make it permanant : 

```
sudo nano ~/.bashrc 
```

And you add everything from the custom_aliases to the actual file (in the custom section)
But I wouldn't recommand it if you're not sure yourself.

That's all, feel free to get in the file and make your own changes, and send them back in here! 

(https://phoenixnap.com/kb/linux-alias-command)

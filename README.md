<h1 align="center"><code>norminette @ home</code></h1>

<div align="center">
  <sub>Created by <a href="42.fr">42.fr</a></sub>
</div>
<div align="center">
  <sub>Adapted by <a href="https://hive.fi">Hive Helsinki</a> for all the 42 Network</sub>
</div>

---

# Norminette

The Norminette is a tool by 42 Network, to check that the source code respects the school’s norm.

Given the temporary lockdown of Hive’s facilities, we have decided to give remote access to the Norminette.
<br /><br >
# Installing instructions

### OSX:

*Tested on Mac OS X 10.14.6 with ruby 2.6.3p62*

```bash
git clone https://github.com/hivehelsinki/norminette-client.git ~/.norminette/
cd ~/.norminette/
bundle # it will ask for your password.
```

**Create an alias**

```bash
echo 'alias norminette="~/.norminette/norminette.rb"' >> ~/.zshrc
source ~/.zshrc
```
<br /><br />
### GNU/Linux

*Tested on Ubuntu 18.04.4 with ruby 2.5.1p57*

```bash
sudo apt-get install ruby ruby-bundler ruby-dev build-essential
git clone https://github.com/hivehelsinki/norminette-client.git ~/.norminette/
cd ~/.norminette/
bundle
```

**Create an alias**

```bash
echo 'alias norminette="~/.norminette/norminette.rb"' >> ~/.zshrc
source ~/.zshrc
```
<br /><br />
### Windows

- Install ruby 2.7 without DevKit: https://rubyinstaller.org/downloads/
- git clone this repository or download as a zip file
- extract into C:\norminette
- Go inside this folder with cmd.exe
- Run: `bundle`
- Add C:\norminette into your PATH so you can use `norminette.rb` from any folder. (https://docs.alfresco.com/4.2/tasks/fot-addpath.html)

Here it is!

---
layout: docs
---

# Get Ruby

Ruby is a dynamic programming language focused on simplicity and productivity. It's intuitive, so beginners can pick it up quickly, and powerful enough to power all kinds of applications, large and small.

To write and run Ruby programs on your computer, you first need to install the language (also just a program). Follow the instructions below for your operating system. If you get stuck, tweet us at [@learn_ruby](http://twitter.com/learn_ruby) (your feedback will help make this guide even better).

Below are instructions for [Mac OS X 10.7 (Lion) and Newer](#osx-10_7), [Mac OS X 10.6 (Snow Leopard)](#osx-10_6), and [Windows](#windows).

<!--
If you're stuck, you can also try the Rails Girls guide: http://guides.railsgirls.com/install/
-->


<a name="osx-10_7"></a>
## Mac OS X 10.7 (Lion) and Newer

1. Install Xcode by opening the Mac App Store and searching for "Xcode".

2. In the menu bar, open the Xcode preferences (`Xcode > Preferences...`)

3. Select the `Downloads` tab, find the `Command Line Tools` line, and click `Install`.

4. Install Ruby by running:

  ```bash
  $ \curl -L https://get.rvm.io | bash -s stable --ruby
  ```

5. After installation finishes, set the current version of Ruby by running:

  ```bash
  $ rvm use 2.0.0 --default
  ```

<a name="osx-10_6"></a>
## Mac OS X 10.6 (Snow Leopard)

1. Download and run the OS X GCC installer at https://github.com/kennethreitz/osx-gcc-installer

2. Install Ruby by running:

  ```bash
  $ \curl -L https://get.rvm.io | bash -s stable --ruby
  ```

3. After installation finishes, set the current version of Ruby by running:

  ```bash
  $ rvm use 2.0.0 --default
  ```

<a name="windows"></a>
## Windows

Just go to http://railsinstaller.org, download the kit, and run it. Choose the default options when installing.

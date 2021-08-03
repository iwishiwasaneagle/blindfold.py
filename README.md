<h1 align="center"> blindfold.py - a lightweight and simple .gitignore generator</h1>

[![Build](https://github.com/iwishiwasaneagle/blindfold.py/actions/workflows/build.yml/badge.svg)](https://github.com/iwishiwasaneagle/blindfold.py/actions/workflows/build.yml)
[![GitHub license](https://img.shields.io/github/license/iwishiwasaneagle/blindfold.py)](https://github.com/iwishiwasaneagle/blindfold.py/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/iwishiwasaneagle/blindfold.py)](https://github.com/iwishiwasaneagle/blindfold.py/stargazers)

## ✨ Features
* Pulls .gitignore templates from gitignore.io. 
* Clean and simple CLI
* Allows for the combination of any number of different templates all into one gitignore

## 📦 Installation

#### 📥 Download from pypi.org

```bash
pip install blindfoldpy
```

#### 🏗️ Build from source
```bash
git clone https://github.com/iwishiwasaneagle/blindfold.py
cd blindfold.py
python3 setup.py install
```

<!-- ## 🔧 Examples of use:
```bash
# generates a single gitignore file for both dart and flutter in ./src/.gitignore
blindfold --lang dart flutter
```

```bash
# use the append flag to add to the pre-existing gitignore file (can be shortened to -a)
blindfold --append macos
```

```bash
# you can specify a specific destination to store the gitignore file using the dest argument
blindfold --lang rust --dest ./src/
```

```bash
# you can put languages into directories by prefixing the language name with the path (which can include '**')
blindfold --lang rs/rust py/python **/make
```

```bash
# arguments can also be written in shorthand
blindfold -l rust -d ./src/
```

```bash
# shows full list of available templates
blindfold list
```

```bash
# There is a help screen that can be shown which details the subcommands and arguments to supply to the program
blindfold -h
``` -->

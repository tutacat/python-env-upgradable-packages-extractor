* This program is an **pip list** warper to generate two python packages list files in **pip-update** folder.
* These files are upgradable packages list in environment.
* One of files is current+today.txt that is current version list.
* Anther of files is update.txt that is upgradable version list. 
* You can use "pip install -r .pip-update/update.txt" to upgrade your packages or recovery by anther file.

Installation
============

To install pip-update from PyPI:

    $ pip install pip-update
Usage
=====

Options::

    usage: pip-update [-h] [-v]

    A current and update package list of environment extractor.

    optional arguments:
      -h, --help            show this help message and exit
      -v, --version         show version number and exit

這程式是一個 **pip list** 的包裹器，以來自虛擬環境中可升級的python 套件版本列表的資料，在**pip-update**資料夾內產生二個檔案, current+today.txt是當前的版本號列表，update.txt則是可升級的版本號列表。
然後我們可以用pip install -r 來進行升級或還原python 虛擬環境。
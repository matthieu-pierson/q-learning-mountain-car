<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT -->
## About

<p align="center">
  <img width="460" height="300" src="./mountaincarv0.gif">
</p>


This repository contains a basic code for understanding the mechanics behind q learning.

### Built With

* [Python 3](https://getbootstrap.com)

<!-- GETTING STARTED -->
## Getting Started
### Prerequisites

* pyenv (optional)
* python 3.8.3
* gym
* numpy

### Installation

Copy the repository to a new directory :

    $ mkdir ~/qlearning_mountaincar_v0
    $ cd ~/qlearning_mountaincar_v0
    $ git clone https://github.com/matthieupierson/qlearning_mountaincar_v0.git


It is not required to install pyenv, but it is easier to manage python versions and packages with it.

pyenv & python 3.8.3 installation : (optional)

    $ curl https://pyenv.run | bash
    $ curl -L https://github.com/pyenv/pyenv-installer/raw/master/bin/pyenv-installer | bash
    $ exec $SHELL

You can now begin using pyenv. Let's install python 3.8.3 an the requiried packages. (optional)

    $ pyenv install 3.8.3

Check current version by using : (optional)

    $ pyenv versions
    *system (set by /home/ etc..)
    3.8.3

There is two ways to define which pyhton version you want to use. The first one (recommended) is to assign a python version to a directory. (optional)

    $ cd ~/qlearning_mountaincar_v0
    $ pyenv local 3.8.3

The second way is to set a global python version. (optional)

    $ pyenv global 3.8.3

Check current version by using : (optional)

    $ pyenv versions
    system (set by /home/ etc..)
    *3.8.3

Now that we have configured our environment let's install the required packages.

    $ pip install gym
    $ pip install matplotlib

<!-- USAGE EXAMPLES -->
## Usage

    $ cd ~/qlearning_mountaincar_v0
    $ python qlearning_mountaincar_v0.py

<!-- CONTRIBUTING -->
## Contributing

Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [sentdex - Reinforcement Learning](https://www.youtube.com/playlist?list=PLQVvvaa0QuDezJFIOU5wDdfy4e9vdnx-7)
* [pyenv](https://github.com/pyenv/pyenv)
* [pyenv-installer](https://github.com/pyenv/pyenv-installer)

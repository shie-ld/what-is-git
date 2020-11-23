[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<br />
<p align="center">

  <h3 align="center">What is Git?</h3>

  <p align="center">
    An interactive  tutorial meant to teach you the core concepts of git, not merely just which commands to use.
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Tutorial](#about-the-tutorial)
* [What is Git?](#what-is-git)
* [Outline](#outline)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)



<!-- ABOUT THE TUTORIAL -->
## About The Tutorial

This tutorial is aimed at providing you the knowledge of `source code management` and `version control` using `git`. You will not just merely learn about which commands to execute, but how git achieves the whole funda of version control.

I'll try to incorporate as many things as I can in simple English in it, but after reading this, if you want to learn more about git, then the best resources are [Git Bool](https://git-scm.com/book/en/v2) and [Git Reference](https://git-scm.com/book/en/v2), also the source of this tutorial. This tutorial will aid you in understanding all the git features listed there.


<!-- WHAT IS GIT? -->
## What is Git?
Git is a tool that helps you in `version control` and `source code management` of your project. But wait a minute :thinking:, what are these things. Say we have a directory which contain two files - `foo.txt`, being containing `Hello foo` and `bar.txt` being containing `Hello bar`, as part of a project. Let us say it as `version 1` of our project. So our `version 1` will look like something: 

<p align="center">
    </ br>
    <b> Version 1</b>
    </ br>

</p>

File | Content
--- | ---
`foo.txt` | `Hello foo`
`bar.txt` | `Hello bar`



Now let us edit our `foo.txt` file and change it's content from `Hello foo` to `Hello foo boo`, and leave `bar.txt` uneditied. And say this is our `version 2` of the project. So our `version 2` will look like:

<p align="center">
    </ br>
    **Version 2**
    </ br>

    File | Content
    --- | ---
    `foo.txt` | `Hello foo boo`
    `bar.txt` | `Hello bar`

    </ br>
</p>



So till now, we have successfully rolled out 2 versions of our project. But in `version 2` I do not like the content of `foo.txt` and I want to roll back to previous version. So what a `version control` and `source code management` tool like `git` does is to make this task **seamless and efficient** without neck in the pain and having to remember when we released a specified version, or maintaining a `todo list` for that.


Now consider a mammoth size project on which thousands of developers are working. So there should be a way to manage all that stuff, so as to maintain integrity of project and all the related data. Here `git` come to our rescue :smile:. `git` will take care of everything - from source code management to version control.

Now we have a brief idea about what `git` is. So let us dwell deep about how `git` acheives that and how can we use it into our projects :nerd_face:.






<!-- OUTLINE -->
## Outline

![outline](./images/outline.jpg)

<br />

Let's start with the `Remote Repository`. Suppose you are one of the members in the team working on a project.   It is where you send the changes made by you in the project to share with other people


### Here's why: ###
* Your time should be focused on creating something amazing. A project that solves a problem and helps others.
* You shouldn't be doing the same tasks over and over like writing assignments.
* So this project *aims at taking input as a text file and generating a brand new handwritten pdf file from it*.


Of course, this project is highly documented for your convinience so that you can tweak it as you wish. You may also suggest changes by forking this repo and creating a pull request or opening an issue.



### Built With

* [Python3](https://www.python.org/)
* [Jupyter notebook](https://jupyter.org/)





<!-- GETTING STARTED -->
## Getting Started

Grab a python3 distribution and run the source code with the help of jupyter notebook. Both of these get set up if you install anaconda distribution on your system.

<p align="center">
    **OR**
</P>

Just install any python3 distribution, install the dependencies and run `textwritten.py` in the `src` folder.


### Prerequisites

* path.py
* numpy
* Pillow

After installing anaconda, run in the `src` directory 
```sh
pip install -r requirements.txt
```
in your terminal to install all the required dependencies and modules. Else they get installed automatically if you run the ipython notebook.

### Installation

1. Clone the repo
```sh
git clone https://github.com/shie-ld/textwritten.git
```
2. Install required modules
```sh
cd src
pip install -r requirements.txt
```
3. Run the ipython notebook in `src` folder 

Don't forget to put in the `INPUT_FILE` from which you want to generate pdf and resulting `OUTPUT_FILE` just above the `main()` function in the end of the notebook. . Check current directory and viola, you have generated the required pdf.

<p align="center">
    **OR**
</P>

3. Run the `textwritten.py` in the source folder with correct options and arguments.





<!-- USAGE EXAMPLES -->
## Usage
### Using Jupyter Notebook:

```sh
INPUT_FILE = 'infile.txt'
OUTPUT_FILE = 'outfile.pdf'

main()
```

### Using CommandLine:

```sh
OPTIONS
-i | --input : specify the input text file, required
-o | --output : specify the output pdf file, default is out.pdf
```


So practical usage will look like:
```sh
# cloning the repo in your machine
git clone https://github.com/shie-ld/textwritten.git

cd textwritten/src

pip install -r requirements.txt

python3 textwritten.py -i hello.txt -o output.pdf

```

And you are good to go:smile:

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/shie-ld/textwritten/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Project Link: [https://github.com/shie-ld/textwritten](https://github.com/shie-ld/what-is-git)


Rudresh Dixit : 00rudreshdixit@gmail.com





<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/shie-ld/textwritten.svg?style=flat-square
[contributors-url]: https://github.com/shie-ld/textwritten/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/shie-ld/textwritten.svg?style=flat-square
[forks-url]: https://github.com/shie-ld/textwritten/network/members
[stars-shield]: https://img.shields.io/github/stars/shie-ld/textwritten.svg?style=flat-square
[stars-url]: https://github.com/shie-ld/textwritten/stargazers
[issues-shield]: https://img.shields.io/github/issues/shie-ld/textwritten.svg?style=flat-square
[issues-url]: https://github.com/shie-ld/textwritten/issues
[license-shield]: https://img.shields.io/github/license/shie-ld/textwritten.svg?style=flat-square
[license-url]: https://github.com/shie-ld/textwritten/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/rudresh-dixit-11a15618a/








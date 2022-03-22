# carbon

![carbon](https://s6.uupload.ir/files/carbon_r7tm.jpg)

## Description

**carbon** is a free and open source software for create shortened URL for free.
you can use carbon with github pages or use it on your own server to create urls.

to run carbon you will need python3.
config of carbon are set as default so you don`t need to re-configure it.

carbon name came from the shape of carbon molecule!
which each atom linked to each other and make a hexgon.


## Usage

1. clone the repo `https://github.com/shabane/carbon.git`
2. `cd carbon` and then just type `./carbon.py`
3. carbon will prompt you a cli which will ask you for *link, name, title, desctipiton and a question*
4. the question is that whenever user rich the url, he/she should click on a button to open the link?, or just redirect the user to the actual link immediately?.


## Config

all setting are in a single file called `config.py`.
read the config [doc](documentation/config.md) to learn about it`s variable.


## Deployment

- [read how to config carbon on the server with *nginx*](documentation/deploy_nginx.md)
- [how to config carbon with github pages for free](documentation/deploy_github_pages.md)


## Theme

each theme directory will save under the `theme` directory by default.
default theme is `carbon_default` which is configured in the config.
you can save theme in any directory, but just don't forget to change the `DIR` variable in the `config.py` file.

to write your own theme read the [doc](documentation/theme.md).


## Examples

- firest example is [https://shabane.github.io/carbon/on_open](https://shabane.github.io/carbon/on_open). whene you open this, you will redirect to the actual link.

- and the second one is [https://shabane.github.io/carbon/click_open](https://shabane.github.io/carbon/click_open) which will ask you to click on a button to open up the actual link.


## Contribute

to contribute on this project all you need is read the [code](documentation/code_doc.md) doc


## Documentation

you can read full documentation in [this link](documentation/index.md)

**contents**

|number|pages|
|:----:|:---:|
|   0  |[index](documentation/index.md)|
|   1  |[configs](documentation/config.md)|
|   2  |[deploy on github pages](documentation/deploy_github_pages.md)|
|   3  |[deploy on server](documentation/deploy_nginx.md)|
|   4  |[how to make your own theme](documentation/theme.md)|
|   5  |[development document](documentation/code_doc.md)|
|999999| [Donate!](documentation/donate.md)|


## Thanks

thank you for choosing carbon. i hope this program work as well as it should.
if you think this stuff worse it, if it's possible for you, i need donate to keep working on my
stuff, if you can please concider [any donate](documentation/donate.md). **thank you**.
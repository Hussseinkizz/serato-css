# Contributing To Serato CSS

## 👍  Thanks for your interest and contributions in advance

And just a re-assurance, Serato CSS is a mini futuristic and predictable sort of well crafted CSS framework built on Open Props CSS library and flex with beginners in mind. So this is a contribution guidline if you think such a framework is cool or at least it should be

## How do users use this framework?

They use the usual conventional ways like using a cdn or installing into their projects or even download a css file and then import that. Then they can use classes from the framework to get a couple of this done, for example adding a class of `button-primary` to an html element's classes on the class attribute gives out a cool well styled button and that's it

> Note that users can always find additional documentation over the docs!

## Getting started as a contributor

So basically, you clone or dowonload the source code from the repo and run some commands with npm or yarn  and then start adding in some css, here are the details of how exactly...

### Setup

```shell
git clone git@github.com:Hussseinkizz/serato-css.git
yarn
yarn dev
```

From the snippet above, the `git clone` command clones and pulls the source code onto your machine, then the `yarn` command installs all required dependencies required to compile and convert all the scss into css for us and finally the `yarn dev` command starts the dev environment with live reloading in broswer and recompilation whenever a change occurs in the html or scss files in the project and there you can start adding in cool css into the framework but before that let's fisrt get to know how everything is organized in the project.

## How things are organized

> Well, there various files and folders in the project, but so far the scss and public folders are what we need to attend our attention to.

Now, all source scss files are in the scss folder and respectively the output css is all in the public folder.

Meanwhile in the scss folder we find the following folders and files

### The folders

* animations - contains animations
* base - contains resets, and experimental css
* components - contains component level css, such as buttons, cards, etc
* helpers - conatins all the  helpers or utilitity class css, such as spacing, typography, etc
* layout - contains css for different layout styles, such as holy grail layout
* plugins - contains all css pulled from community, such as hvr-css a css library we're using for `on-hover` animations
* themes - contains anything to do with colors, such as famous brands colors, gradients etc
* utilities - contains functions, mixins and all stuff like global variables which is used in conjunction with others

### The files

* dump.scss - This is where you can put those lines of code you don't want to lose yet though you don't need them to be in the ideal either, it's like a code recycle bin
* test.scss - This where you put scss you want to test in isolation and get to see what it compiles to, you can see the ouput in `/pulbic/css/test.css`
* serato.css - This is the guest of honor of the party where every sass partial is imported and compiled into css, it's the entry point for everything.

### And again

Every folder contains scss partials and those get imported into one file which is then imported into the `serato.scss` file for overall compilation into css. Usually such file inherits the name of the folder to show that it's the entry point of that folder and that's all about how things are organized.

## Adding in stuff or making a change

💡  First realize what you want to work on or improve, for example if you want to add a new component, say a `footer` component, then that's categorized in components therefore it should be in components folder or to be exact `scss/components/_footer.scss`, so go to components and create that as a sass partial and then import it into the entry point of that folder which usually takes the name of the folder, in this case the `components.scss` file for example, and in this scenario, it would be like;

``` scss

@forward 'buttons';
@forward 'cards';
@forward 'footer'; // your new component!

```

## After making a change, acknowledge it

So after adding or changing some stuff, you need to also acknowledge it in the `CHANGELOG.md` file and basically you just follow the convention there already, duplicate down the last block in there, and change some stuff like the dates and then add a simple line telling what you have just added in for example;

```md

## [1.2.5] - Serato Version 2 - New Melody, 2022-05-19

- css: created the footer component
- dev: changed CHANGELOG.md to CHANGELOG.old.md and then CHANGELOG-v2.md to CHANGELOG.md

```

> Usually `dev` or `css` means the change affects the dev experience or it's just a bare css improvement respectively.

## That's it

Now make your pull request and we merge it in and thanks for your contribution and we will make sure the community credits your work, just keep things cool and simple for beginners to jump into, and feel free to contact me, on twitter at [Hussein kizz](https://twitter.com/Husseinkizz) for any inquiries, take care!

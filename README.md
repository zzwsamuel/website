# GitHub Pages Workshop
Essex, 2h

The plan was to:

1. make a **very basic website** on GitHub;
2. use a **custom theme** to make a website;
3. look into a **multilingual theme**;
4. demonstrate **localhost development**;
5. SWOT;
6. use the README.md file as your log;

We will jump straight to nb 3 and focus on creating a website with a multilingual theme.

## 1. very basic website
### 1.1 Home page
- create a [GitHub](https://github.com/) account;
- setup a repository (repo);
- turn this repo into [GitHub Pages](https://pages.github.com/) in the Settings of the repo (not the account settings);
- add and edit the 'index.md' file with markdown syntax;
- [kproxy.com](kproxy.com);

### 1.2 html and md
- add and edit an 'index.html' file with html syntax;
- compare the .html and the .md files;
- add another file, 'portfolio.md' and hyperlink two files;
- html vs markdown ([html](https://duckduckgo.com/?q=html+syntax&t=brave&ia=cheatsheet) vs [md](https://guides.github.com/features/mastering-markdown/));
	- markdown is a shortcut to html;
	- markdown is easier to remember than [html](https://duckduckgo.com/?q=html+syntax&t=brave&ia=cheatsheet);
	- some simple markdown editors on the computer are [ByWord](https://www.bywordapp.com/) or [MacDown](https://macdown.uranusjr.com/);
	- there are slightly different versions of markdown syntax, stick to GitHub markdown for now;

### 1.3 Styling

- add a new file to your repo called 'style.css' with the following content:

```   
body {
  margin: 0 auto;
  max-width: 35em;
  padding: 0.5em 0.5em;
  color: #566b78;
  line-height: 1.3;
}
```

- link this 'style.css' file to your 'index.hml' file. Have only the following lines in your 'index.html' file:

```
<head>
<link rel="stylesheet" href="style.css" />
</head>
<body>
<h1>header 1</h1>
<p>text</p>
</body>
```

- let's add an image:
	- find an [image](https://duckduckgo.com/?q=translation&t=brave&iax=images&ia=images);
	- get it's url link;
	- add this code to your 'index.html' file's body part:

```
<img src="http://i.huffpost.com/gen/1554459/images/o-COMPUTER-TRANSLATE-facebook.jpg" alt="Translation">
```
- images on the website atm are not responsive, so your image might be sticking out. To make the website a bit more responsive, please add the following code to your 'style.css' file:

```
/* responsive images */
img {
    width: 100%;
    height: auto;
}
```

Then wait a bit and reload your website. While waiting, let's check [this](https://jgthms.com/web-design-in-4-minutes/) out for some quick customisation ideas.

Perhaps try adding an image to the .md file with the .md syntax.

### S
quick, fast, free, simple, adds to your technical skills;
### W
waiting time for updates to be live;
### O
there is plenty of space to grow (see later);
### T
might not be for you...

<br>

## 2. custom themes
### 2.1 where?

* [https://jekyll-themes.com/](https://jekyll-themes.com/)
* [http://jekyllthemes.org/](http://jekyllthemes.org/)
* [https://github.com/jekyll/jekyll/wiki/Themes](https://github.com/jekyll/jekyll/wiki/Themes)
<br>

### 2.1 theme 1

* choose a theme within the Settings of your repo;
* check how this has changed your folder;

good: quick;  
bad: you still cannot change much, takes too long initially;

### 2.2 theme 2 (minima)

* visit [this](https://github.com/jekyll/minima) repo;

#### 2.2.1 fork copy
* fork it;
* in settings, for GitHub Pages, choose Master Branch for source;
* open the url (we might need to wait a bit);
* copy/paste your url in your repo's top header for a shortcut [click on Edit];

#### 2.2.2 download and upload
* download ZIP of the repo;
* create a new repo and upload all files (make sure you copy hidden files as well;

This way you don't have all the options that come with the fork.

#### 2.2.3 other ways?
* there are;

<br>

## 3. multilingual theme
We will look at Jekyll Basic theme the from [Wiredcraft](https://github.com/wiredcraft).

- github, jekyll and wordpress;
- find the link for website version of this repository: [https://krisztian-hofstadter-tedor.github.io/jekyll-multiling/](https://krisztian-hofstadter-tedor.github.io/jekyll-multiling/)
- download ZIP version to computer;
- create a GiHub account (verify email);
- create a repo (no need for readme.md);
- unzip what you downloaded and delete 'site' folder;
- upload all folders and files to your newly created repo (hidden files are not needed);
- while the site is created on your repo let's have a look at the site in my repo again, the one that is built;
- when your files are uploaded, visit repo settings and turn repo into GitHub pages;
- visit the url (probably not ready yet - try kproxy.com);
- copy/paste the website's url in your repos description for a shortcut;
- edit url in 'config.yml', change it to your new website's url;
- we might need to wait a bit (sometimes longer) for everything to be built;
- in the meantime, let's explore my site again, perahps with the localhost files;
- if ready, lets' edit a few things.


## 4. localhost dev.

Briefly mention Atom, Ruby, etc.
<br>

## 5. SWOT
### S
- fast;
- cheap;
- easy to scale up;

### W
- might be a steeper learning curve;

### O
- gain understanding of the GitHub system;
- gain understanding of basic html and markdown syntax;

### T
- can be time consuming;

<br>
<br>

## 6. Log

- use the readme.MD for your log/todo, examples [1](https://github.com/krisztian-hofstadter-tedor/bcmi), [2](https://github.com/krisztian-hofstadter-tedor/OpenBCI-SuperCollider);

<br><br>

## Resources
### Github
* [Fork or Clone](https://stackoverflow.com/questions/6286571/are-git-forks-actually-git-clones)
* Getting Sh*t Done with Jekyll: [Youtube](https://www.youtube.com/watch?v=No7dtPtbtcE)
* Designing Fast Websites With Jekyll //JekyllConf 2016: [Youtube](https://www.youtube.com/watch?v=TteAQq25_Ns)

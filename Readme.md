# Hello World!

Good, you are finally here. This is your personal, **Hello World** repository. Inside of it, you are going to create two different Hello World Projects, one in HTML and one in Javascript.

### Prerequisites

Of course, you can just start coding, but for an enjoyable experience, you'll need some tools. And that is the reason why this README file exists.

##### 1. Get yourself a text editor
As you might already know, you can't just write code in Word or Pages. Code needs to be written in something called "Plain Text". Plain text is text without any formatting, just text.

I recommend you to use [Atom](https://atom.io/) as your text editor, it's free.

##### 2. Javascript Node
To run Javascript outside of your browser, we need something called "Node". Node is a JavaScript runtime, we'll teach you more about it later.

##### 3. Git
This whole project is managed with [Git](https://git-scm.com/). Git is a version control system, by keeping track of historical points of the project, allow people to collaborate and it also allows to track who did what. Simple.

I recommend you to use [GitHub Desktop](https://desktop.github.com/) for this, as it has a painless integration with GitHub.

### Cloning the repo

#### ...with GitHub Desktop
> TODO: @Gerd, add steps for GitHub Desktop

> TODO: failed attempt of Jessica trying to explain how to do this on the command line... this is too difficlut to summarize as "simply do A, then execute B, you're done with C now..."
<!-- #### ...with the command line
If you want to experiment with the command line, go ahead, no one's stopping you.
Search for and launch the Terminal application on you Mac, you will be greeted with Bash:

##### 1. check to make sure you have `git` installed.  
  Type the following without `$`, the dollar sign is only there to signify the beginning of a command.
  ```
  $ which git
  ```
  If anything is printed, great, you can continue. Otherwise, you will need to [install `git`](https://codeburst.io/installing-git-for-the-first-time-on-mac-osx-bf9c513af2b8) first.

##### 2. head to where you'd like to keep this project.  
  You can do so by using the `cd`,  _change directory_, command. It allows you to navigate to anywhere in the file system. 
  > note: directories are commonly refered to as folders

  Say I'd like to keep my project in `geek-force` folder in ` Docements`, I can navigate there by:
  ```
  $ cd Docements/geek-force
  ```

##### 3. Now you can clone the repository from GitHub
  

- `ls` - _prints list of files in directory_  
executing `ls`, it should print 
- `pwd` - _print working directory_, tells you where you are -->

---

### HTML Hello World

First, we got to open your project folder inside of atom. Once you opened atom, press `⌘+⇧+O` to open a new project and navigate to where you cloned your project to. You can close all tabs that open. In the sidebar, you should be able to see five things:
- one `.git` folder
- a `.gitignore` file
- one `html` folder
- one `js` folder
- this `Readme.md` - now you can choose to continue reading this tutorial inside of Atom by opening it and Markdown Preview, which you can get by pressing `⌘+⇧+P` for the command palette and searching for `Markdown Preview: Toggle`.

We are going to edit the only file in the html folder. Open it up!

You should see something like
```html
<html>
    <head>
        <title>Hello World!</title>
    </head>
    <body>
        <!-- insert your hello world after this line -->

    </body>
</html>
```

This is the basic structure of an HTML file, it consists of any depth of nested elements, the word "hierachical" might come to mind. Most of the elements consist of an opening tag, enclosed in `<>`,  content (which can include more elements) and the corresponding closing tag, which is the opening tag with a `/` added after `<`.

The `HTML` tag encapsules head and body. Everything inside of `body` is going to be rendered onto the page, while everything in the `head` tag are additional information you supply the browser. In this case, the `title` tag tells the browser the title of the page (pretty self-explanatory), which is typically displayed as the name of the tab.

Now, right below the comment, add "Hello World" into the file. Then save (`⌘+S`) and navigate to the file in Finder. Double click it, or choose to Open With your browser. You should see `Hello World`is now displayed on the page. 

Congratulations! You have just made your first Hello World!

You might have noticed the content of Line 6 is not displayed, that's because it's a comment, wrapped between `<!--` and `-->`. Comments are meant as notes for people authoring and editing the web page, like you and I.

> Don't go around telling people you program, yet. HTML is a markup language, not a programming language.

---

### Formatting Text

Now, there are a lot more you can put into body to have browsers display than short messages. For instance, anything formatting word processors, like Microsoft Word, support, you can express in an HTML document with tags as well.

> TODO: examples & explanation
> TODO: a task

##### reference
[Mozilla's HTML Cheatsheet](https://developer.mozilla.org/en-US/docs/Learn/HTML/Cheatsheet) includes common tags you might want to use to format text. For anything else, like a table, don't be afraid to look it up!

---

### Adding Cool Elements

But before we leave you in the world of tags, you should know of a few concepts to check against for sanity:

##### 1. block vs inline element
- Block level elements form a visible block on a page, they will appear on a new line from content before, and any content after will also appear on a new line. These tend to be structural elements on the page, elemets like `<p>` (paragraph), lists, navigation menus.
- Inline elements surround only small parts of content, typically inside a paragraph of text, for example, `<a>` element (hyperlink) or emphasis elements such as `<em>` or `<strong>`.

Simply put, inline elements can be nested in block elements, while block elements are not allowed to be nested in inline elements.

##### 2. empty elements
Some elements need not to have content to function, such as when embedding an image:
```html
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/1200px-HTML5_logo_and_wordmark.svg.png">
```
In which case, only the opening tag is needed, serving as a placement anker.

##### 3. attribute
You also see that this tag has an attribute, which are extra information placed inside of the opening tag. Most attributes are specified in key-value pairs, the possibly keys vary depending on the specific element, and the value always have to be enclosed in `""`. Here we are specifying the source of the image to be embedded in in URL. 
<!-- We can also specify location of the desired image relative from this very HTML file, if we wanted to include a file which does not exist elsewhere. -->

Great! Now you can do some serious coolness with HTML markup!

> TODO: task
> TODO: reference

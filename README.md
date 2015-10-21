## Send Tweets From Anyone Anytime
### AKA: Maybe don't believe everything you read on the internet

**But trust us...this you can believe. Even Jimmy Fallon loves programming! He tweeted about Flatiron!!**
<img src="https://s3.amazonaws.com/after-school-assets/jimmy-fallon-tweet.png" alt="Jimmy Fallon tweets about loving Flatiron School">

**And One Direction...**

<img src="https://s3.amazonaws.com/after-school-assets/one-direction-tweet.png" alt="One Direction tweets about Flatiron School">

**And Drake...**

<img src="https://s3.amazonaws.com/after-school-assets/drake-tweet.png" alt="Drake tweets about Flatiron School">

**And Ed Sheeran...**

<img src="https://s3.amazonaws.com/after-school-assets/ed-sheeran-tweet.png" alt="Ed Sheeran tweets about Flatiron and Programming">

**And so did Taylor Swift!!**

<img src="https://s3.amazonaws.com/after-school-assets/taylor-swift-tweet.png" alt="Taylor Swift Tweets about loving programming">

Programming is so cool that pretty much every celebrity everywhere has tweeted about it. 

### What In the World?
So you're really supposed to believe that everyone loves programming with Flatiron? That can't even be possible, but those images sure prove they did!! So how did we do that? And better yet how can you prank all your friends in just the same way?

Basically, we played with the code that makes up the styling and content of these Twitter pages. We didn't change it on Twitter's servers or change it for *everyone* but we did change it on our browsers, which makes it easy for us to take screenshots. #picsoritdidnthappen

###Let's Get Started

####Step 1:

Developer Tools exist in the Firefox browser, Chrome browser, and Internet Explorer (8 and up). Make sure you download one of these browsers if you don't already have one.

All three of these browsers have incredibly powerful Developer Tools that allow you to see the nuts and bolts of every website. Basically, we can see and locally edit the HTML and CSS. 

The following steps will work the exact same for Chrome of Firefox. To access the Internet Explorer Developer Tools, open up a browser window and hit the `f12` key. The following examples will be using Chrome, but the Firefox and Internet Explorer tools operate in the exact same way!

#### Step 2: 

Go to the Twitter page of your favorite celebrity. If your school blocks Twitter, feel free to go to your favorite news site and change some headlines. We'll be using Jimmy Fallon Twitter as an example. Once you're on that page, you'll want to hover your mouse of the text of their first tweet, and right click.

<img src="https://s3.amazonaws.com/after-school-assets/jimmy-fallon-hover.png" alt="right click on text of tweet" width="500px" align="middle">

#### Step 3:

Select `Inspect Element` from the dropdown options.

<img src="https://s3.amazonaws.com/after-school-assets/jimmy-fallon-inspect-element.png" alt="Select inspect Element" width="500px" align="middle">

This will bring up Chrome's Developer Tools, where we can start to play around with both the actual text on the page, as well as the HTML and CSS of the page.

<img src="https://s3.amazonaws.com/after-school-assets/jimmy-fallon-developer-tools.png" alt="CHrome developer tools" width="500px" align="middle">

#### Step 4:

Because we right clicked on top of the text of the tweet (the text that we want to change), the Developer Tools drop us right into the code for that text on the page. 

The should should start with something like this `<p class="TweetTextSize TweetTextSize--16px js-tweet-text tweet-text"`...

From there, you can right click on that code and select either `Edit as HTML` or `Edit as Text`. 

<img src="https://s3.amazonaws.com/after-school-assets/jimmy-fallon-edit-html.png" alt="edit as html" width="500px" align="middle">

If you're using Chrome and you can't find that selection of the text, you can select the search icon in the top left corner of the Developer Tools.

<img src="https://s3.amazonaws.com/after-school-assets/dev-tools-search.png">

Once you've selected the search icon, you can click on any text on the website (like the text of the tweet) and it will drop you to that portion of the code in the Developer Tools.


#### Step 5: 

Once we select `Edit as HTML`, a text box appears where we can start to edit the text on the page and actually type. 

<img src="https://s3.amazonaws.com/after-school-assets/jimmy-fallon-tweet-text.png" alt="tweet code" width="500px" align="middle">

We want to keep the HTML tags that surround the text, but everthing highlight in blue above, we can delete so we're just left with this:

<img src="https://s3.amazonaws.com/after-school-assets/jimmy-fallon-editing.png" alt="deleting html" width="500px" align="middle">

#### Step 6:

Now we can start typing our own text!! Once you're done typing, just click off to the side and see your text appear.

<img src="https://s3.amazonaws.com/after-school-assets/jimmy-fallon-completed.png" alt="completed editing tweet" width="500px" align="middle">

Remember, you will lose your text changes as soon as you refresh the page. 

#### Step 7:

See if you can play around with the images in a tweet to replace them of pictures of yourself. 

### Step 8: Share Share Share!
Finished your work? So proud of you want to show it off to the world? Share a screenshot of your own twitter hack with **\#flatironcodeclub** **\#twitterhack**


### Tell Me More About The Code

Ready to learn how to actually write your own HTML and how the text of a website actually shows up? Keep reading to learn how!

Every single website in existence is made up of at least two different programming languages - HTML and CSS. HTML, which stands for hypertext markup language, is a language that defines the content of the page. It's a programming way of marking the specific title of your page, images, articles, lists, etc. This is useful for Google to know what search keywords should display our website. CSS, which stands for Cascading Style Sheets, is the language used for styling a website. We use CSS to change font colors and styles, as well as layout and positioning of different items on the page. Without these two languages, websites wouldn't look the way they look or deliver content to us the way they do. Pretty powerful stuff. Today, we're just focusing on HTML

What if we want to write our own website using HTML? The first thing that we need to do is create our own directory to store our code in Nitrous.

#### Step 1:

Go ahead and open your IDE in Nitrous, by going to Nitrous.io. You should see a page that looks like this: 

<img src="https://s3.amazonaws.com/after-school-assets/open-ide.png" alt="Open Nitrous IDE">.

### Step 2:
You should click on the blue button labeled `IDE` which will take you to your workspace. 

There, you should see something like this:

<img src="https://s3.amazonaws.com/after-school-assets/nitrous_terminal.png" alt="nitrous">

### Step 3:
You'll want to click on the terminal, the long black box at the bottom of the screen. In terminal, type the words `mkdir my_website` and hit enter. `mkdir` is a command that will make a directory (directory and folder are the same thing) for you.

<img src="https://s3.amazonaws.com/after-school-assets/mkdir.png">

Sometimes Nitrous is slow to show a new directory. If the directory doesn't show up in the file navigator right away, click the arrow next to `nitrous` in the navigator twice. Once to close the file, and once to reopen. 

### Step 4:

Next, we need to move inside of the directory we just made (so that we can create files and edit existing files) by entering in terminal `cd my_website`. `cd` stands for change directory. 

### Step 5: 

Inside of that directory, we need to create our own HTML file. In terminal enter: `touch index.html`. `touch` is a command that will create and save a file for you, in this case a file named `index.html`.

<img src="https://s3.amazonaws.com/after-school-assets/touch.png">

### Step 6:

You'll want to have your HTML file open in the text editor so that you can add text to a page, as well as the HTML files open in the browser. You can open it in the text editor by double clicking on the name of the file in the file navigation on the left side. 

### Step 7:

When you're writing HTML for a website, you don't expect your user to actually open a text editor and look at the code that makes up the website. They want to actually view the website in the browser. 

In fact, most people probably don't even want to think about the code that makes up the website. In order to view our HTML file, which is the text of your website, in the browser, you have to start a server. A server is basically a computer that continually runs the code you wrote so that people can view our site. Because our sites are still a work in progress, this server won't permanently host our site. It won't give us a URL to send to our friends, but it will let us view the fruits of our labor like it is a real site. To view your code in the browser, in terminal in Nitrous, inside of the `my_website` directory, copy and paste the line below into terminal:

```bash
python -m SimpleHTTPServer 3000
```

 This command starts up a server automatically for you so you can view the website. If you see something like this, then you're good to go:

<img src="https://s3.amazonaws.com/after-school-assets/started-server.png">

 Once you have the server running, select `preview` and then `port 3000`, just like in the image below.

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-preview.png" alt="nitrous preview">


This little server we just started is just a test server so that you can write HTML and see what it looks like in the browser. It hasn't permanently hosted your site so that other people can visit it. 


To stop your server once you're done testing, you can just hit `control` and then `c`, so that you're pressing both at the same time. This will work on both Mac's and PC's. If you don't stop your server, you won't be able to use your terminal again to create any more directories or files, or work on any new labs. 

If you would like to start your server back up again, you just simply enter:

```
python -m SimpleHTTPServer 3000
```

###Let's Write Some HTML. 

HTML is made up of tags that surround pieces of content. Let's say we wanted to put this paragraph from the Wikipedia page about ice cream on our page:

```html
<p> Ice cream (derived from earlier iced cream or cream ice[1]) is a frozen food, typically eaten as a snack or dessert, usually made from dairy products, such as milk and cream, and often combined with fruits or other ingredients and flavours. It is typically sweetened with sucrose, corn syrup, cane sugar, beet sugar, and/or other sweeteners. Typically, flavourings and colourings are added in addition to stabilizers. The mixture is stirred to incorporate air spaces and cooled below the freezing point of water to prevent detectable ice crystals from forming. The result is a smooth, semi-solid foam that is solid at very low temperatures (<35 °F / 2 °C). It becomes more malleable as its temperature increases. </p>
```

In this example, we have an opening p tag `<p>` followed by the text of the paragraph, and finally the closing p tag `</p>`. Pretty much every HTML tag has an opening tag and a closing tag.  The content to be displayed on the page goes in the middle. The opening tag, content, and closing tag is called an HTML element. This way, the browser knows that piece of content is a paragraph.


Try copying and pasting this simple site example into `my_website/index.html`. You'll want to save the chanages to the file, and then refresh the page in the browser to see your code displayed! Feel free to play around with the text and the tags!

```html
<!doctype html> 
<!-- The doctype tells the browser which version of HTML we're using -->
<head>
 <!--  The head is the brains of the page. It contains information about the language used, the subject matter of the page and other descriptive information about the page. Nothing in the head shows up in the actual website -->
 <title> I Love Coding </title>
 <!-- The title tag creates the text that appears on the tab in the browser -->
</head>
<body>
  <!-- In the body, we put all the text we want to appear in our website -->
  <h1> Programming Is My Super Power </h1>
  <!-- The h1 tag marks the actual title of our page. It's a level 1 header. Every page should only have one h1 tag. -->
  <h2> Programming lets me build whatever I want</h2>
  <!-- h2 tags are smaller than h1, and are used for sub-headers. There are h3, h4, h5, and h6 tags too, which all get progressively smaller in text size -->

<img src="https://s3.amazonaws.com/after-school-assets/coding-super-power.jpg" alt="Super Power">
  <!-- the img tag only has an opening tag, and no closing tag. This tag has an attribute src which stores the source of the image, in quotation marks, after the equals sign. It also has an attribute `alt` which stands for alternate text. This is the text that will show up if your image breaks and doens't show up on your page -->
</body>
```

Aside from the `img` tag, every HTML element has an opening and closing tag.   There are many many many more HTML tags than the few demoed above. 

The Mozilla Developer Network has a great resource with [details about every HTML tag](https://developer.mozilla.org/en-US/docs/Web/HTML/Element). Don't be shy to play around with your code!

### Want To Learn More?

1 [HTML5 Guide](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) - This page gives you specific details on the latest version of HTML, HTML5, which has a lot of cool new tags you can use, like `<audio>` for embedding audio clips and songs in your site.

2 [W3Schools Intro](http://www.w3schools.com/html/html_intro.asp) - W3 pops up a lot when Googling topics related to HTML. They keep it short and sweet, giving you just what you need to get your HTML tags right.

3 [Mozilla Intro](http://docs.webplatform.org/wiki/guides/the_basics_of_html) - Another good walkthrough on the basics of HTML.


















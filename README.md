## Send Tweets From Anyone Anytime
### AKA: Maybe don't believe everything you read on the internet

**But trust us...this you can believe. Even Jimmy Fallon loves programming! He tweeted about Flatiron!!**
<img src="https://s3.amazonaws.com/after-school-assets/jimmy-fallon-tweet.png" alt="Jimmy Fallon tweets about loving Flatiron School">



**And One Direction...**

<img src="https://s3.amazonaws.com/after-school-assets/one-direction-tweet.png" alt="One Direction tweets about Flatiron School">

**And so did Taylor Swift!!**

<img src="https://s3.amazonaws.com/after-school-assets/taylor-swift-tweet.png" alt="Taylor Swift Tweets about loving programming">

Programming is so cool that pretty much every celebrity everywhere has tweeted about it. 

### What In the World?
So you're really supposed to believe that everyone loves programming with Flatiron? That can't even be possible, but those images sure prove they did!! So how did we do that? And better yet how can you prank all your friends in just the same way.

Basically, we played with the code that makes up the styling and content of these Twitter pages. We didn't change it on Twitter's servers or change it for *everyone* but we did change it on our browsers, which makes it easy for us to take screenshots. #picsoritdidnthappen

###Let's Get Started

####Step 1:

Download the Chrome browser if you don't already have it.

Chrome has incredibly powerful Developer tools that allow you to see the nuts and bolts of every website. Basically, we can see and locally edit the HTML and CSS.

#### Step 2: 

Go to the Twitter page of your favorite celebrity. We'll be using Jimmy Fallon as an example. Once you're on that page, you'll want to hover your mouse of the text of their first tweet, and right click.

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


#### Step 5: Once we select `Edit as HTML`, a text box appears where we can start to edit the text on the page and actually type. 

<img src="https://s3.amazonaws.com/after-school-assets/jimmy-fallon-tweet-text.png" alt="tweet code" width="500px" align="middle">

We want to keep the HTML tags that surround the text, but everthing highlight in blue above, we can delete so we're just left with this:

<img src="https://s3.amazonaws.com/after-school-assets/jimmy-fallon-editing.png" alt="deleting html" width="500px" align="middle">

#### Step 6:

Now we can start typing our own text!! Once you're done typing, just click off to the side and see your text appear.

<img src="https://s3.amazonaws.com/after-school-assets/jimmy-fallon-completed.png" alt="completed editing tweet" width="500px" align="middle">

Remember, you will lose your text changes as soon as you refresh the page. 

#### Step 7:

See if you can play around with the images in a tweet to replace them of pictures of yourself. 


### Tell Me More About The Code

Every single web site in existence is made up of at least two different programming langues - HTML and CSS. HTML, which stands for hypertext markup language, is a language that defines the content of the page. It's a programming way of marking the specific title of your page, images, articles, lists, etc. This is useful for Google to know what search keywords should display our website. CSS, which stands for Cascading Stylesheets, is the language used for styling a website. We use CSS to change font colors and styles, as well as layout and positioning of different items on the page. Without these two languages, websites wouldn't look the way they look or deliver content to us the way they do. Pretty powerful stuff. Today, we're just focusing on HTMl

What if we want to write our own website using HTML? The first thing that we need to do is create our own directory to store our code in Nitrous.

In terminal, enter `mkdir my_website` 

Inside of that directory, we need to create our own HTML file. In terminal enter: `touch index.html`. 

HTML is made up of tags that surround pieces of content. Let's say we wanted to put this paragraph from the Wikipedia page about ice cream on our page:

```html
<p> Ice cream (derived from earlier iced cream or cream ice[1]) is a frozen food, typically eaten as a snack or dessert, usually made from dairy products, such as milk and cream, and often combined with fruits or other ingredients and flavours. It is typically sweetened with sucrose, corn syrup, cane sugar, beet sugar, and/or other sweeteners. Typically, flavourings and colourings are added in addition to stabilizers. The mixture is stirred to incorporate air spaces and cooled below the freezing point of water to prevent detectable ice crystals from forming. The result is a smooth, semi-solid foam that is solid at very low temperatures (<35 °F / 2 °C). It becomes more malleable as its temperature increases. </p>
```

In this example, we have an opening p tag `<p>` followed by the text of the paragraph, and finall the closing p tag `</p>`. Pretty much every HTML tag has an opening tag and a closing tag.  The content to be displayed on the page goes in the middle. The opening tag, content, and closing tag is called an html element. This way, the browser knows that piece of content is a paragraph.


Simple Site Example:
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
  <h2> Programming let's me build whatever I want</h2>
  <!-- h2 tags are smaller than h1, and are used for sub-headers. There are h3, h4, h5, and h6 tags too, which all get progressively smaller in text size -->

<img src="https://s3.amazonaws.com/after-school-assets/coding-super-power.jpg">
  <!-- the img tag only has an opening tag, and no closing tag. This tag has an attribute src which stores the source of the image, in quotation marks, after the equals sign. -->
</body>
```


Aside from the img tag, every html element has an opening and closing tag. It's important to keep your styling separate from your HTML. There are many many many more HTML tags than the few demoed above. 

The Mozilla Developer Network has a great resource with [details about every HTML tag](https://developer.mozilla.org/en-US/docs/Web/HTML/Element). Don't be shy to play around with your code!

You can see the fruits of your labor in the browser by entering in terminal: 

```
ruby -rwebrick -e'WEBrick::HTTPServer.new(:Port => 3000, :DocumentRoot => Dir.pwd).start'
```

Once the server is started, you'll want to select `Preview` from the tabs at the top of Nitrous, and then `Port 3000`

### Want To Learn More?

1 [CodeAcademy HTML Tutorial](https://www.codecademy.com/courses/web-beginner-en-HZA3b/0/1?curriculum_id=50579fb998b470000202dc8b) - This tutorial is a great practice to walkthrough all sorts of HTML tags.

2 [HTML5 Guide](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) - This page gives you specific details on the latest version of HTML, HTML5, which has a lot of cool new tags you can use, like `<audio>` for embedding audio clips and songs in your site.

3 [W3Schools Intro](http://www.w3schools.com/html/html_intro.asp) - W3 pops up a lot when Googling topics related to HTML. They keep it short and sweet, giving you just what you need to get your HTML tags right.

4 [Mozilla Intro](http://docs.webplatform.org/wiki/guides/the_basics_of_html) - Another good walkthrough on the basics of HTML.


















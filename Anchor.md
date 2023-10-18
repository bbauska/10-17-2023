### A Link to an Anchor
Links can also be used to jump to other places on the same page, on top of the page, on bottom of page or on a specified title. To create a new anchor, we need to add the id attribute a tag that will act as a reference point. We are using this id attribute to give a name to the anchor and after that we will be able to use it to make a link to this anchor:

```
<h1 id="my_anchor">Title</h1>

<a href="#my_anchor">Go to the anchor</a>
```

Normally, if you click the link, it will take you further down the same page (it will be indicated that the page containing an anchor should be long enough for the scroll bar to move automatically).

To create a top of the page anchor, use the #top anchor, as you can see in the below example. First, add to the id attribute the value “top” and then create the link using #top anchor.

<h2 id="top">Top of page!</h2>
<a href="#top">Go to top</a>

### A Link to Send an Email

If you want that visitors to send you an email, you can use the mailto type of link:

```
<a href="mailto:brianbauska@gmail.com">Send me an email!</a>
```

If you want to have a specific subject in the email, you can add it to the html code using subject= setting :

```
<a href="mailto:octaviaanghel@gmail.com?subject=Important">Send me an email!</a>
```

If you would like that visitors send you an email containing specific text in the body of their message, simply add &body=:

```
<a href="mailto:octaviaanghel@gmail.com?body=Please send me your new catalogs and flyers!">Send me an email!</a>
```

Or combine all the options and allow your visitor to send email with the address, subject and text already entered.

```
<a href="mailto:octaviaanghel@gmail.com?subject=Important&body=Please send me your new catalogs and flyers!">Send me an email!</a>
```

By adding the rel attribute to this tag we specify the relationship between the current document and the linked document. Some values for the rel attribute are:

  * alternate – provides a link to an alternate representation of the document, like print page
  * external – means that the referenced document is not part of the same site as the current document
  * prev/next – the previous/next document in a selection
  * author – Provides a link to the author of the document
  * license – Provides a link to licensing information for the document
  
The hreflang attribute of the <a> tag should include a reference to itself as well as to all the pages that serve as alternates for it. If we want to link to a Spanish version of a website, in our case https://www.amazon.com, the hreflang attribute for your homepage might look like this:

```
<a rel="alternate" href="https://www.amazon.com/" hreflang="ES" AMAZON</a>
```

If you want to connect internally to another page of your web site, you do not have to specify the full address, but only the file name:

```
<a href="https://www.amazon.com/gift-cards">Gift Cards</a>
```

The target attribute – specifies how the landing pages should be opened and the target document could take one of the values listed below:

  - _blank – Opens the linked document in a new window or tab <a target=”_blank” href=”https://www.amazon.com/”>AMAZON</a>
  - _self – Opens the linked document in the same frame as it was clicked (this is default value) <a target=”_self” href=”https://www.amazon.com/”>AMAZON</a>
  - _parent – Opens the linked document in the parent frame <a target=”_parent” href=”https://www.amazon.com/”>AMAZON</a>
  - _top – Opens the linked document in the full body of the window <a target=”_top” href=”https://www.amazon.com/”>AMAZON</a>

The download attribute specifies that the target will be downloaded when a user clicks on the hyperlink.

```
<a href="flower.rar" download Download File</a>
```

You can set the name for your downloaded file like this:

```
<a href="flower.rar" download="My flower archive">Download File</a>
```

The goal of the HTML type attribute is to specify the content type of the corresponding element when used within the <a> tag. HTML type attribute supports a, button, input, link, object, param, script, style elements.

```
<a type=”media_type”>, where media_type could have different kinds of types:
```

 - application
 - audio
 - font
 - example
 - image
 - message
 - model
 - multipart
 - text
 - video
 
As an example of using the type attribute is listed below:

```
<a href="https://www.google.com" type="text/html" Google.com</a>
```

The anchor text is the visible words that hyperlinks display when linking to another document or anything else on the web. It looks like blue underlined text, but you can change the colors and styles of your site’s link through CSS or HTML.

```
<a href="http://www.tennis.com" style="color:#00cc00">Tennis.com</a>
"Tennis.com"

<a href="http://www.tennis.com" style="background-color:#ffffa0">Tennis.com</a>
"Tennis.com"
```

The anchor text can provide search engines and users with relevant information about the content of the link destination. Search engines use external anchor text, as a mirror of how other people view your page and what your pages can be. You can also make sure that the anchor text you use on your site is one. relevant, descriptive and very useful.

### Types of Anchor Text

In a Search Engine Optimization process, it is very important to use different kind of anchors for increasing the visibility of your website. The main anchor text is the brand names anchor, because if someone is looking your website, it should probably use the name of your company or brand.

**Generic** – “Click here,” “Read more,” “Learn more,” etc. are common generic anchors widely used.

**Images** – When an image is linked, Google will use the text contained in the image’s other attribute as anchor text. It is simple to use an image as hyperlink. We just need to place the existing image element within an anchor element as shown below:

```
<p>Click on the image</p>
<a href="https://informaticaccmb.wordpress.com/"><img src="painting.png" style="width:250px; height:150px" alt="Teo's painting"></a>
```

<a href="https://github.com/bbauska/cubeit/blob/main/images/9-9-slide-img-3.jpg">Roswell autopsy</a>

<a href="https://github.com/bbauska/cubeit/blob/main/"><img src="images/9-9-slide-img.jpg" style="width:250px; height:150px" alt="Roswell autopsy."></a>



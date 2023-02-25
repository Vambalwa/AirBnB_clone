0x01. AirBnB clone - Web static
Web static, what?
Now that you have a command interpreter for managing your AirBnB objects, it’s time to make them alive!

Before developing a big and complex web application, we will build the front end step-by-step.

The first step is to “design” / “sketch” / “prototype” each element:

Create simple HTML static pages
Style guide
Fake contents
No Javascript
No data loaded from anything
During this project, you will learn how to manipulate HTML and CSS languages. HTML is the structure of your page, it should be the first thing to write. CSS is the styling of your page, the design. I really encourage you to fix your HTML part before starting the styling. Indeed, without any structure, you can’t apply any design.


Question #0
Is following CSS syntax valid?

body {
    color: #FF0000;
}

* {
    font-size: 14px;
    font-weight: 400
    text-align: center;
}
=No

Question #1
In the following code, is the text Best School red?

css:

h1 {
    color: red;
}
html:

<h1>Best School</h1>

Yes

Question #2
In the following code, is the text Best School red?

css:

h3 span.text,
h1,
div.title {
    color: red;
}
html:

<h1>Best School</h1>
=Yes

Question #3
In the following code, is the text Best School red?

css:

h2 {
    color: red;
}
html:

<h1>Best School</h1>

=No

Question #4
Is the following HTML markup valid?

<html></html>
(elements are correctly tagged, we don’t care about !Doctype here)

=Yes

Question #5
Is the following HTML markup valid?

<html>
    <head>
    </head>
    <body>
        <h1>Best <b>School</h1></b>
    </body>
</html>
(elements are correctly tagged, we don’t care about !Doctype here)
=No

Tips:
“Always close something before opening a new thing”

Question #6
Is the following HTML markup valid?

<html>
    <head>
    </head>
    <body>
    </body>
</html>
(elements are correctly tagged, we don’t care about !Doctype here)
=Yes

Question #7
Is the following HTML markup valid?

<html>
    <head>
    </head>
    <body>
        <img src="logo.png" />
    </body>
</html>
(elements are correctly tagged, we don’t care about !Doctype here)
=Yes

Tips:
<img /> is an empty element

Question #8
Is following CSS syntax valid?

body {
    color: #FF0000;
}

div.filters p.title h2 span.text.big {
    font-size: 20px;
}

=Yes

Question #9
Is the following HTML markup valid?

<html>
    <head>
    </head>
    <body>
        <h1>
            <a href="www.google.com'>Google</a>
        </h1>
    </body>
</html>
(elements are correctly tagged, we don’t care about !Doctype here)

=No

Tips:
Number of quotes is important!

Question #10
Is following CSS syntax valid?

body {
    color: #FF0000;
}

h3,
div.full_text,
div.small_text h4,
div.filters p.title {
    font-size: 20px;
}
=Yes

Question #11
Is following CSS syntax valid?

body {
    color: #FF0000;
}

h3,
div.full_text
div.small_text h4
div.filters p.title {
    font-size: 20px;
}

=Yes
Tips:
, separates multiple selector, without it’s specific selector

Question #12
Is following CSS syntax valid?

body {
    color: #FF0000;
}

* {
    font-size: 14px;
}

=Yes
Tips:
Universal selectors

Question #13
Is following CSS syntax valid?

body {
    color: #FF0000;
}

* {
    font-size: 14px;
    text-align: center;
    margin: 30px 12px 4px;
}
=Yes

Tips:
margin and padding support 4 different syntaxes: margin

Question #14
In the following code, is the text Best School red?

css:

h1 {
    color: green;
}

span.my_title {
    color: red;
}
html:

<h1>
    <span class="my_title">Best School</span>
</h1>

=Yes

Tips:
CSS selector math

Question #15
Is the following HTML markup valid?

<html>
    <head>
    </head>
    <body>
        <h1>
            <a href="www.google.com">Go to <b>Google</b>
        </h1>
    </body>
</html>
(elements are correctly tagged, we don’t care about !Doctype here)
=No

Question #16
Is following CSS syntax valid?

body {
    color: #FF0000;
}

* {
    font-size: 14px;
    text-align: center;

    h1 {
        margin: 30px;
    }
}

=No

Tips:
CSS vs SCSS

Question #17
In the following code, is the text Best School red?

css:

h1 div.title {
    color: red;
}
html:

<h1>Best School</h1>

=No

Question #18
Is following CSS syntax valid?

body {
    color: #FF0000;
}

div.filters h2 {
    font-size: 16px;
}

Yes

Question #19
In the following code, is the text Best School red?

css:

h1 .my_title {
    color: green;
}

.my_title {
    color: red;
}
html:

<h1>
    <span class="my_title">Best School</span>
</h1>
=No

Tips:
CSS selector math

Question #20
Is the following HTML markup valid?

<html>
    <head>
    </head>
    <body>
    <body>
</html>
(elements are correctly tagged, we don’t care about !Doctype here)
=No

Tips:
Each HTML tag must be closed

Question #21
Is following CSS syntax valid?

body {
    color: #FF0000;
}

=Yes

Question #22
In the following code, is the text Best School red?

css:

h1.title {
    color: red;
}
html:

<h1>Best School</h1>
=No

Question #23
Is following CSS syntax valid?

body {
    color: #FF0000;
}

h1.title {
    font-size: 16px;
}

=Yes



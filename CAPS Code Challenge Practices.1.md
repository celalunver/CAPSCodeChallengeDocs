# PROJECT MANAGEMENT (SCRUM) PRACTICES

## Pre "Code Challenge" Discussions

As ETG Consultancy Inc. (from now on stated as "We" or "Etg"), we developed a solution approach before getting to know the rules of Code Challenge for Capital Asset Planning System Modernization (CAPS) Project. We decided to present the Province with two different solutions where one of them would be based on Modern Web Programming stack and the other based on Microsoft Dynamics 365 F&O. In this regard, we prepared a demo project for the sample project given in "Code Challenge.pdf" document using Scrum methodology and modern web stack (Vue.js, postgresql, .net and github). In the mean time, we discussed about a Dynamics 365 F&O approach/solution as well (which we didn't implement this solution).

The roles of the team has been decided as;
- Selami Kul - Product Owner
- Celal Unver - Scrum Master
- Mesut Boztas - Development Team - Dynamics Expert
- Enver Yilmaz - Development Team - Backend, Dynamics
- Ender Yilmaz - Development Team - Backend, Dynamics
- Salim Serdar - Development Team - Frontend
- Tufan Bilge - Development Team - Backend, Frontend

The team has decided to get together everyday twice for Daily Scrum meetings because of the time constraint. Team also has decided to have a Sprint Review Meeting on 9th of September Monday morning at 9:30 PST (right after the Code Challenge issued and the team had a chance to study Code Challenge requirements)

## "Code Challenge" Sprint Review Meeting
The team met on 9th of September Monday at 9:30. The team members already examined the issued Readme.md file for the Code Challenge by the Province. The team has concluded the following decisions and the related action items;

- Decision 1 - The solution requested by the Province is a Dynamics based solution. So, the team decided to issue only one solution based on Dynamics 365 F&O.
- Decision 2 - The team for the Code Challenge has been formed as follows;
  * Product Owner - Selami Kul
  * Scrum Master - Celal Unver
  * Development Team - Mesut Boztas (Dynamics Expert)
  * Development Team - Enver Yilmaz (Dynamics Developer - Tester)
- 

## "Code Challenge" Daily Scrum Meeting - 1
## "Code Challenge" Daily Scrum Meeting - 2
## "Code Challenge" Sprint Review Meeting



# Publication

Publishing in StackEditPro makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **WordPress** and **Zendesk**. With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.

> Before starting to publish, you must link an account in the **Publish** sub-menu.

## Publish a File

You can publish your file by opening the **Publish** sub-menu and by clicking **Publish to**. For some locations, you can choose between the following formats:

- Markdown: publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).

## Update a publication

After publishing, StackEditPro keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the **Publish now** button in the navigation bar.

> **Note:** The **Publish now** button is disabled if your file has not been published yet.

## Manage file publication

Since one file can be published to multiple locations, you can list and manage publish locations by clicking **File publication** in the **Publish** sub-menu. This allows you to list and remove publication locations that are linked to your file.


# Markdown extensions

StackEditPro extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTEzMTYzMjUyMywtOTQxMzkwMjk5LDUzMD
EyMTE2LC0xNTY4ODMzNDUyLDEyODA2MzMwMDIsMTAxNjc1NDgy
XX0=
-->
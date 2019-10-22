Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform.

**What we need to know:**

- How the Markdown format makes styled collaborative editing easy
- How Markdown differs from traditional formatting approaches
- How to use Markdown to format text
- How to leverage GitHub’s automatic Markdown rendering
- How to apply GitHub’s unique Markdown extensions

## What is Markdown?

Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or \*.

## Syntax guide

Here’s an overview of Markdown syntax that we can use anywhere on GitHub.com or in your own text files.

# Italics and Bold

\_This text will be italic\_

\*This text will be italic\*

---

\_\_This text will be bold\_\_

\*\*This text will be bold\*\*

Of course, you can use \_both italics and bold\_ in the same line, and also span them across multiple words.

# Headers

\#This is a h1

\##This is a h2

\###This is a h3

\####This is a h4

\#####This is a h5

\######This is a h6

# Links

There are two different link types in Markdown, but both of them render the exact same way.
The first link style is called an inline link.
To create an inline link, you wrap the link text in brackets [ ] , and then you wrap the link in parenthesis ( ).

Example: [Visit GitHub!](www.github.com)

                  [Visit GitHub!](www.github.com)

The other link type is called a reference link. As the name implies, the link is actually a reference to another place in the document. Here's an example of what we mean:

     Here's [a link to something else][another place].
     Here's [yet another link][another-link].
     And now back to [the first link][another place].

     [another place]: www.github.com
     [another-link]: www.google.com

# Images

Images also have two styles, just like links, and both of them render the exact same way. The difference between links and images is that images are prefaced with an exclamation point ! .

The first image style is called an inline image link. To create an inline image link, enter an exclamation point ( ! ), wrap the alt text in brackets [ ] , and then wrap the link in parenthesis ( ) .

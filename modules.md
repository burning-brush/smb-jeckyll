---
layout: default

media:
    image:
        url: https://via.placeholder.com/150
    heading: Media Object
    content: For any markup that is not covered by Markdown’s syntax, you simply use HTML itself. There’s no need to preface it or delimit it to indicate that you’re switching from Markdown to HTML; you just use the tags.
---
test modules

#### Headings

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6


#### Lists

- one
- two
* three
* four

1. one
2. two
1. three

### Blockquote

> This is a test for blockquotes,
> Testing to see when it breaks.

### Code Blocks

    This is preformatted text


### Copy

Markdown is intended to be as easy-to-read and easy-to-write as is feasible.

Readability, *however*, is **emphasized** above all else. A Markdown-formatted document should be publishable as-is, as plain text, without looking like it’s been marked up with tags or formatting instructions. While Markdown’s syntax has been influenced by several existing text-to-HTML filters — including Setext, atx, Textile, reStructuredText, Grutatext, and EtText — the single biggest source of inspiration for Markdown’s syntax is the format of plain text email.

To this end, Markdown’s syntax is comprised entirely of punctuation characters, which punctuation characters have been carefully chosen so as to look like what they mean. E.g., asterisks around a word actually look like `*emphasis*`. Markdown lists look like, well, lists. Even blockquotes look like quoted passages of text, assuming you’ve ever used email.

* * *

<div class="row">
    <div class="col">
        <div class="alert alert-primary" role="alert">
        A simple primary alert—check it out!
        </div>
        <div class="alert alert-secondary" role="alert">
        A simple secondary alert—check it out!
        </div>
        <div class="alert alert-success" role="alert">
        A simple success alert—check it out!
        </div>
        <div class="alert alert-danger" role="alert">
        A simple danger alert—check it out!
        </div>
        <div class="alert alert-warning" role="alert">
        A simple warning alert—check it out!
        </div>
        <div class="alert alert-info" role="alert">
        A simple info alert—check it out!
        </div>
        <div class="alert alert-light" role="alert">
        A simple light alert—check it out!
        </div>
        <div class="alert alert-dark" role="alert">
        A simple dark alert—check it out!
        </div>
    </div>
    <div class=col>
        <h5>Example Badge <span class="badge badge-secondary">New</span></h5>
        <button type="button" class="btn btn-primary">Primary</button>
        <button type="button" class="btn btn-secondary">Secondary</button>
        <button type="button" class="btn btn-success">Success</button>
        <button type="button" class="btn btn-danger">Danger</button>
        <button type="button" class="btn btn-warning">Warning</button>
        <button type="button" class="btn btn-info">Info</button>
        <button type="button" class="btn btn-light">Light</button>
        <button type="button" class="btn btn-dark">Dark</button>
    </div>
</div>

### Cards

{% include card/card.html %}

### Carousel

{% include carousel/carousel.html %}

### Media Object



{% include media-object/media-object.html media=page.media %}
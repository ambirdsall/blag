# Blog
Posts are written in [Jade](jade-lang.com)

### Organization of posts
* The blog is organized by topic.
* Each post has one topic and one title;
* Each topic has one title.
* Topics are a list from most- to least-recent;
  within a topic, posts are listed from least- to most-recent.

### Presentation of posts
* Left sidebar
  - Has the list of topics, properly ordered (as many as fit on the screen, but
    `position: fixed`, so only what fits fits)
  - Topics are collapsed, and expand to list of posts when clicked
  - Upon scrolling, slow fade to light grey (pure CSS) so text is emphasized
* Text
  - Section (sub)headers
    * All have anchors ('§') for ease of deep-linking
      That is, both a class attribute and an `\<a href='foo'\>§\</a\>`
    * Closer to black in color than body text

### Text Style
* margin
  * Headers
    top and bottom in golden ratio (bottom -> 38%, top 62%)
  * Paragraphs
    no margin top or bottom
    - following another paragraph
      top margin to match section header bottom margin

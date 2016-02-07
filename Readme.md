# Blockchain Embed Tag

Blockchain Embed Tags are code blocks you can copy and paste into web pages.

They are snippets of code that make sure the data you are viewing on a page is correct.

# ------------------

This includes metadata

the metadata can have many forms:

- RDF format
- Simple HTML tags with data attributes
- a custom format


# ------------------


example in riot.js and with a normal iframe - can be ported to polymer as well

### Riot.js

<embed>

</embed>


### Iframe

<!-- hash = "bitcoin tx hash" -->

url = "http://antani.com?hash=x"

<iframe src=":url">


### Flow

in parallel:

  <download :iframe>
  <match = check :hash>
    <load if match>

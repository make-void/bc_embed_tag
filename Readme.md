# Blockchain Embed Tag

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

# Shane's Open Source slides

A better place to write and store slide decks for the various open source
conferences that I speak at. Be sure to look for speaker notes!

Please [view this on the web at https://ShaneSlides.com](https://ShaneSlides.com/)

## Technology

After years of using an office suite to craft slides using a custom template
for every conference, I've switched many presos to using simple Markdown and
one of the modern browser-based JS slide tools.

Using Remark, I usually run a slide deck **locally** (having seen far too 
many conference wifi networks barf).  Open a command terminal, cd 
to the /shaneslides/ directory, and then run slides.sh or:

```ruby -run -ehttpd . -p8000```
or do:
```python -m http.server 8000```

- Open your browser to http://127.0.0.1:8000/apachecon
- Click on the .html presentation shell
- Hit "C" to clone the presentation into a new window (without address bar), and move the cloned window to projector
- Hit "P" in the original window to start presentation mode (with timer, etc.)

### Ddbugging

Even working locally, when changing slides/css/images, you may need to 
force refresh in developer mode or otherwise explicitly clear caches.

## Conferences

I speak regularly at [ApacheCon and
Community Over Code](https://communityovercode.org/) on community and branding issues
around Apache projects. I've also spoken at All Things Open, OSCON, Ignite, Camel One, the Software Freedom Law Conference, and the PLI Law Education conference.

## License

Copyright © [Shane Curcuru](https://shanecurcuru.org/) 2017-2023 | A [Punderthings℠ Production](https://punderthings.com/) | Licensed: [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0.html)

May include externally developed code licensed under MIT, BSD, or other
similar licenses compatible with the Apache License v2.0.

## Historical Note

Code historians may note this site was manually created by copying files from my /slides repository in November 2022; all development is now in this repo.

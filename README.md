# Works without JS

Empower your users with disabled Javascript to experience your website

## Background

Javascript is an awesome technology that has helped us push the web forward to a place we could hardly imagine
twenty years ago.

Being able to stream high quality video, explore the streets of a city, and
connect with people from around the world in real time are wonders that would have been unthinkable without the advent of Javascript
and the evolution of the web as a platform.

However, we have relied on it too much for a while now, and assumed it must be used by default, without even thinking if it
is a good fit for our use cases.

For example, static-content sites like online newspapers and magazines, technical documentation, etc. shouldn't rely on JS
to display basic text, images, code: plain HTML+CSS can do the job perfectly.

This doesn't mean that your site should be 100% free of Javascript. Instead, you should still be able to provide your core 
experience
via graceful degradation or progressive enhancement whenever possible.

Some examples of websites that work with JS disabled:

- [Amazon](https://www.amazon.com)
   - Not the typical example, this must have required a big effort
- [Hacker News](https://news.ycombinator.com/)
- [Wikipedia](https://en.m.wikipedia.org/wiki/Main_Page)


## Badge

![Badge](https://img.shields.io/badge/works%20without%20js-compliant-green.svg)

### HTML

```html
<!-- Just the image -->
<img src="https://img.shields.io/badge/works%20without%20js-true-green.svg"
     alt="Works without JS">

<!-- Image with link to this page -->
<a href="https://github.com/thewarpaint/works-without-js/">
   <img src="https://img.shields.io/badge/works%20without%20js-true-green.svg"
        alt="Works without JS">
</a>
```

### Markdown

```markdown
![Works without JS](https://img.shields.io/badge/works%20without%20js-true-green.svg)
```

## Related

- https://en.m.wikipedia.org/wiki/List_of_most_popular_websites
- https://medium.freecodecamp.org/what-the-web-looks-like-without-javascript-c7eaf09c9983
- https://sonniesedge.co.uk/posts/a-day-without-javascript

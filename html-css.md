# Notes on HTML and CSS

## Susanne's Remarks

Use [this tool](https://validator.w3.org) to validate the HTML markup.

Start with:

1. Elements.
2. Structure.
3. Style.

Use the `<div>` tag only for styling purposes. Before you type it, always ask yourself if there is another tag that better describes the block you are going to create. And then, use it.

`<h1>` is the title of the page. It's better if there is only one per page.

**Navigation**: it's better to use an unordered list. Possibly the `<nav>` and `<a>` tags are not going to be enough to fully style the list, and the `<ul>` tag will provide an additional level for definition.

## Boilerplates

The word "boilerplate" means standardized pieces of text for use as clauses in contracts or as part of a computer program.

An HTML boilerplate will contain the most common elements of a page as a sample that can be cloned and used as a starting point for a project.

1. [HTML Shell](https://www.toptal.com/developers/htmlshell) has an interactive selector that lets the user build up a basic boilerplate.
2. [html5boilerplate](https://html5boilerplate.com/) is a HTML5 framework to develop webpages.
3. [SitePoint](https://www.sitepoint.com/a-basic-html5-template/) discusses how to architecture a website. Not only provides the boilerplate, but also explains every line of it.

## Resources and Online Material

- [When Should ALT Text Be Blank?](https://osric.com/chris/accidental-developer/2012/01/when-should-alt-text-be-blank/)
- [HTML5 Outliner](https://gsnedders.html5.org/outliner/)
- [HTML Validator by Input](https://validator.w3.org/#validate_by_input)
- [Free Accessibility Course by Google](https://www.udacity.com/course/web-accessibility--ud891)
- [Why you should choose article over section](https://www.smashingmagazine.com/2020/01/html5-article-section/)
- [HTML Doctor](https://html5doctor.com/)
- [Semantics in HTML 5](Semantics in HTML 5)
- [Intro to the Semantic Web](https://www.youtube.com/watch?v=OGg8A2zfWKg)
- [ADA Compliance for Websites in Plain English](https://krisrivenburgh.medium.com/the-ada-checklist-website-compliance-guidelines-for-2019-in-plain-english-123c1d58fad9)
- [Using White Space For Readability In HTML And CSS](https://www.smashingmagazine.com/2013/02/using-white-space-for-readability-in-html-and-css/)

## HTML Exercises

### Mockup of an existing web

freelancer.html tries to replicate <https://startbootstrap.com/theme/freelancer>

- <https://startbootstrap.com/theme/freelancer>
- <https://startbootstrap.com/previews/freelancer>
- <https://github.com/StartBootstrap>

### HTML Exercise 1

exercise1.html

Issues:

- Navigation does not work: anchor to other sections.
- w3.org validator does not find an end-of-section.

## ToDo

- Include most common attributes into form.html

## HTML Dig Deeper

- [Introduction to Web Accessibility](https://www.w3.org/WAI/fundamentals/accessibility-intro/)
- [HTML elements reference](https://developer.mozilla.org/en-US/docs/web/html/element)
- [HTML5-Boilerplate Quick Start](https://github.com/h5bp/html5-boilerplate#quick-start)
- [HTML5 Please](https://html5please.com/)
- [CSS Values](https://cssvalues.com/)
- [CSS Click Chart](https://css3clickchart.com/)

## CSS

### Definitions

```css
a /* selector */ {
  /* attribute: value - this pair is called declaration */
  color: red; /* declaration */
  height: 20 rem;
  width: 100%;
  font-size: 18px; /* em / vh /vw / ch / auto */
} /* Block or CSS rule */
```

### Selector Examples

```css
/* Applies only to span's immediately following an a tag */
a + span {
  color: orchid;
}

/* all span children from an a  */
a ~ span {
  color: sandybrown;
}

a {
  transition: color 0.5;
}

a:hover {
  color: greenyellow;
}
```

**ToDo**

Research how to fix (syntax) this code:

```css
[a:target="_blank"]::after {
  content: "(opens in new tab)";
}
```

### References

- [A brief history of web design for designers](https://blog.froont.com/brief-history-of-web-design-for-designers/)
- [CSS Selector Reference](https://www.w3schools.com/cssref/css_selectors.php)
- [Confused About REM and EM?](https://j.eremy.net/confused-about-rem-and-em/)
- This article explain the cascading hierarchy: [The CSS Cascade](https://wattenberger.com/blog/css-cascade)
- This is the reference about cascading: [Introducing the CSS Cascade](https://developer.mozilla.org/en-US/docs/Web/CSS/Cascade)
- [Pseudo-classes and pseudo-elements](Pseudo-classes and pseudo-elements)

In order to deal with different browser styles people came up with stylesheets which would **reset** these styles or **normalize** them.

#### Normalization

- [The New CSS Reset](https://elad2412.github.io/the-new-css-reset/)
- [Normalize.css - The best CSS reset library in 2023](https://byby.dev/normalize-css)

#### CSS Colors

- [CSS Color Names](https://147colors.com/)
- [HTML Color Picker](https://www.w3schools.com/colors/colors_picker.asp)
- [Color Palettes Generator](https://coolors.co/)

**Best practice**:

1. hex codes
2. rgba
3. hsla is best for one-color schemes.

#### Fonts

- [CSS Fonts](https://www.w3schools.com/css/css_font.asp)
- [Fundamental text and font styling](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals#web_safe_fonts)
- [Google Fonts](https://fonts.google.com/)
- [Get Started with the Google Fonts API](https://developers.google.com/fonts/docs/getting_started)
- [CSS Tricks Icon Fonts](https://css-tricks.com/examples/IconFont/)

#### Images

- [When to Use the JPG, GIF, PNG, and SVG Formats](https://www.thoughtco.com/when-to-use-certain-image-formats-3467831)

### Further Refs. (found in Pocket)

- [https://blog.geekyants.com/5-most-annoying-things-with-css-8c356dc24f5e](https://blog.geekyants.com/5-most-annoying-things-with-css-8c356dc24f5e)

- [10 Responsive Design Problems and Fixes](https://uxmag.com/articles/10-responsive-design-problems-and-fixes)

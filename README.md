# inline.css

inline.css is a rapid-prototyping framework for web projects. It allows you to quickly tweak common css properties within your page's layout using CSS classes. This makes web prototyping much simpler and keeps your style files small.

Of course, you can also use it to speed up writing preprocessed styles, since it comes with a bunch of built-in, terse class names.

Plus, it's modular, so you only get what you need. It's also fully configurable.

And it's being continually updated with more and more features.

---

Instead of having this:

`<span style="width: 100%; text-align: center">centered text</span>`

You can do this:

`<span class="w100 center">centered text</span>`


Or instead of creating a bazillion different classes for simple styles, like:

	<div class="title">Title</div>
	<div class="subtitle">subtitle</div>
	<div class="file-size">size</div>
	
	.title     { margin-bottom: 20px; }
	.subtitle  { margin-bottom: 10px; }
	.file-size { display: inline; }

You can do this:

	<div class="bottom20">Title</div>
	<div class="bottom10">subtitle</div>
	<div class="inline">size</div>

---

inline.css is licensed under the [&#9786; License](https://github.com/jonstoler/The-Happy-License).
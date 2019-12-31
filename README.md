# seq-diagram-poc

This is an example of of a sequence diagram that's been dynamically generated from source UML markup.

The `example.puml` URL is passed to the PlantUML proxy server for processing and an SVG is returned which is then displayed as an image in markdown. The following markdown yields the sequence diagram that you see below:

```markdown
![example sequence diagram](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/seesleestak/seq-diagram-poc/master/example.puml&fmt=svg)
```

![example sequence diagram](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/seesleestak/seq-diagram-poc/master/example.puml&fmt=svg)

## External usage

Usage in a confluence document would include two things:

1. Markdown/confluence plugin that can be supplied a URL
2. The URL to your [markdown file rendering a graph](https://github.com/seesleestak/seq-diagram-poc/blob/master/withSignatures.md)

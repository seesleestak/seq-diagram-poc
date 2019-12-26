# seq-diagram-poc

This is an example of of a sequence diagram that's been dynamically generated from source UML markup.

The `example.puml` URL is passed to the PlantUML proxy server for processing and an SVG is returned which is then displayed as an image in markdown. The following markdown yields the sequence diagram that you see below:

```markdown
![example sequence diagram](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/seesleestak/seq-diagram-poc/master/example.puml&fmt=svg)
```

![example sequence diagram](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/seesleestak/seq-diagram-poc/master/example.puml&fmt=svg)

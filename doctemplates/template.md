### Markdown
```markdown

|Model Name| Version | Actor | Branch  | CommitId| 
|----------|---------|-------|---------|---------|
{{#each models}}
|{{modelName}} | {{modelVersion}}| {{#with modelTags}} {{githuB_ACTOR}} | {{githuB_REF}} |{{githuB_SHA}} {{/with}} | 

{{/each}}
# CSV To Markdown Table

Simple JavaScript CSV to Markdown Table Converter

You can see it in action and play with the [live Example](https://donatstudios.com/CsvToMarkdownTable).

Requires **no external libraries**. Works in Node as well as in the browser.

Example Use:

```js
csvToMarkdown( "header1,header2,header3\nValue1,Value2,Value3", ",", true);
```

Outputs:

```
| header1 | header2 | header3 | 
|---------|---------|---------| 
| Value1  | Value2  | Value3  | 
```

Which displays in markdown as:

| header1 | header2 | header3 | 
|---------|---------|---------| 
| Value1  | Value2  | Value3  | 

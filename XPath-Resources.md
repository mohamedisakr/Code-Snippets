### 2 big tricks that XPath can do that CSS currently can't. 
#### 1. To select an element by its text content, which looks something like: `//a[contains(text(),"chive")]`. 
#### 2. The ability to move "up" from an element. So you can use XPath to select a parent of an element, which isn't possible yet in CSS.

### - MDN XPath documentation
https://developer.mozilla.org/en-US/docs/Web/XPath

### - Scrapy XPath Tutorial
https://docs.scrapy.org/en/xpath-tutorial/topics/xpath-tutorial.html

### - Xpath cheatsheet
https://devhints.io/xpath

### There are 2 big tricks that XPath can do that CSS currently can't. 
1. To select an element by its text content, which looks something like: `//a[contains(text(),"chive")]`. 
2. The ability to move "up" from an element. So you can use XPath to select a parent of an element, which isn't possible yet in CSS.

We can combine these two techniques to find the parent container of our "Archive" link:

```
//a[contains(text(),"chive")]/ancestor::ul
```

### Evaluate and Validate XPath/CSS selectors
http://yizeng.me/2014/03/23/evaluate-and-validate-xpath-css-selectors-in-chrome-developer-tools/

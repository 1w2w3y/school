# Grade 3: Algorithms and Robotics Unit  
## HTML and CSS Introduced  
### My First Web Page Information and Activity

## Vocabulary
- **World Wide Web**: A network of computers that share documents with each other.
- **Web pages**: Digital documents shared on the web.
- **Website**: A group of web pages that link to each other.
- **Web browser**: A software application (e.g., Chrome, Firefox, Safari) where you can open and interact with web pages.
- **HTML**: Short for Hypertext Markup Language. It is used to create web pages using regular text.
- **CSS**: Short for Cascading Style Sheets. It is used with HTML to change the appearance of web pages.
- **JavaScript**: A scripting language that can be used to create presentations, games, animations, and more.
- **Elements**: HTML markup that is used to format a web page. It usually consists of start and end tags along with any attributes.
- **Tags**: These indicate the start and end of an HTML element and use angled brackets.

---

# HTML Document

To create a web page, you must create a file that uses HTML elements to format the contents of the page.  
This file is called the HTML document and usually ends with an `.html` extension.

## Document Type
Browsers need to know the type of markup language contained within a file in order to render the contents correctly.  
The first line of the HTML document must specify the document type using the declaration:

```html
<!DOCTYPE html>
```

## Document Start and End
HTML pages must start with an `<html>` tag and end with an `</html>` tag. All other HTML elements are contained between these tags.

## Empty HTML Document
```html
<!DOCTYPE html>
<html>
</html>
```

## Document Head
The head of an HTML document is where we declare special instructions for the browser known as metadata.  
The document head is enclosed within the `<head>` and `</head>` tags.  
The contents of the head are not displayed when the page is loaded.

## Document Body
The visible part of the HTML page is called the body.  
The body is enclosed within the `<body>` and `</body>` tags.

---

## Paragraph Example
Here is an example of paragraphs in HTML:

```html
<p>This is the first paragraph.</p>
<p>This is another paragraph.</p>
```

## Line Breaks
We can add line breaks using the line break element.

### Line Break Element
The line break element is self-closing and written as:

```html
<br />
```

It breaks text onto a new line wherever it is placed.

## Paragraphs vs Line Breaks
A line break is similar to a paragraph but does not include extra spacing.  
Paragraphs (`<p></p>`) add spacing between lines.

## Using Paragraphs and Line Breaks
```html
<p>Things I like...</p>
Ultimate Frisbee<br />
Rainy Days<br />
Dogs<br />
Chocolates<br />
Soccer<br />
```

---

# CSS Styling

## Set Background Color
We can change the page background color using CSS:

```css
body {
  background-color: teal;
}
```

## Text Color
We can change paragraph text color using CSS:

```css
p {
  color: white;
}
```

## Colors in CSS
Ways to specify colors in CSS:
- Predefined color names
- RGB color values
- Hexadecimal color values

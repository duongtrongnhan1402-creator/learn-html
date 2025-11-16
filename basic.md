# ✅ 1. Basics of HTML (Detailed Explanation)

## **What is HTML?**
HTML stands for **HyperText Markup Language**.  
It is the **standard language used to create web pages**.  
HTML provides the **structure** of a page, like a skeleton for a website.

HTML is made of:
- **Elements** → building blocks (like `<p>`, `<h1>`, `<img>`)
- **Tags** → the actual markup inside angle brackets (`< >`)
- **Attributes** → additional information inside elements (`src=""`, `class=""`)

---

## **How HTML Works**
When you open a webpage, your **browser reads the HTML file** and displays the content based on the tags.

Example:
- `<h1>` tells the browser: “This is a big heading”
- `<p>` tells the browser: “This is a paragraph”
- `<img>` tells the browser: “Show this image”

HTML does *not* control design — that’s what **CSS** is for.  
And HTML does *not* control behavior — that’s **JavaScript**.

---

## **The Structure of an HTML Document**
Every HTML file follows a similar structure.  
Here’s the simplest example:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Webpage</title>
</head>
<body>
    <h1>Hello World!</h1>
    <p>This is my first webpage.</p>
</body>
</html>

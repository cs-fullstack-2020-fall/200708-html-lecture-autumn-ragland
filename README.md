# 20-07-08 HTML Basics Lecture

## Objectives
- HTML Structure
- Attributes
- Elements

## Code Together
1. Clone repository and open repository in code editor
2. Create HTML file called `index.html`
3. Create basic page structure using the VSCode html:5 shortcut and change the document title to `Lecture`
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Title</title>
</head>
<body>
    
</body>
</html>
```
4. Create a `div` with a the text `CodeCrew Code School`
```HTML
<div>
  CodeCrew Code School
</div>
```
5. Create a second `div` with a nested `p` tag with your name
```HTML
<div>
  <p>Your Name</p>
</div>
```
6. Create a `section` with a nested `ordered list` and list three things you have learned so far in the Code School
```HTML
<section>
  <ol>
    <li>one thing you learned</li>
  </ol>
</section>
```
7. Add an `image` inside of a div of the CodeCrew logo below the `CodeCrew Code School` text
```HTML
<img src="image address" alt="Code Crew Logo"/>
```
8. Add a `link` that opens in a new page to the CodeCrew website below the CodeCrew logo
```HTML
<a href="site address">Code Crew Website</a>
```
9. Add a `footer` below everything else on the page with today's date 
```HTML
<footer>20-07-08</footer>
```
10. Check that your final product looks like `HTML_Basics.PNG`
10. Add, commit, and push your assignment
```
git add -A
git commit -m "meaningful message"
git push
```
And check your repository on GitHub to be sure that your changes were pushed
## Resources
- [Sprint Documentation](https://github.com/Kevin-CodeCrew/coding_concepts_sprint_2/blob/master/Introduction_to_HTML.md)
- [W3Schools Structure Documentation](https://www.w3schools.com/html/html_basic.asp)
- [W3School Attributes Documentation](https://www.w3schools.com/html/html_attributes.asp)
- [W3Schools Elements Documentation](https://www.w3schools.com/html/html_elements.asp)

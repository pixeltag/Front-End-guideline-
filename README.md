# Front-End-guideline-

## HTML

##### 1- Always declare the document type as the first line in your document <!DOCTYPE html> . 
##### 2- Use Lower Case elements names  
##### 3- Close all HTML elements . 
##### 4- Image Attributes : Must add alt attribute to IMG element. 
##### 5- HTML5 allows spaces around equal signs. But space-less is easier to read, and groups entities better together. 
##### 6- When using an HTML editor, it is inconvenient to scroll right and left to read the HTML code. Try to avoid code lines longer than 80 characters.
##### 7- Do not add blank lines without a reason. For readability, add blank lines to separate large or logical code blocks. 
##### 8- For readability, add two spaces of indentation. Do not use the tab key.
##### 9- Meta Data : like title tag , To ensure proper interpretation, and correct search engine indexing, both the language and the character encoding should be defined as early as possible in a document: 
##### 10- Viewport : HTML5 introduced a method to let web designers take control over the viewport, through the <meta> tag.
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
##### 11- Add comments between each componanet to make the code more clean and maintainable .
##### 12- Class names based on BEM and SMACSS methdology , use meaningful or generic ID and class names.
###### Instead of presentational or cryptic names, always use ID and class names that reflect the purpose of the element in question, or that are otherwise generic.
###### Names that are specific and reflect the purpose of the element should be preferred as these are most understandable and the least likely to change.

    https://smacss.com/files/2012-03-15-workshop-essen.pdf
##### 13- Use W3C Validator to validate your HTML Markup . 
##### 14- Use Bootstrap4 Markup in all common component like Inputs and UI kits . 
##### 15- Try to use Primeng Componant in excluding the componanet like DataTable - Model -  Tree ... etc .
##### 16- Don't use Table HTML Markup , use UL list is better . 
##### 17- For Icon the better way to use SVG Icon nether than Icon fonts like font-awesome .
##### 18- A good guide for HTML Syntax here : http://codeguide.co/#html-syntax 
 
## CSS & SASS 

##### 1- Use variable in colors anf font size . 
##### 2- Every componant should have a SCSS file named on the component's name . 
##### 3- Every componant should have a parent Class selector and write the scss in nested way . 
##### 4- Should using Bootstrap grid system  like col-12 col-sm-12 col-md-12 col-lg-12 . 
##### 5- Use valid CSS where possible.
##### 6- Don't use !important attribute .
##### 7- Use shorthand properties where possible.
##### 8- Don't Use Margin or Padding or Top to animate any elements just use transform property . 
##### 9- Prefix selectors with an application-specific prefix (optional).
##### 10- Use soft tabs with two spaces—they're the only way to guarantee code renders the same in any environment.
##### 11- Include one space after : for each declaration.
##### 12- Each declaration should appear on its own line for more accurate error reporting.
##### 13- Related property declarations should be grouped together following the order:
#####            - Positioning
#####            - Box model
#####            - Typographic
#####            - Visual
#####   - Positioning comes first because it can remove an element from the normal flow of the document and override box model related styles. The box model comes next as it dictates a component's dimensions and placement.

#####   - Everything else takes place inside the component or without impacting the previous two sections, and thus they come last.
##### 14- Use bootstrap4 Media Query in responsive mode . 
##### 15- Prefixed properties


## JavaScript & TypeScript 

##### 1- Add Comments to explain code as needed, where possible.
##### 2- 

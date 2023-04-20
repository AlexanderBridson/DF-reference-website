# reference-website

1. Naming convention for all filenames, paths and folders
    - Namming conventions for all filenames, paths, and folder should only have lowercase lettering, no spaces (use dashes or underscores instead), and only use letters, numbers and dahses (no symbols).

2. Best practices for commit messages
    - The best practises for commit messages is to do so when you finish a section. Your commit message should be descriptive of what u did in the section, and you may add extra details in the description section.

3. What is HTML?
    - Hmtl is the language used to create a webpage.

4. Proper syntax for HTML tags
    - The proper syntax for an html tags is for example <p> and </p>. 

5. Explain or demonstrate commonly used html tags/elements:
    - headings: h1-h6
        - The h1 heading is used for the primary title/heading of the page and there is normally only one h1 on each .html page. The h2-h3 are used for other subtitles and sections going from important to least important. For example, a title would be h1, a section title would be h2, and then an article title would be h3.

    - p: 
        <p>Hello this is my example.</p>

    - lists: ul, ol, dl
        <ul>
            <li>Item a</li>
            <li>Item b</li>
            <li>Item c</li>
        </ul>
        <ol>
            <li>1. Wash item a</li>
            <li>2. Cut item a into cubes</li>
            <li>3. Place item a into a bowl</li>
        </ol>
        <dl>
            <dt>This is an orange</li>
            <dd>The orange is soft and bright</li>
            <dd>The orange is sweet and seedless</li>
        </dl>

    - a
        - The <a href=""></a> tag or otherwise known as the anchor tag and href attricubte are used for linking websites, other .html pages, and other locations within a page.

    - img 
        - The <img src="" alt=""> tag is used for linking images to an html document. The source attribute uses the links of the image to link it to the desired url page. The alt attribute is used to add more descriptive text to the image while in screen reader mood in order to create a more accessible website.  

    - q 
        - The <q> tag is used to mark quotes within a paragraph.

    - blockquote
        - The <blockquote> tag is used to display a quote tag on its own.

    - cite
        - The <cite> tag is used to display the source of a quote. It's usually placed inside the quote tag. For example, <q><cite>Insert source link</cite>Insert quote</q> 

    - em
        - The <em> within a <p> tag is used to emphasis a particular word or phrase within a sentence by italicizing it.

    - strong
        - The <strong> tag is used within a <p> tag to emphasize a particular word or phrase within a sentence by putting it in bold.

    - b
        - The <b> tage is used within a <p> tag to add bold to any text without adding extra importance.

    - i
        - The <i> tage is used within a <p> tag to add italics to any texts without adding extra importance. It's usually used on on technological terms or different languages.

    - small
        - The <small> tag is used within a <p> tag to decrease importance of a word or phrase within a sentence by reducing the size.

6. Explain block Elements and also explain the list of block elements and why they are used from below:
    
    - A block element is an element that's used within an html document and begins a new line of content and/or text. 

    - html
        - Hmtl is the language used to create a webpage. It's use to oragnize information on your website and create order. 

    - head
        - The head is an element within the index.html file that isn't a visible part fo the website. The head is used to link fonts, display the title of the webpage, include the metadata of the website, and more.  

    -  body
        - The body element is used to group all important informatin a orage webpage.

    - header
        - The header is the introductory content usually located at the top of the page. It would include a logo or company name and navigation for the website. It is used to separate the navigation and introductory elements from the body of the webpage.

    - nav
        - The navigation element is located normally at the top of the page in forms of hyperlinks and/or buttons. They are used to link users to other areas on the page the current document or other documents.

    - main
        - The main elements is used to wrap the main elements. It's used to tell the user where the main content is on the page.

    - section
        - The section element is used to wrap related content into a section and usually has its own heading.

    - article
        - The article element is used to wrap self contained content. It's used to allow the content to be independently distributable or reusable. 

    - div
        - The div block element is used to group elements together.

    - aside
        - The aside elements wraps content that's inddirectly related to the main content mostly displayed as a sidebar on the website. 

    - footer
        - The footer element is located at the bottom of the page. It's most commonly used to display lists of links, copyright information, extra information about the company, and the terms and conditions.

    - span
        - The span element is an inline container used to phrase/mark up text or a part of a document that doesn't inherently represent anything.

    - small
        - The small element decrease the inportance of a word or sentence. It's used within a paragraph to decrease importance of a word or phrase within a sentence by reducing the size.

7. Explain why accessibility is important and also explain the accessibility properties like:
    - Accessibility is important when creating a website because it invites all people to enjoy and interact with your site.

    - Landmark roles
        - Landmarks roles are important because they allow viewers who may be using a screen reader to jump straight to specific content on the webpage.

    - Aria labels are important because they offer more information to someone who are using screen recordiers.

    - Image alternative texts are imporatant because it allows a viewer with visiual impairments to view the image with the help of a screen reader.

8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)
    - CSS is short for Cascading Style Sheets. CSS is to manipulate the appearance of html pages. To link the CSS to the html you much attach it using this code <link rel="stylesheet" href="css/style.css"> within the head of the .html page.

9. What is the difference between CSS property and value (write explanation and an example code)
    - A CSS property is the design your adding to your html such as colour, width, and border. A CSS value is the value/descriptor/size of the property such as green, 40px, 4rem, and 2em. That said the difference between the two is that a CSS property is design element itself and a CSS value is just the value of the property. 
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            color: green;
        }

10. Why do we use border-box property in CSS?
    - We use border-box property in CSS because it includes the border and padding within the width and height. 

11. Explain different type of ways we can add spacing to an element
    - Different type of ways we can add spacing to an element is with margin and padding. Padding adds space to an elements space like withing it's border and margin adds space to any extra space the element has within it's box area.

12. What is the main difference between margin and padding?
    - The main differeence between the two is that margin represenets the space outside an element like a box and padding represents the spacing inside an element like a box.

13. What are different types of display properties?
    - Different types of display properties are display inline, block, inline-block, and none.

14. Write a brief explanation of flexbox property.
    - The flexbox property is used to allows the user/coder to apply complex and unique layouts to elements on an html. It does so by changign to flow and alignmnet of elements.

15. What are different types of flexbox properties and what is the major difference between them?
    - Different types of flexbox properties are flex, inline-flex, flex direction, wrapping flex items, and justification & alignmnets. The main difference between these elements is that flex direction property only allows for elements to change in one direction in the flex container, the flex container when wrapping can break elements into differents lines or wrap/contain them, justification & alignmnets allows you to control the position/placement and alignment of the itmes wihtin the flex container and control the space between the flex items.

16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property.
    - The flexbox property of flex container is used by targeting the parent element and adding a display: flex property in css. Also with display flex there's preset flex properties such as felx directio set to row, justfications & alignment set to the start egdge and strecth, and wrap set to nowrap.
    <section>
        <div></div>
        <div></div>
    </section>
    section {
        display: flex;
    } 

17. Write a code example on how you will use a flexbox property on a parent element with sub properties.
    <section>
        <div></div>
        <div></div>
    </section>
    section {
        display: flex;
        flex-direction: row
        flex-wrap: nowrap;
        justify-items: start;
        align-items: stretch;
    }  

18. What is CSS grid property?

19. Write the parent and two sub-properties used for CSS Grid Property.

20. What is the difference between display: flex and display: grid?

21. What sub-property we use to divide elements in CSS Grid properties?

22. What unit we use to fractionally divide the element width in CSS Grid property and what are others unit we can use alternatively? (Write a code example)

23. What is the area property in CSS grid we use for the child elements?

24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property.

25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file.
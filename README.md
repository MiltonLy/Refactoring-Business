# Code Refactoring Business

## Technology Used

Technology Used
Resource URL
HTML [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
CSS  [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) 
Git  [https://git-scm.com/](https://git-scm.com/)

## Description

The project is a webpage for Horiseon to advertise marketing ideas. This project was to here to display refactored code of the Horiseon webpage and alllowed me to practice. I was able to accomplish this by observing the initial code structure and determine what was needed to fix. Refactoring allows someone to clean up restructure code that might not be as seamatic as someone needs it to be. 

I learned that messy code can still run properly on a webpage, but not as assessible to all users on the webpage. This project motivated me to step out of my comfort zone and take steps to learn new things.

## Usage Instructions

First open terminal(or gitBash) and navigate to the location of the file. Type in (code .) to access the code in Visual Studio Code. 

<header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
 </header>

The code above shown above was refactored to show an appropriate [<header> semantic element]. This also required changes in the CSS selector.

.header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}

This shows that the ".header" identifies all class that fall under ".header", but we only need it to identify the "header" portion as shown below.

header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}

## Learning Points

Overall this project allowed me to stretch my coding muscles in an envioronment that I wasn't comfortable in. I was able to practice refactoring, good semantic html techniques, and the importance of alt attributes when displaying images.

## Author Info

Milton Ly

[Github] https://github.com/MiltonLy
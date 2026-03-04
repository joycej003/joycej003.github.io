
Homework 2 Reflection & AI Attribution

1. Explain the difference between flex-direction: row and flex-direction: column.
    When using flex direction row, the items are laid horizontally, flex firection column is laid vertically like a list.

2. Why is it important to use relative units (like %, vh, or rem) instead of fixed pixels (px) for responsive design?
    When on different devices, the dimensions are different, so using relative units can make it easier to adapt to the mobile phone, laptop, etc. It would scale porportionally, the fonts would be readable, and layouts can adjust to the devices screen. fixed pixels could leave to elements that overlap or get cut off.

3. AI Attribution: List the prompt you used if you consulted GenAI. Identify one specific piece of CSS code the AI provided that you had to modify to make it work for your layout.
    I ask chatgpt "how do i use @media in css for mobile and laptop? give me an example" and it showed:
    /* Styles for laptops / larger screens (min-width 1024px) */
    @media (min-width: 1024px) {
    body {
        font-size: 20px;
        background-color: lightblue;
    }
    }
    /* Styles for mobile phones (max-width 600px) */
    @media (max-width: 600px) {
    body {
        font-size: 14px;
        background-color: lightyellow;
    }
    }
    I didn't use body or change background color. I added sections for my classes and ids and changed the font sizes, max-width size, image width and length and changed things for my navigation bar.








Homework 1 Reflection & AI Attribution

Describe the path an HTTP Request takes from a browser to your GitHub Pages site.

The browser sends an HTTP request over the internet to the github server. The github server then sends the HTML back to the browser through the internet and the browser renders the HTML into the github page site.



We discussed Docker Containers in class. Explain how a Docker Container differs from the environment provided by GitHub Pages.

A docker container allows an application to run in an isolated environment. A docker image have all the files, libraries and packages needed to run the application.

Github is more for coding and collaborating. In github, multiple people can work in the same repositories, making branches and merging. It is for coding and tracking the changes.



AI Attribution: If you used GenAI (ChatGPT, Claude, etc.) to help write code, you must include the prompt you used and explain one logic error the AI made that you had to fix manually.

I did not use GenAI to generate code. 
I did use the automatic ai in visual studio code to help write code when it predicts what code I want to type. For example, when I wanted to add a class, after I manually added a class to a tag to some sections, it predicted it when I started typing again.

An error it made was when I added a class and id in the same tag to do the specificity challenge and it wanted to delete the ' id=" ' so that it became only a class with combinated name of both the class and id name.
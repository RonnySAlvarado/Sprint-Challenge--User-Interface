1. If you had to describe semantic HTML to the next cohort of students, what would you say?

2. Describe some differences between ```display: block;``` and ```display: inline;```.

3. What are the 4 areas of the box model?

4. While using flexbox, what axis are you using when you use the property: ```align-items: center```?

5. What is the git command to commit staged changes as well as write a message? 

Answer 1) Semantic HTMl is essentially a way to give your html code meaning. It used to be that you'd write <div> everywhere it seems and was just a mess, but
being able to split code into <header> and <footer> and <main> and <section> and <article> and <nav>...there's meaning behind everything. Plus, each one has a
set rule that browsers know how to read, which is convenient.

Answer 2) Block elements, such as <p> and <div> and <h1>, take up the whole width and are stacked on top of each other because of that. 
Inline elements don't respect width/height because they take up as much space as there is content and goes side-by-side.

Answer 3) The 4 areas of the box model are, and starting with inner most going outer: content, padding, border, and margin.

Answer 4) If you're using align-items, that's going from the cross axis. The main axis equivalent is justify-content.

Answer 5) That would be git commit -m "your text here involving meaning to what it is you're commiting"
Q1. In your form, why must a <label>'s for match its <input>'s id? What goes wrong if they don't match?

Answer:
Matching the label's for attribute with the input's id creates a direct connection between the text and the input field. This is important for web accessibility because it allows screen readers to correctly read out the label text when a user selects that field. If they do not match, clicking on the label will not focus or activate the input element, which completely breaks the user experience for mouse and touch users.

Q2. You used both <section> and <article>. What is the difference? Why did the hackathon story become an <article>?

Answer:
A section tag is used as a generic container to group together related content or thematic parts on a web page. On the other hand, an article tag is specifically meant for completely independent and self-contained content that can stand alone. The hackathon story became an article because it represents a single, complete piece of narrative text or news that makes sense on its own even if it is separated from the rest of the site.

Q3. What is the difference between <th> and <td>? Why should a table never be used to lay out a whole page?

Answer:
The th tag defines a table header cell which automatically makes the text bold and centered to act as a column title, while the td tag defines a standard table data cell for regular values. Tables should never be used to create the layout of a whole web page because it ruins semantic accessibility for screen readers and makes the layout extremely difficult to scale or make responsive on smaller mobile screens.

 

Adhoc
Let’s make full use of our Bootstrap knowledge and its accompanying documentation to create a website for Adhoc, an office administration website. Check out Adhoc’s design spec for more information. You also have the option of not following the steps/design spec and creating a website of your own design!

We’ll be using the following image assets:

Adhoc logo.
jumbotron background.
experienced icon.
fun icon.
smart icon.
picture of Brian M. the CEO.
picture of Andy C. the CFO.
picture of Angela W. the COO.
picture of Amie S. the CTO.
Be ready to browse Bootstrap’s documentation. The steps provided will explain what you need to do, but it’s up to you to find out how to implement it. If you’re have difficulty locating the correct resource, check the hint for some helpful links.

Remember, as you code along, save your code in order to see your changes reflected in the browser!

Tasks
0/21 Complete
Mark the tasks as complete by checking them off
Getting Ready
1.
Before we touch the code, look over Adhoc’s design spec provided in the introduction. Notice that the design spec includes information about what Bootstrap utility classes components are used.

And keep in mind that the website is designed to be responsive so that it accommodates desktop and mobile screens. Therefore, as you work through the project, resize your browser to see both the desktop and mobile versions!

Also, check out the links provided for the images used on the website.

Lastly, look over the provided code in index.html. You’ll see some starter code that you’ll have to edit in order to have a functioning site.

Editing the Navbar
2.
Let’s first tackle the navbar, but notice that there’s already some code there! That’s the code copied from Bootstrap’s navbar example.

It’s a good starter template but we still have to edit this code to fit our needs. Therefore, remove the code that renders these elements:

the dropdown option.
the disabled link.
the search bar.

Stuck? Get a hint
3.
Add Adhoc’s logo to the navbar.

Locate the element with class "navbar-brand". Delete the text Navbar and replace it with an <img> element with an src value of "https://content.codecademy.com/courses/learn-bootstrap-4/adhoc/logo.png".

Remember to assign an appropriate value to the alt attribute.


Stuck? Get a hint
4.
According to the design spec, we should have 4 links (not including the brand) in the navbar.

Use the second link as a template and make 2 additional links. Change the text of the links to follow the design spec.


Stuck? Get a hint
Adding the Jumbotron
5.
Under the navbar, there’s a <div> that we’re going to turn into our jumbotron!

It currently has some inline CSS that renders a background image.

Provide it with a class of "jumbotron" and "jumbotron-fluid" to get a jumbotron that spans the entire screen/viewport.


Stuck? Get a hint
6.
Inside the jumbotron, add another <div>. This new <div> is going to act as a background and container for the text we want to insert. Therefore, inside the <div> add an <h1> element followed by a <p>.

Use the design spec and add the appropriate text inside both the <h1> and the <p> elements.


Stuck? Get a hint
7.
Time to style the elements we just added. We want the new <div> to have:

a grey background.
white and centered text.
larger top and bottom margins by assigning a class of "my-5". This utility class targets and increases the vertical margins of an element.
Also, give the <h1> element a display heading by assigning a class of "display-3".


Stuck? Get a hint
Styling the Quote
8.
Let’s style the quote under the jumbotron using utility classes.

Follow the design spec. Provide the <h2> element with

italic font.
a light font-weight.
Notice the stying of the name, it:

is aligned to the right
has a bold and italic font
the text inside the <span> has a normal weight.
Finish up the quote styling by increasing the top and bottom margins of the column containing the quote. You can do so by assigning a class of my-5.


Stuck? Get a hint
Why Adhoc? - Cards
9.
Locate the <h2> element with text Why Adhoc?.

Center the text and give it a display heading that follows the design spec.


Stuck? Get a hint
10.
In the next row, we’re going to continue following the design spec and add one card in each column.

In each column, add a card that:

Does not have a border.
Has an image icon on the top.
Has centered text on the bottom.
Here are the linked icons for convenience:

experienced icon.
fun icon.
smart icon.

Stuck? Get a hint
11.
While the columns look good on a large screen, the contents look squished on a smaller screen. Change the width of the column so that it has a width of 4 on medium, and larger, sized screens.

For extra small and small-sized screens, it should have a width of 8.


Stuck? Get a hint
12.
Let’s also have the row center the columns containing the cards.


Stuck? Get a hint
13.
Increase the vertical margins of the row with the text Why Adhoc and the row containing the cards to space out the rows.


Stuck? Get a hint
Meet the Team - Carousel
14.
Locate the row with the text Meet the Team. According to the design spec, provide that row with utility classes that render a dark background with rounded top border.


Stuck? Get a hint
15.
Now let’s style <h2> element that has the text Meet the Team.

Apply the following styling for the <h2> element:

Make the text white.
Center the text.
Make it a Bootstrap display header.

Stuck? Get a hint
16.
Time to style the row below the text Meet the Team.

Give the bottom row a dark background and a rounded bottom border.


Stuck? Get a hint
17.
Take a look at the code that renders a carousel. It was copied directly from Bootstrap’s carousel with controls example.

Like with the navbar, we’re going to modify the code to fit our needs. For each <div> with a class of "carousel-item", assign the nested <img>‘s src a URL to the provided pictures in the intro’s image assets. Also, provide an appropriate value for the alt attribute.

Here are the linked images for convenience:

picture of Brian M. the CEO.
picture of Andy C. the CFO.
picture of Angela W. the COO.
picture of Amie S. the CTO.

Stuck? Get a hint
18.
With the slides set up, we can add some captions to each slide.

Style the captions so that it has a black background, no vertical padding, and a rounded-pill border.

Inside the captions, add the appropriate text and style it according to the design spec.


Stuck? Get a hint
19.
Change the sizing of the carousel to only take up 50% of the width and set the margin to automatically center its contents.

Then go back and adjust the spacing of the rows to follow the design spec.


Stuck? Get a hint
Finishing up
20.
The last element we have to style is the <footer>, center the text.

21.
Congratulate yourself on a website well Bootstrapped!

There are different ways to re-create the layout of the website, so figure out what works best for you!

If you want to challenge yourself:

Add the HTML pages in the navbar and link to them.
Add more Bootstrap components.
Apply extra styling to the components.
Make the columns even more responsive by including more breakpoints.
Redesign the website to follow a different layout. This is the most involved task since it requires that you think about what you want on your site, how to arrange the layout, and how to implement this idea. While it may be challenging, it’s also extremely rewarding!


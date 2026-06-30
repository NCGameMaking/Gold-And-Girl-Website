Case Study: Making the Website for Gold and Girl Honey
Location: Queensland, Australia



Introduction
This is the story of how I designed and built the website for "Gold and Girl," a local business in Queensland that sells raw, natural honey. The goal was to make a nice website for desktop computers. I wanted the site to look like a friendly, handmade local brand, but also teach people about protecting the environment. I did not want it to be just a boring shop. I wanted it to make people think about what is happening to bees in Queensland.

1. The Research Phase
Talking to the Owner
I talked to the business owner to find out what they wanted. I learned that this project was not just about selling jars of honey. It was about telling the whole story of the bees and the farm.

Looking at Competitors
I looked at other honey websites and small business shops to see what they do. Here is what I found:

Fonts
They use fonts that look casual and handmade, not corporate.

Colors
They use warm colors like honey yellow, amber, and rich brown.

They use earthy colors like soft cream and leafy green.

They use lots of white space so the text is easy to read and the golden colors pop.

Layouts
They use neat grids to show off different products and jar sizes.

They use overlapping pictures and soft curves instead of stiff, boring squares.

They put a big, beautiful picture right at the top of the page so you instantly know what the site is about.

What they include
They always have a "Meet the Beekeeper" section to tell their story.

They clearly label things with words like "100% Raw" or "Chemical-Free."

They use videos of honey dripping, bees flying, or the owners saying hello.

They use lots of hexagon shapes because they look like natural honeycombs.

2. The Planning Phase
The Main Goal
Gold and Girl needs a website that shows off their natural honey products and teaches people about the environment. This is super important right now because a dangerous bug called the Varroa mite is threatening bees in Queensland. The site needs to help save local bees and appeal to shoppers who care about the planet.

What the Website WILL Have
The Homepage: A nice layout showing the honey with clear rules: "No Chemicals, No Heating, No Plastic".

The Bee Crisis Section: A part of the page that explains the Varroa mite danger and tells people what plants to grow to help local bees.

The Navigation Bar: A simple menu at the very top of the page so users can click around easily.

What the Website WON'T Have
Mobile Layouts: The site only needs to work on desktop computers for now. No smartphone layouts yet.

A Real Shopping Cart: Users cannot actually buy anything or log in yet. This is just to test the look and feel.

A Live Forum: No comment sections or message boards, because those take too much work to look after.

3. The Idea Phase
Choosing Materials
Colors: I used a website called Coolors.co to pick nice shades of yellow, cream, and brown that match real honey.

Fonts: I picked clean fonts from Google Fonts that look professional but still feel friendly and homemade.

Pictures: I gathered a bunch of reference photos of bees, honey jars, and nature to help me get the vibe right.

Picking the Best Layout
I drew three different layout ideas and chose the first one because:

It puts the logo and links right at the top where people expect them to be.

It flows nicely. Users see the brand logo, read about the honey, see the story, and then see how to help the bees at the bottom.

It feels natural and is easy to read.

4. Building the Contact Page
Adding to the Project
After finishing the main pages, I decided to build a brand new Contact Page from scratch because the old site did not have one. This lets customers actually send messages to the business.

How the Contact Page Looks
I split the page into two sides:

The Left Side (Info): A simple card that shows the business email (enquiries@goldandgirl.com.au), phone number, and location.

The Right Side (The Form): A neat form where people can type their name, email, pick a topic from a dropdown list, and type a message.

The Bottom (Social Media): A clean box at the very bottom that holds links to the Facebook, Instagram, and X accounts.

5. Coding Troubles and How I Fixed Them
Trouble 1: Making the Form Boxes Line up
At first, the dropdown menu and the big message box looked messy. They were wider than the name and email boxes, which broke the layout.

The Fix: I added a line of CSS called box-sizing: border-box and made all the boxes 100% width. This forced them to line up perfectly inside the card with nice rounded corners.

Trouble 2: Fixing the Social Media Icons
When I first added the social media links, the logos were giant and looked terrible. Also, the usernames were stuck underneath the icons instead of next to them.

The Fix: I used a CSS tool called Flexbox (flex-direction: row). This forced the icons and the text to sit side-by-side in a neat line. I also shrank the logos down so they look clean.

Trouble 3: Making the Email Form Actually Work
A normal website form is just for looks and does not actually send messages anywhere. I wanted this one to work.

The Fix: I connected the form to a free service called Web3Forms. I immensely struggled to write some JavaScript code that works, so I got AI to do it. Now, when a user clicks submit, the code checks to make sure no boxes are left empty. Then, it changes the text on screen to say "Thanks for your message!" and instantly sends a real email notification straight to my personal inbox.

6. Testing the Site
Did it pass?

Live Form Test (Passed): I tested the form myself. The dropdown menu successfully changes the success message on the screen, and the emails show up in my inbox just a few seconds after hitting submit.


AI USAGE:

I used AI to help me learn VS code, help me with some of the coding for the javascript with the live web forms as well as the annotations for the style.css (I did the /htmls by myself)
Project 1:
Take Your First Steps With HTML
Scenario:
You’ve just joined web design agency Webonsai on an internship as a junior developer.

Roman, who is CTO and your internship supervisor, is away on business the week of your arrival. 
So that you can make a start without him, he’s sent you an email assigning your first task: 
- to update a web page for Riding Cities, an association that promotes skateboarding in the region.

Project:
Client: Riding Cities, a skateboarding association

Task: Update the Riding Cities web page as follows:

Step 1: Create the “Founding Members” section
The goal here is to create a new section with “Founding Members” as the title, and text and images in columns. You’ll base this new section on the existing “The Association’s Mission” section. Here are the various actions you’ll need to take:

Action 1: Familiarize yourself with the files 
First, take a look at the existing page and its code. A preliminary analysis of the code will help you understand how it works. 
Next, study the mockup. It will give you an idea of what the association’s new page should look like after the requested changes. 
Action 2: Copy the existing code to reuse it
You can take some lines from the existing code and adapt them to produce the desired result shown in the mockup. 

You need to add a section, and you already have one coded on the website. So it makes sense to start with this piece of code to create the new section.

Copy and paste the “section” tag for “The Association’s Mission” section.

Action 3: Change the HTML code
At this point, you have two identical sections, one below the other.

You will need to change the lower one so that it looks like the “Founding Members” section in the mockup.

Look at the differences between the two sections and change the code where necessary.

Columns: The new “section” tag currently contains four columns. The “Founding Members” section only has three columns.
You’ll need to delete one of the columns so you’re left with only three, as in the mockup.
Text: There are tags containing text, but the text for the new section is different.
Replace the text inside the tags with the text in the mockup.
Images: “The Association’s Mission” section has no images, but you need to display photos in the “Founding Members” section.
Locate the photos in the corresponding folder.
Add the photos to the columns.
Make sure you specify the “src” attribute (it’s important to specify a relative path) and the “alt” attribute (up to you to come up with something appropriate).
Action 4: Use the CSS classes in the code to format the section 
The content for the section now matches the mockup, but the formatting is still way off. This is where the CSS classes come in.

Text: You’ll now need to change the color and alignment of the text elements so that they match the mockup. CSS classes are available in the code to do this:
Find the corresponding class.
Apply it to the text.
Background color: You’ll need to change the background color. Again, a CSS class is available in the code to make this change:
Find the corresponding class.
Apply it to the section background.
Useful resource: The Decorate your content with CSS chapter in the HTML and CSS course, which you can also use for subsequent steps.

Step 2

Step 2: Improve the download button section at the bottom of the page
After creating the “Founding Members” section below the “Association’s Mission” part, the section containing the download button is now at the bottom of the page. You’ll need to make several changes to match the look of the mockup. Here are the actions you’ll need to take: 

Action 1: Add a title and background color to the section
Add “Learn more about our classes” as the section title. Use the existing titles as a guide.
Add a gray background color to the section using an existing CSS class.

Action 2: Change the download button
For now, you can focus on the existing button, transforming it into something close to the first button shown on the mockup.

Shape and color of the button: You’ll notice that the shape of the “Download class schedule” button is different from the buttons in the mockup. 
Add the CSS classes needed to give the button rounded corners and the same color as in the mockup.
Hover effect: In the mockup, the second button shows the desired hover effect, which is the effect you see when you move the mouse cursor over the button.
Add the CSS class needed to produce the mouse hover effect on the button. 
Action 3: Add the second download button and position the buttons as shown in the mockup
First, copy and paste the existing button tag.
At this point, the two buttons should be next to each other. 

Next, put these two buttons in a column:

Change the CSS class applied to the “div” tag containing the two buttons.
Lastly, make the remaining changes to the buttons:

Change the text content of both buttons to match the text in the mockup.
Change both buttons to the correct color by changing one of the CSS classes applied to the button. 
Action 4: Link the right documents to the download buttons
The two download buttons must link to the class schedules for children and adults respectively. Check the document names in the “Documents” folder.

You will then need to populate the “href” attribute for each button so that it links to the right document.

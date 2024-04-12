# COS10026 ASSIGNMENT 1

___

## GUIDELINE

### ~~INDEX~~

This page should contain:
- appropriate title
- a description
- graphic related to the company.

It should contain a menu that links to the other pages on your Website.
This same menu should be in every page of your website with an email link to your student email.

### JOBS
- 2 position descriptions. 
[For one of these your tutor will allocate you a job title from the IT industry.]

The HTML on this page must contain:
- Hierarchically structured headings of at least 2 levels
- More than one \<section>
- An \<aside> with appropriate content
- At least one ordered list
- At least one unordered list
- The page should also have an appropriate footer.

Your job descriptions should be concise but as a minimum include:
- Company’s position description reference number (5 alphanumeric characters)
- Position title
- Brief description of the position
- Salary range
- The title of the position to whom the successful applicant will report
- Key responsibilities. A list of the specific tasks that are to be performed
- Required qualifications, skills, knowledge and attributes. These should be divided into “essential” and “preferable”.

These requirements should include such things as:
- programming languages required
- number-of-years of experience required

The content of the job description should be appropriately structured with:
- headings
- sections
- subsections
- lists
- Using the appropriate HTML elements.

### APPLY

HTML5's data validation should be used to check the user’s input.

The form will allow a potential applicant to fill in the following:

| Field                                                            | Format requirement                               |
|------------------------------------------------------------------|--------------------------------------------------|
| Job reference number                                             | exactly 5 alphanumeric characters                |
| First name                                                       | max 20 alpha characters                          |
| Last name                                                        | max 20 alpha characters                          |
| Date of birth                                                    | dd/mm/yyyy                                       |
| Gender                                                           | radio inputs grouped using a fieldset and legend |
| Street Address                                                   | max 40 characters                                |
| Suburb/town                                                      | max 40 characters                                |
| State                                                            | drop down selection                              |
| Postcode                                                         | exactly 4 digits                                 |
| Email address                                                    | validate format                                  |
| Phone number                                                     | 8 to 12 digits                                   |
| Skill list - the last item in list should read “Other skills...” | checkbox inputs                                  |
| Other skills                                                     | textarea                                         |
- All inputs should have labels.
- All form values, except the comment textarea are ‘required’ or have a default value (e.g. select and checkbox inputs).
- The user should not be able to submit the form if any of these required fields are blank.
- The form should have a submit button labelled "[Apply](https://mercury.swin.edu.au/it000000/formtest.php)"

### ABOUT

| Information                                             | HTML element to be used  |
|---------------------------------------------------------|--------------------------|
| Your group name                                         | Definition list          |
| Your group ID                                           | Definition list          |
| Your tutor’s name                                       | Definition list          |
| Course you are doing                                    | Definition list          |
| Photo of your group                                     | 100k HTML figure element |
| Your timetable (assume you all have the same timetable) | HTML table               |
| A mailto link to your group email                       | ?                        |

It could also include group profile:
- Programming skills
- Working experiences
- Interests
- Information that is related to your group.

This extra information gives you an opportunity to extend the techniques you apply in your assignment, and could include:
- Demographic information about all of you
- Description of your hometown
- A list of your group members’ favourite books, music, films etc.

### CSS

- No style markup should be included in your HTML file.
- consistent ‘look and feel’, particularly common elements such as menus, headers and footers.

Your pages should follow basic usability / accessibility principles:
- distinguishable foreground
- background colour
- font readability
- One single external stylesheet that applies to all your Web pages.
- This file should be named style.css
- placed in a styles folder on the server.

The stylesheet should style the common elements on all your web pages,
and address the following specific style requirements.

Comments:
- The CSS should include comments at the beginning of the CSS file to identify author and purpose.
- Individual line comments should be used as necessary to explain particular styles and explain where they are applied.

Selectors:
- element, #id, .class, grouping, contextual
- pseudo class, pseudo element

Menu:
- The menu should have its own set of styles applied.
- Use a background colour.

Index Page:
- display a background graphic.

Jobs Page:
- \<h1> elements should have their font variant, size and family etc. set using the short-hand font property.
- The \<aside> should be 25% of the width of page and float to the right.
- The \<aside> should have a coloured border with an appropriate margin and padding.
- The footer should cover the full width of the page the footer text should be in a small font and centred in the footer

About Page:
- Style the definition list so that each <dt> is on the left and the <dd> on the right in a single line.
  Set the dt to have a common width.
- The photo should be styled with a single border using the short-hand border-property,
  and the figure should be floated to the right of the definition list
- \<table> should be centred within the section, headings in bold, table cells with a background colour specified in hexadecimal format
- The email should be styled similarly to the definition list.

All pages:
- should have a fluid layout (the page should “Reflow” on page resize).
- Other CSS selectors and properties can be used as necessary and appropriate for the presentation
- Do not include any proprietary CSS mark-up, such as –moz- or –webkit etc.
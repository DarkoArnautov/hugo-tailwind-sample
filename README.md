Approach
In this project, the goal was to implement a well-structured content management system (CMS) with Cloudcannon compatibility. The approach involved creating a series of collections that could be easily managed through Cloudcannon's interface.

Key Steps Taken:
Content Organization:

I organized content into different collections, including feature, footer, header, result, revenue, and trusted, each stored in its respective markdown file within the content/ directory.
Each collection corresponds to a specific part of the website, ensuring that non-technical editors can easily manage content without touching code.
Cloudcannon Configuration:

A cloudcannon.config.yml file was created to specify paths for each collection and group them under a "Content" heading in the Cloudcannon sidebar.
The configuration defines each collection’s editable fields, including text fields, images, and arrays, making the interface user-friendly for non-technical editors.
Usability Focus:

Emphasis was placed on making the editor interface simple and intuitive for non-technical users, with clear labels and types for each field (e.g., text, textarea, image, and array).
Assumptions
Non-technical Users: It was assumed that the users who will manage the content via Cloudcannon would not have technical expertise. Therefore, the focus was on creating a user-friendly configuration and structuring content so it could be easily edited.
Content Types: Assumed that the content primarily consists of textual data, images, and arrays for managing multiple items (like team members or services).
Cloudcannon Setup: Assumed that Cloudcannon would be used for editing and that its features, such as sidebar management and file-based collections, would be compatible with the project’s structure.
Challenges
Complex Array Handling:

One challenge was structuring the array fields for dynamic content, such as team members or services. The flexibility of these fields had to be balanced with ensuring that the content editor could easily add and manage multiple items without feeling overwhelmed by too many options.
Ensuring Compatibility:

Ensuring compatibility between the content structure and Cloudcannon’s features was a bit tricky. For instance, making sure that Cloudcannon could correctly interpret and allow for easy editing of images and arrays required extensive testing.
Usability for Non-Technical Editors:

Ensuring that the CMS would be simple enough for non-technical editors to use without feeling confused or overwhelmed was a key consideration. Clear labeling, intuitive field types, and good groupings of content collections helped overcome this.
File Path Management:

Managing paths for the markdown files and ensuring they were correctly mapped in the cloudcannon.config.toml file took some time, particularly when it came to organizing collections in a way that made sense for the editorial workflow.
Future Improvements
Dynamic Content Rendering: In the future, I plan to introduce dynamic content rendering to allow for real-time previewing of content as it’s being edited.
Custom Field Types: Adding custom field types, like a rich text editor, to give editors more flexibility in formatting their content.

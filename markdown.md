# Version Control Markdown Scripting
*   **Description**: To explain about the markdown in version control,  Formates of markdown scripting and html scripting using in markdown scripting.

*   **Markdown**: Markup is a lightweight scripting language that can be scripted very easily. Even its scripting codes can be read and understood very easily. It is used to create files that distribute information on Git servers. HTML scripting can also be used in conjunction with it.

*   **Markdown Formates**: The following explains the Markdown formats and their uses for scripting Markdown files created with the .md extension.
    *   **Headings**: Headings are used to create headings in Markdown files.

    ```text
    # Heading 1
    ## Heading 2
    ### Heading 3
    ```
    -   The "# Heading 1" heading in this is the top-level heading. After the #, enter a tab space and then type the required heading text.
    -   The "## Heading 2" heading in this is the second-level heading. After the ##, enter a tab space and then type the required heading text.
    -   The "### Heading 3" heading in this is the third-level heading. After the ###, enter a tab space and then type the required heading text. This can be done up to the sixth level of heading. The number of #'s should be increased according to the level of the heading.
    <p style="line-height:2.0;"></p>

    *   **Bold**: Bold is used to create bold text in Markdown files.
    
    ```text
    **Bold Text**
    ```
    -   If you put two *'s at either end of a text, that text will appear as bold text.
    <p style="line-height:2.0;"></p>
    
    *   **Italic**: Italic is used to create italic text in Markdown files.
       
    ```text
    *Italic Text*
    ```
    -   If you put one * at either end of a text, that text will appear as italic text.
    <p style="line-height:2.0;"></p>

    *   **Strikethrough**: Strikethrough is used to create strikethrough text in Markdown files.
    
    ```text
    ~Strikethrough Text~
    ```
    -   If you put two ~'s at either end of a text, that text will appear as strikethrough text.
    <p style="line-height:2.0;"></p>
    
    *   **Code**: Code is used to create code in Markdown files.
    
    ```text
    ```Code Text```
    ```   
    -   If you put three ` at either end of a text, that text will appear as code text. But at the beginning of this, you need to specify which code this is. Like ```javascript.  In this way, if it is JavaScript, you should enter JavaScript, if it is Bash script, you should enter Bash, if it is Python, you should enter Python, and if it is Text, you should enter text.
    <p style="line-height:2.0;"></p>

    *   **Blockquote**: Blockquote is used to create blockquote in Markdown files.

    ```text
       > Blockquote Text
    ```
    -   If you put > at the beginning of a text, that text will appear as blockquote text. Blockquote is used for specifying the important text.
    <p style="line-height:2.0;"></p>

    *   **List**: List is used to create list in Markdown files.
    
    ```text
    - 1st List Text
    - 2nd List Text
    ```   
    -   If you put - at the beginning of a text, that text will appear as list text. List is used for creating bullet pointlists in Markdown files.
    <p style="line-height:2.0;"></p>

    *   **Ordered List**: Ordered List is used to create ordered list in Markdown files.
    
    ```text
    1. Ordered List Text
    2. Ordered List Text
    ```   
    -   If you put 1. at the beginning of a text, that text will appear as ordered list text. Ordered List is used for creating numbered lists in Markdown files.
    <p style="line-height:2.0;"></p>

    *   **Task List**: Task List is used to create task list in Markdown files.
    
    ```text
    - [ ] Task List Text 1
    - [ ] Task List Text 2
    ```   
    -   If you put - [ ] at the beginning of a text, that text will appear as task list text. Task List is used for creating task lists in Markdown files.
    <p style="line-height:2.0;"></p>

    *   **Link**: Link is used to create link in Markdown files.

    ```text
    [Link Text](Link URL)
    ```
    -   If you put [Link Text](Link URL) at the beginning of a text, that text will appear as link text. Clicking on the link text will access and display the file provided in the link URL.
    <p style="line-height:2.0;"></p>
    
    *   **Image**: Image is used to create image in Markdown files.

    ```text
    ![Image Text](Image URL)
    ```
    -   If you put ![Image Text](Image URL) at the beginning of a text, that text will appear as image text. Clicking on the image text will access and display the image provided in the image URL.
    <p style="line-height:2.0;"></p>
    
    *   **Table**: Table is used to create table in Markdown files.
    
    ```text
    | Table Text 1 | Table Text 2 |
    | Table Text 3 | Table Text 4 |
    ``` 

    ```text
    | Table Header 1 | Table Header 2 |
    | -------------- | -------------- |
    | Table Text 1   | Table Text 2   |
    ```  
    -   If you put | Table Text 1 | Table Text 2 | at the beginning of a text, that text will appear as table with that text. But to get a table with headings, you must use the second method.
    <p style="line-height:2.0;"></p>
    
    *   **Horizontal Rule**: Horizontal Rule is used to create horizontal rule in Markdown files.
    
    ```text
    ---
    ```   
    -   If you put --- at the beginning of a text, that text will appear as horizontal rule text. 
    <p style="line-height:2.0;"></p>
    
    *   **Emphasis**: Emphasis is used to create emphasis in Markdown files.
    
    ```text
    *Emphasis Text*
    ```   
    -   If you put * at the two ends of a text, that text will appear as emphasis text. That means bullet point text. 
    <p style="line-height:2.0;"></p>
    
*   **HTML Formates in Markdown**: HTML formats can be used to script Markdown files, as explained below.
    
    *   **Line Height**: HTML line-height are used to create line height in Markdown files.
    
    ```text
    <p style="line-height:2.0;"></p>
    ```
    -   If you put <p style="line-height:2.0;"></p> at the beginning of a text, that text will appear as line height text. The number after line-height is the line height of the text. The default line height is 1.0. You can increase or decrease the line height by increasing or decreasing the number after line-height.
    <p style="line-height:2.0;"></p>

    *   **Underline**: HTML underline are used to create underline in Markdown files.
    
    ```text
    <u>Underline Text</u>
    ```
    -   If you put <u> at the beginning of a text and </u> at the end of a text, that text will appear as underline text. 
    <p style="line-height:2.0;"></p>

    *   **Font Size**: HTML font-size are used to create font size in Markdown files.
    
    ```text
    <font size="2">Font Size Text</font>
    ```    
    -   If you put <font size="2"> at the beginning of a text and </font> at the end of a text, that text will appear as font size text. The number after font-size is the font size of the text. The default font size is 1.0. You can increase or decrease the font size by increasing or decreasing the number after font-size. 
    <p style="line-height:2.0;"></p>

    *   **Font Color**: HTML font-color are used to create font color in Markdown files.
    
    ```text
    <font color="red">Font Color Text</font>
    ```    
    -   If you put <font color="red"> at the beginning of a text and </font> at the end of a text, that text will appear as font color text. The number after font-color is the font color of the text. The default font color is black. You can change the font color by changing the number after font-color. 
    <p style="line-height:2.0;"></p>

    *   **Image Linking and Resizing**: HTML image linking and resizing are used to create image linking and resizing in Markdown files.
    
    ```text
    <img src="Image URL" alt="Image name" width="100" height="100">
    ```    
    -   If you put <img src="Image URL" alt="Image name" width="100" height="100"> at the beginning of a text and </img> at the end of a text, that image will appear. The width and height are the width and height of the image. The default width and height is 100. You can increase or decrease the width and height by increasing or decreasing the number after width and height. The alt is the image naming section. The src is the image URL section.
    <p style="line-height:2.0;"></p>
    
    *   **Video Linking**: HTML video linking are used to create video linking in Markdown files.
    
    ```text
    <iframe width="560" height="315" src="Video URL" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    ```    
    -   If you put <iframe width="560" height="315" src="Video URL" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> at the beginning of a text and </iframe> at the end of a text, that video will appear. The width and height are the width and height of the video. The default width and height is 560 and 315. You can increase or decrease the width and height by increasing or decreasing the number after width and height. The src is the video URL section. The frameborder is the frameborder of the video. The allow is the allow of the video. The allowfullscreen is the allowfullscreen of the video. The frameborder is the frameborder of the video. The allow is the allow of the video. The allowfullscreen is the allowfullscreen of the video. 
    

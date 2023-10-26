# age-verification-popup
This is code to add Age Verification popup with Yes &amp; No button

1. From your Shopify admin, go to Online Store > Themes.
2. Find the theme you want to edit, and then click Actions > Edit code.
3. Click on the Snippets folder to expand and view its content.
4. Under the Snippets folder, click on Add a new snippet.
5. Name your new snippet age-check, and click Create snippet. Your age-check snippet will open in the online code editor.
6. In a new browser tab, open the following file.
7. Copy all of the code you see there and return to your Themes page.
8. In the online code editor, paste the code you copied into your age-check.liquid snippet.
9. Save your changes.
10. In the Layouts folder, locate and click on your theme.liquid file to open it in the online code editor.
11. In the online code editor, scroll down a bit until you see the opening <body> tag.
12. Right after the opening <body> tag, paste the following code:

{% render 'age-check' %}
 

This will include the age-check.liquid snippet at the very beginning of the body content of your theme file.
Click Save to save your changes.

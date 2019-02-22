+++
title = "Example Page Title"
menuTitle = "This text can differ from the 'title'"
+++

This is your root index file, meaning it's the first page a user will see when clicking on your docs project folder.

You configure the page title by completing the 'front-matter' content located at the beginning of this markdown file.

Below you will see a "Note" callout. Check the markdown text of this page to see how it's created. Refer to our Confluence documentation for information on other callout types, as well as other shortcodes you can use in your page.

{{% notice note %}}
If you're previewing this page using a local copy of Hugo, along with the website's design and theme elements, it will <u>NOT</u> appear in the TOC nav sidebar. Otherwise, this page should show up as your Project Repo name in the nav bar.
{{% /notice %}}  

Below is a "Children" shortcode which shows a list of all the pages below the current page.

## Site contents

{{% children style="li" %}}
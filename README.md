# revit-plugin-fun

<b>Description</b><br>
This is a filterable and searchable tool library that will be embedded via an iframe in LumApps. The HTML, CSS, and JavaScript are combined into a single file for ease of use.

<b>How to Edit</b><br>
Locate the HTML file
The entire project is contained within the index.html file. You can edit this file directly for any changes.

<h1>Sections of the HTML File</h1><br>

<b>HTML Structure:</b> Handles the layout and content of the tool library.
CSS (Embedded in <style>): Controls the appearance, including layout, colors, and font styling.
JavaScript (Embedded in <script>): Provides functionality for searching, filtering, and dropdown toggles.
To Update the Filters/Search

<b>Filtering logic:</b> JavaScript functions for filtering by <i>data-install-type, data-where-type,</i> and <i>data-managed-by</i> attributes.<br><br>
<b>Search functionality:</b> The search feature uses the entered title and description of each tool. No <i>data-title</i> or <i>data-keywords</i> attributes are used—just what is visible in the HTML.<br><br>
<b>Testing Changes:</b>
After making edits to the file, open it in a browser to test the functionality before committing changes.
Ensure that the search and filter functions work as expected, with particular attention to ensuring the search and filtering functions interact seamlessly, so both can be applied simultaneously and reflect changes in either.
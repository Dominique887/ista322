## CH5

### By:Dominique, Austin



1. A view engine processes ASP.NET content and looks for instructions. Usually to insert dynamic content into the output sent to a browser.
2. A razor is the name of the MVC framework view engine.
3. Views express parts of the model to the user by displaying it and formats data.
4. An @ tells razor that following it is code.
5. A @: tells razor that the following statement isnt code.
6. Standard formatting for all pages can be done using a layout.
7. The difference is you can set the attributes using curly brackets instead of just a colon.
8. The view start file is used to automatically set a value for the layout property. Its located in the Views folder.
9. A razor code block is the @{}. It tells razor that all the content inside the curly brackets are code.
10. The roles of Action methods are to pass a view model object to the view, and the role of the view is to use the view model object to present content to the user.
11. The @using statement brings a namespace into focus the same way it does with c# code, which is what razor interprets it as. An example of using it would be: @using System.Console; @Write("using statement");
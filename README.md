## Project Structure:
source/

	constants/(static texts)
	fonts/(google fonts)
	images/(necessary images)
	js/
		actions/
		api/(API calls)
		components/(common components)
		reducer/
		store/
 		views/(pages)
		styles/
		app.js
		index.js
		routes.js	



## Coding standards:

•	Use a linter to make your code easier to review

•	Avoid Inline CSS as and when possible (a CSS class should be created when there are more than 2 CSS attributes).

•	Create multiple files instead of writing a big file.
•	Clean code is self-commenting. Use comments only to explain complex functions.
•	Review your own code before creating a pull request
•	Split your code into multiple smaller functions
•	Create multiple files instead of writing a big file
•	Be very careful while naming your files
•	Always write tests for your code
•	De-structuring your props is a good way to help make your coder cleaner and more maintainable.
•	Putting imports in an order
	a. React import
	b. Library imports (Alphabetical order)
	c. Absolute imports from the project (Alphabetical order)
	d. Relative imports (Alphabetical order)
	e. Import * as
	f. Import ‘./<some file>.<some extension>
Each kind should be separated by an empty line.
•	Filename: Use pascal case for filename. Example: ReservationCard.jsx
•	Component name: Use pascal case
•	Component filename: Use camelCase. Example: commonUtils.js
•	Folder name: Use camel Case 
•	Test files should be named the same as the component or non-component file.
•	CSS files should be named the same as the component Pascal Case. Global1 CSS which applies to all components should be placed in global.css and should be named in camelCase
o	Example: LoginScreen.css (for components), global.css (for global styles)


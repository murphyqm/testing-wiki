# Testing out a wiki structure

Testing out various options for an easy-to-use wiki.

If required, the index of the wiki can just copy the content from this readme.

The aim of this is to:

- Be very easy to use from an organisation/logistics point of view: no need to build anything or run anything
- To be totally doable and quick through the browser
- To encourage inclusion of useful team-relevant information (requiring a pull request)
- To be regularly pruned etc., but also to have a secure version control history so previous versions can be found if needed
- To work identically to just a plain git repo but with better in-file searching.

## To contribute

1. Create or upload a new file/folder and file
  ![Screenshot of GitHub interface and the new file option.](https://github.com/user-attachments/assets/3761d7cb-eb42-406e-a17c-0d5813f7519c)


2. Either upload a markdown file, or create and edit one in browser. You can paste in images.
  ![Screenshot of GitHub file editor with text that reads "Here is my H1 title" and then "Here is some content"](https://github.com/user-attachments/assets/074ed78f-462d-42ec-adc7-256e8e6521ca)


3. Add a file title. You can add it to a folder/create a new folder path here too by typing in `folder_name/file_name.md`. GitHub will automatically parse this. Ensure you give your file an `.md` file ending. We can decide on naming conventions.
   ![Screenshot of GitHub file editor with the file path dialogue highlighted and reading "path_to_file"](https://github.com/user-attachments/assets/028fe400-1487-4c9c-8cac-4f56e2bd5738)


4. You can hit "Commit changes" when you want to save, and will be prompted with this dialogue to create a new branch. You can commit the changes to the branch (by clicking "Propose changes") and come back to modify it later.
   ![Screenshot of GitHub dialogue instructing you to add a commit message, with a button highlighted saying "Propose changes"](https://github.com/user-attachments/assets/64b72356-86ea-4d96-917c-a0497369d276)


5. This will open the pull request dialogue. You can leave this page if you want to make more changes, or can select "Create pull request". Once a pull request is created, GitHub actions will automatically run a test to see that the website will compile.
  ![Screenshot of GitHub pull request drafting screen.](https://github.com/user-attachments/assets/05ab5e51-7b52-4d7f-987e-8f7a2501083a)

6. You can see if your additions built correct, and merge the pull request.
  ![Screenshot of GitHub pull request screen with passed checks.](https://github.com/user-attachments/assets/c072cbc7-af5f-43d2-8dab-f9d2f9e8147e)




All you need to do is visit the GH repo and add a file in the appropriate folder. You can also create a subfolder if needed (to create hierarchical categories).

You will be prompted to create a new branch to store your addition. You can wait until you're happy with your addition before merging it back into the main branch. The site will then render and update to include your addition.

If you want to see the rendered output of a work in progress, you can always put it in the "misc" folder and then run the workflow manually to check it looks correct, or simply add WIP (for work in progress) to the title.

Each page of the rendered site also has a link to the repo location.

You can also see the authors/contributors of any specific article by clicking the "view source" link to the right.

## For findability

If your article/note is relevant to a certain area or field, but does not contain terms that someone might search for, consider adding in a list of keywords or themes somewhere in the body of the article so it will be picked up by the search function.

SEATTLE SNAKE DRAFT – HOW TO SHARE A WORKING LINK

WHY THE TEXT-MESSAGE PREVIEW LOOKS EMPTY
Apple Messages / Quick Look and cloud-drive previews may show HTML and CSS but disable embedded JavaScript. These tools need JavaScript to populate the player table, weights and optimized rosters. HTML code cannot enable JavaScript inside a restricted preview.

BEST METHOD: HOST THE FILES AS A WEBSITE (GITHUB PAGES)
1. Sign in to github.com. Create a PUBLIC repository, e.g. seattle-snake-draft.
2. Upload ALL THREE files to the root of the repository:
   index.html, with_ops.html, without_ops.html
3. Repository > Settings > Pages > Build and deployment > Deploy from a branch.
4. Select main branch and /(root), then Save.
5. Once published, copy the website URL shown on Pages, e.g.
   https://YOUR-USERNAME.github.io/seattle-snake-draft/
6. Text this HTTPS link to teammates. It opens in a regular browser and executes the app's JavaScript.

ALTERNATIVE – SHARE THE HTML FILE ITSELF
Send with_ops.html or without_ops.html as an attachment. Recipients must DOWNLOAD the file and use Open With > Google Chrome (or Safari), rather than opening it in a Messages/Drive preview.

IMPORTANT
- The files are self-contained (no external library or web API).
- The page does not synchronize picks between multiple users.
- Some schools prohibit any AI use in coursework; check your course policy before sharing or using the tool.

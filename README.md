# Asciidoc-link-checker
Tool to check each link of each asciidoc inside a wiki of a gitHub repository
# How to use
1. Clone this repository into a local folder on your computer
2. Open the console and move to that folder
3. Install the tool globally:

	`npm install -g @oasp/asciidoc-link-checker`

4. Clone the wiki you want to check links:

	`git clone https://github.com/my-repository/my-repository.wiki.git`

5. Start the checkout:

	`$ linkchecker ./my-repository.wiki/`

The tool will check each link of each asciidoc inside the wiki searching those links that are wrong

# Output
When the check is done, you will see on your console the links that didn't work along with one of this messages:

If all links are correct you will see:
'Done: All links are correct'

Otherwise you will see:
'Done: Some link failed' 

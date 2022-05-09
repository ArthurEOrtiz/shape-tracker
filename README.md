# Modern JavaScript Development
## Shape Tracker Application




 ### Notes

  _From the lesson plan_

  _"If you do accidentally add a file that should be ignored to your repository, you'll need to remove it. You can do so by running $ git rm -r --cached [FILE-NAME], where [FILE-NAME] is the name of the file that shouldn't be tracked. Git will no longer track the file"_

  _"If you find yourself needing to remove a file from a repository's history, see [Removing Files from a Repository's History](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github)."_

  -"We could also verify all the changes we've made in ready-to-commit.js since our last commit by using the $ git diff command. If we run $git diff ready-to-commit.js, we'll see a list of these changes. It's generally a good idea to do a quick git diff before committing files. That way, we can verify we're committing the right code."_

    * First, get the -git status.
     * Use  -git diff [FILE-NAME] to verify that the changes look correct.
     * Use  -git add [FILE-NAME] to select a file to commit. Multiple files can be committed at once if they are related to the same feature - but should be added one by one by doing $ git add file1 file2 etc.
     * Run -git commit and add a great commit message.

  For running $ git diff - github desktop has a better UI to quickly visualize all changes made to a repo. 

  For the HTML plugin many students have found that their projects load faster in development when they use inject: 'head' instead of inject: 'body'. Ultimately, you may use either option based on your preferences. As always, keep in mind that having the script at the end of the body is preferable for production sites.

  _[webpack documentation](https://webpack.js.org/)_

  Try using import '../css/styles.css' in the code if we get failures again. 

  #### Issues 

  Ran into the same issue when working through the bundling CSS prompt. It failes to apply the css page. The remedy was to delete the node_modules and then run npm install and npm run build. I think this is the equivalant of turning it off and turning it back on again. I also changed line 2 of index.js to "import '../css/styles.css';"

   

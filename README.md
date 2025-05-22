Name: Svetlana Bobiles

### Check Your Understanding

1) I would fit my automated tests in my recipe project development pipeline within a Github Action that runs whenever code is pushed because the tests are automatically run, and good to have when new code is pushed because if it's in a pull request it's good to see if it's ready before merging. The other options aren't good because if you manually run them locally before pushing code, it's not automatic anymore and what if someone on the development team forgot to test it locally. And to run them all after all development is completed is very risky because you shouldn't test your code when your done, it should be while writing it so you can catch each error.

2) Yes because if an end-to-end test is supposed to mimic a user's actions then it should also return the correct output.

3) The difference between navigation and snapshot mode is that navigation mode analyzes the page right after it loads and snapshot analyzes the page in its current stage. It's better to use navigation mode for an overall performance, but it can't process changes in content. While in snapshot mode it's good for finding accessibility issues but it can't analyze Javascript or changes in DOM.
4) Based on the lighthouse report we can improve the website by compressing the images so it can save storage when fetching and make it faster for the images to load, add a meta viewport tag so the website can be adaptable for more screen sizes, and lastly preconnnect to required origins which will help the page run faster too.
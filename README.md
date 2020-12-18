**PHP EXERCISE - migration solution**

Our client is migrating from PHP 5.6 to 7.4.

This is a small piece of code that needs to be prepared for this migration.
Client is not interested in waiting for full refactoring, therefore we need to have smooth transition period.
Keeping in mind that we use Symfony (4.4) as a framework for the backend system, ideally, we would like to see some kind of transformation to it.
The decision how to migrate is solely yours. There is no initial guidelines, however, you can follow the steps below:


- describe your migration plan
- if there is more than one solution, please recommend the better one and explain the difference between them
- apply necessary changes and best known practices
- make sure output behaviour for both PHP versions remains the same or as close as possible
- make sure we can use any or both versions at the same time
- describe bootstrap process for each php version (e.g. below)


Project bootstrap example:

Windows: `cd public & php5.exe -S 127.0.0.1:8080`

Linux: `cd public & php5 -S 127.0.0.1:8080`



_PLEASE MAKE SURE:_
- Please use Github and set up a git repository
- Please ensure you have at least one commit within the first hour
- We want to be able to know how you develop, so we will review your commit history
- Send us the Github link to your repository once you are happy

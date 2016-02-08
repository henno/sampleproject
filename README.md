This is a test.

The assignment
===
"As an authenticated user, I want to sort the table on the Users page by clicking on the table headers".

Remember that less is more: nothing that has not been defined in the user story should be assumed. Choose the fastest means to implement what the story says. 

Setup the project
====
1. Fork the project and clone the fork to your computer
2. Copypaste config.sample.php to config.php and adjust settings there
3. Import doc/database.sql to your local mysql database
4. Run composer install
5. Install codeception globally to your computer or use vendor/bin/codecept
6. Test that http://localhost/sampleproject/ opens and you can click on Users and log in with demo:demo.

Do the story:
===

1. Create a new acceptace test: run codecept generate:cept acceptance "UsersPageTableIsSortable"
2. Write acceptance test in tests/acceptance/UsersPageTableIsSortable.php (don't forget to include login steps)
3. Implement story. Put script links to master_template.php. The table is located in users_index.php
4. Run codecept run to see that the story passes
5. Commit with the message of the 

Send me your results
===
1. Send me the link to your pull request along with how much would that story have cost me, if it was a real story for a real project.

This is a test.

To pass the test:

Setup the project
====
1. Fork the project and clone the fork to your computer
2. Copypaste config.sample.php to config.php and adjust settings there
3. Import doc/database.sql to your local mysql database
4. Run composer install
5. Test that http://localhost/sampleproject/ opens and you can click on Users and log in with demo:demo.

Do the story:
===
1. Install codeception globally to your computer or use vendor/bin/codecept
2. Run codecept generate:cept acceptance "UsersPageTableIsSortable"
3. Write acceptance test in tests/acceptance/UsersPageTableIsSortable.php (don't forget to include login steps)
4. Implement story. Put script links to master_template.php. The table is located in users_index.php
5. Run codecept run to see that the story passes
6. Create pull request to me with this change. 
7. Send me the link to your pull request along with how much would that story have cost me, if it was a real story for a real project.

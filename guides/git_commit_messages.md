# Git Commit Message Principles

The following guidelines for Git commit messages are put in place to make it easy to follow the developments in the various Git branches. We would like to have a concise and consistent commit history so that it becomes an effective tool for communication between developers .For inspiration have a look at the [Spring Boot](https://github.com/spring-projects/spring-boot/commits/master) project.


## Principles

1. **Limit the subject line to 60 characters:** Ensure that the subject is informative, short and concise and fits within the GitHub commit history for easy browsing.

2. **Capitalize the subject line:** Write proper English and being all subject lines with a capital letter. For example use  "Introduced performance boost option", not "introduced performance boost option".

3. **Do not end the subject line with a period**: Trailing punctuation is unnecessary in subject lines and space is precious when limiting the subject line length.

4. **Use the imperative mood in the subject line:** Imperative means as if giving a command. Start the subject lines with a verb. Examples: "Update spacecraft launch module", "Refactor JSONB user type". Good verbs to start the subject with are: Add, Fix, Start, Refactor, Reformat, Optimize, Introduce, Document.

5. **Use the body to explain what and why:** Use git commit message bodies to communicate what you are doing and why. This is very helpful to other developers to stay up to date on developments in master.

6. **Avoid generic messages**: Avoid using generic commit messages like "Minor fix" and "Clean-up", rather explain what you are doing any why.

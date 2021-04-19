## Professional Self-Assessment

The skills that I've learned from my coursework at Southern New Hampshire University has helped prepare me for employment in multiple ways. First, it gave me a foundation for learning data structures & algorithms. From my intro to data structures & algorithms class, I've been able to learn and use different types of algorithms and data structures to solve many different problems. Learning the thought process behind basic algorithms, such as different sorting algorithms, has opened my up to different ways to approach solving an issue that is in front of me.

Another important skill that has been strengthened throughout my time in my courses is collaboration. Working with other students to build and create projects helped me learn how collaboration works in software development, including strengthening my applicable knowledge of git, proper communication with teammates, and picking up tasks that are laid out. 

The artifact that I'm presenting in this ePortfolio represents the skills that I've learned in regards to applicable databse knowledge, software design and engineering, and algorithms and data structures. This specific artifact and enhancement was picked as I felt it demonstrated all of those areas together, as well as demonstrating my ability to pick up issues on an established codebase. 

## Artifact

### [Kumoricon Registration](https://github.com/kumoregdev/registration)

#### [Code Review](https://learn.snhu.edu/d2l/common/viewFile.d2lfile/Database/MjIyMTE4MDk/caleb_dederick_2-2_code_review.mp4?ou=692037)

Kumoricon Registration is a system that is used by volunteers of Kumoricon to check-in attendees. This includes printing badges, checking-in pre-registered members, and registering new attendees. This artifact has been included in my ePortfolio as it's something that I've helped with by picking up issues in the github repository over the past year. 

The specific enhancement that I'm presenting is an enhancement that automatically creates registration user accounts. Previously, registration staff members' accounts were created manually. With this new enhancement, when the staff members are imported into the system, their user accounts are created alongside their person profile. 

Link to enhancement: https://github.com/kumoregdev/registration/commit/b912c5963ce713530f9885563016ceba7482e74c

I learned a decent amount while working on this enhancement. Specific to the artifact, I learned how staff import works, and how automatic user account creation could exist within the import function. Another area that I learned a lot about was the PostgreSQL database. A new key needed to be added into the database to allow for users to have a unique identification. This process taught me how to add a new field to an existing schema as well as how to wipe and rebuild the schema from scratch. 

For software design and engineering, working on this artifact improved my ability to get familiar with and enhance an established repository. It helped me learn how to work with the frameworks within the project while applying consistent coding standards that are present in the codebase. 

For algorithms and data structures, a simple algorithm was used to ensure that usernames generated for each account were unique, and that each created user was not a duplicate. Essentially, the user would be attempted to be found by username (last name appended to first initial of first name). If this returns null, then the username is returned. If a user is found from the username, the unique ID for the user is compared to the newly created user. If the IDs match, the username pulled is the new user and a new user is not created. If the IDs don't match, this means that a user exists with the same username to someone that is not the current user. A simple iteration is then done through the letters in the user's name until a unique username can be created. 


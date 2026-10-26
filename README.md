**Software Testing and Quality Assurance Portfolio**

About This Portfolio

This repository highlights work I completed in my software testing course. Project One focused on building and testing a contact service, while Project Two gave me the opportunity to evaluate my testing approach and explain what I learned. Together, these artifacts show how I use requirements, automated tests, and careful design to improve software quality.

Portfolio Artifacts

Project One — Contact Service

Contact.java — Defines a contact and the rules its data must follow.
ContactService.java — Manages contacts in memory, including adding, updating, and deleting records.
ContactTest.java — Tests the contact object's validation rules.
ContactServiceTest.java — Tests the service's behavior and error handling.

Project Two — Summary and Reflections Report

A report discussing my unit testing approach, the quality of my tests, and the lessons I learned about software testing and automation.
Reflection
How can I ensure that my code, program, or software is functional and secure?

I have learned that getting a program to run is only the first step. I also need to make sure it behaves correctly when users enter unexpected or invalid information. For the contact service, I used JUnit tests to check requirements such as unique contact IDs, required fields, character limits, and phone number formatting. I also considered how the service should respond when someone tries to add a duplicate contact or update or delete a record that does not exist.

Automated tests make it easier to find problems early and check that later changes do not break existing features. To keep software secure, I would build on that foundation with input validation, careful error handling, appropriate access controls, and regular reviews of dependencies. Unit tests are important, but they are one part of a larger testing and security process.

How do I interpret user needs and incorporate them into a program?

I start by turning the user's requests into specific behaviors that I can build and test. In this project, the requirements explained what information a contact needed, which values were allowed, and which operations the service had to support.

Rather than treating those details as suggestions, I used them to guide the class design and create tests for both valid and invalid inputs. This helped me see how even a small requirement, such as a phone number needing exactly ten digits, affects the code and the tests. If a requirement is unclear, I would rather ask questions early than make an assumption that causes problems later.

How do I approach designing software?

My approach is to understand the requirements first, then divide the work into smaller pieces with clear responsibilities. For the contact service, Contact.java represents an individual contact, while ContactService.java handles the collection of contacts and the operations performed on them. Keeping those responsibilities separate made the code easier to follow and test.

I prefer to build a working piece, test it, and make improvements before moving on. This course reinforced that good design is not just about making the program work today; it is also about making the code understandable, maintainable, and easier to change in the future.

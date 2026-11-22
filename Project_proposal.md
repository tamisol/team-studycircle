# FindBack

## 1. Project Overview

**FindBack** is a campus lost and found platform designed to help students find their lost belongings and return items they find on campus.

Students lose items such as phones, wallets, ID cards, books, chargers, keys, and other personal belongings. In most cases, they have to ask around, check different locations, or post in group chats to see if anyone has found their item. This can make the process of recovering a lost item difficult.

FindBack will provide one platform where students can report items they have lost or found. Other students can then search through the reports to see if an item they are looking for has been posted.

---

## 2. Problem Statement

Students can lose personal belongings in different places around campus. When this happens, there is no single platform where they can easily report the item and check if someone else has found it.

Students usually have to rely on friends, class groups, WhatsApp groups, or physically search different locations.

This can lead to:

- Students spending a lot of time looking for lost items.
- Lost items remaining unclaimed.
- Difficulty connecting the owner of an item with the person who found it.
- Important belongings being permanently lost.
- Lost and found information being spread across different platforms.

FindBack is intended to provide a simple and organized way for students to report and search for lost and found items.

---

## 3. Proposed Solution

We propose to develop **FindBack**, a web-based lost and found platform for Babcock University students.

Students will be able to register and log in using their matriculation numbers. After logging in, they can report an item as either **Lost** or **Found**.

For a lost item, a student can provide information such as the item name, description, location where it was lost, date, category, and an image if available.

A student who finds an item can provide similar information about where and when the item was found.

Other users can search through the reports and filter them by categories, locations, and dates. If a student believes they have found their lost item, they can contact the person who posted the report.

An administrator will also be able to manage users and remove reports that are inappropriate, false, or no longer needed.

---

## 4. Project Objectives

The main objectives of FindBack are to:

- Create a central platform for lost and found items on campus.
- Make it easier for students to report lost belongings.
- Allow students to report items they find.
- Make it easier to search for lost items.
- Help connect students who have lost items with students who have found them.
- Reduce the number of items that remain unclaimed.
- Keep track of reported and recovered items.
- Provide a simple and organized alternative to relying only on group chats and word of mouth.

---

## 5. Target Users

The platform will have two main types of users.

### Students

Students will be able to:

- Create an account and log in.
- Report lost items.
- Report found items.
- Add descriptions and images to reports.
- Search for lost and found items.
- Filter search results.
- View the details of an item.
- Contact the person who posted an item.
- Update the status of their reports.
- View their previous reports.

### Administrator

The administrator will be able to:

- Manage student accounts.
- View lost and found reports.
- Remove inappropriate or suspicious reports.
- Review reports made by users.
- Manage reported content.
- Remove old or resolved posts when necessary.
- Monitor the overall platform.

---

## 6. Main Features

### 6.1 Student Registration and Login

Students will register and log in using their matriculation numbers and other required information.

The system should only allow registered users to access the main features of the platform.

One of the challenges will be verifying that the matriculation number actually belongs to a current Babcock student.

### 6.2 Report a Lost Item

A student who loses an item can create a lost item report.

The report will contain information such as:

- Item name.
- Description.
- Category.
- Location where it was lost.
- Date it was lost.
- Additional identifying details.
- Image of the item, if available.

### 6.3 Report a Found Item

A student who finds an item can create a found item report.

The report can include:

- Item name.
- Description.
- Category.
- Location where it was found.
- Date it was found.
- Additional information.
- Image of the item, if available.

### 6.4 Search and Filter

Students will be able to search for items using keywords.

They will also be able to filter reports by information such as:

- Category.
- Location.
- Date.
- Lost or found status.

This will make it easier to find a possible match.

### 6.5 Item Details

Users will be able to view more information about a reported item, including:

- Item name.
- Description.
- Image.
- Location.
- Date.
- Status.
- Information provided by the person who reported it.

### 6.6 Contact User

If a student believes that a reported item belongs to them, they should be able to contact the person who made the report.

The exact communication method will be decided during development.

### 6.7 Item Status

Users will be able to update the status of their reports.

Possible statuses include:

- Lost
- Found
- Claimed
- Returned

For example, when a student gets their lost item back, they can mark the report as **Returned**.

### 6.8 User Dashboard

Students will have a dashboard where they can see:

- Their lost item reports.
- Their found item reports.
- Active reports.
- Resolved reports.

### 6.9 Admin Dashboard

The administrator will have a dashboard for managing the platform.

The dashboard will allow the administrator to:

- View users.
- View lost item reports.
- View found item reports.
- Remove inappropriate posts.
- Review reported content.
- Manage resolved or outdated reports.

---

## 7. Possible Challenges

### 7.1 Verifying Students

One of the main challenges will be making sure that people using FindBack are actually Babcock students.

Students will register using their matriculation numbers, but simply entering a matriculation number may not be enough to confirm that the person is a current student.

If access to an official university database is not available, an alternative verification method will need to be considered.

### 7.2 Fake Reports

A user could create a false lost or found item report.

To deal with this, users should be able to report suspicious posts to the administrator. The administrator can then review the report and remove it if necessary.

### 7.3 False Claims

Someone could falsely claim that a found item belongs to them.

To reduce this problem, users should not provide every identifying detail about valuable items in a public post. The person claiming the item can be asked to provide additional information to prove ownership.

### 7.4 Finding Matching Items

Different students may describe the same item in different ways.

For example, one student might report a "black Apple phone" while another reports a "black iPhone."

The search feature should therefore support keywords and categories to make it easier to find possible matches.

### 7.5 User Privacy

The platform will contain personal information belonging to students.

The system should therefore protect user accounts and avoid displaying unnecessary personal information publicly.

### 7.6 Old Reports

Some items may never be recovered, while others may be returned to their owners.

The platform will need a way to mark resolved reports and manage older posts so that users can focus on active reports.

---

## 8. Technologies

The technologies used will depend on what the team decides is most suitable for the project.

Possible technologies include:

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python, Java, Node.js, or another suitable technology
- **Database:** MySQL, PostgreSQL, or another suitable database
- **Version Control:** Git and GitHub
- **Code Editor:** Visual Studio Code

The final technologies will be agreed upon by the team before development begins.

---

## 9. Team Collaboration

The project will be developed by five team members using Git and GitHub.

GitHub will be used to:

- Store the project code.
- Track tasks.
- Manage different versions of the project.
- Create issues for tasks.
- Review code through pull requests.
- Keep track of project documentation.

Each team member will be given specific tasks and will work on their own branch. After completing a task, the member will push their changes and create a pull request for the team to review before the changes are added to the main branch.

---

## 10. Expected Outcome

At the end of the project, we expect to have a working prototype of **FindBack** that allows Babcock students to report, search for, and manage lost and found items.

Students should be able to create accounts, report lost or found items, search through reports, view item information, and contact other users when necessary.

The administrator should be able to manage users and reports and remove inappropriate or suspicious content.

The finished project should provide a simple solution to the problem of lost belongings on campus while giving the team practical experience in software development, databases, user authentication, Git, GitHub, and teamwork.

---

## 11. Conclusion

**FindBack** is intended to make the process of finding and recovering lost belongings on campus easier.

Instead of students depending only on WhatsApp groups, friends, or physically searching around campus, they will have one platform where lost and found items can be reported and searched for.

The project will include basic features such as student registration, lost and found reports, search and filtering, item status updates, user communication, and administration.

Through this project, the team will also gain practical experience in planning, designing, developing, testing, and managing a software project collaboratively using GitHub.
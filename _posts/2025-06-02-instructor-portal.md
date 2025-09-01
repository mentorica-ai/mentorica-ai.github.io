---
title: "Managing AI Activities in the Instructor Portal"
excerpt: "A tutorial on using the instructor portal to configure AI activities and assign them to students."
author: "Mochen Yang"
image: 
  path: /images/2025-06-02-instructor-portal/header.webp
  thumbnail: /images/2025-06-02-instructor-portal/thumbnail.webp
categories:
  - Tutorial
---

In this article, we will show you how to use Mentorica.AI's instructor portal to easily configure AI activities and assign them to your students (individually or in groups).

If you haven't already, please register for a free instructor account on our [instructor portal](https://instructor.dab.bot). Upon first login, you will notice a "DEMO101" course waiting for you, and the "Global Bank" AI activity already selected. This DEMO101 does not involve any real students, and is there to help you get familiar with the instructor portal. We will also use it for illustration here.

# Configure an AI Activity

All AI activities can be managed under the "My Dashboard" page of your course. Take the "Global Bank" case as an example (see screenshot below), you have sevearl configuration options:
- The "ENABLED/DISABLED" toggle: this controls the visibility of this AI activity for your students. Switching an AI activity to the "Enabled" state would make that AI activity immediately available and visible to your students. Please note that a activity will automatically be toggled to the "Enabled" state on the specified start date of your activity and to the "Disabled" state on the specified end date.
- The "EDIT" button: The pop-up window is where you can specify the desired start and end dates for this AI activity, as well as whether it should be assigned to individual students or student teams. For our pre-configured AI activities, you won't be able to modify the name or description.
- The "DELETE" button allows you to delete an AI activity altogether.
- Moerover, directly clicking on the AI activity card will take you to your private chatting channel with that activity, where you can interact with the AI agent for testing and demo purposes.
- If we have deployed custom AI activities for your course, they can be found in the same place as Mentorica's curated AI activities. Your custom AI activities are only visible to you.

![activity config](../../images/2025-06-02-instructor-portal/activity_config.webp)


# Assign an AI Activity

The first step to assign an AI activity is to enter your student roster into the course, which you can do under the "Students" tab. You can either enter students manually or import a csv file (template can be found next to the import button) with the following fields:
- Email: The email address that a student intends to use (e.g., the student's University email). **IMPORTANT**: our system uses the email address as the **unique identifier** for a student. Once entered, the student has to use that email address when logging into the student portal, and you cannot edit it. If a student wants to use a different email than the one already in the system, you need to delete and then re-enter that student under the desired email address.
- Name: Last name and first name, separated by a comma. E.g., "Yang, Mochen"
- Group: If you'd like assign AI activities to student groups, you can specify the group names here. This field is **optional** -- if you leave it empty, AI activities will be assigned to each student individually. If you have specified a group set, all AI activities will be assigned at the group level by default, unless you explicitly toggle the "Individual Activity" control for the AI activities that you wish to keep at individual level.

Related to entering student information, you can also invite co-instructors or teaching assistants to your course. This is done under the "Instructors" tab, which has a very similar interface as the "Student" tab. The only difference is that you cannot specify any grouping for co-instructors or TAs -- AI activities will be assigned to each instructor or TA individually.

# Monitor Student Activities

Under the "Channels" tab, you will be able to see the chatting channels for yourself (and any other co-instructors or TAs) as well as all your students. Simply click on a row to see what a student has been doing with an AI activity. Please be aware that with many students / AI activities, there will be a large number of channels under this tab (e.g., a course with 50 students and 2 individual-level AI activities would already create 100 chat channels). You can easily filter channels by channel name, group, or student name, using the filter function embedded in the table header. We will roll out some AI-driven reporting tools (e.g., channel-level summaries) in the near future!
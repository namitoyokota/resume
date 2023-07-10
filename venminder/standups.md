# Standups @ Venminder

> December 5th, 2022 - Present

### 7/10/23
- I'm still working on the context menu fix - 1573
- Then probably get started on the graph story - 1070

### 7/7/23
- Worked on wiring up the account icon in the header - 1569
- Cleaned up all of the file names to make them shorter - 1565
- Also fixed a bug that Jess found with the Clear Data not working - 1597
- At the end of the day, I wrote documentation for the new vm-radio component - fe32

### 7/6/23
- Wrapped up migrating the theme table to v3 - 1269
- Also deleted all of the v2 grid files so that no longer exists in our codebase - 1269
- At the end of the day, I started investigating the issue with the account icon in the header - 1569

### 7/5/23
- Worked on the templates table migration to v3 grid - 1269
- Started working on the theme table at the end of the day

### 7/3/23
- Worked on using the vm-radio component in Control Assessments - 1582
- Also started working on the vm-grid migration (finished theme file list table and order details) - 1269

### 6/30/23

-   Go back to the vm-radio component in vm-library package hoping to finish that today

### 6/29/23

-   Worked on the formula preview and calculating with user inptu data, PR is up and ready for review - 1068
-   Also found that I missed the disabled flag in the vm-button updates so went back to do that, also ready for review - 1571

### 6/28/23

-   Updated the vm-library package to latest - 1571
-   Wrapped up the 1067 story and PR is ready for review

### 6/27/23

-   Continued working on 1067 story for the calculation dialog
-   Also fixed a bug with the 1063

### 6/26/23

-   Started working on the workflow for creating an equation for the table row - 1067
-   I found a couple of edge case concerns so want to discuss that after everyone has gone

### 6/23/23

-   Added Trend and Rating columns to the table - 1064
-   Also added the calculation modal - 1066
-   Tested all of recent changes I made on GETS - everything should be ready for testing

### 6/22/23

-   I wrapped up the PR for 1454 with some of the unit tests updated
-   Had a sync up with Tracey and Jess on design change to support deleting and reordering tables
-   Continued working on finalizing 1063 story for adding the table
-   I also added support for downloading the preview PDF for 1461

### 6/21/23

-   Got help from Carol on adding the new property to the AssessmentData DTO
-   Updated the theme with some feedback from Lisa-Mae
-   Started working on 1063 again with Patrick's changes there

### 6/20/23

-   I worked on the spike story for Chart.js (1069) and found that it will work for all of our needs. I did find some blurriness in the PDFs but Patrick and I think it's just a viewport issue and should not be a blocker.
-   I also noticed that I broke the error dialog when I cleaned up the event names with the control refactor story so fixed that
-   I then started working on 1524 story for the clearing assessment data. Got the frontend for that working so will be getting help from Carol today on the backend work.

### 6/16/23

-   This morning, I worked on 1063 to use the new template sections that Patrick made
-   Also was prototyping sticky headers and since it worked pretty well, will be pushing that change up soon
-   Start looking into 1065 for adding textarea to FHA

### 6/15/23

-   Worked on cleaning up the unused code with the 1443 change
-   Was able to find a few bugs while testing that so those should also be fixed

### 6/14/23

-   Continude working on the Assessment control wrapper component - 1443
-   Got the PR up, waiting on one more reviewer

### 6/13/23

-   Merged the first pass for the control refactor (template builder) - 1443
-   Also added the store service for controls - 1523
-   Continued working on 1443 for the assessment side (got the wrapper implemented with dates and textfields)

### 6/12/23

-   Continued working on 1443 have the PR up now and will demo the change in a meeting after standup
-   Also worked on the store service for controls - should be pretty much done - 1523

### 6/9/23

-   Continued working on 1443 for the control refactor
-   Met with Jess and Patrick with more feedback and implemented that to the theme

### 6/8/23

-   Started working on the template version for the controls - 1443
-   Got the textfield and checkbox working

### 6/7/23

-   Continued working on the Theme improvements as more suggestions came up - 1472
-   Wrote documentation on how to create a Theme for Jess and Marketing - 1472
-   Started brainstorming the 1443 story and added subtasks for refactoring our existing control components

### 6/6/23

-   Contiuned working on the 1472 story with Jess and Patrick
-   Also worked on the frontend piece for 1461 but looks like there may be one more piece to the frontend piece to work on later after Nathan gets a chance to support PDF

### 6/5/23

-   Met with Jess and Patrick to test my current theme
-   Good things came out of that so worked on that for most of the day
-   Towards the end of the day we were able to start testing again with the suggestions in place

### 6/2/23

-   Met with Jess about the theme then started adding placeholders

### 6/1/23

-   Continued working on the ISPA Theme for 1472
-   Also worked with Patrick on and off about the 1303 change

### 5/31/23

-   Continued working on ISPA Theme for 1472

### 5/30/23

-   Fixed an issue I found with the in app view - 1303
-   Ditched vm-radio work for now
-   Then started working with Jess on the 1472 story
-   Looked into the design and Jim's theme but it would've taken more time editing so decided to start from scratch

### 5/27/23

-   Was all over the place
-   Trying to finish up vm-radio
-   Found an issue with View Assessment causing the HTML to not load
-   Something else too
-   Got off an hour early

### 5/26/23

-   I got my vm-radio PR up now ready for review - fe-32
-   I'm assuming today will be a lot of finalizing that and also testing my recent changes
-   If there are no more work afterwards, I'll get started on 1443 for the control refactor

### 5/25/23

-   Removed admin role requirement from the View Assessment page - 1303
-   Also added the View Assessment link to Vendilligence page - 1303

### 5/24/23

-   Continued working on the vm-radio component - fe32
-   Had the frontend guild meeting

### 5/23/23

-   Fixed the narrative dialog issue in the morning - 1451
-   Started working on the new vm-radio component, made good progress - fe32

### 5/22/23

-   Added changes to hide NA NP checkboxes when creating a control - 1224
-   Worked on a bug where with the narrative dialog and I found some minors issues related to it so I hardened that code - 1451
-   I also tested a change to the Get Assessment Types endpoint from Patrick and created a PR - 1602

### 5/19/23

-   I continued working on wrapping up the 1061 with Patrick
-   Also spent some time working on 1382 for adding the Cancel button to Deliver Assesssment dialog
-   Spent an hour or so reading through the vm-library documentation on contributing

### 5/18/23

-   Worked on 1061 changes most of the day for implementing the year section and also supoprting the new inheritance structure
-   Also met with Jim for a second but he had a electricial come during the meeting so he had to go. I send him the PDF generated by CLAK and also all of the changes that he needed to make.

### 5/17/23

-   All over the place
-   I first brainstormed a way to improve our component structure for controls and wrote a tech debt story
-   I then worked on a small change for 1062 that Carol and I talked about with the FHA being included in the assessment type API
-   I also started looking into the vm-radio implementation and the design for that (hoping to work on it next week)

### 5/16/23

-   I started working on 1062 and got the basic section done (subheaders, context menu, reorder) - PR is ready for review

### 5/15/23

-   Fixed a bug with the N/A N/P checkbox (good to test on GETS) - 1224
-   Spent rest of the day with Carol and David fixing the issue with selected files and feature flags (I appreciate the help) - 1433

### 5/12/23

-   Mental Health

### 5/11/23

-   Finished up 1224 for adding N/A N/P checkboxes
-   THen worked on 1060 for the standard section with Patrick - 1416

### 5/10/23

-   Finished up adding subheader to risk profile section - 1393
-   Also finished up the PR for View Assessment page to display saved HTML and download PDF button - 1303
-   I started working with Carol on adding N/A N/P checkboxes to textfields and date controls - 1224

### 5/9/23

-   Worked on the template builder section refactor to allow subheaders for risk profile - 1393

### 5/8/23

-   Worked on the View button in Doc Storage for 1303
-   Fixed a few bugs in the afternoon: 1383 (allowing N/A) and 1362 (populating section rating) - PRs are up

### 5/5/23

-   I started working on DCDev work for Viewing Assessment - 1303

### 5/4/23

-   Continued working on 1303 and got the HTML to display on the page and also got the download feature working

### 5/3/23

-   Fixed the section rating error bug that Jess found - 1111
-   Got some help from Carol on setting up the Legacy Nuget Packages and started testing the Saved HTML endpoint - 1303

### 5/2/23

-   Created an empty page for the View Assessment - 1303
-   Started working on adding the new endpoint for getting the saved HTML - 1303
-   Also investigated the issue with the Perform Review page load (should be good now) - 1270

### 5/1/23

-   Team building
-   Added a warning dialog when you try to refresh while a PDF is being generated - 1283
-   Fixed an issue I found with the theme table caused from the store service change - 1356
-   Started looking into the 1303 story and asking questions to Jess and Carol as I planned work

### 4/28/23

-   Continued working on 1283 for the PDF generation, finally got my local environment working
-   Tested all of the different arguments that I could use and then tested the trigger through HTML
-   Result: average speed through 5 trials 21.45 seconds to 11.69 seconds (54% improvement)
-   Also got the final module of the security compass finished (all of them are completed)

### 4/27/23

-   Continued worked on the Perform Review page refactor (PR is up) - 1111
-   Moved the 1290 PR into the latest feature branch but ended up not needing to complete
-   Started debugging the PDF generation tool - 1283

### 4/26/23

-   Started working on Perform Review page refactor for cleaning up the data (less work than I though) - 1111
-   Also had the frontend guild meeting - not a lot of updates (the notes are in the chat)

### 4/25/23

-   Fixed the error issue on all controls in a section that's not risk profile - 1315
-   Worked on auto populating the checked documents (adding method in controller to call v2) - 1290
-   I also wrote subtasks for removing listOfSections property in Perform Review (now is perfect time, i'll spend free time here) - 1111

### 4/24/23

-   Team building in the morning
-   Created a PR for displaying the deliver assessment dialog only for Completed Assessments - 1290
-   Investigated why the all controls in a section is throwing an error in Perform Review - 1315

### 4/21/23

-   Continued working on PDF generation improvement story (got stuck with infinite load, local issue) - 1283
-   Security Compass Training

### 4/20/23

-   Finished up 1290 for the new Deliver Assessment dialog (is on GETS and tested)
-   I then started researching different arguments for the PDF generation tool
-   I found the flag to trigger from the HTML and also a few others to potentially improve styling
-   Right now, with the new flags, the PDF is either getting stuck or taking too long

### 4/19/23

-   I started looking into 1290 for adding a new deliver assessment dialog (got a good bit done)

### 4/18/23

-   Added more console logs for debugging the control answers not triggering an event - 1306
-   After that, GETS randomly started working so I was unable to find the issue
-   I then talked with Sean to see how I can speed up CLAK's PDF generation process (didn't really change) - 1283
-   Started looking into 1290 for adding a new dialog when you submit an assessment - 1290

### 4/17/23

-   Investigated the issue with section rating not calculating on control answer - 1306

### 4/14/23

-   Fixed the issue with feature flag not working for document checkboxes - 1168
-   Went through all of the bugs and feedbacks from the demo (unable to reproduce some) - 1315
-   Test out the ISPA Theme using Grid instead of Flexbox and it worked well - 1283

### 4/13/23

-   Got a PR up for the template type select dialog - 1058
-   Fixed the FHA template type being hardcoded to use the API - 1058
-   Investigated the issue with the feature flag detection not working correctly - 1168

### 4/12/23

-   Got most of the FHA template builder work done - 1058
-   Investigated an issue with the section rating not updating 1306
-   Had the Frontend Guild meeting
-   Started working the new dialog for selecting CA or FHA template - 1058

### 4/11/23

-   Sick

### 4/10/23

-   Sick

### 4/7/23

-   Continued working on setting up the foundation for FHA template builder - 1058
-   Logged off at 1pm Eastern

### 4/6/23

-   Wrapped up 1168 story by hide the checkboxes behind a feature flag
-   Tested different ways to layout the ISPA theme (found a way that might work, waiting to test)
-   Started working on 1058 for adding the new FHA template builder (2 PRs up)

### 4/5/23

-   Continued working on 1168
-   With help from Sean, got the v2 endpoint added to v1
-   Updated the frontend to call that endpoint

### 4/4/23

-   Added support for editing tags and also fixed the dropdown (ready for testing) - 902
-   Dove into the 1168 work - added checkboxes to the table

### 4/3/23

-   Spent most of the day trying to set up the Postgres Local Environment
-   Investigated the issue with the tag dropdown not updating - 902
-   During testing, I also found that I didn't account for displaying tags when editing a control

### 3/31/23

-   Tested all of my changes from yesterday - ready for Jess now
-   Dove into Nathan's story to test all of the frontend code - 1226
-   Investigated an issue with the merge engine code (would like to discuss) - 1282

### 3/30/23

-   Fixed the issue with Section Rating disabled for Risk Profile - 1101
-   Fixed group controls not working for non-risk profile sections - 1274
-   Investigated the theme attachment bug that Carol found (left a comment on the story) - 1253
-   Learned more knockout.js and started looking at the codebase - 1259

### 3/29/23

-   Updated the Approved text in Perform Review page - 1259
-   Moved sharable components to a new folder - 1059
-   Fixed the bug for overall rating calculation on N/A section rating - 1271
-   Started learning Knockout.js to prep for future stories
-   Had the Frontend Guild meeting at the end of the day

### 3/28/23

-   Fixed the iframe error I broke yesterday - 1258
-   Finished up last bit of work for the store service (timer and CRUD) - 902

### 3/27/23

-   Wrapped template builder refactor PR - 1203
-   Implemented the store service for templates - 902

### 3/24/23

-   PTO

### 3/23/23

-   Fixed create template button in perform assessment page - 1256
-   Fixed overall rating calculation including risk profile - 1101
-   Worked on the last bit of work for the template builder refactor (PR up) - 1203

### 3/22/23

-   Reviewed Nathan's PR for 1226
-   Will continue working on the template builder refactor - 1203
-   Have Frontend Guild meeting at the end of the day

### 3/21/23

-   I'll create a PR for 902 if no one objects
-   Then start working on a big clean up tasks for the template builder - 1203
-   Japan won the WBC - World Baseball Classic so feeling good

### 3/20/23

-   Test and finish new property change for Section class - 1101
-   Going back to 940 to send N/A to overall rating calculation if risk profile toggle off - 940
-   Picked up 2 new stories - 902 and 1224
-   Would like to demo one and ask a question on one after everyone goes

### 3/17/23

PTO

### 3/16/23

-   Go test integration
-   Add frontend changes for new property in Section class to indicate risk profile - 1101
-   Security Compass Training

### 3/15/23

-   Fix merge issues with 1101 PR
-   Fixed a group control bug Jess found - 1222
-   Pick up a new story
-   Frontend Guild Meeting

### 3/14/23

-   Creating a new component for dropdown pane in template builder - 1174
-   Worked on 941 with Patrick to differentiate risk profile calculation

### 3/13/23

-   Finish up supporting editing of controls (PR is up) - 1107
-   Final bit of changes for Overall Rating calculating (PR is up) - 940
-   Making necessary changes to prep for Template Builder dropdowns - 1174

### 3/10/23

-   Work with Patrick on 940
-   Start working on editing controls - 1107

### 3/9/23

-   Adding a new event to the `vm-date-picker` on clear - 1101
-   Will start working on calculating overall rating - 940
-   Make a minor PR to move the order details section - 1174

### 3/8/23

-   Have a demo for you guys to handle autosave - 1190
-   Implement the same workflow for Perform Review page
-   Frontend Guild Meeting
-   Maybe start working on calculating overall rating - 940

### 3/7/23

-   Implement a new service for handling autosave - 1190
-   KnowBe4 Training Courses

### 3/6/23

-   Commented on a few demo feedbacks
-   Will work on using the latest vm-date-picker component from vm-library
-   After I finish, will start brainstorming how to prevent auto save from triggering too often

### 3/3/23

-   1019 for cleaning up the add control dialog UI was kind of a rabit hole so still trying to finish that up this morning.
-   After that, I'm go investigate the issue Carol found with the models generated by the T4 script are not using the latest class names

### 3/2/23

-   I will continue working on 1019.
-   I was looking through all of the UX designs yesterday afternoon and found some differences in the design and the current UI, so I'll also make those minor changes in the same PR as well.

### 3/1/23

Yesterday

-   1189 which was moving the API service files to a new directory
-   1170 for refactoring our current moment.js code to start using date-fns

Today

-   1175 to create a new enum to store display types for controls
-   1019 which is cleaning up the UI for the add control dialog

<hr />

**Standups**
&copy; Namito Yokota
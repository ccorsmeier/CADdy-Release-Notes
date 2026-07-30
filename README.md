# CADdy v0.4.0-Beta
@date: 2026-05-11
## New Features
- Updates to Project and BOM pages to display part costs.
- Backups are now stored more efficiently with cleanup tools.
- Background processes reduced for lower CPU usage.
- Updates to all VAV pages: Points, Sequence, and BOM have major updates to meet new standards.
## Bug Fixes
- User authentication fixes.
- Styling updates across pages.
- Styling updates to better support smaller screens.
- File cleanup and removal of redundant files for improved load times.
- Fixes to submittal PDF generation.

# CADdy v0.3.0-Beta
@date: 2026-04-28
## New Features
- Project Page: Added backups, unit file versioning, application versioning, backwards compatibility support, preview updates, All Projects changes, submittals, and saved unit presets.
- Selections Page: Fixed issues with VAV items.
- Points Page: Fixed the missing custom point column.
- Review Page: Added special-case red dot notifications, plugin selection on errors, and compile workflow updates.
- AutoCAD: Added file fixes, general updates, and support for a notes section.

# CADdy v0.2.3-Beta
@date: 2026-03-11
## Bug Fixes
- Fixed additional issues found after v0.2.2-Beta.

# CADdy v0.2.2-Beta
@date: 2026-03-10
## Bug Fixes
- Fixed file encryption issues where files were being encrypted when they should not have been.

# CADdy v0.2.1-Beta
@date: 2026-03-06
## Beta Features
- Released the CADdy Desktop beta.
- Added customization for wiring, points, bill of materials, sequence of operations, and drawings.
- Added drawing notes that can be viewed later in AutoCAD.
- Added customization for wiring blocks, block placements, wiring types, tags, and related wiring details.
- Added editable points, including the ability to create custom points.
- Added editable bill of materials items, including tags and descriptions.
- Added editable sequence of operations sections, including the ability to add, remove, edit, and create custom content.
- Added a review page before compiling.
- Added project-linked equipment drawings with project information, backups, previews, and related project tools.

# CADdy v0.1.7-Alpha
@date: 2025-11-25
## New Features 
- Added an input box for initials that automatically populates the lower section of all drawings. 
- Added submittal creation and shared file upload for admin users. 
## Bug Fixes 
- Wiring values now sync automatically during compilation, removing the need for ATTSYNC. 
- Bill of Materials now populates in the correct location. 
- Removed CHWS, HWS, and HPU from the equipment dropdown. 
- Improved plugin performance and reliability. 
- Made various diagram corrections and formatting updates. 

# CADdy v0.1.6-Alpha
@date: 2025-11-06
## Bug Fixes
- Generic users no longer have access to the admin page.
- Report bugs email now sends to caddy@brookssolutions.net.

# CADdy v0.1.5-Alpha
@date: 2025-10-28
## Bug Fixes
- Fixed an error that occurred when loading favorites.
- Improved styling for some popups.
- Drawing output now includes user-entered information.
- AutoCAD script now copies and pastes correctly in non-LT versions.
- Report feedback emails now send successfully.


# CADdy Lite v0.1.0-Alpha
@date: 
## Features
- Project Management: Save and manage project details including project date, address, architect, engineer, facility, and client.
- Equipment Customization: Configure VAVs, FCUs, AHUs, and RTUs with custom details for each project.
- Real-Time Updates: View live updates to the sequence of operations, points list, and schematic drawing as equipment settings change.
- Favorites System: Save equipment configurations as favorites for faster project setup.
- Output Files: Generate a schematic drawing (AutoCAD or PDF), points list (Excel or PDF), and sequence of operations (RTF) with a single click.
## Things to keep in mind
- We recognize that some equipment configurations, sequences, or points may be inaccurate at this early stage. Your engineering expertise is incredibly valuable, and we would greatly appreciate any feedback on what should be corrected or improved.
- If anything seems confusing or different from how you usually do things, we’d appreciate your feedback. Likewise, if you have ideas for features that would make CADdy more enjoyable to use, your suggestions are welcomed and appreciated.
- We’d also love your thoughts on speed and workflow. Does CADdy help you get things done faster than your current process? If not, please let us know what could make the workflow smoother.
- Please be fully honest with your feedback. If something feels off, unclear, or not useful, we genuinely want to know. Thanks so much!


# CADdy Bid v0.2.2-Alpha
@date: 2026-07-30
## New Features
- Add more documents to an invite after it's already sent, then email the subcontractor to let them know.
- Invite expiration dates now change color as they get close, yellow when expiring soon, red once expired.
- Estimators are now included on the confirmation email when their estimate is approved and the job moves to Sent to Sales.
- You can now increase assembly quantities while estimating.
- Estimate managers can now edit estimates while they're in review, instead of having to deny them back. Edits autosave; estimates only lock once approved.
- The estimate manager can now download a PDF summary of an estimate while reviewing it.
- New Documents column on the Invite page shows how many files each subcontractor can see, with a button to view the list.
- New Hours column on the Projects page (PEG / PM / Tech), auto-filled from the latest estimate and editable by anyone with edit access.
- "Back to top" button on the Projects page.
## Bug Fixes / Improvements
- File upload limit raised to 75MB.
- Fewer duplicate emails to salesmen: inviting several subcontractors at once now sends one summary email instead of one per invite.
- Fixed the status dropdown closing when you scrolled inside it.
- Projects page now remembers your scroll position on refresh.
## Admin Updates
- New PEG / PM / Tech settings on the admin Labor page that drive the new Hours column on the Projects page.
- The catalog-approval email now shows any adjustments the admin made to the request before approving.

# CADdy Bid v0.2.1-Alpha
@date: 2026-07-29
## New Features
- "Go to project" button in the project logs jumps you straight to that project's row.
- The Values column now shows for estimators and sales, and both roles can change them.
## Bug Fixes
- Faster AIA PDF exports, and automatic exports no longer get stuck on the "prices are outdated" prompt.
- Fixed a blank pie slice on summary PDFs when everything was in one category.
- Projects no longer briefly disappear after checkout moves them to a new status tab.
- Cleaner project logs: links, contact and winning-bidder changes, review decisions, and checklist events now read properly, with tidy dates and trimmed notes.
- Clearer message when a salesmen tries to submit a job for review.
- Add New Estimate button now hides on in-review/approved projects and comes back if moved back.
- Imported Monday jobs now follow the normal approval gate instead of skipping it.
- Package naming: spaces in a custom controller code now become underscores.
## Admin / Manager Updates
- BuildOps now requires a Project / Contract Number to mark a job "Job Setup Complete." It saves onto the project.
- Estimate files now show on approval cards and download in one click, and the "no estimate yet" popup points you to them too.
- Fuller Approval Logs: now shows every Legal and Manager decision, not just submissions and approvals.

# CADdy Bid v0.2.0-Alpha
@date: 2026-07-28
## New Features
- Subcontractors can now say "No Bid" on an invite. If a sub isn't going to bid, they can decline right from the invite page and leave a quick reason. You'll get an email letting you know and their status shows as "Declined" on your invite list. Subs who decline no longer show up as install options, and their "Re-Invite" button is turned off.
- Sales users get personalized dashboard tiles. The Missing close dates, Follow-ups needed, and Upcoming action tiles now take you straight to your projects.
- Sales users can now delete projects with estimates, which was previously blocked.
- Deleting a project now asks you to type a confirmation first.
## Bug Fixes
- Sales dashboard "missing close dates" now displays the correct number.
- One person can now be both the estimator and salesperson on a project.
- The estimator and salesperson lists now only show people who actually have that role, so they're easier to pick from. Anyone already assigned still stays in the list.
- Search bar added to the Lessons Learned owner list, and the owner box only shows up once you pick "Owner" as the subject.
- You can now link a sales action to any of your deals, whether it's open or closed (before it was open deals only).
- Fixed the weekly sales metrics and restored the week that was affected.
## Admin Updates
- Subcontractor declines are recorded in the logs (with the reason), and re-invites are now tracked separately from the first invite.

# CADdy Bid v0.1.9-Alpha
@date: 2026-07-27
## New Features
- Edit multiple projects at once — Select several projects (ctrl+click or shift+click) and apply a change to all of them in one step, instead of editing each one individually.
- Sort by won date — You can now sort projects by their won date on the Projects page.
- "Won" split by year — The "Won" status is now broken out into individual years for clearer tracking.
- Project Logs — A new Logs button on the Projects page shows a history of changes made to projects, with search and filters.
- Added a scrollbar to the project status area.
## Bug Fixes
- Sales Actions loads faster — large dropdowns were shortened and optimized.
- Fixed Sales Action bugs with marking linked follow-ups and the Projects page link.
- Fixed a refresh-related error.
## Admin / Manager Updates
- Estimate review submissions are now restricted so only estimators can submit their own estimate for review by Chris.
- Approval reminder emails — Managers will now get a daily reminder email for jobs that are waiting on you to review or approve.
- Approval Logs — A new Logs button on the Approvals page shows recent approval activity across all jobs.
- Gross margin on approval cards — Approval cards now show the GM% right next to the bid amount.
- Better BuildOps handling for Monday jobs — When a job doesn't have an estimate in CADdy yet, BuildOps now gets a clear explanation with links to the Monday item and the SharePoint files, instead of an error.

# CADdy Bid v0.1.8-Alpha
@date: 2026-07-23
## New Features
- Package & Assembly categories and estimate trees. Packages and assemblies now support nested categories, with a category tree view on the estimate page. The Packages and Assemblies views on the estimate page are now split into their own sections.
- Multi-select projects → export to Excel. Ctrl+click to select multiple projects on the Projects page, then right-click to copy the selection into an Excel document.
- Quick links from the project overview for faster navigation.
- Full PDF download for BuildOps insert (previously only the AIA document was available).
- Larger max upload size for estimate files.
- More detailed job status updates in Approvals, plus an "approved" flag for jobs marked Won.
## Bug Fixes
- Dashboard close dates display corrected.
- Scrollbar now stays in place when new estimates are created.
## Admin Updates
- Package & Assembly upload/download. Admins can now upload and download packages and assemblies via Excel.
- New Estimate Manager role. Fixed the manager role and added a dedicated Estimate Manager role to control who can review and approve estimates.
- Admin Users default permissions fixed so users now receive the correct default admin permissions based on their role.
- Construction vs. Service labor now separated correctly, so Service labor only shows SER- offices.

# CADdy Bid v0.1.7-Alpha
@date: 2026-07-22
## New Features
- New BuildOps flow: once a job is approved by both manager and legal and moves to Won, BuildOps users can view the AIA and mark when the job is submitted into BuildOps.
- Assembly requests for estimators: estimators can now request assemblies (alongside catalog requests).
- Estimate upload: estimators can upload an existing estimates / estimate files, and managers can view it for approval.
- Subcontractor invites for estimators: finished invite page letting estimators invite subcontractors with document upload.
- Multi-select project filters: filter projects by multiple values at once.
- Review Estimate Checklist: new button for managers to go straight to the review page for estimates in review.
- "See Revisions" status: sales can easily see when legal marks a job as needing revisions.
## Bug Fixes
- Approval emails now send to managers every time legal marks a job "not ready" or "see revisions".
- Fixed the "submit for approval" modal and flow so it works for existing jobs in sent to customer.
- Tutorial bug fixed.
## Admin Updates
- Admin User Requests page now has a separate tab splitting catalog requests from assembly requests.
- Admin page list re-ordered alphabetically.
- Removed the approved / denied tabs in approval tab.
- New-user onboarding: a Brooks user signing in will now need approval from an admin.
- Tutorials turned off for now until they're updated.

# CADdy Bid v0.1.6-Alpha
@date: 2026-07-21
## New Features
- All projects imported from Monday, including updates, values, dates, people, etc.
- Estimate review (Ready for Review): estimates sent to sales now go through a manager review, with email notifications to the manager, estimator, and sales.
- Bid approval process (two-stage): bids now go through a final approval with separate Legal and Manager sign-offs.
- New Approvals page with new approval roles and status flags.
- New "Ready for Approval" status in the project flow.
- Post-win checklist: a checklist must be filled out before a bid goes to approval, including marking the winning bidder on the job.
- Private assemblies: create your own private assemblies.
- Invite page office filter: filter the subcontractor list by office when inviting.
## Admin Updates
- New admin Checklists page to configure checkout questions per type (Sales, CO, PM).
- New admin Sales settings to route review and approval emails.
- Admin catalog Categories tab bug fixes.
- Admin Subcontractors tab: link subcontractor people to offices and set their primary company.
- Admin Assemblies: make assemblies company-wide or private, plus a "show all" scope view to see everyone's assemblies.
- Info popups on names: click a company name to see all its people, or click a person's name to see their companies.
- Add Question modal now shows which checklist type you're adding to (e.g. "Add Sales Question").
## Bug Fixes
- Sales checklist now resets when a project moves back before "Ready for Approval," so Won re-locks and the checklist must be re-submitted and re-approved.
- Re-inviting now keeps the invite's own expiry date instead of defaulting to the project bid date, which could already be in the past.
- Approval checklist now opens in its own window.
- Fixed logging on the projects page.
- Restrictions so a bid can't move past Ready for Review or to Won before the required review and approval steps are complete.
- Styling fixes across the review, approval, and checklist screens

# CADdy Bid v0.1.5-Alpha
@date: 2026-07-16
## New Features
- New catalog category tree — Estimators can now browse a nested category tree to find items faster, instead of always searching or scrolling one long list.
- Updated subcontractor list — Refreshed the subcontractor contacts used throughout the app.
- Back-to-top button — A quick "back to top" button now appears while scrolling long estimate pages.
## Admin Updates
- Redesigned admin catalog page — The old "Materials" page is now "Catalog," with clickable subcategories. Uploads now automatically create tabs, add categories, and move items between categories.
## Bug Fixes
- Fixed the /invite page — The invite page now works correctly with the updated subcontractor contacts.
- Fixed scrollbar on estimate / sidebar.

# CADdy Bid v0.1.4-Alpha
@date: 2026-07-14
## New Features
- New Sales section with pipeline pages, weekly performance, and metrics dashboards, including a contractor-revenue chart and an Export button to pull a report of the data.
- Sales Actions board with your own actions plus collaborator actions, group-by-status, drag-and-drop reordering, column sorting, right-click to delete, and attendee/company filters.
- A new Communications tab on the updates modal for both actions and projects, where linked emails and phone numbers can be viewed.
- A new Info tab on the updates modal that shows project details and any linked actions.
- Threaded action updates with @-mention tagging.
- A new Sales Admin page to manage action options and follow-up reminder days.
- Email notifications for action date changes, collaborator assignments, and a morning reminder for upcoming actions.
- Status tabs across the top of the projects page, plus an "Other" dropdown.
- Separate sales and estimator views of the projects page, with a trimmed-down set of columns for estimators and a read-only estimates view for salesmen.
- Support for multiple salespeople and estimators on a single project.
- Follow-up tracking: completing an action linked to a job can close that project's follow-up, and follow-ups automatically flag as "Needed" after two weeks of no activity.
- The project updates modal has been reworked into Updates and Follow-ups, with a new Info tab.
- A new Admin Users Deleted tab to fully remove a user's access, or restore and view deleted users who still show on old projects, plus clearer enabled/disabled indicators.
- An admin release scheduling page for maintenance banners, plus a new-release alert on the dashboard.
- A new homepage with a left sidebar for easier navigation.
## Bug Fixes
- The sales page now reads loss dates correctly, and the salesperson dropdown only lists salespeople.
- Fixed chart and table refresh issues on the sales metrics pages.
- Collaborators can no longer edit an action's section, date, time, or status.
- Deleted users can no longer log in, and inactive users now see a blank dashboard instead of restricted pages.
- The Admin Materials page-size switcher now shows a loading spinner.
- Wider, more readable column widths on the projects page.
- Various styling fixes across the sales, install, and estimate pages.
- Added mobile views for projects and sales pages.

# CADdy Bid v0.1.3-Alpha
@date: 2026-07-08
## New Features
- Subcontractor invite emails now list the equipment count and the devices under each item, so subs can see exactly what's included.
- You can now reorder items on the estimate by dragging and dropping them.
- The salesperson is now emailed automatically when a subcontractor invite is sent and again when the subcontractor submits their quote.
- The estimate items filter now lists categories alphabetically and includes a search bar. Active filters are clearly marked so you can tell at a glance when one is applied, and a new Clear Filters button resets them all at once.
- New estimates are now prepopulated with the project name, and revision numbers are assigned in the order the estimates are created.
- Fixed package search bar to search package names / descriptions.
## Admin Updates
- Added a new role picker for testing, so admins can preview the app as a different role.
- The admin materials table no longer has its own scrollbar and now fills the full width of the page.
- Added an All option to the items-per-page setting so you can view every item on a single page.
- Added new description column to the Packages page.

# CADdy Bid v0.1.2-Alpha
@date: 2026-07-02
## New Features
- You can now create a new salesperson or estimator if they aren't in the database yet by entering their first name, last name, and email.
- You can now assign up to 3 estimators or salespeople to a single project.
- Moved the quote number to the bottom of the Create Project modal, since it's tied to the salesperson. It now uses the first salesperson listed.
- Widened the project column widths for better readability and the Project Name is now always visible when scrolling.
- Added a set of subcontractor companies to the install page (the invite page notes that we don't have contacts for these yet).
## Admin Updates
- Reworked the Accounts page so both companies and people can be set as subcontractors, for use on both the install and invite pages.
- Added filters, collapsible People and Companies sections, and column sorting to the Accounts page.
- The Packages equipment type filter is now a dropdown.

# CADdy Bid v0.1.1-Alpha
@date: 2026-06-25
## Admin Updates
- Renamed "Hours" to "Labor" across the app.
- Added multiselect for offices when creating a new labor row.
- Added multiselect to edit the cost or rate of multiple labor rows at once.
- Added drag and drop to rearrange rows on the admin Labor page.
- Split Labor into Construction and Service tabs, with admin permissions split between the two.
- Added a Client Labor table under Service Labor to set client rates per company, per office.
- Construction Labor now always uses cost for pricing, with rate removed from the Construction Rates page.
- Added an Admin Labor Offices column on the Users page to set which offices a user can edit labor rates for.
- Added a Default Perms tab on the Admin Users page to set the default admin permissions for each role, still changeable per user on the Permissions tab.
- Added right-click to delete a user, fully removing access (disabling a user still left them read-only access to the Projects page).
- Bug fixes: Log page now shows 12 logs per page, subcontractors are created through an existing person.

# CADdy Bid v0.1.0-Alpha
@date: 2026-06-22
## New Features
- Added a right click option to view assembly items in the sidebar when creating estimates.
- Added companies and people management in Accounts admin page.
- Added all BuildOps clients to the DB.
- Added search bar to dropdowns that list companies or people from accounts.
- Updated subcontractor invite page to have better filters for finding accounts.
- Assemblies can have hours attached to them now.
- Added warnings to admin pages if you forget to save and try to move tabs or close the page.
- Added a new Hours admin page with the ability to create, edit, and delete hour entries including cost code, cost, and rate.

# CADdy Bid v0.0.6-Pre-Alpha
@date: 2026-06-16
## New Features
- Accounts admin pg: Checkout questions, subcontractors, and locations. Will eventually add more customer management here.
- Lessons admin pg: View submitted lessons learned by estimators using the checkout sheet, can be general or by-client. Also manage lesson subjects here.
- Automations admin pg: Admins can set up email notifications when status changes are made to projects.
- Checkout sheets:
- Submitted when project is switched to “Ready for Review”, but estimators can add to it on the estimate page or using the action icon on projects page.
- Opens as a separate window for them to fill out.
- Saves as they go, with optional notes for each checkbox.
- Lessons learned can be added, which are optionally linked to a client.
- Marked with a green checkbox once submitted. Click this indicator to view the submitted answers. Reopens if the project is no longer Ready for Review.
## Improvements
- Package/Assembly items can have decimals quantities up to 2 decimal places
- Updated projects page: added estimator and salesperson columns, renamed contacts, fixed minimum width to show all column headers.
- Admin hours changes: Added other hours (commissioning, etc) to the export, added a warning for hours that don’t have a group size but have set duplicate hours. Still allows save.
- Changed the generated quote number to use the salesperson instead of the current user.
- Split assemblies and packages into their own separate admin pages with different admin permissions.
- Added a right click option to view assembly items in the sidebar when creating packages.

# CADdy Bid v0.0.5-Pre-Alpha
@date: 2026-06-10
## New Features
- Right click an estimate item to request adding it to the master BOM list.
- New admin page to approve or deny requested BOM items, with an automatic email sent to whoever made the request.
- Added export / import for material items on the admin materials page — export items, edit any part information, and import the changes back in. The update tab now also accepts Belimo or Distech parts sheets and Brooks BOMs directly.
- Added a right click option to move an item to a new section on the admin materials page (works with single or multi-select).
- New feedback page for users to submit issues, bugs, or suggestions.
- New admin page to view submitted feedback, with statuses for open, in progress, and closed.
## Improvements
- On the admin materials page, you can now hide columns (with a "show hidden columns" option) and adjust the page size dynamically.

# CADdy Bid v0.0.4-Pre-Alpha
@date: 2026-06-03
## New Features
- Added subcontractor invites:
  - Email invite with Brooks logo & colors
  - Set expiration dates; filter by company, location, or radius
  - Logs sent, opened, quote sent, etc.
  - Prefills new subcontractor quotes in the install tab
  - Add new subcontractors when inviting them
- Added breakouts:
  - Create a breakout from existing equipment or as a standalone breakout
  - Breakout-only views in the estimate pages
  - Breakouts have separate hours and install
  - Options to include or exclude from the final estimate
- New project columns: bidders, bidder contacts, and owners — create a new contact, company, and role if needed (up to 3 contacts per column).
- Added a locations tab to the Admin Users page; subcontractors can be linked to multiple locations, and locations now include zip codes.
- Added group size override for controller hours.
- Custom hours can now be added to the estimate hours summary.
- Added export / import options for controller hours and materials on the admin pages.
- On the admin materials page, you can now hide columns (with a "show hidden columns" option) and adjust the page size dynamically.
## Improvements
- Double clicking an estimate item manufacturer lets you change it, with a custom option that saves a new manufacturer (auto-capitalized).
- New install page dropdowns and inputs for subcontractors (3 max; will eventually prefill with invited subcontractors & their quotes).
- Admin hours page now highlights rows for controllers missing hour rules, with new filters to find specific missing hours.
- Added a warning on the estimates page when a controller has no recommended hours.

# CADdy Bid v0.0.3-Pre-Alpha
@date: 2026-05-26
## New Features
- Added warranty to the estimate summary page & PDF export (5% of materials).
- Added warranty to the miscellaneous admin page (Misc Prices) where admins can change the percentage.
- Quote numbers now auto-count per user (formatted with user initials, month, year, and user quote number — CCmmyy00X).
- Added assigned people (sales, estimator, manager) to the projects page.
- Added a "show assemblies" checkbox to the estimate package sidebar filter.
## Improvements
- Added actual hours & hourly rate to the "Cost Breakdown" on PDF export.
- Separated submittals and O&Ms/As-builts in the Hours breakdown on PDF export.
- Added install cost code to the PDF export.
- Combined AIA material cost codes into one "materials" group on the estimate page and PDF export.
- Added salesperson, quote number, and office to the top of the PDF export.
- Made salesperson required when creating a new project.
- Made quote number read-only on the projects page.
- Made part number editable on the admin materials page.
- When the project office is changed, it prompts you to update hourly rates for the new office in existing estimates.
- Changed admin package filters to match the estimate items filter.
## Bug Fixes
- Adj $/Hour now actually saves.
- Additional fixes: tutorial, logout redirect, tax added to AIA, and more.

# CADdy Bid v0.0.2-Pre-Alpha
@date: 2026-05-21
## New Features
- Added custom install $/device input on the estimate install tab.
- Added summary and AIA export document.
- Added double click to edit estimate name & rev number on the projects page.
- Added double click to edit description, part number, & price of manually added estimate items.
- Added categories to the materials admin page — add new categories or assign items to a category (multi-select or double click).
- Split the estimate sidebar into item & package views (double click the title to switch views).
- Added filters to the estimate sidebar: filter by category, search by tag, description, or part number.
- Users can edit manually added device / controller description, part number, or price by double clicking.
## Improvements
- Estimate sale price total on the projects page now matches the estimate sale price.
- Revision numbers start with "Rev", and the same rev numbers are allowed for estimates with different names.
- Removed project number from the create new project popup.
- Any user can now be assigned to an estimate under any role (manager, estimator, sales).
- "Use recommended hours" button now excludes travel.
- Recommended travel hours are based off tech + PM recommended hours.
- Added cost code number to the AIA tab.
- Made pie chart colors more distinct & added percent / category total below the chart.
- Added travel to the summary breakdown section right after gross margin.
## Bug Fixes
- Fixed package image upload bug.

# CADdy Bid v0.0.1-Pre-Alpha
@date: 2026-05-18
## Features
- Project Management: Create projects and add one or more estimates to each project. Add project updates and tag users with @mentions to notify them by email.
- Estimate Creation: Build estimates from scratch using Belimo and Distech parts.
- Hours Pricing: Add labor hours to estimates with office-specific hourly rates.
- Install Systems: Add and price install systems within an estimate.
- Cost Code Review: Review cost code totals to better understand how estimate pricing is distributed.
- Warranty and Contingency: Update warranty and contingency values as part of the estimate pricing workflow.
- Package Management: Create reusable packages of items to speed up estimate setup.
- Admin Setup: Manage estimate items, packages, hours, install systems, and other pricing data used throughout CADdy Bid.
## Things to keep in mind
- CADdy Bid is currently in a pre-alpha testing phase. Some pricing logic, calculations, cost codes, and recommended hours may still need adjustments.
- Not all recommended hours have been finalized yet, and some packages, install systems, or pricing details may still be missing.
- If something looks incorrect, breaks unexpectedly, feels confusing, or seems like it could be improved, please send feedback to caddy@brookssolutions.net


# CADdy Upcoming Features
- TBD

# CADdy Lite Upcoming Features
- Collaborating on projects with friends
- Multi-zone unit configuration
- Shared project logs

# CADdy Bid Upcoming Features
- Sales commissions page.
- Package and assembly categories and grouping.
- Service view with BuildOps information.
- Estimate backup options.
- Restore options from project and estimate logs.
- User preferences, such as custom color options for project sections and statuses, or the ability to hide specific columns.
- Custom project locations that can update per diem travel rates automatically.

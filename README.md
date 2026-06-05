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


# CADdy Bid v0.0.5-Pre-Alpha
@date: 2026-06-05
## New Features
- Right click an estimate item to request adding it to the master BOM list.
- New admin page to approve or deny requested BOM items, with an automatic email sent to whoever made the request.
- Added export / import for material items on the admin materials page — export items, edit any part information, and import the changes back in.
- Added a right click option to move an item to a new section on the admin materials page (works with single or multi-select).
- Added a category option when creating a new material item.
## Improvements
- On the admin materials page, you can now hide columns (with a "show hidden columns" option) and adjust the page size dynamically.

# CADdy Bid v0.0.4-Pre-Alpha
@date: 2026-06-03
## New Features
- Added subcontractor invites:
  - Email invite with Brooks logo & colors
  - Set expiration dates; filter by company, location, or radius
  - Logs sent, opened, quote sent, etc.
  - Add new subcontractors right from the invite page
  - Admin tools to add, update, or delete subcontractors
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
- Estimate save history and backup options.
- Restore options from project and estimate logs.
- Copying items between equipment and breakout sections.
- A dashboard with project summaries, estimate activity, and customizable widgets.
- Improved project organization with separate views for active projects, turned-over projects, lost projects, and special-case projects.
- User preferences, such as custom color options for project sections and statuses, or the ability to hide specific columns.
- Custom project locations that can update per diem travel rates automatically.
- Proposal exports and additional estimate document exports.
- Monday.com integration for linked project tracking.
- Subcontractor invitation workflows, including contact lists, email invites, and status tracking.
- Project file uploads and item photos.
- Order status visibility for items in completed estimates.

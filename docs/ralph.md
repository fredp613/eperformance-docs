# Intake Portal
The Intake Portal offers a streamlined area for the submission of applications. Users are initially brought to the landing page, where they are able to begin the submission process.

## Registration and Login
Once a user has navigated to the landing page for the Intake+ portal, there is an option for them to sign in if they have previously registered or register as a new user. If previously registered, users will be able to enter their login information to access available forms and profile information. 

If the user needs to register, they must complete the required registration information. This includes: first name, last name, email address, password, and password confirmation.

## Client Profile
Client profiles are used for the management of clients within the portal system. Here, clients are defined as individuals that interact with programs. This differs from portal users, who will log into an account for the management of client submissions. Clients create and submit applications through the portal. 

To create a new client user, follow the steps below.
1.	Navigate to Client Profiles. 
2.	Click the Add New (+) icon. 
3.	Complete the dialog by filling out information for profile type and name.

To create a profile type, follow the steps below.

To edit a client user, follow the steps below.

To delete a client user, follow the steps below.

There are various roles associated to clients. By default, a user will have an administrator role for their clients. [^1] This can be changed using the client user page. Available roles include administrator, contributor, and read-only. As an administrator, a user can read and edit client information as well as start, edit, and submit applications on behalf of clients. As a contributor, a user can read client information as well as start, edit, and submit applications on behalf of the client. They are unable to edit client information. A read-only user will only be able to view the profiles of their clients. They are unable to edit client information and cannot start, edit, or submit client applications.

[^1]: It is important to note that an administrator is different to an administrative user. Administrators have full access to administrative tools found within Ralph, such as the form manager.

## Service Amendments

 
# Tenant Manager
## Multiple Tenants
## Adaptor
## Customizing Intake Portal
## SaaS

 
# Form Manager
## Orbeon Overview
Forms are generated using Orbeon Forms, which is a web-based application that provides a platform for easily designing forms. This solution can handle the building and deployment of large web forms with complex validation, making it a very useful tool for enterprises and governmental organizations. 

Administrators have access to use this solution to generate forms directly from the Ralph portal in a browser. This tool uses a WYSIWYG editor style, where the administrator is able to immediately see how the form looks as it is being built. All forms built through Orbeon are accessible via desktop and laptop computers, as well as mobile devices.

•	Validation, visibility, calculations, and branching – Define validation rules; Specify errors, warnings, and alert messages to be displayed; Define visible and editable fields; Automatically calculate and populate values   
•	Repeating sections and tables – Groups of fields can be repeated; Set a minimum and maximum number of items allowed; Reorder items for convenience
•	Encryption – Select encryptions for specific fields in database; Comply with various data protection and privacy regulations
•	Actions and services – Specify HHTP and database service endpoints
•	PDF generation – Generate PDF files with data entered by users; Based on layout of web form or from a template
•	Multi-page forms – Navigation between form pages so users are not overwhelmed by large forms; See errors associated to given form pages and easily navigate to the appropriate page

## Create, Edit, Configure, and Activate Forms
There are various types of forms to be created within the Ralph portal. Such forms are listed and further described below. 

•	Application – For the submission of grants or programs
•	Assessment – Reviews, checklists, evaluations, and other assessments for a grant or program
•	Claim – Funding recipient to request payment at various times throughout the life cycle of the project
•	Profile – For information about a client’s name, number, description, status, and associated actions
•	Reviewer Profile – For information about a reviewer
•	Survey – 

For users to complete and submit forms, there must first be forms available for them to access. These are to be created by administrative-level users working with the various form types. Administrators must navigate to the Forms section, where an initial dropdown menu option is selected. The user will proceed to the View section. Here, the available types of forms as well as existing forms will be listed. 

To create a new form, under the Forms grid, select the Add New button as denoted by the “+” sign. This will prompt for required information, such as the form’s code, type, and initial form version name. Once the form has been initially generated, there is another Add New button located under the form name. Use this to create a new version of a form. It is possible to base the new form off a previous version by selecting to copy contents of an existing form and then adding the required changes. 

Every version is stored under its parent form, as shown above when expanding the parent form. Additional form information is also displayed, such as the form’s version, name, status, activation version, created on date, and last modified on date. From here it is possible to edit, configure, activate, and view the forms. These are denoted by icons to the right of the form version and discussed in upcoming subsections.

From the Orbeon form creator, it is possible to create a form from scratch or edit an existing form. The side panel provides all the tools and functionalities available to create and edit a form. The following features are found in the side panel.
1.	Cut, copy, and paste
2.	Undo/redo insert control
3.	Form settings – Options for general settings that apply to the entire form definition (application name, form name, form title, and description), form options (maximum attachment size, allowed file types, appearance of control labels and hints, and automatic calculation dependencies), control settings (number, currency, date, and time), wizard options (views, navigation validation, subsection navigation, and subsection table of contents), and about this form (versions and form statistics)

## Form Controls


## Data Mapping and Sync to CRM


## Auto-numbering
The Ralph portal has the option for automatic program numbering associated with given schemas, such as case files, submissions, and accounts. Each of these schemas will be associated with a given competition. It is possible to customize the naming conventions for the automatic numbering system as shown below.

1.	Navigate to Forms. Select Tools from the dropdown menu and then select Auto Numbering.
2.	Select the program to be customized. 
3.	Click Edit, as denoted by the pencil icon to the right of the selected program. This will display a dialog window.
4.	Ensure that the program details are correct by verifying the program and schema name. It is possible to change these values by selecting other options from the respective dropdown menu. 
5.	Fill out the following information as desired:
•	Current Number
•	Prefix
•	Separator
•	Pad with Zero
•	Extension Enabled (this checkbox will allow for additional parameters to be defined including prefix, separator, pad with zero, and value)
6.	Click Save. 

## Translation Management
As with an IIPS, Ralph uses a translation manager to toggle a form’s language between English and French. This is done following a specific protocol to ensure the feature’s functionality.

When a field is created on a form, click the control setting icon. Once in the “Settings” screen, go to the “Label” tab. The label should be formatted to have a “_” value in front of the label name for French translations. This is the display key for translations.  Click “Apply” to have the setting be saved. This is shown below. 

A list of all in-use translations is found under the Orbeon configurator. The available translation keys are displayed in a grid containing both the English and French translations. From here, translations can be edited and deleted by navigating to the appropriate icon.

## User Management
Administrator accounts can log into the Intake+ Forms Manager to access portal user information. Here, it is possible to change and reset passwords. This is shown below.

1.	Navigate to Portal Users.
2.	Select the profile to be changed. Click the edit icon to the right of the user, as denoted by a key.
3.	Enter and confirm a new password in the dialog box.
4.	Click Save.
A user can be disabled for various reasons. This should only be done when the user is no longer required or permitted to access the Ralph portal. Follow the steps below to disable a user.
1.	Navigate to Portal Users.
2.	Select the profile to be changed. Click the disable icon to the right of the user, as denoted by a circle containing an “x”.
3.	Confirm the disabling of the selected user by selecting OK in the popup dialog window. A ribbon will be displayed at the bottom of the page confirming the user is no longer enabled. The user will remain as listed in the portal grid but will not have a checkmark under the enabled column. 
4.	If a disabled user attempts to log in, the ribbon will be displayed stating “Failed to sign in. The account is currently locked out.”.

 
# Reviewer Manager
## Registration
## Profile

 
# Troubleshooting

 

# GSPReplaceMe -- Tutorial: ReplaceMe #

## Overview
ReplaceMeText

### Objectives ###
ReplaceMeText 

## Prerequisites VerifyMe##

 -  You have a Google Cloud Platform account and a Google Project (note the Google Project Id) provided by Quiklab. You can find this on the left side of the QwikLab page.
 -  The [Google Chrome browser](https://www.google.com/chrome/browser/desktop/). Other browsers are currently not supported by Cloud Dataprep.
 
 
### Task 1. Setting up your development environment ##
#### Qwiklab
##### Before you click the Start Lab button
Read these instructions. Labs are timed and you cannot pause them. The timer, which starts when you click Start Lab, shows how long Cloud resources will be made available to you.

This Qwiklabs hands-on lab lets you do the lab activities yourself in a real cloud environment, not in a simulation or demo environment. It does so by giving you new, temporary credentials that you use to sign in and access the Google Cloud Platform for the duration of the lab.

#### What you need
To complete this lab, you need:

Access to a standard internet browser (Chrome browser recommended).
Time to complete the lab.
Note: If you already have your own personal GCP account or project, do not use it for this lab.

#### Setting up Google Cloud Platform Console
##### How to start your lab and sign in to the Console

1. Click the Start Lab button. If you need to pay for the lab, a pop-up opens for you to select your payment method. On the left is a panel populated with the temporary credentials that you must use for this lab.  


Note: You can view the menu with a list of GCP Products and Services by clicking the Navigation menu at the top-left, next to “Google Cloud Platform”.
<walkthrough-spotlight-pointer spotlightId="devshell-web-preview-button"
                               text="Open Web Preview">
</walkthrough-spotlight-pointer>
![](https://cdn.qwiklabs.com/a6YnJv8GlGae4rnJIbjA27J8c7YApa%2B6noPFkkKxZjk%3D)

- Verify current account from QwikLab
```bash
gcloud auth list
```

- Check your current project.
```bash
gcloud config list project
```
Your current project name is: {{<project-name>}}  
Your current project id is: {{<project-id>}}  
 Be sure to compare this to the display in your Qwiklab after you start the lab. The display looks like this:  
 ![Login Info](https://cdn.qwiklabs.com/%2FtHp4GI5VSDyTtdqi3qDFtevuY014F88%2BFow%2FadnRgE%3D)  
 
1. Copy the username, and then click Open Google Console. The lab spins up resources, and then opens another tab that shows the Choose an account page.

Tip: Open the tabs in separate windows, side-by-side.

1. On the Choose an account page, click Use Another Account.  
 ![Login Info](https://cdn.qwiklabs.com/eQ6xPnPn13GjiJP3RWlHWwiMjhooHxTNvzfg1AL2WPw%3D) 
 
1.   The Sign in page opens. Paste the username that you copied from the Connection Details panel. Then copy and paste the password.

Important: You must use the credentials from the Connection Details panel. Do not use your Qwiklabs credentials. If you have your own GCP account, do not use it for this lab (avoids incurring charges).

1. Click through the subsequent pages:

Accept the terms and conditions.
Do not add recovery options or two-factor authentication (because this is a temporary account).
Do not sign up for free trials.
After a few moments, the GCP console opens in this tab.
Note: You can view the menu with a list of GCP Products and Services by clicking the Navigation menu at the top-left, next to “Google Cloud Platform”.
![Hamburger](https://cdn.qwiklabs.com/9vT7xPlxoNP%2FPsK0J8j0ZPFB4HnnpaIJVCDByaBrSHg%3D)  
Open the Navigation Menu Icon
<walkthrough-nav-menu-icon>
</walkthrough-nav-menu-icon>
<walkthrough-spotlight-pointer
    spotlightId="nav-menu-icon">
    spotlight on the nav menu icon
</walkthrough-spotlight-pointer>

#### ReplaceMeSectionTitle
ReplaceMeText 
ReplaceMeBelow - Below is an example imagefrom the Qwiklab site.
![](https://cdn.qwiklabs.com/O2n0exH9RUENSsK99EJIUKFgk%2BX8HlTC95mpNxwqZcM%3D)  

Task 2ReplaceMeText.ReplaceMeText
ReplaceMeText

In the left pane, select your project name:
![](https://cdn.qwiklabs.com/esw2SaacyT37O73Yl9AXNNnlfgwdd2YzbCs5W1m8yZU%3D)  
Then from the right-hand side of the Console, click CREATE DATASET:

ReplaceMeText 

Task 3. ReplaceMeText
ReplaceMeText

Task 4. ReplaceMeText
In this task, you will connect Cloud Dataprep to your BigQuery data source. On the Cloud Dataprep page:

Task 5. 
ReplaceMeText
![](https://cdn.qwiklabs.com/ReplaceMeLink)

ReplaceMeText
![](https://cdn.qwiklabs.com/ReplaceMeLink)

Task 6. 
ReplaceMeText
![](https://cdn.qwiklabs.com/ReplaceMeLink)

ReplaceMeText
![](https://cdn.qwiklabs.com/ReplaceMeLink)

Congratulations!
You've successfully explored your ecommerce dataset and created a recurring data transformation pipeline with Cloud Dataprep.

Go back to the Qwicklabs page to verify the lab shows as complete.

<walkthrough-conclusion-trophy></walkthrough-conclusion-trophy>

#ReplaceMeExamplesStart
##This section is from the Github Markdown guide https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf
HEADERS
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

EMPHASIS
*This text will be italic*
_This will also be italic_
**This text will be bold**
__This will also be bold__
*You **can** combine them*

BLOCKQUOTES
As Grace Hopper said:
> I’ve always been more interested
> in the future than in the past.
As Grace Hopper said:
 I've always been more interested
 in the future than in the past.
 
 LISTS
Unordered
* Item 1
* Item 2
 * Item 2a
 * Item 2b
 
Ordered
1. Item 1
2. Item 2
3. Item 3
 * Item 3a
 * Item 3b

IMAGES
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

LINKS
http://github.com - automatic!
[GitHub](http://github.com)

BACKSLASH ESCAPES
Markdown allows you to use backslash escapes to generate literal characters which
would otherwise have special meaning in Markdown’s formaing syntax.
Markdown provides backslash escapes for
the following characters:
\ backslash
` backtick
* asterisk
_ underscore
{} curly braces
[] square brackets
() parentheses
# hash mark
+ plus sign
- minus sign (hyphen)
. dot
! exclamation mark

\*literal asterisks\*
*literal asterisks*

USERNAME @MENTIONS
Typing an @ symbol, followed by
a username, will notify that person
to come and view the comment.
This is called an “@mention”,
because you’re mentioning the
individual. You can also @mention
teams within an organization.
ISSUE REFERENCES
Any number that refers to an Issue or
Pull Request will be automatically
converted into a link.
#1
github-flavored-markdown#1
defunkt/github-flavored-markdown#1

EMOJI
GitHub supports emoji!
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat: 

FENCED CODE BLOCKS
```javascript
function test() {
 console.log("look ma’, no spaces");
}
```

TASK LISTS
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](),
**formatting**, and <del>tags</del>
supported
- [x] list syntax required (any
unordered or ordered list
supported)
this is a complete item
this is an incomplete item
@mentions, #refs, links, formaing,
and tags supported
list syntax required (any unordered or
ordered list supported)

TABLES
First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column 2
First Header Second Header
Content cell 1 Content cell 2
Content column 1 Content column 2

End of Markdown reference

Begin Cloud Shell Walkthrough reference:
https://cloud.google.com/shell/docs/walkthroughs

Writing a Walkthrough
Walkthroughs are written in Markdown - specifically, in CommonMark format, and without HTML - and can be developed using any text editor. You can also add directives to your Walkthrough which include advanced functionality, like spotlighting and adding inline icons, with Walkthrough-specific Markdown to make it easier to follow.

Create Steps
When creating a Walkthrough, headings are important in determining its structure. To set the right title, step headings, and underlying instructions, follow the hierarchy below:

H1 (#) tags for the Walkthrough title. There should only be a single H1 tag in the Walkthrough.
H2 (##) tags for a step title.
H3 (###) tags for a sub-step title.
Here is a sample Markdown file you can use to create a Walkthrough:

# First Walkthrough

## First step

Hello World

### Part 1

Part One Instructions.

### Part 2

Part Two Instructions.

## Conclusion

Done!
Add a Code Block
To callout a code snippet, use backticks as follows:

```
print("hello world")
```
The resulting code snippet comes with a copy-to-clipboard button in the right-hand corner.

Add directives
To add a directive (advanced walkthrough functionality like spotlighting a UI element, displaying an inline icon, and triggering file actions), use the following custom element format:

<walkthrough-directive-name param="optional parameter">
</walkthrough-directive-name>
In this format, 'directive-name' and 'param' are placeholders. For example, if you'd like to use the directive, editor-open-file, and the parameter, filePath, use this format:

<walkthrough-editor-open-file filePath="test/hello.md">
</walkthrough-editor-open-file>
Note: Parameters are strings separated by whitespace. Quotes around the parameters are optional. If the parameter does contain whitespace, such as the label text for a spotlight pointer, quotes are required.
Create a spotlight
A spotlight is a visual focus to help users find a specific UI element within Console.

To spotlight a Console element, use this format:

<walkthrough-spotlight-pointer spotlightId="target" text="label text">
</walkthrough-spotlight-pointer>
Putting it into practice, if you'd like to spotlight the button to open the web preview window for Cloud Shell, use:

<walkthrough-spotlight-pointer spotlightId="devshell-web-preview-button"
                               text="Open Cloud Shell">
</walkthrough-spotlight-pointer>
For elements within the editor, choose to use the editor-spotlight directive. To spotlight an existing hello.md file when a user clicks 'My file', use:

<walkthrough-editor-spotlight spotlightId="navigator" filePath="hello.md"
                              text="My file">
</walkthrough-editor-spotlight>
Tip: For UI elements that don't have spotlight IDs, you can use a CSS selector.

Use an inline icon
To effectively call out the use of a Console button, use an inline icon.

For example, <walkthrough-cloud-shell-editor-icon></walkthrough-cloud-shell-editor-icon> produces an inline icon of the Cloud Shell editor icon Cloud Shell Icon.

Trigger file actions
Additionally, you can have links in your Walkthrough that open useful files for users. To open a file in Cloud Editor as your user walks through your Walkthrough and clicks on the display text, 'Open sample file', use the following directive:

<walkthrough-editor-open-file filePath="path/to/test.md"
                              text="Open sample file">
</walkthrough-editor-open-file>
Note, the file must exist on the users' Cloud Shell instance and the provided path must be its relative file path. The file must be located in the Home directory or in any of the Home directory's subdirectories.

Find the right directives
Look up the Walkthrough Markdown Reference for an extensive list of all possible spotlights (and their parameters) available to you.

Launching Walkthroughs in Cloud Shell
There are two ways to kickstart a Walkthrough in Cloud Shell:

Note: To launch a Walkthrough in developer mode, use `cloudshell launch-tutorial -d tutorial-name.md`.
Use the cloudshell launch-tutorial command

Run the following cloudshell command in your Cloud Shell session to launch a Walkthrough from an existing Markdown file, tutorial.md:

cloudshell launch-tutorial tutorial.md
Alternatively, you can use the teachme alias by running the following command in your Cloud Shell session to launch a Walkthrough from an existing file, hello.md:

teachme hello.md
Use 'Open in Cloud Shell'

Alternatively, you can use the 'Open in Cloud Shell' feature to guide your users from a website, blog or open source project, to your Walkthrough hosted in a git repository. The 'Open in Cloud Shell' feature allows for a 'tutorial' parameter, and can be added to the end of the URL as such &tutorial=path/to/file.md to specify the location of the source Markdown file in the repository. This means that the Markdown for a button linked to your Walkthrough would look like:
[![Open in Cloud Shell](https://gstatic.com/cloudssh/images/open-btn.png)](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/testuser/myproject&tutorial=resources/hello.md)

https://cloud.google.com/shell/docs/walkthrough-markdown-reference

Cloud Shell tutorials, also known as Walkthroughs, help users familiarize themselves with your project quickly and effectively, while being easy to set up and launch. A Cloud Shell Walkthrough is a set of instructions written in CommonMark Markdown. It can also include directives which are Walkthrough specific Markdown expressions to add advanced functionality like spotlighting and project selection.

Refer to the Writing Walkthroughs guide for how to set up, compose, and launch a Walkthrough in Cloud Shell.

Directive format
To add a directive, use the following format:

<walkthrough-directive-name param-name="param-value">
</walkthrough-directive-name>
In this format, 'directive-name' and 'param' are placeholders. For example, if you'd like to use the directive, editor-open-file, and the parameter, filePath, use this format:

<walkthrough-editor-open-file filePath="test/hello.md">
</walkthrough-editor-open-file>
Note: Parameters are strings separated by whitespace. Quotes around the parameters are optional. If the parameter does contain whitespace, such as the label text for a spotlight pointer, quotes are required.
Cloud Shell directives
The tables below list the directives, and their respective parameters, available for use when authoring a Cloud Shell Walkthrough.

Walkthrough metadata and layout
Directive: Author
<walkthrough-author></walkthrough-author>
The author tag defines metadata about the author. All parameters are optional.

Parameters	Description
name	Author's name.
repositoryUrl	Link to the repository which is used for feedback.
tutorialName	Walkthrough id
Directive: Walkthrough Duration
<walkthrough-tutorial-duration></walkthrough-tutorial-duration>
The Walkthrough duration tag renders a clock icon and message estimating how long the Walkthrough will take.

Parameters	Description
duration	Estimated Walkthrough duration in minutes.
Directive: Suggested Walkthrough card
<walkthrough-tutorial-card></walkthrough-tutorial-card>
A Walkthrough card tag links to a suggested Walkthrough.

Parameters	Description
url	URL to the Walkthrough.
icon	Icon name.
label	Label for analytics for click events.
Directive: Footnote
<walkthrough-footnote>Footnote text here</walkthrough-footnote>
A footnote directive styles the text as a footnote at the bottom of the step. Footnote text is written as the inner text.

Project selection
Directive: Project setup
<walkthrough-project-setup></walkthrough-project-setup>
The project setup component helps the user create or select a project to use. This step will block the user from continuing until a valid project has been selected.

The project permissions tag sets required project permissions for the Walkthrough. If the user lacks the permissions on the selected project, the project setup will not consider it a valid project.

See the documentation for a description of how project permissions work.

Parameters	Description
permissions	(Optional) Comma separated list of required permissions.
Directive: Project and billing setup
<walkthrough-project-billing-setup></walkthrough-project-billing-setup>
The project and billing setup component helps the user create or select a project to use. This step will block the user from continuing until a valid project with billing enabled has been selected.

Parameters	Description
permissions	(Optional) Comma separated list of required permissions.
Spotlights and buttons
Directive: Spotlight pointer
<walkthrough-spotlight-pointer>Label text here</walkthrough-spotlight-pointer>
The spotlight pointer directive creates a clickable label that will spotlight the specified UI element on the screen. Only one of the parameters is needed. If both are provided, the spotlightId will be used.

The pointer can select an element by instrumentation id, which is a property on the DOM element, or by using a CSS selector. Both types of selectors allow comma separated selectors to match elements. All elements matching the selector will be highlighted.

Label text is written as the inner text.

Parameters	Description
spotlightId	Instrumentation ID, can use commas to separate multiple IDs.
cssSelector	A CSS selector
Spotlight targets/instrumentation IDs	Description
console-nav-menu	Console navigation menu, hamburger in top left.
devshell-activate-button	Button to open Cloud Shell, near top right.
devshell-web-editor-button	Opens Orion editor, on Cloud Shell's top bar.
devshell-web-preview-button	Opens a web preview window for Cloud Shell.
For spotlights within the editor frame, see the section of Editor directives.

Directive: Enable APIs
<walkthrough-enable-apis></walkthrough-enable-apis>
The enable APIs component creates a button that enables APIs when clicked. This will allow your project to access the GCP APIs.

Refer to the documentation for which APIs you can enable.

Parameters	Description
apis	Comma separated list of APIs to enable.
Directive: Open Cloud Shell
<walkthrough-open-cloud-shell-button></walkthrough-open-cloud-shell-button>
The open Cloud Shell component creates a button that opens Cloud Shell when clicked (with the current project selected).

Parameters	Description
open-cloud-shell	Opens Cloud Shell when the parent step is viewed.
Directive: Open Cloud Shell in the background
<walkthrough-devshell-precreate></walkthrough-devshell-precreate>
The devshell-precreate directive provisions a Cloud Shell instance in the background so the load is faster. Runs when the step is shown.

Dynamic variables
Directive: Data binding
<walkthrough-watcher-constant></walkthrough-watcher-constant>
Walkthroughs allow data binding for key-value pairs. The values are set by directives or by the Walkthrough framework. They can be defined within the Walkthrough session using the directive watcher-constant.

Afterwards, the string value can be referenced with:

{﻿{<key>}}

Example usage in Markdown:

# My Walkthrough

## Step 1

<walkthrough-watcher-constant key="my-key" value="Hello Google">
</walkthrough-watcher-constant>

My message: {﻿{my-key}}
There are built-in keys available:

Key	Value description
project-id	The user's current project id.
project-name	The user's project name.
Directive: Watcher constant
<walkthrough-watcher-constant></walkthrough-watcher-constant>
A Watcher is a dynamic string that can be set for a Walkthrough. A watcher constant defines the value at the beginning of the Walkthrough. See the data binding section for more information.

Parameters	Description
key	Key to the watcher.
value	Value of the watcher.
Directive: Inline icons
<walkthrough-inline-icon-name></walkthrough-inline-icon-name>
'inline-icon-name' is a placeholder for the icon you'd like to specify (like nav-menu-icon and conclusion-trophy).

The following icons are styled as inline icons.

Inline icon name	Icon
cloud-shell-icon	Cloud Shell Icon
web-preview-icon	Web Preview Icon
cloud-shell-editor-icon	Cloud Shell Editor Icon
nav-menu-icon	Nav Menu Icon
notification-menu-icon	Notification Menu Icon
pin-section-icon	Pin Menu Section Icon
The following icons are styled as images.

Inline icon name	Icon
conclusion-trophy	Conclusion Trophy
Cloud Shell Editor directives
Editor directives are supported by the Cloud Shell Editor page.

Directive: Open file
<walkthrough-editor-open-file></walkthrough-editor-open-file>
The open file directive creates a clickable label to open a file from the Cloud Shell disk in the editor.

Label text is written as the inner text.

Parameters	Description
filePath	Relative file path
Directive: Open selected text in editor
<walkthrough-editor-select-line></walkthrough-editor-select-line>
The editor-select-line directive creates a clickable label to open a file in the editor and select a line of text within it.

Parameters	Description
filePath	Relative file path
startLine	Start line
startCharacterOffset	Start index
endLine	End line
endCharacterOffset	End index
Directive: Open regex specified text in editor
<walkthrough-editor-select-regex>Label text here</walkthrough-editor-select-regex>
The editor-select-regex directive creates a clickable label to open a file in the editor and selects text within it, based on the provided regex.

Parameters	Description
filePath	Relative file path
regex	Regex to match
Label text is written as the inner text.

Directive: Spotlight pointer
<walkthrough-editor-spotlight>Label text here</walkthrough-editor-spotlight>
The spotlight pointer directive creates a clickable label that will spotlight the specified UI element within the editor on the screen.

The pointer can only select predefined targets.

Parameters	Description
spotlightId	Editor ID
Label text is written as the inner text.

Editor spotlight targets	Description
fileMenu	Highlights the file menu button.
editMenu	Highlights the edit menu button.
navigator	Highlight a file specified in the item field.
Was this page helpful? Let us know how we did:
SEND FEEDBACK
Except as otherwise noted, the content of this page is licensed under the Creative Commons Attribution 4.0 License, and code samples are licensed under the Apache 2.0 License. For details, see our Site Policies. Java is a registered trademark of Oracle and/or its affiliates.




##This Section is from the 




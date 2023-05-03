Download Link: https://assignmentchef.com/product/solved-cs1xa3-project2-shellscriptfun
<br>
You must keep your repo inside of your directory located in $HOME/private on the mac1xa3.ca server

<ul>

 <li>WARNING not doing so or changing the default permissions on the private directory will be considered academic dishonesty</li>

 <li>If you accidentently delete the directory, contact me or one of your TA’s (preferably me / dalvescb on discord)</li>

</ul>

<h2><a name="_Toc5258"></a>1.2           Create a new folder in your repo</h2>

On the master branch, create a new folder CS1XA3/Project01 (where CS1XA3 is the already existant root of repo)

<h2><a name="_Toc5259"></a>1.3           Add the folowing files</h2>

<ul>

 <li>Add CS1XA3/Project01/project_analyze.sh</li>

 <li>Add CS1XA3/Project01/README.md</li>

</ul>

<h2><a name="_Toc5260"></a>1.4           Commit and Push</h2>

<ul>

 <li>Add and commit with the following message EXACTLY “Initial Project01 Commit”</li>

 <li>Push to GitHub</li>

</ul>

<h2><a name="_Toc5261"></a>1.5           Create a Branch</h2>

<ul>

 <li>Create a branch called project01</li>

 <li>Push the branch to github (i.e git push origin project01)</li>

 <li>Work from the project01 branch and only merge with master when your ready to submit Part 1 or Part 2</li>

</ul>

Merge to the master branch a WORKING SCRIPT that:

<ul>

 <li>implements at least 20 points worth of 5 point features including the Script Input feature</li>

 <li>documents the features you implement and script usage in the md</li>

 <li>documents the two custom features you plan to implement (although you don’t need to implement them yet)</li>

 <li>has a commit/merge message “Submitting Project 01 Part 1” EXACTLY WARNING make sure to push to GitHub to complete your submission</li>

</ul>

<h1><a name="_Toc5263"></a>3           Part 2 Submission</h1>

Merge to the master branch a WORKING SCRIPT that:

<ul>

 <li>implements at least 20 points more worth of features including at least one 10 point feature</li>

 <li>implements 2 custom features that should be around the same level of difficulty as the 10 point features</li>

 <li>has completed documentation of all features in the md</li>

 <li>has a commit/merge message “Submitting Project 01 Part 2” EXACTLY</li>

</ul>

WARNING make sure to push to GitHub to complete your submission

<h1><a name="_Toc5264"></a>4           README</h1>

You MUST document your code in a file CS1XA3/Project01/README.md

<ul>

 <li>The document should be styled with MarkDown (see <a href="https://guides.github.com/features/mastering-markdown/">https://guides.github.com/features/ </a><a href="https://guides.github.com/features/mastering-markdown/">mastering-markdown/</a><a href="https://guides.github.com/features/mastering-markdown/">)</a></li>

 <li>The document should describe usage of the script (i.e how to execute, with what arguments, under what conditions)</li>

 <li>The document should contain a section (header) for each feature (including custom features)</li>

 <li>You must reference any code used that was found online with a link to the url (failing to do so will be considered academic dishonesty)</li>

</ul>

An example of the general outline of the document would be as follows (this is not an exact template you need to follow, you are encouraged to use your best judgment for constructing a useful README):

# CS 1XA3 Project01 – &lt;MyMacId&gt;

## Usage

Execute this script from project root with:

chmod +x CS1XA3/Project01/project_analyze.sh

./CS1XA3/Project01/project_analyze arg1 arg2 …

With possible arguments arg1: ….

arg2: ….

….

## Feature 01

Description: this feature does ….

Execution: execute this feature by …

Reference: some code was taken from [[https://someurl.com]]

## Feature 02 …

## Custom Feature SomeFeature …<a name="_Toc5265"></a>

<h2><a name="_Toc5266"></a>5.1           Criteria: README Documentation</h2>

<ul>

 <li>30% for using good style (i.e using proper markdown, proper sectioning of functionality etc)</li>

 <li>30% for specifying execution/usage information correctly</li>

 <li>40% for proper detail: what each feature does, as well as pitfalls for the feature not functioning correctly, while still be concise and not containing superfluous information</li>

</ul>

<h2><a name="_Toc5267"></a>5.2           Criteria: Custom Features</h2>

<ul>

 <li>Each of the two custom features is worth 20% of the overall project mark</li>

 <li>Per each feature:

  <ul>

   <li>50% for the creativity / difficulty level of the feature you came up with</li>

   <li>50% for implementing the feature correctly</li>

  </ul></li>

</ul>

<h2><a name="_Toc5268"></a>5.3           Criteria: Other Features</h2>

<ul>

 <li>You will implement 40 points of features directly corresponding to 40% of your overall project mark</li>

 <li>Features will be marked on level of correctness. Partial marks will be taken off for failing to include edge case, including but not limited to:

  <ul>

   <li>failing to account for directories/files including special characters (i.e whitespace)</li>

   <li>failing to account for directories/files not existing / already existing</li>

   <li>failing to account for command IO failure</li>

  </ul></li>

</ul>

<h2><a name="_Toc5269"></a>5.4           Plagiarism / Academic Dishonesty</h2>

Tools will be used to compare your code with your peers (including previous years of this course)

<ul>

 <li>Stealing a custom feature idea will be considered plagiarism</li>

 <li>Using code without referencing the source in your README will be considered plagiarism.</li>

 <li>Any account of plagiarism will result in an automatic grade of 0</li>

</ul>

<h1><a name="_Toc5270"></a>6           Features</h1>

<h2><a name="_Toc5271"></a>6.1           Script Input (Mandatory) (5 Points)</h2>

<ul>

 <li>Make the script interactive (i.e select which feature(s) are executed) either by providing script arguments or by user prompted input</li>

 <li>Describe this feature in the Usage section of the md document rather than in it’s own header</li>

</ul>

<h2><a name="_Toc5272"></a>6.2           FIXME Log</h2>

<ul>

 <li>Find every file in your repo that has the word #FIXME in the last line</li>

 <li>Put the list of these file names in CS1XA3/Project01/fixme.log with each file separated by a newline</li>

 <li>Create the file CS1XA3/Project01/fixme.log if it doesn’t exist, overwrite it if it does</li>

</ul>

<h2><a name="_Toc5273"></a>6.3           Checkout Latest Merge</h2>

<ul>

 <li>Find the most recent commit with the word merge (case insensitive) in the commit message</li>

 <li>Automatically checkout that commit (so that you’re in a detached head state)</li>

</ul>

<h2><a name="_Toc5274"></a>6.4           File Size List</h2>

<ul>

 <li>List all files in the repo (just files not directories) and their sizes in a human readable format (i.e KB, MB, GB, etc)</li>

 <li>List the files sorted from largest to smallest</li>

</ul>

<h2><a name="_Toc5275"></a>6.5           File Type Count</h2>

<ul>

 <li>Using the read command (with a prompt), prompt the user for an extension (i.e txt, pdf, py, etc)</li>

 <li>Output the number of files in your repo with that extension</li>

</ul>

<h2><a name="_Toc5276"></a>6.6           Find Tag</h2>

<ul>

 <li>Using the read command (with a prompt, prompt the user for a Tag (any single word)</li>

 <li>Create a log file CS1XA3/Project01/Tag.log (where Tag is the name of the Tag provided) if it doesn’t already exist, overwrite it if it does</li>

 <li>For each python file (i.e ending in .py) in the repo, find all lines that begin with a comment (i.e #) and include Tag and put them in CS1XA3/Project01/Tag.log</li>

</ul>

<h2><a name="_Toc5277"></a>6.7           Switch to Executable</h2>

<ul>

 <li>Find all shell scripts (i.e ending in .sh) in the repo</li>

 <li>Create a file CS1XA3/Project01/permissions.log if it doesn’t already exist</li>

 <li>Using the read command, prompt the user to Change or Restore (use a prompt that tells the user what to do)</li>

 <li>If the user selects Change:

  <ul>

   <li>For each shell script, change the permissions so that only people who have write permissions also have executable permissions (i.e if only user has write permissions, then only user has executable permissions)</li>

   <li>Store a log of the file and it’s original permissions in CS1XA3/Project01/permissions.log (overwrite it if it already exists)</li>

  </ul></li>

 <li>If the user selects Restore

  <ul>

   <li>Restore each file to its original permissions (as specified in CS1XA3/Project01/permissions.log)</li>

  </ul></li>

</ul>

<h2><a name="_Toc5278"></a>6.8           Backup and Delete / Restore</h2>

<ul>

 <li>Using the read command, prompt the user to Backup or Restore (use a prompt that tells the user what to do)</li>

 <li>If the user selects Backup:

  <ul>

   <li>Create an empty directory CS1XA3/Project01/backup if it doesn’t exit</li>

   <li>Empty the directory CS1XA3/Project01/backup if it does exist</li>

   <li>Find all files that end in the .tmp extension</li>

  </ul></li>

</ul>

∗ copy them to the CS1XA3/Project01/backup directory

∗ delete them from their original location

∗ create a file CS1XA3/Project01/backup/restore.log that contains a list of paths of the files original locations

<ul>

 <li>If the user selects Restore:

  <ul>

   <li>use the file CS1XA3/Project01/backup/restore.log to restore the files to their original location</li>

   <li>if the file does not exist, through an error message</li>

  </ul></li>

</ul>
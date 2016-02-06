# 2.0 Administration Menu

There are four options on top:

|Option|	Action|
|---|---|
|Preferences|	Here you can configure your preferences for the module|
|Update|	Click here if you’ve made some changes to the module, uploaded new files, etc. – this will recompile the module and update all entries in the database |
|Blocks|	When you click here, it will redirect you to the Blocks section of XOOPS, and select the blocks related to your module|
|Templates|	This will open for you the template editor window|
|Comments|	Here you can view comments related to this module|
|Unistall|	Click here to easily uninstall the module. Very handy in testing|
|Go to module|	If the module is visible on the user side, this will take you there|

In the Admin Menu, there are following key menu Tabs:

* Index
* Categories
* Forums
* Permissions
* Order
* Prune
* Reports
* Digest
* Votes
* Topic types
* Group Moderate
* Sync Forums
* About

Let's explore in detail each of them:

#### Index
![](../assets/image001.jpg)

In this tab you can see the statistics about the module, incl. number of Topics, number of Posts, and how many views you had on the NewBB. 

You can also see if there are any Pending reports.

####  Categories
![](../assets/newbb_admin_categories.jpg)

This Tab gives you an overview of your Categories. You have also a button to create a new Category, if needed, which opens the form below:

![](../assets/newbb_admin_categories_new.jpg)

You will need to fill out the form and save it, in order to create the new category. The same form is also used for editing existing Categories.

####  Forums

![](../assets/newbb_admin_forums.jpg)

For each Category, you can create Forums and Sub-Forums, and the "Forums" Tab gives you the overview of the available Forums. In addition to creating new Forums and Sub-Forums, you can also "move" and "merge" existing forums. 

![](../assets/newbb_admin_forums_move.jpg)

![](../assets/newbb_admin_forums_merge.jpg)

To create a new Forum, you need to fill-out this form that will open after you click on the "Add" button:

![](../assets/newbb_admin_forums_edit.jpg)

![](../assets/info/tips.gif) You can use existing "Default Permissions" for your new forum, which will save you a lot of time. You will learn how to set the permissions below.

####  Permissions

![](../assets/newbb_admin_permissions.jpg)

When you go to the Permissions tab, as first you'll see in the left column list of available Groups (normally: Webmaster, Registered Users, and Anonymous Users), and on the right list of available Categories and Forums. 

You can select individual "activity" from the list below by clicking on the drop-down menu:

![](../assets/newbb_admin_permissions_selectPermissions.jpg)

and then select for each Group and each Category/Forum the appropriate permission.

If you have the same level of permissions for all Groups and for all Categories/Forums, you can define a "Default" set of Permissions, that you can reuse for all new and existing forums. This makes the management of Permissions much easier, while still allowing you to customize it as needed.

This powerful Permissions system is one of the strongest points of XOOPS, as you can reuse it in all modules, and you can assign individual permissions at a very granular level.   


![](../assets/newbb_admin_permissions_setDefault.jpg)



####  Order

![](../assets/newbb_admin_orderForums.jpg)

Here you can reorder the Forums within each Category. 

As you remember, in the Forums Tab, you can also move and merge the Forums. 

####  Prune

![](../assets/newbb_admin_prune.jpg)

Sometimes you might decide that some of the Topics and/or messages are outdated, and you need to do a Clean-up!  That's where the Prune tab is coming very handy. You can select the topics that you would like to remove, and you can do it in very granular level. 

Instead of just deleting them, you can also move them to a specific location (e.g. you can create an "Archive Forum" and move them there, so you can keep them for future references, if needed. 

####  Reports
![](../assets/newbb_admin_reports.jpg)

When somebody posts messages that are against the rules, the users can report these messages to you. You can then review these messages here and take appropriate actions.

####  Digest

![](../assets/newbb_admin_digest.jpg)

"Digest Manager" is designed for sending digest through emails, not for the digested threads themselves.

Digest has two major functionalities:

1. marked with a special label indication the thread is important or valuable

2. sending digest though email: it lets members to read valuable thread periodically, e.g. once a week. 

A digest is marked by a moderator or webmaster through "topic manager", in other words, it is judged totally by the one who marks it.

####  Votes

![](../assets/newbb_admin_votes.jpg)

You can allow your users to vote on individual topics, to see what is "hot", and what is not. Here in this tab you can review the votes and see if they are legit, or if somebody is trying to manipulate the voting. In such case, you can delete the votes and take appropriate actions. 

####  Topic types

![](../assets/newbb_admin_types.jpg)

Sometimes you would like to have the option to highlight specific topics. You can that by creating "Types" and assigning a color to them:


![](../assets/newbb_admin_typesAdded.jpg)

Once you have created Types in your NewBB, you can now select Forums by clicking on the "Type per forum" button and selecting the Forums:

![](../assets/newbb_admin_typesSelectForum.jpg)

After submitting the Forum selection, you can now add the Types of you choice to the selected Forums, by assigning a value greater than 0 for the particual Type:

![](../assets/newbb_admin_typesToForum.jpg)


####  Group Moderate

![](../assets/newbb_admin_moderate.jpg)

Sometimes, on some "public" forums, there is a need to moderate the forums, to make sure that everybody is treating each other and is behaving the way it is spelled out in the Forum rules and regulations. The "Group Moderate" tab allows you to select a forum and then assign a particular group as a moderator:

![](../assets/newbb_admin_moderate_selected.jpg)

![](../assets/info/tips.gif) You can create a specific Group just for the moderation purpose, and then assign individual members to it. Of course, there is no limitation on this, so you could create a "moderation group" to be responsible for each individual Forum, and then assign somebody to it, but this would be an overkill.

A better way is to assign a group (or groups) for several Forums, and then go back to each individual Forums, and select those individuals who you want to be a Moderator for that particular Forum. 

####  Sync Forums
![](../assets/newbb_admin_sync.jpg)

Sometimes, maybe because of a crash of you Website, some of the records might get corrupted and out of sync. The "Sync Forums" tab will help you with getting the forums and the posts is sync.

####  About
![](../assets/newbb_admin_help.jpg)

Finally, the "About" tab will provide you with more info about the module itself, like version number, release date, authors, and the changelog. 

===============
Custom Fields
===============
You can enter bugs immediately after setup, but you probably want to make some configuration changes first.

Log in as "admin" and click on the "admin" link along the top. You should now be viewing a page with links to "users", "projects", "categories", "priorities", and "statuses". Add/delete/change the values according to your needs.

When you first install BugTracker.NET, there are only these half-dozen or so fields on the "edit_bug.aspx" page. Many people add more, for example "Version Fixed", "Due Date", etc. There are three ways to add custom fields:

1. "user defined attribute" - This is the simplest way to add one custom field. You can use the simple "user defined attribute" dropdown that applies to all projects. Edit these lines in Web.config to use and name this additional dropdown:

.. sourcecode:: xml
    <add key="ShowUserDefinedBugAttribute" value="1"/>
    <add key="UserDefinedBugAttributeName" value="YourAttribute"/>

2. "custom field" - You can add custom columns to the bug table and they will show up in the edit bug page and the search page. See the admin "custom fields" page. The fields you add here apply to all projects. You can add as many custom fields as you want.

.. sourcecode:: xml
    <add key="ShowUserDefinedBugAttribute" value="1"/>

Here is a code block

.. code-block:: xml
    <add key="ShowUserDefinedBugAttribute" value="1"/>


Here is a sourcecode block

.. sourcecode:: xml
    <add key="ShowUserDefinedBugAttribute" value="1"/>



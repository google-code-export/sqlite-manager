The project has shifted to Github at https://github.com/lazierthanthou/sqlite-manager.

Now we have some documentation available under the wikis. Thanks to fairfaxwatershed for these docs.

Manage all your sqlite databases using this lightweight extension for firefox, thunderbird, seamonkey, komodo etc. ([See the complete list of supported applications](SupportedApplications.md)) This extension will be useful to developers who want to create and play with sqlite databases.

SQLite Manager is available as a XULRunner application too. The file with _XR_ in its name is the zip of the XULRunner application. [Read More...](XulrunnerApplication.md)

**Version 0.7.6 supports English, German, Japanese, French, Russian, Spanish, Swedish and Italian languages**

You can also download from https://addons.mozilla.org/addon/sqlite-manager

### SQLite Manager for other applications ###
  * Songbird: http://addons.songbirdnest.com/addon/1711
  * Komodo: http://community.activestate.com/xpi/sqlite-manager

[![](http://www.mozilla.org/contribute/buttons/468x60bubble_b.png)](http://www.mozilla.org/firefox?WT.mc_id=aff_en18&WT.mc_ev=click)

### Features ###
  * dialogs for creation, deletion of tables, indexes, views and triggers
  * ability to rename, copy, reindex tables
  * ability to add and drop columns
  * create new db, open any existing db, copy an existing db
  * supports writing your own queries (single or multiple)
  * supports saving the queries with a name
  * a tab for database settings (no need to write the pragma statements) where you can view and change the sqlite library settings
  * export tables/views as csv, sql or xml files
  * import tables from csv, sql or xml files
  * a dropdown menu showing all profile db (.sqlite)
  * an intuitive heirarchical tree showing all tables, indexes, views and triggers
  * ability to see the master tables
  * ability to see the temporary tables, indexes, views and triggers
  * ability to browse data from any table/view
  * dialogs to allow searching in a table/view
  * allows editing and deleting selected record while browsing a table's data
  * allows adding, saving and changing blob data
  * an extensive menu that helps with writing sql by hand and then executing it
  * remembers the last used db, table and the tab (structure, browse & search, etc.) across sessions


More and more developers will start using SQLite. To help them manage their databases through a Mozilla extension is the motivation behind this add-on extension.

SQLite is a small C library that implements a self-contained, embeddable, zero-configuration SQL database engine. An SQLite database is a single ordinary disk file that can be located anywhere in the directory hierarchy.
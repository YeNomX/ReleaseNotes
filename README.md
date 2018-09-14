
[简体中文](/VersionHistory-iOS/zh_Hans) | [繁體中文](/VersionHistory-iOS/zh_Hant)

------

__v3.10.9 @ 2018-09-14__
  
  - Update style for some list views;
  - Update Auto-Lock setting view;
  - BUGFIX: Add button disappears after sorting items in Summary Widget setting view.

__v3.10.7 @ 2018-09-10__
  
  - Support multiple currencies (or any other unit) in one account;
  - Support custom unit creation (related management view is "Settings - General - Unit");
  - Support adding API to update exchange rate (related management view is "Settings - General - Unit Relation");
  - Update unit related options in "Settings - General - Number Format";
  - Account Edit View: Add "Account Default Unit" & "Account Unit" options;
  - Rule Edit View: Add "Unit" field for rule outcome section;  
  - BUGFIX: Editing record amount to delete last number twice might lead crash.  
  
---

__v3.9.1 @ 2018-07-12__
  
  - Tags Management View: Make new tag to use the selected filter account by default;
  - Provide "Include Origianl Value" option in report export setting view if general & report numbers' exchange rate is not "1:1";
  - Adjust font size for PDF report.

__v3.9.0 @ 2018-07-09__
  
  - Introduce more unit types (Time, Weight, Distance, etc) as well as Currency;
  - Allow to set different units for general number & report number, w/ exchange rate provided;
  - Update report titles & fix incorrect "Name" title in Chinese version;
  - Separate number format related columns from "Account" report to a new "Number Format Settings" report.
  
---

__v3.8.2 @ 2018-06-26__
  
  - BUGFIX: Rule Widget doesn't update after deleting Manual Rule in edit view or by swiping to left on cell.

__v3.8.1 @ 2018-06-23__
  
  - Update account number format related tip;
  - Replace account's old help view w/ the new tips view;
  - Do not let tip video interrupt background music;
  - Improve loading interaction for tips view.

__v3.8.0 @ 2018-06-22__
  
  - BUGFIX: Account specific currency format example mismatched in Account Edit View;
  - Introduce rounding setting options in "Currency Format";
  - Apply rounding to record amount field when press confirm button;
  - Record edit view: Adjust font size if the number is long;
  - Rename "Currency Format" to "Number Format";
  - Some other UI fine-tunes.
  
---

__v3.7.9 @ 2018-06-13__
  
  - Provide options to handle related Rules in Account Deletion step.

__v3.7.8 @ 2018-06-12__
  
  - Add "Version History" row under "Settings - About" section.

__v3.7.7 @ 2018-06-08__  

  - Add "Contribution" row under "Settings - About" section.  

__v3.7.2 @ 2018-05-30__  

  - Highlight part description for tips view;  
  - Provide App Preview demo video.

__v3.7.1 @ 2018-05-28__  

  - Show a button at records timeline's right-bottom if new tips available;  
  - Provide all tips in "Settings - Help & Feedback - Tips" view.

---

__v3.6.16 @ 2018-04-26__  

  - BUGFIX: Crash at Photo Picker setup step in devices w/ iOS 9.

__v3.6.15 @ 2018-04-24__  

  - Update photo picker.

__v3.6.14 @ 2018-04-23__  

  - BUGFIX: Cannot save tag's new name if just edit the name field.  

__v3.6.13 @ 2018-04-11__  

  - Support account switching in record edit view.  

__v3.6.12 @ 2018-04-02__  

  - Move record filter option from menu to records timeline's left-top corner.  

__v3.6.11 @ 2018-03-26__  

  - Smoother tag report switching;  
  - Fine-tune some UI elements.  

__v3.6.10 @ 2018-03-21__  

  - Provide way to extend tag report view;  
  - Provide date range detail for report date selection button.  

__v3.6.9 @ 2018-03-10__  

  - Tag Report Improvement: Provide related records detail.  

__v3.6.8 @ 2018-03-06__

  - Do not show deactivated rule in Lock View & Rule Widget.  

__v3.6.7 @ 2018-02-20__

  - Some bug fixes for record pagination logic.  

__v3.6.6 @ 2018-02-11__

  - Support account sorting.

__v3.6.5 @ 2018-02-07__
  
  - Optimize records timeline w/ paging supported;  
  - Handle spotlight searching action w/ view locked case;  
  - Fine tune help view.  

__v3.6.3 @ 2018-01-31__

  - When add new record from manual rule, use amount editing by default if its outcome amount is ZERO;  
  - Use 'YeNom - Summary' widget as 3D Touch home screen widget.  

__v3.6.2 @ 2018-01-24__

  - Fix monthly & yearly rule’s day on setting logic;  
  - Update description for rule outcome related fields.  

__v3.6.1 @ 2018-01-23__

  - Introduce new feature: Rule & Automation.  

---

__v3.5.6 @ 2017-11-15__

  - Optimize Summary Widget's data updating logic.  

__v3.5.5 @ 2017-11-11__

  - When app is locked, do not allow to go to settings view directly from Widget’s "Go" button;  
  - Provide more options to send exported reports.

__v3.5.2 @ 2017-11-02__

  - Fine-tune layout for iPhone X;
  - Support Unlock w/ Face ID if available.

__v3.5.1 @ 2017-10-11__

  - BUGFIX: Unable to add new record from lock view when it’s auto-locked from settings view.

__v3.5.0 @ 2017-10-10__

  - Introduce "Auto-Lock" feature (Settings - Privacy - Auto-Lock), you can:  
  - Unlock lock view w/ passcode or Touch ID if needed;  
  - Add new record from lock view if needed.    

---

__v3.4.1 @ 2017-09-22__

  - Introduce "Summary Widget" extension.     

---

__v3.3.2 @ 2017-09-14__

  - BUGFIX: Settings - Feedback - "Custom User Info" view's name fields cannot be saved.

__v3.3.1 @ 2017-08-29__

  - Add "Balance" column for exported Account Report;  
  - Remove category management in original record’s tag selection view.  

__v3.3.0 @ 2017-08-23__

  - New independent tag management view (provided in main menu, between Account & Report);  
  - Sort accounts by name;  
  - Bugfix for Sync: Create tag w/ same name but different record type will lead merging error.  

---

__v3.2.4 @ 2017-07-15__

  - Support custom date range selection for report view & data export view;  
  - Update report view's records count info when filter records by type;
  - Some UI fine-tunes.  

__v3.2.3 @ 2017-07-05__

  - Fix issue: Cannot select last three accounts that beyond device screen height.

__v3.2.1 @ 2017-06-29__

  - Optimize record date picker;
  - Make "Package & Compress" as an optional way to mail exported reports.

__v3.2.0 @ 2017-06-27__

  - Support specific currency setting for different accounts;
  - Support custom encoding format for exporting report;
  - Support tag name & amount sorting in tags report (by tapping on section title);
  - Remove original tags filter view, and support it in tags report;
  - Reflect records w/o any tag in reports;
  - Optimise report date range selection component;
  - Optimise report charts' preview indicator;
  - Fix crash in save step whenever new account or tag name contains single quote;
  - Some other bug fixes;
  - Update lowest support version to iOS 9.

---

__v3.1.10 @ 2017-04-25__

  - Fix issue: Third party keyboard conflicts w/ default record number keyboard;  
  - Update help view for record number keyboard;  
  - Support zero amount record.

__v3.1.9 @ 2017-04-13__

  - Fix issue: Cannot create non-English tag;  
  - Fix some typos.

__v3.1.7 @ 2017-03-10__

  - Fine-tune record edit view;  
  - Add more logs for "Data Sync Debug Mode".  

__v3.1.6 @ 2017-03-08__

  - Support currency format setting (Settings - General - Currency Format);  
  - Optimise iCloud Sync;  
  - Optimise layout for different devices.  

__v3.1.4 @ 2017-02-20__

  - Introduce "Data Sync Debug Mode" (Settings - Data Sync - Synchronization);  
  - Use compressed ZIP file as attachment for mailing report;
  - Support exporting multiple reports at same time;
  - UI fine-tuned.

__v3.1.2 @ 2017-01-25__

  - Support multiple accounts;
  - Support grouping tags into category;
  - Support tag chain;
  - Improve report;
  - Support exporting report as CSV;
  - Improve record photo related func;
  - Improve record date picker;
  - Support record & tag searching;
  - Introduce new iCloud Sync func;
  - Support 3D touch to add record from home screen;
  - Improve UI & performance;
  - etc.

---

__v3.0.0 @ 2014-01-09__

  - Fix bugs on iOS7;
  - Unlock "Full Features".

---
---

__v2.4.2 @ 2013-02-25__

  - Fix bug: Remove date picker when cancel from date setting state;
  - Enable to export records date as a PDF file (included in "Full Features" package).

---

__v2.3.1 @ 2013-02-14__

  - Modify style for record setting view;
  - Add custom date picker (include in "Full Feature" package).

---

__v2.2.5 @ 2013-01-24__

  - Re-enable to view the income/expenses count for the selected month/day.

__v2.2.4 @ 2013-01-10__

  - Update UI;
  - Modify statistics view;
  - Fix bug for UI blocking after added a new record (iOS 6);
  - Fix bug for background freshing between empty data & none-empty data situation.

---

__v2.1.5 @ 2012-12-21__

  - Fix title for keyboard help view;
  - Enable item modification (included in "Full Features" package);
  - Generate record without inserting into database before confirm the settings;
  - Fix a crash bug after inserted a new record for a new month;
  - Change method for deleting item: Select the item, swipe to right or left to confirm delete.

---

__v2.0.1 @ 2012-12-05__

  - Reconstruct code of basic functions and optimize performance;
  - Fix bug for item's value color changing in settings table view;
  - Part style & feature modification.

---
---

__v1.9.5 @ 2012-11-21__

  - Enable date modification (included in "Full Features" package);
  - Asynchronously load image after taking the photo;
  - Fix localization in action sheet for deleting the photo;
  - Modify the size of default photo;
  - Modify photo preview style (full screen, enable scrolling & zooming, etc).

---

__v1.8.3 @ 2012-10-23__

  - Fix layout for iPhone 5's 4" screen;
  - Fix a bug on iOS6: UITextFieldTextDidChangeNotification will not be sent when textfield was changed programmatically.

---

__v1.7.11 @ 2012-09-19__

  - Change system keyboard to customize keyboard for number pad;
  - Add basic calculation function for number pad;
  - Change icon;
  - Optimize performance;
  - Reset selected cell index after remove the tag item;
  - Offer an action sheet to user for confirming to delete the tag;
  - Modify options (Fast, Normal, Slow) for delay time setting;
  - Fix navigation bar back button's state: back to previous view from donate view when loading timeout;
  - Enable purchase for 'Full Features';
  - Fix record tag's frame width;
  - Modify default keyboard style for tag adding;
  - Allow to enter 'Free Code' to turn 'Full Features' on;
  - Change navigation bar style for mail view.

---

__v1.6.8 @ 2012-08-23__

  - Modify statistics view: support month & day statistics;
  - Support year setting in statistics view;
  - Optimize performance;
  - Rename "Delay Time for Swipe Gesture" to "Delay TIme" in settings view;
  - Allow user to delete all records for one month;
  - Fix bug: Delete the data at 00:00 of next month incorrectly while deleting one month's data;
  - Fix bug for statistics: Double count for 00:00 and 24:00;
  - Fix bug: Selecting a row in one section leads the same row of another section to expand either.

---

__v1.5.4 @ 2012-08-23__

  - Enable to delete a single record;
  - Add iCloud;
  - Allow user to toggle iCloud service.

---

__v1.4.3 @ 2012-08-09__

  - Add In-App Purchase for donation;
  - Part UI modified;
  - Remove `+` / `-` button in the root view, use drag-and-hold gesture only;
  - Fix a bug: Adding the first record leads the font size to be wrong;
  - Add some help views for gestures.

---

__v1.2.4 @ 2012-07-26__

  - The first released version on App Store.


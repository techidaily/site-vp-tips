---
title: Tracking Your Printer Activity on Windows 11 - A Step-by-Step Guide
date: 2024-08-26 20:11:13
updated: 2024-08-29 12:46:59
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/a-desk-with-a-laptop-and-a-printer.jpg
---

## Tracking Your Printer Activity on Windows 11 - A Step-by-Step Guide

### Quick Links

* [Enable Printer History Logging for Recently Printed Documents on Windows 10](https://fox-blue.techidaily.com/witty-visuals-crafting-kapwings-laughs/)
* [Enable Printer History Logging for Recently Printed Documents on Windows 11](https://some-guidance.techidaily.com/2024-approved-uncover-5-powerful-speech-recognition-tools-for-your-mac/)
* [Enable Long-Term Print History in Event Viewer.](https://data-wizards.techidaily.com/celestial-cinema-outstanding-videos-plus-testimonies/)
* [View Print History in Event Viewer](https://video-capture.techidaily.com/2024-approved-top-picks-9-innovative-mobile-video-conferencing-tools-iphoneandroid/)
* [Use Third-Party Print Logging Software](https://extra-hints.techidaily.com/discover-the-ultimate-free-subtitles-convertors/)

 Checking the history of a printer to see what was printed can be somewhat difficult to monitor. As your toner level doesn't convey how much the accessory has been used, you'll need to enable logging within Windows 10 or Windows 11\. Here are a few ways to do that.

## 

##  Enable Printer History Logging for Recently Printed Documents on Windows 10

 By default, your printed document history will be wiped after each document has finished printing. You can change this setting to enable you to see a list of your recently printed documents from the print queue for your printer. You'll need to change this setting for each printer you have installed.

###  Access Your Print Queue to Enable Logging

 To access your print queue, right-click the Windows Start menu button and select the "Settings" option. From here, click Devices > Printers & Scanners.

![Access your Windows printer settings by right-clicking your Start Menu button, clicking Settings, then Devices &gt; Printers &amp; Scanners](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/Windows-Printer-Settings-Menu.png) 

 Find your printer in the "Printers & Scanners" list, click on it, and then click "Open Queue" to open the print queue.

![Click on your printer and click Open Queue to open the printer queue](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/Windows-Printer-Settings-Queue-Button.png) 

 Your printer queue with current and queued printed items will be listed. Documents you've previously printed will not be shown, which is why you'll need to enable logging.

 In the print queue window for your printer, click Printer > Properties. Alternatively, select your printer and click "Manage" in the "Printers & Scanners" settings menu.

![Click Printer > Properties in the print queue for your printer](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/Print-Queue-Properties-Button.png) 

 In your printer properties, click on the "Advanced" tab and then select the "Keep Printed Documents" checkbox.

 Click "OK" to save your settings.

![Click the advanced tab in your printer settings and enable the keep printed documents checkbox](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/Windows-Printer-Enable-History.png) 

 Once your document history is enabled, your documents will no longer disappear from your print queue after the printing process has completed.

##  Enable Printer History Logging for Recently Printed Documents on Windows 11

 Windows 11 doesn't enable a print history by default, much like its predecessor. To enable a short-term print history, press Windows+i or otherwise open the Settings app, then navigate to Bluetooth & Devices > Printers & Scanners, then select your printer. 

Close 

 Scroll down and then click "Printer Properties." 

![Click or tap 'Printer Properties.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/3-printer-preferences.png) 

 Select the "Advanced" tab, tick the box next to "Keep Printed Documents," then click "Apply." You can then close all the windows.

![The 'Advanced' tab in Printer Properties.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/4-5.png) 

 Whenever you want to review your print history, all you need to do is open to Settings > Bluetooth & Devices > Printers & Scanners, select your Printer, then click "Open Print Queue." 

##  Enable Long-Term Print History in Event Viewer.

 The print queue will provide a short-term overview of your previously printed documents. If you want to view a long-term list, you'll need to use the Windows Event Viewer.

 To start, right-click your Windows Start menu button and click the "Event Viewer" option.

![Open the Event Viewer through the Power User Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/09/open-event-viewer.png) 

 The Event Viewer will allow you to view a list of previously printed files, but you'll need to set Windows to begin logging your long-term printer history first. In the Windows Event Viewer, click Applications and Services Logs > Microsoft > Windows in the "Event Viewer (Local)" menu on the left.

![In Event Viewer, click Applications and Services Logs &gt; Microsoft &gt; Windows.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/print-services-event-viewer-1.png) 

 This will reveal a significant number of Windows services. Scroll down to find the "PrintService" category.

 From here, right-click the "Operational" log and then click the "Properties" button.

![properties](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/properties.png) 

 Click to enable the "Enable Logging" checkbox and then set a maximum size for the log. The larger the size, the longer Windows will record your printed document history.

 Click the "Apply" button to save the setting.

![Tick the box next to 'Enable Logging,' set the log size you want, then click 'Apply.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/enable-logging.png) 

 Windows will now automatically save the printer history for all of your installed printers to a log file that you can access within Event Viewer.

##  View Print History in Event Viewer

 Once your printer history is enabled, you can access it at any time from the Event Viewer. To do so, find and open the "PrintService" category and then click on the "Operational" log.

![In Event Viewer, click 'PrintService', then click Operational](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/operational.png) 

 A history of all Windows printer events will be listed, from initial printer spooling to completed or failed prints.

 Under the "Task Category" section, items listed as "Printing a Document" are documents that have been successfully printed. Failed prints will also appear in this category.

![The PrintService Operational log will list your printed document history](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/Windows-Event-Viewer-Printed-History.png) 

 To make it easier to sort, you can group your print log by categories, making it easy to separate the "Printing a Document" events into their own section. To do so, right-click the "Task Category" heading and then click the "Group Events by This Column" button.

![In the Event Viewer logs list, right-click Task Category, then click Group Events by This Category](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/Windows-Event-Viewer-Group-List-by-Categories.png) 

 Your items will now be separated by category.

 You can minimize the other categories, leaving the "Printing a Document" category to display only a list of your previously printed documents.

![A list of printed documents in the Event Viewer, separated by categories](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/Windows-Event-Viewer-Categories-List.png) 

##  Use Third-Party Print Logging Software

 While the Event Viewer is functional, it doesn't provide the clearest view of your printed documents. You can use third-party print logging software like [PaperCut Print Logger](https://www.papercut.com/products/free-software/print-logger/) to view your long-term printer history instead.

 PaperCut Print Logger provides you with a time-stamped list of your printed documents, including information on the Windows user who printed the document, the document name, and the number of pages and copies.

![An example of a print log within the PaperCut Print Logger admin page](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/PaperCut-Admin-Log.png) 

 The admin page can be accessed from the default PaperCut Print Logger directory.

 On Windows 10, this is usually `C:\Program Files (x86)\PaperCut Print Logger` . Double-click the "ViewLogs" shortcut to open the admin panel, where a list of your printed documents will be available, separated by date.

![In the PaperCut installation directory, double-click the ViewLogs shortcut](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/PaperCut-Directory.png) 

 Once you've opened the PaperCut Print Logger admin page, under the "View" category, click the "HTML" button to access your print history for that date within the panel.

 You can also click the "CSV/Excel" button under the "Date (Day)" or "Date (Month)" categories to export your daily or monthly print history as a Microsoft Excel XLS file.

![An example of the PaperCut admin page](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/10/PaperCut-Admin-Page.png) 

 You can also access these logs from the Logs > CSV folder inside your PaperCut Print Logger installation directory.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

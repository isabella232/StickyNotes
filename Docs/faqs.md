---
title: Sticky Note FAQ
description: Answers to frequently asked questions about Microsoft Sticky Notes. 
author: Reza1024
ms.author: rejooyan
ms.date: 10/08/2018
ms.topic: conceptual
ms.prod: windows
ms.technology: stickynotes
keywords: FAQs
---

# Sticky Note FAQs

# Sticky Notes FAQ

# **Frequently Asked Questions**

**Q: How do I launch the Sticky Notes app?**

A: You can access Sticky Notes from your All Apps list, or by opening Windows Ink Workspace from its task bar icon. If you don’t see the Windows Ink Workspace icon on your task bar, right click the task bar, and then select **Show Windows Ink Workspace**.

If your machine has a pen digitizer, you can also get to Windows Ink Workspace from the lock screen, if you have that option turned on in Settings. To turn on, go to Settings > Devices > Pen & Windows Ink > Turn on “Click once to open my Windows Ink Workspace notes even when the device is locked”. This version of Sticky Notes has a palm rejection background so you don’t accidentally change the focus from the sticky notes to a background open app when you are resting your hand on your screen during the inking experience.

**Q: How do I upgrade my notes from the previous app?**

A: The new app automatically migrates your existing notes.

**Q: How do I save my notes?**

A: The new app automatically saves your notes as you edit them.

**Q: How can I use Sticky Notes on my mobile device?**

A: You can view your Sticky Notes in OneNote on both Android and iOS.  Just install the OneNote app from the app store, sign in with the same account, and click on the Sticky Notes tab in OneNote.

**Q: Can I get to my Sticky Notes on the web?**

A: Yes!  You can get to your Sticky Notes from any supported web browser by navigating to [https://www.onenote.com/stickynotes](https://www.onenote.com/stickynotes).  As long as you're signed in with the same account you're using for Sticky Notes on other devices, you'll be able to view, edit, and create notes there as well.

**Q: Are my Sticky Notes and my Outlook Notes related?**

A: Sticky Notes and notes in the Outlook Notes module are stored in the same place.  You can view your Sticky Notes in Outlook Desktop and vice-versa. 

**Q: Where can I share feedback on Sticky Notes?**

A: We'd love to hear your feedback.  You can let us know more about your experience by using the following tools:

- For the Windows Sticky Notes App, you can file feedback using the Windows Feedback Hub app or by leaving a review in the Windows Store.
- For the Sticky Notes experience within OneNote on mobile or the web, you can leave feedback and make requests via the OneNote Uservoice site.

# **Troubleshooting and Common Issues**

**Issue: My notes aren't syncing.**

1. Make sure you are signed in with the same account in Sticky Notes. You can check this from the Settings page of Sticky Notes. Click on the gear icon in the Notes List page of Sticky Notes.
2. On the Settings page, select the "Sync now" button. This will attempt a full sync of all your notes.
3. Ensure you have internet access.
4. Sign-out, and then sign back in.

**Issue: I can't sign in.**

1. Ensure you have internet access.
2. Try again in a few minutes

**Issue: I closed the list of notes, and I can't find it.**

The notes list can be opened by selecting the "..." button in any Sticky Note window, then selecting the "All notes" button. Alternatively, you can right-click the Sticky Notes app in the task bar and select "All notes".

**Q: Why can’t I see my notes after upgrading to the anniversary update?**

**A:** If you don’t see your notes right after the upgrade, try opening the Sticky Notes app again, from the All Apps list in the Start menu. They should be there.

Notes:

- The new app supports 45 Sticky Notes rather than 50. If you had more than 45 notes before the upgrade, please delete some of your existing notes, open the Sticky Notes app again, and your older notes should be there.
- The new app doesn’t support pictures. If you had pictures in your old notes, they will be saved to your hard drive.

**Q: What insights are currently supported and how do I enable them in Sticky notes?**

**A:** Here are some tips for creating insights:

- Type a phone number with dashes to make a call with Skype.
- Flights are best recognized with both the airline code and the flight number, such as BR26
- Stocks are recognized only when the ticker symbol is preceded with a dollar sign, such as $MSFT.
- Cortana reminders can be created when times are recognized, like 6pm, today, tomorrow, Saturday, next week, July, etc. Once a time is recognized, click **Add Reminder**.
- Start a list of items with bullets, dashes, or numbers to have it formatted as a list, which you can then modify, move around, and change the order of list items.
- Type an email address to see the option for sending email.
- Type a web address (URL) to see the option to open it in a browser.
- Type in a full (physical) address to see it on a map.

**Q: Why are my notes so large?**

**A:** This has been fixed by an update to the app. Go to the Store and make sure you have the most up-to-date version of the app.

**Q: I want to leave my sticky notes open on my desktop as a constant reminder. How do I do that?**

**A:** Open the Sticky Notes Trusted Windows Store app version of the product, or open it from Ink Workspace. Sticky Notes will remain running no matter how you launch them, from Start or Ink Workspace.

**Q: Why are insights not working? How do I turn on insights?**

**A:** Insights are only available in the English (United States) Windows keyboard display language at this time, with more languages coming soon. This is found in Settings > Time & Language > Region & language > Languages > English (United States) Windows display language.

If you have multiple display languages installed, you need to be using the English (United States) as your keyboard when you are using the Sticky Notes app. The task bar would look like this with English:

If you are using the English (United States) Windows Display language and still don’t see insights, open the Sticky Notes app > click “…” for more > click the settings icon > toggle Enable Insights to ON. (If you don’t see the insights setting, you are using another language that it’s not supported on yet.)

**Q: I open the Sticky Note app (either Store app or through Windows Ink) and the app crashes or there is no starting sticky note available. What can I do to get Sticky notes to work?**

**A:** There are a few things you can try if Sticky Notes is not working for you.

1. Try opening the app again.
2. Make sure you are running the latest version of the app – go to the store and select your account icon in the upper-right > Downloads and updates > Check for updates. If any updates are found, select **Update all**.
3. Try restarting the device.
4. Save your notes and data, then reinstall Sticky Notes.
- From **Start**, select **File Explorer**. Copy the following text and paste it into the File Explorer address bar, then press Enter: 

```%LOCALAPPDATA%\Packages\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe\LocalState\plum.sqlite```
- Right-click on the file and select **Copy**. Go to your desktop, and **Paste** the file there.
- From **Start**, search for **powershell**. Right-click on **Windows Powershell** in the search results, and choose **Run as administrator** from the menu that comes up.
- Copy the following text: 

```Get-AppxPackage "*stickynotes*" | Remove-AppxPackage ; Get-AppxProvisionedPackage -Online | ? { $_.DisplayName -like "*stickynotes*" } | Remove-AppxProvisionedPackage -Online```
- In the Powershell window, **Paste** that text, and then hit Enter.
- Reinstall the app from the Store. You can use this direct link: ms-windows-store://pdp/?productid=9nblggh4qghw
- Copy the following text, and then Paste it into the address bar of File Explorer:

```%LOCALAPPDATA%\Packages\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe\LocalState```
- Find the file you pasted to your desktop earlier. Right-click on it, and choose Copy. Go back to the File Explorer window, and Paste the file in.
- Launch the app from Start and verify that your notes are available.
5. If none of these work, please post in [the Windows 10 - Windows Ink Community.](https://na01.safelinks.protection.outlook.com/?url=http%3A%2F%2Fanswers.microsoft.com%2Fen-us%2Fwindows%2Fforum%2Fwindows_10-touch%3Fsort%3Dlastreplydate%26dir%3Ddesc%26tab%3Dthreads%26status%3Dall%26mod%3D%26modAge%3D%26advFil%3D%26postedAfter%3D%26postedBefore%3D%26threadType%3Dall%26tm%3D1472587462592&data=04%7C01%7C%7C75bfb73d01bc4453afd708d623276b5c%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636735049550153971%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwifQ%3D%3D%7C-1&sdata=gO6oPaZYWBldopJNrNvZ9yg5IaR44x6HDKVV%2BMdYZ94%3D&reserved=0)

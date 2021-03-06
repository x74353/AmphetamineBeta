# Amphetamine Beta
This is the distribution channel for beta versions of the macOS app Amphetamine.

[Amphetamine](https://apps.apple.com/app/amphetamine/id937984704?mt=12) is a macOS app that is distributed through the Mac App Store. Apple does not provide a [TestFlight service](https://developer.apple.com/testflight/) for macOS like they do for iOS, however, and thus I distribute beta versions of Amphetamine through this Github page.

<hr><b>
Amphetamine 5 was released on the Mac App Store on 02/20/2020. Amphetamine 5 is a rebranding of version 4.3. Get the update here: https://apps.apple.com/app/amphetamine/id937984704?mt=12 
</b><hr>

<b>Last Available Beta:</b><BR>
Amphetamine 4.3 b4 <BR>
Expires on: March 11th, 2020<BR>

<b>[Click here to download](https://github.com/x74353/AmphetamineBeta/raw/master/Betas/Current/Amphetamine_4%2C3_b4.dmg)</b>

<b>Beta 3 → Beta 4 changelog:</b><BR>
• Fixed an issue that caused Triggers preference pane/view to not load<BR>
• Fixed an issue that caused Battery & Power Adapter Trigger criterion view to not load<BR>
• Visual updates to reflect merging of Power & Sessions preference panes<BR>
• Some small additional bug fixes that are hard to describe in a few words<BR>

<b>Beta 2 → Beta 3 changelog:</b><BR>
• DNS Trigger criterion now allows adding/removing of individual DNS server addresses<BR>
• Fixed an issue that caused Trigger started notifications to not include Trigger name<BR>
• Preferences → Power has been merged into Preferences → Sessions → Non-Trigger sessions<BR>
• Preferences → Sessions pane has been split into Non-Trigger and All Session categories to better illustrate how these preferences work/are applied<BR>

<b>Beta 1 → Beta 2 changelog:</b><BR>
• Fixed an issue that could cause IPv6 address range matching to evaluate true unexpectedly<BR>
• Fixed an issue where only one IP address per interface being found<BR>
• Added "no power adapter" conditions to Power (power adapter/battery) Trigger<BR>
• Added and/or operator to Power (power adapter/battery) Trigger<BR>
• Replaced most instances of "AC power adapter" with "power adapter" (still have a few to update)<BR>
• Updated some help + contextual messages/wording<BR>

<BR>

<b>Pre-Release Release Notes:</b><BR>
  
<b>New Features & Improvements:</b><BR>
• Keep your MacBook awake while its lid is closed <BR>
• Lock your Mac's screen after a period of inactivity (macOS 10.14+)<BR>
• Support for Amphetamine Enhancer (get it at https://github.com/x74353)<BR>
• Redesigned Quick Preferences<BR>
• Redesigned Current Session Details menu section<BR>
• Dock icon now hides and shows automatically when Amphetamine's windows open/close (macOS 10.14+)<BR>
• Improvements to how Amphetamine determines when to the start screen saver<BR>
• Search has been added to app pickers<BR>
• Screen saver no longer runs if screen is already locked<BR>
• Support for IPv6 addresses in Triggers<BR>
• Added ability to manually control padding for menu bar image<BR>
• Added new + updated some existing AppleScript commands<BR>
• Added "no power adapter" conditions to Power (power adapter/battery) Trigger<BR>
• Added and/or operator to Power (power adapter/battery) Trigger<BR>
<BR>
  <b>Bug Fixes:</b><BR>
• Fixed an issue where menu would not display when 2 or more displays were arranged vertically<BR>
• Fixed an issue that caused the Other Time/Until clock to show an unexpected time<BR>
• Fixed an issue that caused the CPU utilization to be monitored unexpectedly<BR>
• Fixed an issue that caused Quick Preferences to continue to use color to represent status unexpectedly<BR>
• Fixed an issue that could cause Screen Saver Exceptions to be removed unexpectedly<BR>
• Fixed an issue that could cause the wrong Screen Saver Exceptions to be used during a session<BR>
• Various other bug fixes that I forgot to write down
<BR>  
  <b>Other changes:</b><BR>
• Triggers are no longer allowed to have the same name<BR>
• Quick Preferences no longer uses color to represent status due to redesign

# FAQs:<BR>
<!--- 
<b>Why is there no beta versions of Amphetamine available?</b><BR>
Historically, most Amphetamine releases have not not available for beta testing. I do not anticipate making every update to Amphetamine available to the public for beta testing. Only releases with substantial changes will typically be available on Github and, generally speaking, will only be available for a short period of time.
--->  
<b>Do betas of Amphetamine Expire? Why?</b><BR>
Yes, they do. Typically, the expiration occurs about a month after the beta version is created. I don't want this Github page to become an alternative to the Mac App Store where people are requesting that I provide new beta versions. Amphetamine's distribution channel is the Mac App Store and I do not want to change that at this time.

<b>Is it safe to download a beta version of Amphetamine?</b><BR>
Beta versions of Amphetamine are code-signed and are notarized by Apple. If you feel uncomfortable with downloading software from outside of the App Store, that's ok. Nobody is forcing you to do it. Just wait for the official release in the App Store.

<b>Are beta versions of Amphetamine stable?</b><BR>
Generally, yes, they should be. I have already done a lot of the beta testing myself. I can't find every bug, though. That's why I need your help.

<b>How can I help test beta versions of Amphetamine?</b><BR>
A big help would be for you to just simply test all of the things you normally use Amphetamine for. If you want to go above and beyond, I could really use help testing older versions of macOS (10.11 → 10.14), and testing a variety of different Macs (iMac, Mac mini, Mac Pro, MacBook(s) +/- Pros/Airs, etc.). You can use the pre-release release notes at the top of this page for general guidance on new features that could use testing. Making sure the "old" features still work is important too, though.

<b>How to I report issues/bugs I experience when using  beta version of Amphetamine?</b><BR>
I would prefer you submit a ticket/bug report on [Amphetamine's support site](https://iffy.freshdesk.com).

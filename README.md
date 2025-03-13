# Table of Contents

1. [Purpose](#-purpose)
2. [TL;DR](#-tldr)
3. [Reduce Publicly Available Data](#-reduce-publicly-available-data)
   1. [Social Media](#-social-media)
   2. [Public Records](#-public-records)
   3. [Data Sharing](#-data-sharing)
   4. [Unused Accounts](#-unused-accounts)
   5. [Data Brokers](#-data-brokers)
4. [Web Browsing](#-web-browsing)
   1. [Browsers](#-browsers)
   2. [Search Engines](#-search-engines)
   3. [Extensions & Add-ons](#-extensions--add-ons)
   4. [Website Cookies](#-website-cookies)
   5. [VPNs](#-vpns)
   6. [Passwords](#-passwords)
   7. [Password Managers](#-password-managers)
   8. [MFA/2FA](#-mfa--2fa)
5. [Artificial Intelligence (AI)](#-artificial-intelligence-ai)
6. [Phones](#-phones)
   1. [Phone Number Masking](#-phone-number-masking)
   2. [iPhone Settings](#-iphone-settings)
   3. [Android Settings](#-android-settings)
   4. [Useful Apps](#-useful-apps)
   5. [Apps to Avoid](#-apps-to-avoid)
7. [Computers](#-computers)
   1. [MacOS Settings](#-macos-settings)
   2. [Windows Settings](#-windows-settings)
   3. [Cloud Storage](#-cloud-storage)
8. [Email](#-email)

| Symbol | Heading level |
| ----------- | ----------- |
| 🔶 | heading 1 |
| 🔸 | heading 2 | 
| 🔹 | heading 3 | 

# 🔶 Purpose
Corporations, through surveillance capitalism, harvest your personal information for profit. That data is often gathered without your explicit informed consent through complex terms & conditions, features such as personalized recommendations, and more. These tactics ensure you don’t understand the breadth of data being collected, how it’s being used, or who gets access to it.

As we’ve seen, data collected by corporations often ends up in data breaches; [AT&T](https://www.cnet.com/tech/mobile/at-t-data-breach-what-is-at-t-doing-for-the-73-million-accounts-breached/), [Change Healthcare](https://techcrunch.com/2024/02/21/change-healthcare-cyberattack/), and [Ticketmaster](https://www.pcmag.com/news/ticketmaster-confirms-user-email-addresses-phone-numbers-stolen-in-hack) to name a few. Why should we trust them to dutifully care for our information, when there aren’t consequences when they lose it?

You deserve to control access to your personal information - who gets it, when it’s given, how it’s used, and for how long. This guide will help you get started. If you want a more thorough guide, check out [The Hitchhiker’s Guide to Online Anonymity](https://anonymousplanet.org/guide.html).

***Disclaimer: I’m not an expert on every topic here - there are gaps in my knowledge. It’s up to you to understand the tools you use.***

# 🔶 TL;DR
There is a lot of information in this guide, so below is a succinct list of recommendations. I think the following will have the largest impact on improving your privacy and security:

- Privacy-focused browser
  - **user-friendly:** Firefox with DuckDuckGo & uBlock Origin
  - **best for privacy:** Tor with DuckDuckGo
    - VPNs and extensions are not recommended with Tor
- “No user logs” VPN
  - **user-friendly:** NordVPN or Proton
  - **best for privacy:** Mullvad
- Password manager
  - **user-friendly:** NordPass or 1Password
  - **offers free tier:** Bitwarden
- Enable MFA / 2FA on everything
- Social media
  - **best:** delete them
  - **good:** remove personal information & make accounts private
- Remove your personal information from data broker databases
- Opt out of third party cookies, AI training, website tracking, and data & location services
- Use applications/software that have end to end encryption (E2EE)

# 🔶 Reduce Publicly Available Data
Try Googling yourself and look at the results. What did you find?

Publicly available information about you can be used:

- in targeted ads
- to [dox you](https://en.wikipedia.org/wiki/Doxing#:~:text=Doxing%20or%20doxxing%20is%20the,Internet%20and%20without%20their%20consent.)
- to stalk or harass you
- against you politically or socially
  - your sexual orientation, political affiliation, or gender identity

## 🔸 Social Media
Here are some suggestions you can apply to all of your social media accounts:

- remove personal details such as your employer, full name, relatives, gender identity, significant others, sexual orientation, etc
- avoid sharing detailed personal information in social media comments
- opt out of data sharing
- block access to your location
- block access to your address book
- disable cross-website tracking
- disable third party cookies
- make your profiles private

## 🔸 Public Records
Depending on your location and situation, you may request your public records be hidden from public-facing websites run by local, county, and state-wide entities.

## 🔸 Data sharing
Outside of social media, most websites you have an account with have privacy settings. For sites that allow it, opt out of third-party data sharing.

## 🔸 Unused accounts
If you have accounts on websites that you’re no longer active on, deactivate or delete them. Before deletion, you may need to request your information be removed from their database. Deleting unused accounts will shrink your digital footprint.

## 🔸 Data brokers
Data brokers collect information about you to sell. People finder sites are a type of [data broker](https://consumer.ftc.gov/articles/what-know-about-people-search-sites-sell-your-information). You can manually request your information be deleted or pay for a removal service to contact them on your behalf. US government agencies [buy your location data](https://www.theverge.com/2024/12/3/24312313/ftc-bans-sensitive-location-data-brokers-gravy-analytics-venntel-mobilewalla) from brokers.

Most, if not all, people finder sites include a “known associates” section of your user profile, meaning the personal details of close friends, significant others, housemates, and others can easily be linked to you.

Start here:

- [modify your Google Activity settings](https://myactivity.google.com/myactivity)
- [Google Account](https://myaccount.google.com)
  - turn off YouTube history
  - turn off personalization
  - turn off location tracking
- [opt out of prescreen offers](https://www.optoutprescreen.com/)

### 🔸 Manual data removal
**Pros:** 
- free
- most effective
- you control the information you share with the data brokers

**Cons:** 
- time-consuming
- requires regular follow up
- not 100% effective

These resources will help:

- [IntelTechniques Data Removal Guide](https://inteltechniques.com/workbook.html)
- [Big Ass Data Broker Opt Out LIst Github](https://github.com/yaelwrites/Big-Ass-Data-Broker-Opt-Out-List)
- [Privacy Guides | Data Removal Services](https://www.privacyguides.org/en/data-broker-removals/)

### 🔸 Paid data removal

**What to look for:** How many data brokers they contact, reputation, and reporting.

**Pros:** 
- significantly less time-consuming
- most offer regular reporting

**Cons:**
- ongoing subscription
- you will likely have to manually reach out to some data brokers anyway
- service may unintentionally provide data brokers too much of your information

Some popular providers:

- [DeleteMe](https://joindeleteme.com/)
- [Incogni](https://incogni.com/)
- [EasyOptOuts](https://easyoptouts.com/)
- [Kanary](https://www.kanary.com/)
- [Optery](https://www.optery.com/)
  - [concerns around OpenAI use](https://www.reddit.com/r/Optery/comments/1flswcu/disappointed_in_optery_opting_customers_in_to/)

# 🔶 Web Browsing
Your ISP (internet service provider), phone apps, cellular provider, web browser, and websites all see some amount of information about you when you use their services.

## 🔸 Browsers

### 🔹 Chrome
Chrome is not recommended for privacy. Google [harvests vast swaths of data](https://www.wired.com/story/google-chrome-browser-data/), and Chrome will [disable ad blockers](https://www.theverge.com/2024/10/15/24270981/google-chrome-ublock-origin-phaseout-manifest-v3-ad-blocker) with manifest v3.

If you must use Chrome, here are some recommendations:

- use a VPN
- turn off everything related to ads and tracking
- change the default search engine to DuckDuckGo or another of your preference
- turn on secure browsing
- [advanced security settings](https://support.google.com/chrome/answer/10468685?hl=en&co=GENIE.Platform%3DDesktop)
- uBlock Origin Lite extension once uBlock Origin is disabled
- use a password manager
- block / reject third party cookies

### 🔹 Safari
Apple does not allow you to uninstall Safari. If you want to use another browser, you only need to change the default browser in your settings.

If you must use Safari, here are some recommendations:

- use a VPN
- change the default search engine to DuckDuckGo or another of your preference
- turn off everything related to ads and tracking
- block / reject third party cookies
- turn on hide your IP
- uBlock Origin
- use a password manager

Many privacy settings can be found [here](https://support.apple.com/en-mz/guide/safari/sfri35610/mac).

### 🔹 Edge
Much like Apple with Safari, Microsoft does not allow you to uninstall Edge. If you use another browser, I recommend the following:

- [change the browser used in taskbar search](https://www.youtube.com/watch?v=tSIyvUFdoyc)
- disable Edge background services
- disable startup features
- block tracking you while you use other browsers: 

If you use Edge, here are some recommendations:

- turn on tracking prevention
- turn on send “do not track” requests
- turn off optional diagnostic data
- you need to have optional diagnostic data turned off in your Windows settings
- turn off personalization & advertising
- use uBlock Origin
- change the default search engine to DuckDuckGo or another of your preference
- use a VPN
- password manager (instead of saving them in the browser)

More settings and information can be found [here](https://fingerprint.com/blog/edge-privacy-security-guide/).

### 🔹 Tor Browser
Download [here](https://www.torproject.org/download/).

**Pros:**
- best for privacy
- best for anonymity
- doesn’t require a VPN (in fact a VPN is not recommended)
- [mitigates fingerprinting](https://tb-manual.torproject.org/anti-fingerprinting/)

**Cons:**
- add-ons/extensions not recommended, they might break the browser or compromise your privacy
- slower performance

### 🔹 Firefox
Download [here](https://www.mozilla.org/en-US/firefox/).

**Pros:**
- good choice for privacy
- user friendly
- near feature parity with Chrome
- supports many add-ons and extensions

**Cons:**
- smaller selection of extensions than Chrome
- less user friendly than Chrome

### 🔹 Brave
Download [here](https://brave.com/).

**Pros:**
- great for privacy
- blocks ads by default
- [mitigates fingerprinting](https://brave.com/privacy-updates/3-fingerprint-randomization/)

**Cons:**
- crypto settings turned on by default
- small selection of extensions
- websites might break due to its strict privacy and ad blocking features

### 🔹 DuckDuckGo
Download [here](https://start.duckduckgo.com/).

**Pros:**
- user friendly
- good for privacy

**Cons:**
- lack of extension support
- DDG search engine pulls from Bing, which some users dislike

## 🔸 Search engines
Google is one of the worst offenders when it comes to surveillance capitalism.

### 🔹 DuckDuckGo (DDG)
- most popular privacy-focused search engine
- doesn’t link your IP address to your identity
- blocks most third party cookies and trackers by default
- aggregates search results from Bing and DDG’s own indexing

### 🔹 Start Page
Download [here](https://www.startpage.com/en/).

### 🔹 Brave
Download [here](https://search.brave.com/).

### 🔹 Kagi
Download [here](https://kagi.com/).

## 🔸 Extensions & add-ons
Be aware that extensions and add-ons can compromise your security. Thoroughly research extensions before installing.

### 🔹 uBlock Origin
- blocks ads
- advanced mode can block scripts and is customizable
- supports filters that prevent website tracking from sites like Facebook
- uBlock Origin, along with other ad blockers, will be disabled when Chrome manifest v3 is released

### 🔹 uBlock Origin Lite
- only use if uBlock Origin is unavailable

### 🔹 ClearURLs

### 🔹 Password manager

### 🔹 VPN

## 🔸 Website cookies
Think of cookies as identifiers that tie your browsing activity to you. There are browser settings and extensions that will block third party cookies automatically. When a website asks you to accept cookies, choose “reject” or “necessary cookies only.”

## 🔸 VPNs
**What:** A VPN is a virtual private network that can encrypt your internet traffic and masks your IP address.

**Why:** VPNs are useful when using public wifi or when you wish to mask your IP address while browsing the web. [Reasons to mask your IP address](https://usa.kaspersky.com/resource-center/preemptive-safety/how-to-hide-ip).

**What to look for:** Whether the VPN service logs/saves your activity and their reputation.

Select a VPN provider that does not log your activity. Confirm they don’t save user logs by checking if they’ve been independently audited. Here are some providers who have been third party verified (based on this post) and are popular:

- [NordVPN](https://nordvpn.com/)
- [Surfshark](https://surfshark.com/)
- [ExpressVPN](https://www.expressvpn.com/)
- [Proton](https://protonvpn.com/)
- [Mullvad](https://mullvad.net/en)
- [PIA](https://www.privateinternetaccess.com/)

Mullvad accounts are randomly generated without your personal details, and they accept cash payment, meaning your account can’t easily be tied to you. Proton also accepts cash.

**Important:** People have the false impression that a VPN will keep them completely anonymous regardless of their online activity. This is incorrect.

**Consider this:** You post from a fake account on a forum, but you’re on a VPN, so your IP address is masked. However, you then place an online order for pizza delivery while still logged into the VPN. That IP address is now directly tied to your address and forum post.

**Takeaway:** A VPN masks your IP address but can still be linked to you based on your online activity. This is why disabling things like tracking and third party cookies is useful. If anonymity is your goal, check out [The Hitchhiker’s Guide](https://anonymousplanet.org/guide.htmlw).

## 🔸 Passwords
Passwords saved in an encrypted app, extension, or software that requires login credentials and 2FA/MFA are safer than in your browser. Always change default passwords and avoid reusing passwords. CISA's [best practices guide](https://www.cisa.gov/secure-our-world/use-strong-passwords).

### 🔹 Passkeys

If setting up a passkey is an option, choose it over a password. More information [here](https://www.passkeys.com/passkey-vs-password).

## 🔸 Password Managers
**What:** Password managers store login credentials, contact details, secure notes, and more in an encrypted “vault.”

**Why:** They enable you to save a lot of unique passwords that you don’t have to memorize.

**What to look for:** Reputation, features, and recent security breaches.

Apple and Google Passwords are secure if that’s your preference. The downside is if you lose access to your Apple ID or Google account, you’ll lose access to all of your passwords.

Some popular password managers:

- [Bitwarden](https://bitwarden.com/)
- [LastPass](https://www.lastpass.com/)
- [NordPass](https://nordpass.com/)
- [1Password](https://1password.com/)

## 🔸 MFA / 2FA
**What:** Multi-factor (MFA) and 2-factor (2FA) authentication are an extra step to verifying your identity when you log into something.

**Why:** These measures help prevent unauthorized access to your accounts by requiring additional steps to log into an account.

**TL;DR:** Enable MFA and 2FA for everything.

There are four **types** of authentication, and a variety of **methods** to achieve each type.

| Type | Method(s) |
| ----------- | ----------- |
| something you know | password, PIN, security questions |
| something you have | one time password (OTP), authenticator app | 
| something you are | biometrics such as face ID or fingerprint | 
| somewhere you are | geolocation | 

Your username and password fall under the “something you know” authentication **type**.

**2FA** requires you to present one (1) additional authentication **method** along with your username and password. 2FA allows you to use the same **type** of method (e.g. something you know, like a PIN or security question).

**MFA** requires you to present at least one (1) additional authentication **method** along with your username and password. However, the additional method cannot be the same **type**. For example, if you log in with a username/password, you cannot use a PIN, but you can use an authenticator app or biometrics.

MFA is more secure than 2FA, and both are more secure than single-factor authentication (just a username and password). Always choose MFA over 2FA if it's available.

# 🔶 Artificial Intelligence (AI)
If no AI haters exist, then I’m dead.

- [privacy concerns](https://iapp.org/news/a/shaping-the-future-a-dynamic-taxonomy-for-ai-privacy-risks)
- [steals from artists/creatives](https://www.latimes.com/opinion/story/2024-06-18/artificial-intelligence-openai-media-manager-apple)
- [unsustainable resource consumption](https://www.vox.com/climate/2024/3/28/24111721/climate-ai-tech-energy-demand-rising)
- [generative AI uses more resources than task-specific tools](https://www.rwdigital.ca/blog/how-much-energy-do-google-search-and-chatgpt-use/)

AI can be a useful tool to those with disabilities, so abandoning it entirely is not an option for everyone. When most people think of AI, they think of generative AI, but narrow AI has been around for years. Generative AI poses a large risk to privacy. [Here’s the difference](https://www.forbes.com/sites/bernardmarr/2023/07/24/the-difference-between-generative-ai-and-traditional-ai-an-easy-explanation-for-anyone/).

What you can do to protect your privacy:

- opt out of AI training
  - this [Wired guide](https://www.wired.com/story/how-to-stop-your-data-from-being-used-to-train-ai/) is a good place to start
- never provide personal information to AI tools like ChatGBT
- disable unused AI features on your devices

# 🔶 Phones
**Important:** Police may legally compel you to use biometrics to unlock your phone. Some courts currently consider the use of biometrics as a “nontestimonial act.”

**Testimonial act:** Providing a password or PIN is considered a testimonial act because it involves revealing potentially incriminating information. Testimonial acts are protected by the 5th amendment.

**Nontestimonial act:** Using a fingerprint or facial recognition relies on physical characteristics instead of personal knowledge, and is therefore considered (in at least some recent court cases) a nontestimonial act. Nontestimonial acts are **not** protected by the 5th amendment.

With this in mind:

- leave your phone and smartwatch at home when attending protests
- consider manually disabling face ID / fingerprint when you’re outside of the home
- if you are stopped by police, and it’s safe to do so, turn off your phone
  - turning off your phone may prevent police from breaking into it with [Cellebrite](https://discuss.privacyguides.net/t/claims-made-by-forensics-companies-their-capabilities-and-how-grapheneos-fares/18445)
- for the safety of Black folks and other POC, you need your phone available to record police interactions
  - you may want to disable face ID / fingerprint instead
- on iOS, quickly [disable face ID](https://www.phonearena.com/news/How-to-force-iPhone-to-require-passcode-quickly-temporarily-disable-Face-ID_id121758) by triggering the “power off” screen, then canceling
- on Android, you can [enable lockdown mode from the lock screen](https://www.androidcentral.com/apps-software/how-to-disable-biometrics-on-your-android-phone-from-the-lock-screen)

I highly recommend that you restart your phone every day.

### 🔹 General FYI
Please, PLEASE turn off your public activity on apps like Venmo. There is no good reason for your transactions to be public.
- [instructions for Venmo](https://www.wikihow.com/Delete-Venmo-History)

## 🔸 Phone Number Masking
Alternative to giving your actual phone number out. This Proton [blog post](https://protonvpn.com/blog/protect-your-privacy-with-second-phone-number-app/) offers tips on what to look for.

Some examples:

- [Firefox Relay](https://relay.firefox.com/)
- [Google Voice](https://voice.google.com/u/0/about)

## 🔸 iPhone Settings

### 🔹 Turn on automatic updates
- regular software updates patch vulnerabilities
- the latest versions may foil tools like Cellebrite and GrayKey
- [instructions]((https://www.businessinsider.com/guides/tech/how-to-turn-on-automatic-updates-on-iphone?op=1))

### 🔹 Turn on Advanced Data Protection
- [instructions](https://support.apple.com/en-us/108756)

### 🔹 Push Notifications
Push alerts from apps can be [tied to your identity](https://www.washingtonpost.com/technology/2024/02/29/push-notification-surveillance-fbi/).
- [turn off notification previews while your phone is locked](https://www.lifewire.com/turn-off-message-preview-iphone-4175842)

### 🔹 Turn on Two-Factor Authentication (2FA)
- [instructions](https://support.apple.com/guide/iphone/use-two-factor-authentication-iphd709a3c46/ios)

### 🔹 Set up Account Recovery
Save your key in a safe location like a fire safe or password manager. Do not save it on any of your Apple devices.
- [instructions](https://support.apple.com/en-us/109345)

### 🔹 Face ID / Passcode Settings
- [use a 6 digit passcode instead of 4](https://support.apple.com/en-us/119586)
- [Turn on ‘Face ID Attention’](https://support.apple.com/guide/iphone/change-face-id-and-attention-settings-iph646624222/ios)
- [Disable control center when the phone is locked](https://www.tomsguide.com/how-to/how-to-disable-control-center-on-a-locked-iphone)

### 🔹 Screen Time Settings
- [turn off ‘Allow changes to: Passcode & Face ID’](https://www.techbout.com/prevent-others-from-changing-iphone-passcode-87736/)
  - this disables the ability to make changes to Passcode or Face ID and hides the option from your settings
  - to increase the effectiveness of this setting, you should set a Screen Time passcode and make sure it’s different from your iPhone passcode
  - note: to make changes to Passcode & Face ID, you must turn this setting back on

### 🔹 Enable Find My tracking when the phone is turned off
- [instructions](https://www.theverge.com/22697218/iphone-apple-ios-15-find-my-how-to)

### 🔹 Turn off ‘Location Services’
Toggle off for any app that does not require your location for functionality and use “while using app” for everything else. Location data brokers.
- [instructions](https://support.apple.com/en-us/102647)

### 🔹 Turn off ‘Allow Apps to Request to Track’
- [instructions](https://support.apple.com/guide/iphone/control-app-tracking-permissions-iph4f4cbd242/ios)

### 🔹 Configure ‘Stolen device protection’
- [instructions](https://support.apple.com/en-us/120340)

### 🔹 Turn off Airdrop
Or set to “Contacts Only.”
- [instructions](https://support.apple.com/en-us/119857)

## 🔸 Android Settings
Start [here](https://veepn.com/blog/10-android-privacy-settings/) to understand the privacy and security settings available to you.

### 🔹 Notifications
Don’t show any notifications or Hide silent conversations and notifications. Turn off sensitive notifications when locked.
- [instructions](https://support.google.com/android/answer/9079661?hl=en)

### 🔹 Turn off ‘Web & App Activity’
- [instructions](https://support.google.com/accounts/answer/54068?hl=en&co=GENIE.Platform%3DAndroid)

### 🔹 Location
Deny anything that doesn’t need your location, and turn on “while in use” for apps that need your location sometimes.
- [instructions](https://support.google.com/accounts/answer/3467281?hl=en)

### 🔹 Turn off personalization
- [instructions](https://support.google.com/My-Ad-Center-Help/answer/12155656?hl=en&co=GENIE.Platform%3DAndroid#turn-on-or-off-personalized-ads)

### 🔹 Enable 2FA
- [instructions](https://support.google.com/accounts/answer/185839?hl=en&co=GENIE.Platform%3DAndroid)

### 🔹 Device admin apps
Disable admin privileges for apps that don’t require it.
- [instructions](https://support.google.com/android/answer/9431959?hl=en)

### 🔹 Permission manager
Use this to review individual app permissions.
- [same link as above](https://support.google.com/android/answer/9431959?hl=en)

### 🔹 Leave on automatic system updates
Regular software updates patch vulnerabilities.

## 🔸 Useful Apps
- [Privacy.com](https://www.privacy.com/)
- [Signal](https://signal.org/download/)
- [Threema](https://threema.ch/en)
- [Session](https://getsession.org/)
- [Telegram](https://telegram.org/)
- [Briar](https://briarproject.org/)

## 🔸 Apps to Avoid
- Temu
  - [it’s basically malware](https://arstechnica.com/tech-policy/2024/06/shopping-app-temu-is-dangerous-malware-spying-on-your-texts-lawsuit-claims/)
- Period trackers
- DeepSeek
  - [awful security practices](https://www.forbes.com/sites/torconstantino/2025/02/04/4-warnings-about-deepseek-you-need-to-know-before-using-it/)

There is concern that data from period tracker apps could be used against someone who received an abortion. Even the Stardust app has been [guilty of sharing user data](https://techcrunch.com/2022/06/27/stardust-period-tracker-phone-number/). Here’s a 2022 [Wired article](https://www.wired.com/story/period-tracking-apps-flo-clue-stardust-ranked-data-privacy/) that covers the concern around period tracker privacy. Clue scored the highest, but doesn’t support local storage, which is a key privacy feature you should look for.

Period tracker apps that store your data on your phone instead of the cloud:
- [Euki](https://eukiapp.org/)
- [Drip](https://bloodyhealth.gitlab.io/)

# 🔶 Computers
Most of you are probably not going to use Linux. I think Linux is the best option for security and usability. Consider [Debian](https://www.debian.org/) or [Ubuntu](https://ubuntu.com/). This [TechRadar article](https://www.techradar.com/news/best-linux-distro-privacy-security) has some additional OS recommendations.

## 🔸 MacOS Settings

### 🔹 FileVault
Full disk encryption prevents someone from exfiltrating data on your hard drive in the event your computer is seized or stolen. You must save your recovery key in a safe place that’s not on your computer’s hard drive.
- [instructions](https://support.apple.com/guide/mac-help/protect-data-on-your-mac-with-filevault-mh11785/mac)

### 🔹 Antivirus
MacOS has built-in protection tools that help prevent malware from being installed. Here’s an [explanation](https://www.macworld.com/article/670537/do-macs-need-antivirus.html) of those features and their shortfalls.

Some options available for MacOS:

- [NordVPN Threat Protection Pro](https://nordvpn.com/features/threat-protection/)
- [Bitdefender](https://www.bitdefender.com/en-us/)
- [Malwarebytes](https://www.malwarebytes.com/)
- [Surfshark One](https://surfshark.com/one)

### 🔹 Updates
Regular software updates patch vulnerabilities.
- [instructions](https://support.apple.com/guide/mac-help/keep-your-mac-up-to-date-mchlpx1065/mac)

## 🔸 Windows Settings

### 🔹 BitLocker
Full disk encryption prevents someone from exfiltrating data on your hard drive in the event your computer is seized or stolen. You must save your recovery key in a safe place that’s not on your computer’s hard drive.
- [instructions](https://support.microsoft.com/en-us/windows/bitlocker-drive-encryption-76b92ac9-1040-48d6-9f5f-d14b3c5fa178)

### 🔹 Turn off ‘Diagnostic data’
- [instructions](https://learn.microsoft.com/en-us/windows/privacy/configure-windows-diagnostic-data-in-your-organization#diagnostic-data-settings)

### 🔹 Turn off ‘Improve inking and typing’
- [instructions](https://support.microsoft.com/en-us/windows/speech-voice-activation-inking-typing-and-privacy-149e0e60-7c93-dedd-a0d8-5731b71a4fef)

### 🔹 Turn off ‘Tailored experiences’
- [instructions](https://windowsloop.com/change-privacy-settings-in-windows-11/)

### 🔹 Antivirus
Windows Defender is built-in and enough for 99% of people. You may wish to supplement it if you’re torrenting or downloading unofficial software.

Some options available for Windows:

- [NordVPN Threat Protection Pro](https://nordvpn.com/features/threat-protection/)
- [Bitdefender](https://www.bitdefender.com/en-us/)
- [Malwarebytes](https://www.malwarebytes.com/)
- [Surfshark One](https://surfshark.com/one)

### 🔹 Automatic Updates
Regular software updates patch vulnerabilities.

## 🔸 Cloud Storage
The safest place your data can be stored is locally on your physical devices. If that’s not an option, it’s possible to improve cloud storage security.

**What to look for:** End to end encryption and what information could be handed over if subpoenaed.

iCloud, Google Drive, and OneDrive are considered safe, but you may want to activate advanced security settings. This [Wired guide](https://www.wired.com/story/9-tips-cloud-storage-security/) is a good starting point.
- [iCloud security overview](https://support.apple.com/en-us/102651)
- [Google Drive key security controls](https://cloud.google.com/docs/security/overview/whitepaper#key_security_controls)
- [OneDrive security overview](https://learn.microsoft.com/en-us/sharepoint/onedrive-privacy-security-overview)

These companies are required to comply with local regulations if subpoenaed. Consider manually encrypting sensitive files/folders. Use a long, complex password and store it in a fire safe AND password manager.
- [encrypt on Windows](https://support.microsoft.com/en-us/windows/how-to-encrypt-a-file-1131805c-47b8-2e3e-a705-807e13c10da7)
- [encrypt using 7zip](https://info.lse.ac.uk/staff/divisions/dts/help/guides-faqs/software/using-7-Zip-to-encrypt-and-decrypt-files)
- [encrypt on MacOS](https://support.apple.com/guide/mac-help/protect-your-mac-information-with-encryption-mh40593/mac)

# 🔶 Email

### 🔹 Email masking
- [Firefox Relay](https://relay.firefox.com/)

### 🔹 Use multiple accounts
I recommend one email address to use professionally (resume, job apps, etc). Then use other email accounts for everything else.

### 🔹 Privacy-focused options
- [ProtonMail](https://mail.proton.me/)

### 🔹 Temporary email options
- [Emailnator](https://www.emailnator.com/)
- [10 minute mail](https://10minutemail.com/)

# 🔶 Resources
Here are some great resources if you’d like to learn more.
- [Electronic Frontier Foundation](https://www.eff.org/)
- [Privacy Rights Clearinghouse](https://privacyrights.org/)
- [The Digital Standard](https://thedigitalstandard.org/)
- [Surveillance Technology Oversight Project](https://www.stopspying.org/)
- [Kaspersky](https://usa.kaspersky.com/)
- [IntelTechniques](https://inteltechniques.com/)
- [Privacy Guides](https://www.privacyguides.org/en/)


If you find this project useful and wish to show your appreciation, I'll happily accept a few bucks: [venmo](https://venmo.com/u/kristonisms)

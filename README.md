# Table of Contents

1. [TL;DR](#tldr)
2. [Reduce Digital Footprint](#reduce-digital-footprint)
   - [Meta](#meta-facebook-instagram-whatsapp)
   - [Data brokers](#data-brokers)
4. [Web Browsing](#web-browsing)
   - [Home network setup](#home-network-setup)
   - [Browsers](#browsers)
   - [Search engines](#search-engines)
   - [Extensions & add-ons](#extensions--add-ons)
   - [Website cookies](#website-cookies)
   - [VPNs](#vpns)
   - [Passwords](#passwords)
   - [Password managers](#password-managers)
   - [MFA / 2FA](mfa--2fa)
6. [Artificial Intelligence (AI)](#artificial-intelligence-ai)
7. [Phones](#phones)
   - [Phone number masking](#phone-number-masking)
   - [iPhone](#iphone-settings)
   - [Android](#android-settings)
   - [Useful apps](#useful-apps)
   - [Apps to avoid](#apps-to-avoid)
9. [Computers](#computers)
    - [MacOS](#macos-settings)
    - [Windows](#windows-settings)
    - [Cloud storage](#cloud-storage)
    - [Word processors](#word-processors)
11. [Email](#email)
12. [Travel](#travel)
13. [Resources](#resources)

---

This guide focuses on data privacy but it often veers into cybersecurity. While they are not synonomous, it's important to emphasize that good cybersecurity practices will go a long way in protecting your personal privacy.

Your data is often gathered through complex terms & conditions, features such as personalized recommendations, location tracking, activity habits, and more. As we’ve seen, data collected by corporations often ends up in data breaches; [AT&T](https://www.cnet.com/tech/mobile/at-t-data-breach-what-is-at-t-doing-for-the-73-million-accounts-breached/), [Change Healthcare](https://techcrunch.com/2024/02/21/change-healthcare-cyberattack/), and [Ticketmaster](https://www.pcmag.com/news/ticketmaster-confirms-user-email-addresses-phone-numbers-stolen-in-hack) to name a few. Additionally, the US government is [partnering with Palantir](https://www.nytimes.com/2025/05/30/technology/trump-palantir-data-americans.html) to build a database on all of us. Read about [Project Esther](https://contendingmodernities.nd.edu/global-currents/jvp-rejecting-project-esther/).

You deserve to control access to your personal information - who gets it, when it’s given, how it’s used, and for how long. I know fighting for your data privacy feels overshelming and seems hopeless - you may be asking yourself what's the point. Fighting against surveillance, fighting for your right to data privacy, even in the smallest way, is worth everything.

***Disclaimer: Be sure to research any privacy measures you implement - don't just take an internet stranger's word for it!***

# TL;DR
Here are some recommendations that I think will have the largest impact on improving your privacy and security. You do not need perfection to get some benefit. If you only do one or two of these then you're doing great.

| Action item | Details |
| --- | --- |
| [Privacy-focused<br>browser & search engine](#browsers) | Firefox with DuckDuckGo is a popular option that will suit most users |
| [Password manager](#passwords) | Best practice is to use unique, long, and complex passwords. A password manager will help. Here are some popular options:<br><ul> <li>1Password</li> <li>Bitwarden</li> <li>NordPass</li> </ul> |
| [MFA / 2FA](#mfa--2fa) | Enable for everything, especially the important stuff |
| [Social media](#reduce-digital-footprint) | <ul> <li>**best:** delete them and any unused accounts</li> <li>**good:** remove personal information, make accounts private, opt out of third party sharing</li> </ul> |
| [Website privacy settings](#reduce-digital-footprint) | When you visit a website that asks you to accept their cookie policy, reject all or as many cookies as you are able. Sometimes you need to customize settings to do this. There are browser extensions that offer this capability as well as browser settings. On websites where you have an account (think social media, ecommcerce, etc.), opt out of AI training, website tracking, and data & location services in your account settings |
| [Data brokers](#data-brokers) | Data brokers are really any entity that stores, buys, sells, or uses a person's personal data to earn revenue. Reducing the amount of information you share on social media or with online companies reduces the amount of data they can gather on you. It's also possible to remove your personal information from data broker databases directly, which I also recommend if you have the time |
| [Apps & software](#useful-apps) | Use applications / software that have end to end encryption (E2EE) |
| Google | [How to de-Google your life](https://proton.me/blog/how-to-de-google) |

# Reduce Digital Footprint
Publicly available information about you can be used:
- in targeted ads
- to [dox you](https://en.wikipedia.org/wiki/Doxing#:~:text=Doxing%20or%20doxxing%20is%20the,Internet%20and%20without%20their%20consent.)
- to stalk or harass you
- against you politically or socially
  - your sexual orientation, political affiliation, or gender identity
 
| Action item | Details |
| --- | --- |
| Social media | Your personal information, activity, enagement, and attention are worth billions. You can combat data harvesting by deleting your social media accounts and/or reducing how much of your information they have access to.<br><br> <ul> <li>remove personal details such as your employer, full name, relatives, gender identity, etc, from your profile</li> <li>avoid sharing detailed personal information in social media comments</li> <li>opt out of (third party) data sharing - this may be framed as "personalization"</li> <li>block access to your location</li> <li>block access to your address book</li> <li>disable cross-website tracking</li> <li>disable third party cookies</li> <li>make your profile private</li> <li>don't use "Sign in with Google/Facebook/etc" on websites - sign up with an email address instead</li> <li>specific instructions for Facebook / Meta will be below</li> </ul> |
| [Google account](https://myaccount.google.com) | If you have a gmail account, then this applies to you. Google has a lot of settings and features that are designed to track your activity. Here are some suggestions to get you started.<br><br ><ul> <li>turn off [search personalization](https://www.google.com/search-personalization/?continue=https://myaccount.google.com/data-and-privacy&hl=en)</li> <li>turn off [personalized ads](https://myadcenter.google.com)</li> <li>turn off [web & app activity](https://myactivity.google.com/activitycontrols) - additionally, delete stored activity data</li> <li>turn off [YouTube history](https://myactivity.google.com/activitycontrols)</li> </ul>Some more ways to [de-Google your life](https://proton.me/blog/how-to-de-google) |
| [Prescreen offers](https://consumer.ftc.gov/articles/prescreened-credit-insurance-offers) | You can opt out of prescreen offers [here](https://www.optoutprescreen.com/). You may want to consider freezing your credit with the 3 major credit bureaus as well. Info on that can be found [here](https://www.usa.gov/credit-freeze) |
| Public records | Depending on your location and situation, you may request your public records be hidden from public-facing websites run by local, county, and state-wide entities |
| Privacy settings | Outside of social media, most websites you have an account with have privacy settings. There is no easy way to do this, but you will need to visit each website you have an account with and manually change your privacy settings to opt out of persaonization, diagnostic data sharing, third party data sharing, and anything else that could link your information or activity to you (whether it's anonymized or not) |
| Pseudonyms | Use a pseudonym when you must create an account on a website whenever possible (you may want to tie a specific pseudonym with an email address) |
| Unused accounts | If you have accounts on websites that you’re no longer active on, deactivate or delete them. Before deletion, you may need to request your information be removed from their database. Deleting unused accounts will shrink your digital footprint |
| Photo metadata | Photos have metadata that can contain lots of information about what device was used to take the photo, location data, and more. Remove photo metadata using [ExifTool](https://exiftool.org/). There are other tools out there that don't use the command line, like ExifCleaner, however, ExifCleaner hasn't been updated in 3 years |
| Data brokers | Data brokers are entities who collect information about you to sell. They exist in different forms and buy/sell different types of data to build profiles on you, the consumer. For example, people finder sites are a type of [data broker](https://consumer.ftc.gov/articles/what-know-about-people-search-sites-sell-your-information). Removing your information from data broker databases is a multi-step process that will take a lot of effort to accomplish, but is well-worth the energy to reduce who has access to your data. There are plenty of reasons to delete your information from these databases and prevent future information from being sold. One example is that US government agencies have been found to be [buying your location data](https://www.theverge.com/2024/12/3/24312313/ftc-bans-sensitive-location-data-brokers-gravy-analytics-venntel-mobilewalla) from brokers |
| End to end encryption (E2EE) | Encryption is meant to keep prying eyes from accessing data without permission. For example, if you send an unencrypted text message to your friend, it could be intercepted and read by an unknown third party. Think of encryption as a process that scrambles the content of your message, so even if a third party snags the text, your message would be unreadable. Not all encryption is created equal, and here is a guide (TBD) I wrote about it. Prioritize apps and software that utlize E2EE. Encrypt your phone and computers (more details in their respective sections) |
| Internet of Things (IoT) | We don't need a bluetooth toothbrush that tells us our brushing habits. Many smart devices and activity & wellness apps sell usage data to advertisers (more specifically, the usage data they gather through their mobile apps that you download to manage the devices). If it's something that doesn't *requie* an internet or bluetooth connection to function, it's good practice to skip on getting the "smart" version |

## Meta (Facebook, Instagram, Whatsapp)
Ideally, we all delete our Meta accounts. If not, here is a list of actions you can take to reduce how much data their products collect on you. Many of these settings can be found in your [Accounts Center](https://accountscenter.facebook.com). Details on [permanently deactivating your Facebook account](https://www.facebook.com/help/224562897555674/FACEBOOK/).

| Action item | Details |
| --- | --- |
| [Password and Security](https://accountscenter.facebook.com/password_and_security) | <ul> <li>enable 2FA</li> <li>enable Advanced Protection</li> </ul> |
| [Your information and permissions](https://accountscenter.facebook.com/info_and_permissions) | <ul> <li>Your activity off Meta technologies</li> <li>Clear specific activity</li> <li>remove external accounts under "Specific ad partners"</li> </ul> |
| [Your activity off Meta technologies](https://accountscenter.facebook.com/info_and_permissions/off_facebook_activity/?entry_point=ACCOUNTS_CENTER) | <ul> <li>Disconnect specific activity - remove any connected brands or services</li> <li>Clear previous activity - select "clear" for all of your Meta accounts</li> <li>Manage future activity - "Disconnect future activity"</li> </ul>
| [Ad preferences](https://accountscenter.facebook.com/ads) | Turn off all of the settings under "Manage info" |
| [Connected experiences](https://accountscenter.facebook.com/connected_experiences) | Disconnect specific activity |
| Profile settings | <ul> <li>remove personal details such as your marital status, location, job, school, family members, etc</li> <li>make your profile private</li> <li>ensure all posts and photo updates are set to "friends only"</li> </ul> |
| Page likes | Consider reducing the number of pages you like that might have political affiliations |
| [Connected apps & websites](https://www.facebook.com/settings/?tab=applications) | Remove all connected apps and websites. They're just mining your data |
| "Login with Facebook" | Don't use Facebook to log into unrelated applications – use an email address instead |
| Friends | Remove people from your friends list that you don't know |
| [How people find and contact you](https://www.facebook.com/settings/?tab=how_people_find_and_contact_you) | Restrict or turn off most of these settings |

### Facebook Activity log
**Profile picture > Settings & privacy > Activity log**
| Setting | Details |
| --- | --- |
| Your Facebook activity | Use this section to check if you have comments or posts that you wish to delete or make visible to "friends only" |
| Personal information | Check that account and profile updates are set to "friends only" or hide them from your profile |
| Connections | remove followers you don't know |
| Apps and websites off of Facebook | Check to see if anything needs to be removed |
| Logged information | Check for public activity you wish to remove |

## Data brokers
This [YouTube video](https://www.youtube.com/watch?v=iX3JT6q3AxA) is a great starting point to help you understand how data is gathered and used. Data brokers are only a small part of the overall picture when it comes to your personal information. Some things you can do to keep your data out of databases are:
- opt out of third party data sharing on websites and apps
- delete unnecessary apps and unused accounts
- reduce the amount of IoT devices you use
- verify the type of data your smart devices (and apps) gather and share with third parties (and opt out where possible)
- turn off location tracking

### Manual data removal
| Pros | Cons |
| --- | --- |
| free | time-consuming |
| most effective | requires regular follow up |
| you control the information<br> shared with the data brokers | not 100% effective |

These resources will help:
- [IntelTechniques Data Removal Guide](https://inteltechniques.com/workbook.html)
- [Big Ass Data Broker Opt Out LIst Github](https://github.com/yaelwrites/Big-Ass-Data-Broker-Opt-Out-List)
- [Privacy Guides | Data Removal Services](https://www.privacyguides.org/en/data-broker-removals/)

### Paid data removal
| Pros | Cons |
| --- | --- |
| significantly less time-consuming | ongoing subscription |
| regular reporting | limited scope & requires manual work |

Some popular providers:

- [DeleteMe](https://joindeleteme.com/)
- [Incogni](https://incogni.com/)
- [EasyOptOuts](https://easyoptouts.com/)
- [Kanary](https://www.kanary.com/)
- [Optery](https://www.optery.com/)

# Web Browsing
Your ISP (internet service provider), phone apps, cellular provider, web browser, and websites all see some amount of information about you when you use their services.

| Security measure | Priority | Details |
| --- | --- | --- |
| Privacy-focused browser | Highest | A privacy-focused browser is the starting point to improving your data privacy. Many of these browsers have features turned on by default that put your data privacy front and center. They might mitigate fingerprinting, block third party cookies and cross-site tracking, mask your IP address, and more |
| Privacy-focused search engine | Highest | Search engines play a big role in third party advertiser tracking |
| VPN | High | While VPNs are not required for daily use, if you wish to increase your level of privacy while on the web, a VPN can be a useful tool if used correctly |
| Password manager | Highest | Reusing passwords puts your privacy and security at risk. It's not recommended to save your passwords in the browser, so the next best option is to use a password manager. Most, if not all, password managers have browser extensions available make their use more convenient |
| Extensions | Optional | Extensions *can* compromise your privacy, so you may want to do some research on an extension before adding it to your browser. There are also plenty of extensions that are meant to aid in privacy and security, such as uBlock Origin and ClearURLs. Keep in mind that extensions can also compromise your privacy and security |
| Third party tracking / cookies | Highest | Starting with a browser + search engine that prioritizes privacy will significantly help with this. To go even further, whenever you access a website that prompts you to accept cookies, always reject them all |

## Home network setup
Configure your home network in a way to prevent unauthorized access and protect your privacy. For more advanced settings like port forwarding, look into your router manufacturer's documentation.

| Action | Details |
| --- | --- |
| Router password | Always change the default password for all of your devices or accounts |
| Router encryption | If you have an older router, verify that [WPS](https://en.wikipedia.org/wiki/Wi-Fi_Protected_Setup) is disabled (unless it's necessary for older equipment) and that it's set to use [WPA2 or WPA3](https://en.wikipedia.org/wiki/Wi-Fi_Protected_Access) |
| Wifi network name (SSID) | Change the default SSID and make sure the router make/model is not in it. This information could be used by bad actors to try to exploit known vulnerabilities, or it can indicate to an attaker that whoever owns the router did not take necessary precautions to protect their network. It's also not generally recommended to "hide" your network broadcast because that can be circumvented and might pique the curiosity of would-be attackers |

## Browsers
Chrome is not recommended for privacy. Google [harvests a lot of data](https://www.wired.com/story/google-chrome-browser-data/), and Chrome [disabled ad blockers](https://www.theverge.com/2024/10/15/24270981/google-chrome-ublock-origin-phaseout-manifest-v3-ad-blocker) with manifest v3.

| Browser | Details |
| --- | --- |
| [Tor](https://www.torproject.org/download/) | If you're looking to improve your anonymity and privacy, then the Tor browser is an excellent choice. It's not as user friendly as other browsers and extensions/plugins are not recommended. Tor is an excellent choice because it works by utilizing [onion routing](https://en.wikipedia.org/wiki/Onion_routing) and it [mitigates fingerprinting](https://tb-manual.torproject.org/anti-fingerprinting/) |
| [Firefox](https://www.mozilla.org/en-US/firefox/) | Firefox is one of the more well-known and popular browsers and is great for people who want a little more privacy paired with Chrome's functionality |
| [Brave](https://brave.com/) | Brave is a great option that [mitigates fingerprinting](https://brave.com/privacy-updates/3-fingerprint-randomization/) |
| [DuckDuckGo](https://start.duckduckgo.com/) | Most people know about DDG as a search engine but it offers a security-focused browser as well |

Be sure to configure additional privacy settings for any web browser you choose to get the most out of it.

## Search engines
There are many great alternatives to Google. Moving away from Chrome is only part of the process of de-Googling.

| Search engine | Details |
| --- | --- |
| [DuckDuckgo](https://duckduckgo.com/) | DDG is one of the most popular Google alternative search engines. Its search results are built from "over 400 sources" including Bing, Yahoo, and its own web crawler |
| [Startpage](https://www.startpage.com/en/) | A search engine that pulls from Google's search results so you get the results without the tracking |
| [Brave](https://search.brave.com/) | Much like the browser, Brave is a search engine alternative that is focused on privacy and is a good replacement if you don't like the DDG search engine |
| [Kagi](https://kagi.com/) | A paid search engine that uses its subscription revenue to pay for operations instead of advertising |

## Extensions & add-ons
Be aware that extensions and add-ons can compromise your security. Thoroughly research extensions before installing and keep in mind the more you have installed, the easier it is to identify your browser.

| Extension | Details |
| --- | --- |
| uBlock Origin | A popular extension that blocks ads, offers a customizable script blocker, and has configurable website tracking filter |
| uBlock Origin Lite | Has far less capabilities than uBlock Origin, but is an option for those who must use Chrome and can no longer access the full extension |
| [ClearURLs](https://github.com/ClearURLs/Addon) | Removes tracking elements from web urls to reduce / prevent tracking |
| [Privacy Badger](https://privacybadger.org/) | Blocks third party tracking |

## Website cookies
Think of cookies as identifiers that tie your browsing activity to you. There are browser settings and extensions that will block third party cookies automatically. When a website asks you to accept cookies, choose “reject” or “necessary cookies only.”

## VPNs
A VPN is a virtual private network that can encrypt your internet traffic and mask your IP address. They can be useful when you wish to mask your IP address while on the web. Most internet users don't really need to use a VPN in their day to day life as they won't necessarily provide you enhanced privacy or security. Unless you have specific use cases for a VPN, this one is okay to skip. Here's a good video on VPNs by [Reject Convenience](https://www.youtube.com/watch?v=mIwfNw5UaHA).

If you choose to use a VPN: select a provider that does not log identifying information along with your activity. Confirm they don’t save user logs by checking if they’ve been independently audited. Avoid using free VPNs (except for Proton) or you might end up with spyware on your phone ([Facebook Onavo](https://www.techradar.com/computing/cyber-security/facebooks-onavo-vpn-used-to-wiretap-competitor-data-court-filings-reveal), anyone?). Here are some providers who have been third party verified and are popular:

- [Proton](https://protonvpn.com/)
- [NordVPN](https://nordvpn.com/)
- [Mullvad](https://mullvad.net/en)
- [Surfshark](https://surfshark.com/)
- [ExpressVPN](https://www.expressvpn.com/)
- [PIA](https://www.privateinternetaccess.com/)

***Important:*** A VPN does *not* keep your online activity completely anonymous.

***Consider this:*** You post from an anonymous account on a forum, but you’re on a VPN, so your IP address is masked. However, you then place an online order for pizza delivery while still logged into the VPN. That IP address is now directly tied to your address and forum post.

***Takeaway:*** A VPN masks your IP address but can still be linked to you based on your online activity, fingerprinting, and other data. This is why disabling things like tracking and third party cookies is useful. If anonymity is your goal, check out [The Hitchhiker’s Guide](https://anonymousplanet.org/guide.htmlw).

## Passwords
For more information, see CISA's [best practices guide](https://www.cisa.gov/secure-our-world/use-strong-passwords).

| Action | Priority | Explanation |
| --- | --- | --- |
| Strong passwords | Highest | The longer and more complex your password is, the more difficult it is to guess. You want to aim for at least 16 characters, with a mix of upper case, lower case, numbers, and symbols. Randomly generated passwords are best (then you just save them to a password manager). For passwords you need to memorize, I recommend using a phrase you can easily remember, but that isn't easily guessable. For example "WeWent2TheMoon&Mars?" - it's not the best, but it's short, has everything you'd want in a password, and meets the 16 character minimum |
| Unique Passwords | Highest | Use a different password for everything. If you utlize a password manager, then there's no need to memorize the password for every application or website you have an account with. When you reuse passwords, if your credentials for one website leak, then it puts all of your other accounts with the same credentials at risk |
| Passkeys | Highest | Passkeys are a more secure alternative to passwords. More information [here](https://www.passkeys.com/passkey-vs-password) |
| Password manager | Highest | You likely have dozens of accounts that require login credentials. It's an unavoidable fact of the modern era. If you have more than a handful of accounts with login credentials, then you pretty much need a password manager. It's the way way to generate random passwords and to manage credentials for dozens of websites |
| MFA / 2FA | Highest | Turn on MFA (best) or 2FA for every account you have. If you need to prioritize what to activate it for, start with your bank, email, Apple/Windows accounts, and social media |

## Password Managers
Password managers store login credentials, contact details, secure notes, and more in an encrypted “vault.”

Apple and Google Passwords are secure if that’s your preference. The downside is if you lose access to your Apple ID or Google account, you’ll lose access to all of your passwords.

Some popular password managers:
- [Bitwarden](https://bitwarden.com/)
- [LastPass](https://www.lastpass.com/)
- [NordPass](https://nordpass.com/)
- [1Password](https://1password.com/)

## MFA / 2FA
Multi-factor (MFA) and 2-factor (2FA) authentication are an extra step to verifying your identity when you log into something. These measures help prevent unauthorized access to your accounts by requiring additional steps to log into an account.

***TL;DR:*** Enable MFA and 2FA for everything.

There are four **types** of authentication, and a variety of **methods** to achieve each type.

| Type | Method(s) |
| --- | --- |
| something you know | password, PIN, security questions |
| something you have | yubikey, one time password (OTP), authenticator app | 
| something you are | biometrics such as face ID or fingerprint | 
| somewhere you are | geolocation | 

For example, your username and password fall under “something you know” authentication **type**.

***2FA*** requires you to present one (1) additional authentication **method** along with your username and password. 2FA allows you to use the same **type** of method (e.g. something you know, like a PIN or security question).

***MFA*** requires you to present *at least* one (1) additional authentication **method** along with your username and password. However, the additional method cannot be the same **type**. For example, if you log in with a username/password, you cannot use a PIN, but you can use an authenticator app or biometrics.

MFA is more secure than 2FA, and both are more secure than single-factor authentication (just a username and password). Always choose MFA over 2FA if it's available.

MFA / 2FA tier list:

| Option | Rank | Examples | Details |
| --- | --- | --- | --- |
| security key | top choice | yubikey | (PCMag on using security keys)[https://www.pcmag.com/how-to/protect-your-online-accounts-physical-security-key#] |
| authenticator app | great choice | Proton Auth | tbd |
| OTP | avoid when possible | codes sent via text or email | tbd |

# Artificial Intelligence (AI)
There are good reasons to be concerned about how much of personal information generative AI (aka LLMs) consumes.
- [privacy concerns](https://iapp.org/news/a/shaping-the-future-a-dynamic-taxonomy-for-ai-privacy-risks)
- [steals from artists / creatives](https://www.latimes.com/opinion/story/2024-06-18/artificial-intelligence-openai-media-manager-apple)
- [unsustainable resource consumption](https://www.vox.com/climate/2024/3/28/24111721/climate-ai-tech-energy-demand-rising)
- [generative AI uses more resources than task-specific tools](https://www.rwdigital.ca/blog/how-much-energy-do-google-search-and-chatgpt-use/)

When most people think of AI, they think of generative AI, but narrow AI has been around for years. Generative AI poses a large risk to privacy. [Here’s the difference](https://www.forbes.com/sites/bernardmarr/2023/07/24/the-difference-between-generative-ai-and-traditional-ai-an-easy-explanation-for-anyone/). Narrow AI can be a better solution in many cases over generative AI.

What you can do to protect your privacy:
- opt out of AI training
  - this [Wired guide](https://www.wired.com/story/how-to-stop-your-data-from-being-used-to-train-ai/) is a good place to start
- never provide personal information to AI tools like ChatGBT
- disable unused AI features on your devices

Consider hosting your own local installation of an LLM. The benefit of hosting an LLM locally is that all of your interactions are saved locally and not sent to some tech giant.
- [LM Studio](https://lmstudio.ai/) is an excellent option for most people
- Mac users can try [Docker Model Runner](https://docs.docker.com/ai/model-runner/)
- for more technically advanced users, consider something directly from [Hugging Face](https://huggingface.co/)
- for even more technically advanced users, consider spinning up your own instance of [llama.cpp](https://github.com/ggml-org/llama.cpp)

# Phones
***Important:*** Police may legally compel you to use biometrics to unlock your phone. Some courts currently consider the use of biometrics as a “nontestimonial act.”

***Testimonial act:*** Providing a password or PIN is considered a testimonial act because it involves revealing potentially incriminating information. Testimonial acts are protected by the 5th amendment.

***Nontestimonial act:*** Using a fingerprint or facial recognition relies on physical characteristics instead of personal knowledge, and is therefore considered (in at least some recent court cases) a nontestimonial act. Nontestimonial acts are **not** protected by the 5th amendment.

With this in mind:
- leave your phone and smartwatch at home when attending protests or other politcal activities
- consider manually disabling face ID / fingerprint when you’re outside of the home
- if you are stopped by police, and it’s safe to do so, turn off your phone
  - turning off your phone may prevent police from breaking into it with [Cellebrite](https://discuss.privacyguides.net/t/claims-made-by-forensics-companies-their-capabilities-and-how-grapheneos-fares/18445)
- for the safety of Black folks and other POC, you need your phone available to record police interactions
  - disable face ID / fingerprint instead
- on iOS, quickly [disable biometrics](https://www.phonearena.com/news/How-to-force-iPhone-to-require-passcode-quickly-temporarily-disable-Face-ID_id121758) by triggering the “power off” screen, then canceling
  - this will also work if you rapidly hit the power button 5 times
- on Android, you can [enable lockdown mode from the lock screen](https://www.androidcentral.com/apps-software/how-to-disable-biometrics-on-your-android-phone-from-the-lock-screen)

| Action item | Details |
| --- | --- |
| Daily restart | tbd |
| Automatic updates | Regular software updates patch vulnerabilities. The latest versions may foil tools like Cellebrite and GrayKey | 
| Public activity | Turn off your public activity on apps like Venmo. There's no good reason for your transations to be public. This activity can be used to tie you to others. [Instructions](https://www.wikihow.com/Delete-Venmo-History) | 
| Tracking | tbd |
| Location services | tbd |
| Phone number masking | tbd |
| Biometrics | tbd |

## Phone Number Masking
Alternative to giving your actual phone number out. This Proton [blog post](https://protonvpn.com/blog/protect-your-privacy-with-second-phone-number-app/) offers tips on what to look for.

Some examples:
- [Firefox Relay](https://relay.firefox.com/)
- [Google Voice](https://voice.google.com/u/0/about)
  - not the best option if you're trying to fully eliminate Google from your life as it requires you to have a Google account

## iPhone Settings
| Setting | Action | Details |
| --- | --- | --- |
| Advanced Data Protection | [enable](https://support.apple.com/en-us/108756) | tbd |
| Push notifications | consider disabling | Push alerts from apps can be [tied to your identity](https://www.washingtonpost.com/technology/2024/02/29/push-notification-surveillance-fbi/). If you leave them turned on, you should [turn off notification previews while your phone is locked](https://www.lifewire.com/turn-off-message-preview-iphone-4175842) |
| 2FA | [enable](https://support.apple.com/guide/iphone/use-two-factor-authentication-iphd709a3c46/ios) | tbd |
| Account Recovery | [enable](https://support.apple.com/en-us/109345) | An option you can use if you lose access to your account or it's compromised |
| Face ID / Passcode | <ul> <li>[use a 6 digit passcode](https://support.apple.com/en-us/119586)</li> <li>[enable ‘Face ID Attention’](https://support.apple.com/guide/iphone/change-face-id-and-attention-settings-iph646624222/ios)</li> <li>[disable control center when the phone is locked](https://www.tomsguide.com/how-to/how-to-disable-control-center-on-a-locked-iphone)</li> <li></li> </ul> | tbd |
| Screen Time | [turn off ‘Allow changes to: Passcode & Face ID’](https://www.techbout.com/prevent-others-from-changing-iphone-passcode-87736/) | This disables the ability to make changes to Passcode or Face ID and hides the option from your settings. To increase the effectiveness of this setting, you should set a Screen Time passcode and make sure it’s different from your iPhone passcode. Note: to make changes to Passcode & Face ID, you must turn this setting back on |
| Find My | [enable](https://www.theverge.com/22697218/iphone-apple-ios-15-find-my-how-to) Find My device tracking even when the device is turned off | tbd |
| Location Services | [disable](https://support.apple.com/en-us/102647) | Disable for any app that does not require your location for functionality and use “while using app” for everything else. |
| Allow Apps to Request to Track | [disable](https://support.apple.com/guide/iphone/control-app-tracking-permissions-iph4f4cbd242/ios) | tbd |
| Stolen device protection | [enable](https://support.apple.com/en-us/120340) | tbd |
| Airdrop | [disable](https://support.apple.com/en-us/102647) or set to "Contacts Only" | tbd |

## Android Settings
Start [here](https://veepn.com/blog/10-android-privacy-settings/) to understand the privacy and security settings available to you.

| Setting | Action | Details |
| --- | --- | --- |
| Notifications | [consider disabling](https://support.google.com/android/answer/9079661?hl=en) | Don’t show any notifications or Hide silent conversations and notifications. Turn off sensitive notifications when locked |
| Web & App Activity | [disable](https://support.google.com/accounts/answer/54068?hl=en&co=GENIE.Platform%3DAndroid) | tbd |
| Location | [disable](https://support.google.com/accounts/answer/3467281?hl=en) | Deny anything that doesn’t need your location, and enable “while in use” for apps that need your location sometimes |
| Personalization | [disable](https://support.google.com/My-Ad-Center-Help/answer/12155656?hl=en&co=GENIE.Platform%3DAndroid#turn-on-or-off-personalized-ads) | tbd |
| 2FA | [enable](https://support.google.com/accounts/answer/185839?hl=en&co=GENIE.Platform%3DAndroid) | tbd |
| Admin privileges | [disable](https://support.google.com/android/answer/9431959?hl=en) | Disable admin privileges for apps that don’t require it |
| Permission manager | [review permissions](https://support.google.com/android/answer/9431959?hl=en) | Use this to review individual app permissions |

## Useful Apps
- [Privacy.com](https://www.privacy.com/)
- [Signal](https://signal.org/download/)
  - enable vanishing messages
- [Threema](https://threema.ch/en)
- [Session](https://getsession.org/)
- [Telegram](https://telegram.org/)
- [Briar](https://briarproject.org/)
  - enable vanishing messages

## Apps to Avoid
- Temu
  - [it’s basically malware](https://arstechnica.com/tech-policy/2024/06/shopping-app-temu-is-dangerous-malware-spying-on-your-texts-lawsuit-claims/)
- Period trackers
  - basically all health & wellness apps, including [mental health apps](https://www.mozillafoundation.org/en/blog/top-mental-health-and-prayer-apps-fail-spectacularly-at-privacy-security/)
  - some exceptions to this are listed below
- DeepSeek
  - [awful security practices](https://www.forbes.com/sites/torconstantino/2025/02/04/4-warnings-about-deepseek-you-need-to-know-before-using-it/)

There is concern that data from period tracker apps could be used against someone who received an abortion. Even the Stardust app has been [guilty of sharing user data](https://techcrunch.com/2022/06/27/stardust-period-tracker-phone-number/). Here’s a 2022 [Wired article](https://www.wired.com/story/period-tracking-apps-flo-clue-stardust-ranked-data-privacy/) that covers the concern around period tracker privacy. Clue scored the highest, but doesn’t support local storage, which is a key privacy feature you should look for.

Period tracker apps that store your data on your phone instead of the cloud:
- [Euki](https://eukiapp.org/)
- [Drip](https://bloodyhealth.gitlab.io/)

# Computers
Most of you are probably not going to use Linux, but I think everyone should use it. Linux is great for privacy, but it only has a fraction of the market share of operating systems. Some good options for Linux newbies:

| Linux distro | Details |
| --- | --- |
| [Linux Mint](https://linuxmint.com/) | A free, user-friendly OS that looks and operates like an older Windows OS |
| [Zorin OS](https://zorin.com/os/pro/) | A user-friendly OS that offers a paid pro version and can support many Windows apps |
| [Ubuntu](https://ubuntu.com/) | A classic Linux distro that's beginner friendly |

Note that these Linux distros don't formally support Apple Silicon chips, so you might not have much success repalcing the OS unless you're working with older hardware that still has Intel chips.

## MacOS Settings
| Setting | Action | Details |
| --- | --- | --- |
| FileVault | [enable](https://support.apple.com/guide/mac-help/protect-data-on-your-mac-with-filevault-mh11785/mac) | Full disk encryption prevents someone from exfiltrating data on your hard drive in the event your computer is seized or stolen. You must save your recovery key in a safe place that’s not on your computer’s hard drive |
| Automatic updates | [enable](https://support.apple.com/guide/mac-help/keep-your-mac-up-to-date-mchlpx1065/mac) | Regular software updates patch vulnerabilities. Pair this with restaring your laptop every day to ensure updates are installed in a timely manner |
| Antivirus | tbd | MacOS has built-in protection tools that help prevent malware from being installed. Here’s an [explanation](https://www.macworld.com/article/670537/do-macs-need-antivirus.html) of those features and their shortfalls. Some options available for MacOS:<br> <ul> <li>[NordVPN Threat Protection Pro](https://nordvpn.com/features/threat-protection/)</li> <li>[Bitdefender](https://www.bitdefender.com/en-us/)</li> <li>[Malwarebytes](https://www.malwarebytes.com/)</li> <li>[Surfshark One](https://surfshark.com/one)</li> </ul> |

## Windows Settings
| Setting | Action | Details |
| --- | --- | --- |
| Bitlocker | [enable](https://support.microsoft.com/en-us/windows/bitlocker-drive-encryption-76b92ac9-1040-48d6-9f5f-d14b3c5fa178) | Full disk encryption prevents someone from exfiltrating data on your hard drive in the event your computer is seized or stolen. You must save your recovery key in a safe place that’s not on your computer’s hard drive |
| Diagnostic data | [disable](https://learn.microsoft.com/en-us/windows/privacy/configure-windows-diagnostic-data-in-your-organization#diagnostic-data-settings) | tbd |
| Improve inking and typing | [disable](https://support.microsoft.com/en-us/windows/speech-voice-activation-inking-typing-and-privacy-149e0e60-7c93-dedd-a0d8-5731b71a4fef) | tbd |
| Tailored experiences | [disable](https://windowsloop.com/change-privacy-settings-in-windows-11/) | tbd |
| Automatic updates | enable | Regular software updates patch vulnerabilities. Pair this with restaring your laptop every day to ensure updates are installed in a timely manner |
| Antivirus | tbd | Windows Defender is built-in and enough for 99% of people. You may wish to supplement it if you’re torrenting or downloading unofficial software. Some options available for Windows:<br> <ul> <li>[NordVPN Threat Protection Pro](https://nordvpn.com/features/threat-protection/)</li> <li>[Bitdefender](https://www.bitdefender.com/en-us/)</li> <li>[Malwarebytes](https://www.malwarebytes.com/)</li> <li>[Surfshark One](https://surfshark.com/one)</li> </ul> |

## Cloud Storage
The safest place your data can be stored is locally on your physical devices. If that’s not an option, it’s possible to improve cloud storage security.

***What to look for:*** End to end encryption and what information could be handed over if subpoenaed.

iCloud, Google Drive, and OneDrive are considered safe, but you may want to activate advanced security settings. This [Wired guide](https://www.wired.com/story/9-tips-cloud-storage-security/) is a good starting point.
- [iCloud security overview](https://support.apple.com/en-us/102651)
- [Google Drive key security controls](https://cloud.google.com/docs/security/overview/whitepaper#key_security_controls)
- [OneDrive security overview](https://learn.microsoft.com/en-us/sharepoint/onedrive-privacy-security-overview)

These companies are required to comply with local regulations if subpoenaed. Assume anything stored in the cloud owned by a US-based company is under the purview of the US government. Consider manually encrypting sensitive files/folders. Use a long, complex password and store it in a fire safe AND password manager.
- [encrypt on Windows](https://support.microsoft.com/en-us/windows/how-to-encrypt-a-file-1131805c-47b8-2e3e-a705-807e13c10da7)
- [encrypt using 7zip](https://info.lse.ac.uk/staff/divisions/dts/help/guides-faqs/software/using-7-Zip-to-encrypt-and-decrypt-files)
- [encrypt on MacOS](https://support.apple.com/guide/mac-help/protect-your-mac-information-with-encryption-mh40593/mac)

## Word Processors
There are many options out there who aren't Google or Microsoft.

| Provider | Details |
| --- | --- |
| [Proton Drive](https://drive.proton.me/) | Encrypted email and documents |
| [CryptPad](https://cryptpad.fr/) | Open source encrypted documents |
| [Grist](https://www.getgrist.com/) | Open source encrypted spreadsheets that can be self-hosted |

# Travel
If you're an American citizen traveling in the U.S., you can request that TSA not take your photo at the airport. They cannot bar you from entering or leaving the country if you opt out.

# Email
To start, do not use email to engage in sensitive conversations. Email was not designed to be secure. Engage in sensitive conversations in person or over secure messaging apps like Signal.

| Action | Details |
| --- | --- |
| Email masking | <ul> <li>[Firefox Relay](https://relay.firefox.com/)</li> <li>[Apple iCloud+ Hide My Email](https://support.apple.com/guide/iphone/create-and-manage-hide-my-email-addresses-iphcb02e76f7/ios)</li> </ul> |
| Newsletters | tbd |
| Multiple accounts | I recommend one email address to use professionally (resume, job apps, etc). Then use other email accounts for everything else. e.g. relay services, temporary email, etc |
| Privacy-focused options | <ul> <li>[ProtonMail](https://mail.proton.me/)</li> <li>[Startmail](https://www.startmail.com/)</li> </ul> |
| Temporary options | <ul> <li>[Emailnator](https://www.emailnator.com/)</li> <li>[10 minute mail](https://10minutemail.com/)</li> </ul> |
| Delete sensitive documents | Google was found to be snooping in users' gmail accounts. Many people use their email to store sensitive documents. Once you've downloaded a document, delete the email |

# Resources
Here are some great resources if you’d like to learn more.
- [Electronic Frontier Foundation](https://www.eff.org/)
  - [EFF Security Starter Pack](https://ssd.eff.org/playlist/want-security-starter-pack)
- [Privacy Rights Clearinghouse](https://privacyrights.org/)
- [The Digital Standard](https://thedigitalstandard.org/)
- [Surveillance Technology Oversight Project](https://www.stopspying.org/)
- [The Hitchhiker’s Guide to Online Anonymity](https://anonymousplanet.org/guide/)
- [IntelTechniques](https://inteltechniques.com/)
- [Privacy Guides](https://www.privacyguides.org/en/)
- [Electronic Privacy Information Center](https://epic.org/)

# What else can I do?
There are many, many reasons to contact the politicians who represent you. Stronger privacy laws could have a significant impact on reducing the amount of our personal information gets sold to advertisors. Contact your local representatives first - local politics is where change starts. Find your federal and state elected officials [here](https://www.usa.gov/elected-officials/).

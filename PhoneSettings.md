
# Table of Contents

1. [Basics](#basics)
2. [iPhone](#iphone-settings)
3. [Android](#android-settings)
4. [Useful apps](#useful-apps)
5. [Apps to avoid](#apps-to-avoid)

# Basics
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
| Daily restart | Ensures updates are installed |
| Automatic updates | Regular software updates patch vulnerabilities. The latest versions may foil tools like Cellebrite and GrayKey | 
| Public activity | Turn off your public activity on apps like Venmo. There's no good reason for your transations to be public. This activity can be used to tie you to others. [Instructions](https://www.wikihow.com/Delete-Venmo-History) | 
| Tracking | tbd |
| Location services | Disable location services by default for apps that don't require your location, then set other apps to "turn on while using" for apps that require your location in the moment like maps, food delivery, or rideshares |
| Biometrics | If you don't need biometric authentication (Face ID, fingerprint), it's a good idea to not configure them. Some phones allow you to customize how frequently you're prompted for your passcode. Unfortunately some advanced security settings are unavailable without biometric authentication enabled |

## Phone Number Masking
Alternative to giving your actual phone number out. This Proton [blog post](https://protonvpn.com/blog/protect-your-privacy-with-second-phone-number-app/) offers tips on what to look for.

Some examples:
- [Firefox Relay](https://relay.firefox.com/)
- [Google Voice](https://voice.google.com/u/0/about)
  - not the best option if you're trying to fully eliminate Google from your life as it requires you to have a Google account

## iPhone Settings
| Setting | Action | Details |
| --- | --- | --- |
| Advanced Data Protection | [enable](https://support.apple.com/en-us/108756) | Note this is only available if you have Face ID turned on. This feature configures E2EE encryption for your entire iCloud, including reminders, iMessage, backups, and more |
| Push notifications | consider disabling | Push alerts from apps can be [tied to your identity](https://www.washingtonpost.com/technology/2024/02/29/push-notification-surveillance-fbi/). If you leave them turned on, you should [turn off notification previews while your phone is locked](https://www.lifewire.com/turn-off-message-preview-iphone-4175842) |
| 2FA | [enable](https://support.apple.com/guide/iphone/use-two-factor-authentication-iphd709a3c46/ios) | tbd |
| Security key | [configure](https://support.apple.com/en-us/102637) | A security key is a more secure 2FA option than OTP |
| Account Recovery | [enable](https://support.apple.com/en-us/109345) | An option you can use if you lose access to your account or it's compromised |
| Face ID / Passcode | <ul> <li>[use a 6 digit passcode](https://support.apple.com/en-us/119586)</li> <li>[enable ‘Face ID Attention’](https://support.apple.com/guide/iphone/change-face-id-and-attention-settings-iph646624222/ios)</li> <li>[disable control center when the phone is locked](https://www.tomsguide.com/how-to/how-to-disable-control-center-on-a-locked-iphone)</li> <li></li> </ul> | tbd |
| Screen Time | [turn off ‘Allow changes to: Passcode & Face ID’](https://www.techbout.com/prevent-others-from-changing-iphone-passcode-87736/) | This disables the ability to make changes to Passcode or Face ID and hides the option from your settings. To increase the effectiveness of this setting, you should set a Screen Time passcode and make sure it’s different from your iPhone passcode. Note: to make changes to Passcode & Face ID, you must turn this setting back on |
| Find My | [enable](https://www.theverge.com/22697218/iphone-apple-ios-15-find-my-how-to) Find My device tracking even when the device is turned off | tbd |
| Location Services | [disable](https://support.apple.com/en-us/102647) | Disable for any app that does not require your location for functionality and use “while using app” for everything else. |
| Allow Apps to Request to Track | [disable](https://support.apple.com/guide/iphone/control-app-tracking-permissions-iph4f4cbd242/ios) | tbd |
| Stolen device protection | [enable](https://support.apple.com/en-us/120340) | tbd |
| Airdrop | [disable](https://support.apple.com/en-us/102647) or set to "Contacts Only" | tbd |
| Advertising ID | tbd | tbd |

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

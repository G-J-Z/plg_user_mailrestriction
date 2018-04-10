# User Mail Restriction Plugin for Joomla
Use this plugin to avoid registration by e-mail address, URL domains and user names. You can insert multiple domains, user names and/or e-mail addresses separated by commas in the plugin parameters. This version is forked from the original 1.0.2 release and released here as 1.0.3. This version is intended if you want to upgrade from 1.0.2, Joomla doesn't allow this without increasing the release number and intend was to keep as much the same as possible.

Standard intended behavior is to blacklist domainnames. Use of a blacklist is less secure and this forked version is to whitelist domains. Other fields are kept the same. Translations are not exact as I only can do the English versions. Also added en-US.

Usage now is to white list. So for example "mail.com,mail.eu" without quotes is your whitelist for domain names.

Reason to use white list is that online too many botnets are active if you have a Joomla site that allow registration of users. Tools with captcha and recaptcha exist but cannot block everything and require updates. With botnets getting smarter you keep fighting the false registrations. This approach is more secure but does force you to add all domains that you allow. So only suitable if you know who you allow to register. If illegal emails are detected you can add them to the blacklist and delete the user. This is unlikely to happen. You can still block individuals.

Original is better if you don't know which domains will be used to register. That approach requires you to review registrations and add domains that you don't want and clean up the user list frequently.

[Official site](https://www.joomlaempresa.es/en/)

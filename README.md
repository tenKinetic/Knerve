# Knerve
A lightweight development server for local static and PHP sites.
> This repository is for Knerve releases. See https://tenkinetic.github.io for details on the software.

* 1.0.10:<br/>
https://github.com/tenKinetic/Knerve/releases/tag/v1.0.10<br/>
 * Changed from .dev to .knerve.
 * Added support for basic authentication. This is currently enabled by editing the settings file. For a given site, add:
 ```
 basicAuth: {
   username: 'u',
   password: 'p'
 }
 ```

* 1.0.9:<br/>
https://github.com/tenKinetic/Knerve/releases/tag/v1.0.9<br/>
 * Fixed path error for static files with query strings.
 * Added default file support for index.php, index.html and index.htm.
 * Extended SSL certificate for 10 years.

* 1.0.8:<br/>
https://github.com/tenKinetic/Knerve/releases/tag/v1.0.8<br/>
 * Fixed xip.io support for network devices.

* 1.0.7:<br/>
https://github.com/tenKinetic/Knerve/releases/tag/v1.0.7<br/>
 * Fixed failure to fully terminate some unserviceable requests.
 * Forwarded all directory level requests if they do not have a trailing slash.
 * Continued startup procedure when starting DNS server results in EADDRINUSE in case the existing server also provides the .dev domain. Future versions will validate the .dev domain when this error is detected.
 * Added ability to edit settings file. MySQL start and stop commands can be edited as well as sites list.

* 1.0.6:<br/>
https://github.com/tenKinetic/Knerve/releases/tag/v1.0.6<br/>
 * Added support for range headers.
 * Added hover state to site background that shows site directory.

* 1.0.5:<br/>
https://github.com/tenKinetic/Knerve/releases/tag/v1.0.5<br/>
 * Added xip.io support. Use sitename.dev.192.168.1.111.xip.io to access a site from other machines on the same network.

* 1.0.3:<br/>
https://github.com/tenKinetic/Knerve/releases/tag/v1.0.3<br/>
 * Added ability to restart PHP servers.

* 1.0.2:<br/>
https://github.com/tenKinetic/Knerve/releases/tag/v1.0.2<br/>
 * Fixed bug with new site ID generation.


* 1.0.1:<br/>
https://github.com/tenKinetic/Knerve/releases/tag/v1.0.1<br/>
 * Restricted to a single running instance.<br/>
 * Added detection of MySQL and ability to stop and start MySQL for installations at /usr/local/mysql that use /usr/local/mysql/support-files/mysql.server.<br/>
 * Resolved logfile error on first run.


* 1.0.0:<br/>
https://github.com/tenKinetic/Knerve/releases/tag/v1.0.0<br/>
 * HTTPS improvements.<br/>
 * Made site names editable.


* 0.1.1 (Public Beta):<br/>
https://github.com/tenKinetic/Knerve/releases/tag/v0.1.1-beta<br/>
 * Improved HTTPS support.


* 0.1.0 (Public Beta):<br/>
https://github.com/tenKinetic/Knerve/releases/tag/v0.1.0-beta

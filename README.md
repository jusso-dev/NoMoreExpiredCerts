<img src="cert.png" height="150px" />

<em>Baby don't cert me, don't cert me .. anymore..</em>

# NoMoreExpiredCerts
Tool to check x.509 certs for expiry dates and alert when they are approaching expiry


## Problem

Don't you hate it when Production goes down because the root CA has revoked a certificate for your site? me too. This tool using ASP.NET Core Hangfire as a task scheduler to remind you when your certificates are approaching expiry.

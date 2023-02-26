AutoPkg Recipes
===============
This repo contains the AutoPkg Recipes used by Route 1337 LLC for managing packages deployed to our Macs via Jamf Pro.

What Is AutoPkg
---------------
[AutoPkg](https://github.com/autopkg/autopkg) is a super handy tool for keeping packages and other configurations in Jamf Pro up to date without manually needing to manage them.  
You can also use [AutoPkgr](https://github.com/lindegroup/autopkgr) for some basic management via a GUI interface to make things even easier.

Dependencies
------------
For deploying packages to Jamf Pro we are relying on the [JamfUploader by Graham Pugh](https://github.com/grahampugh/jamf-upload)

Testing
-------
Due to the nature of these recipes, all testing is done manually.  
[TESTING.md](TESTING.md) contains details and instructions for testing. 

Current Recipes
---------------

| Package                           | Purpose                 | Deployed To Jamf Pro |
|-----------------------------------|-------------------------|----------------------|
| [Cloudflare WARP](CloudflareWARP) | Zero Trust "VPN" client | Yes                  |

Donate To Support These Recipes
-------------------------------
Route 1337 LLC's open source code heavily relies on donations. If you find these AutoPkg Recipes useful, please consider using the GitHub Sponsors button to show your continued support.

Thank you for your support!

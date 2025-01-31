# Firefox Nightly Build for Secure Credential Provision

This modified Firefox Nightly version was developed within the scope of my bachelor thesis to test the [Experimental _Secure Credential Provision_ Extension](https://github.com/1rneh/secure-credential-provision-extension#readme). This setup only servers as proof of concept.

---

Check out the [changeset](https://hg.mozilla.org/try/rev/25f5d34f0436efd359f071fda13fbf906c24425a) to see what the modifications entail.

---

## Installation options

### 1. Option: Include files in your local build

1. If you have a local build of Firefox Nightly, just exchange the files from the directory _local-build_ with the ones from your local Nightly build.

   **all.js**: modules/libpref/init/all.js\
   **LoginHelper.jsm**: toolkit/components/passwordmgr/LoginHelper.jsm\
   **LoginManagerParent.jsm**: toolkit/components/passwordmgr/LoginManagerParent.jsm\
   **LoginManagerPrompter.jsm**: toolkit/components/passwordmgr/LoginManagerPrompter.jsm

2. Rebuild and run the application

### 2. Option: Download the installation file for your operating system

The installation files for Windows, Linux and OS X are provided in the respective directories in this repository.\
The builds were generated on [Mozilla’s automation servers](https://treeherder.mozilla.org/jobs?repo=try&revision=ab7b9ca181abb711760e81f82b6c420cea3141e8).

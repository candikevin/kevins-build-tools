# kevin's build tools

I'm using these to pull code from various git branches, build candi\_powertools\_app, insert information about the git repos into index.html, and push code to SVN.

These tools should go away in Candi's 3.5 release, but they keep getting bigger, so it's time to get them in version control.

They assume that the following directories exist (at the root of the repo, e.g. next to `update`):

    candi_powertools_app/
    cloud-backend-develop/
    cloud-backend-release-3.4/
    cloud-backend-removemongo/
    PublicWeb-develop/
    PublicWeb-release-3.4/
    PublicWeb-removemongo/



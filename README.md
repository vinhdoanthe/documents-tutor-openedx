# Documentation
## Steps to upgrade tutor and open edx
Install and config old version of tutor and edx-platform
- [x] Install `tutor` 15.3.7
- [ ] Config tutor using external volumes for `edx-platform`, version `olive.master`
- [ ] Add some modifications to `edx-platform`

Upgrade tutor and code
- [ ] Update tutor to 16.0.3
- [ ] Checkout `edx-platform` to `palm.master`, rebase code to apply modifications to new code base
- [ ] Run necessary commands to build and start tutor applications

[Detail tutorial](./upgrade-tutor-and-edx-version.md)

## Add cms theme
- [x] Create a theme for cms
- [ ] Apply the theme to Open edX
- [ ] Add modifications to change logo(s) and text of the footer and the header
- [ ] Rebuild images and run necessary commands

## Configure for certification isssuing


## Aug 08

### Update payment page
One thing: On payment page, could you do test purchase? On "Thank You" page after successful purchase, I need the steps to edit it:



1. the path and file name
2. the deployment steps
3. I need to replace the logo and change the style of "dashboard" text to button



As I do not want to use tutor's logo on my site, and the "dashborad" button is displayed as a text, I plan to change the style

ok?

### Other tasks
- [ ] could you try "tutor images build mfe" on your dev env?
- [ ] by the way, could you also provide me the step to edit the header and footer of CMS today?

## Aug 17
### Need to check
1. check the OPENEDX_RELEASE version
2. check the tutor version
3. check with Tony whether he made changes to MFE?
### Solutions
solution 1: uninstall MFE then install, and rebuild

solution 2: install node-superagent as suggested in https://discuss.overhang.io/t/tutor-local-quickstart-fails-with-npm-timeout/2947/2

solution 3: update the docker build as suggested in this https://github.com/overhangio/tutor-mfe/issues/125#issuecomment-1549669393

solution 4: OS version as suggested in https://discuss.openedx.org/t/error-service-mfe-failed-to-build-build-failed/7568

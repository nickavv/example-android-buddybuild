# Black Duck CoPilot Android (Gradle)/buddybuild Example

[![BuddyBuild](https://dashboard.buddybuild.com/api/statusImage?appID=59a5724a6749de0001f9e85e&branch=master&build=latest)](https://dashboard.buddybuild.com/apps/59a5724a6749de0001f9e85e/build/latest?branch=master) [![Black Duck Security Risk](https://copilot.blackducksoftware.com/github/repos/BlackDuckCoPilot/example-android-buddybuild/branches/master/badge-risk.svg)](https://copilot.blackducksoftware.com/github/repos/BlackDuckCoPilot/example-android-buddybuild/branches/master)

Shows a working setup for using Black Duck CoPilot to analyze the risk of project dependencies

## buddybuild setup
The `buddybuild_postbuild.sh` script has been modified to upload generated dependency data to Black Duck CoPilot:
```sh
bash <(curl -s https://copilot.blackducksoftware.com/ci/buddybuild/scripts/upload)
```

## Yahoo Axis Forged Packaged

Yahoo! accidentally included their private certificate file inside the [Axis](http://axis.yahoo.com) Chrome extension

[![screenshot](https://img.skitch.com/20120524-xnwqgtrsq6g5f7tupwb8i3myq.jpg)](https://img.skitch.com/20120524-xnwqgtrsq6g5f7tupwb8i3myq.jpg)

This project is a test package signed using the certificate. Source is in `src` a test build signed with the cert is in `build`

## Install

To test install the package click on the raw link:

[https://github.com/nikcub/yahoo-spoof/raw/master/build/yahoo-spoof.crx](https://github.com/nikcub/yahoo-spoof/raw/master/build/yahoo-spoof.crx)


All that [it does](https://github.com/nikcub/yahoo-spoof/blob/master/src/content.js#L2) is trigger a javascript alert on every page load on every site/domain.

## Implications

Working that out now. I *think* that if you can DNS hijack the update URL a forged package would update and install silently. 
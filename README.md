# Binnen-I-be-gone-safari
How to Binnen-I be gone chrome extension to safari

1) Install on chrome: https://chrome.google.com/webstore/detail/binnen-i-be-gone/ginkajgcbeolbiflkjomlkcdapbegaff?hl=de
2) cd ~/Library/ApplicationSupport/Google/Chrome/Default/Extensions
3) mkdir -p ~/Projects/binnenIbeGone
4) cp -r ginkajgcbeolbiflkjomlkcdapbegaff/* ~/Projects/binnenIbeGone
5) cd ~/Projects/binnenIbeGone
6) xcrun safari-web-extension-converter 2.7_0 (or whatever the folder is called then )
7) XCODE opens. Press RUN
8) Either: "Allow Unsigned Extensions" in Safari Developer Menu or build the package with signature as a developer.
9) Active Extension in Safari
10) Enjoy your german texts in proper german.

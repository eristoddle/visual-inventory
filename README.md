#Ionic2/Electron Starter Project

While it seemed straightforward to do this at first, there were a few quirks that made me create this repo in case I have to do it again. It saves a few hours.

So using Ionic2 and Electron you can build applications using Ionic2/Angular2 in one code base that compiles into applications for:

- Windows
- OSX
- Linux
- Android
- IOS
- Web

It's a work in progress. So feel free to fork and do pull requests.

# start ionic and electron with autoreload,
ionic serve
# open another terminal window for the npm run command!
npm run-script electron

# use electron in dist
ionic build browser
npm run-script electron dist

# build web, android and ios apps
gulp electron:all

# build windows, linux and os applications
gulp electron:all

##TODO

- task to build all applications with one command
- task to do a full release process, with auto versioning, etc.
- add auto-updating with https://www.npmjs.com/package/electron-builder

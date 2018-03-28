#### Thunkable **Cross-Platform **✕ \(Beta\)

# Release Notes

---

#### Mar 30, 2018

New components

* [Location Sensor](/android/components/location/location-sensor.md) - gets a user's current location and with permission of the user, can track a user's location history, both when the app is open and when it is in the background
* [Spreadsheet](/ios/components/data-storage/spreadsheets.md) by Airtable - gets, uploads, updates and deletes data from the popular spreadsheet service
* [Payment](/ios/components/monetisation/payments.md) by Stripe - enable accepting credit card payments in app powered through Stripe; Each payment is subject to a 4.9% + $0.30 per transaction fee

Platform updates

* Enables opening installed app aka Activity Starter on Android via a Control block
* Blocks now includes zoom control and a better location for the trash can
* Advanced properties reorganized into categories

---

#### Mar 20, 2018

Platform updates

* [Custom app package name ](/ios/components/app-settings/bundle-id-package-name.md)/ bundle ID now supported for both Android and iOS; app icon also supported for Android
* [Make a copy](/ios/components/make-copy.md) of your project aka checkpoint in one click
* Tracking of project [shares](/ios/6-share.md) now available on project page; share links no longer require a user to be logged in

Component updates

* Properties now set / changeable in blocks including all Text / Background Color properties for visible components and Language properties for [Translator](/ios/components/voice/translator.md), [Text to Speech](/ios/components/voice/text-to-speech.md) and [Assistant](/ios/components/voice/assistant.md)
* Transparent color now available as a color property across all visible components
* Easy select and upload via Picture property for [Image](/android/components/image/README.md) component

Bug fixes

* [Function](/ios/blocks/functions.md) blocks now work again
* Blocks strings now accepted as numbers
* Changing dropdown component in blocks or duplicating blocks now keeps the same property

---

#### Mar 6, 2018

New component

* [Sign In](/ios/components/screen-layout/authentication/sign-in.md) powered by Firebase - support for email sign-in; set-up requires entering in an API key and database URL into app settings
* [Media Database](/ios/components/data-storage/media-db.md) powered by Cloudinary - support for image, audio and video upload

Component updates

* Most Visible components \(Screen, TextInput, Label, Column, Row, Image, ListViewer, WebViewer, Maps, Google Maps\) - advanced properties including padding, margin, border & user location \(Maps / Google Maps\) added 
* [Realtime DB](/ios/components/data-storage/realtime-db.md) powered by Firebase - changes set-up from adding a .plist file to entering in an API key and database URL into app settings

Platform updates

* Installing an Android .apk no longer requires uninstalling the Thunkable companion app

* Easier discoverability of uploading files \(now in the bottom left under the component tree

* Error message when dropping a Navigator or Screen to the Phone previewer; they can only be added to the Visible components section of the tree

* Small updates to sharing by link and notifications during download and publish

---

#### Feb 23, 2018

Start of Thunkable Cross-Platform **✕ **public beta

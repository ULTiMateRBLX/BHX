# BHX
- Awesome tweak for X

# Features
- Download Videos (even if account private).
- Custom Tab Bar
- No history feature.
- Hide topics tweet feature.
- Disable video layer caption.
- Padlock.
- Font changer.
- Enable the new UI of DM search.
- Auto load photos in highest quality feature.
- Undo tweet feature.
- Theme (like X Premium).
- App icon changer
- X Circle feature.
- Copying profile information feature.
- Save tweet as an image.
- Hide spaces bar.
- Disable RTL.
- Always open in Safari.
- Translate bio.
- Disable new tweet style (A.K.A edge to edge tweet)
- Enable voice tweet and voice message in DM.
- Hide promoted tweet from the timeline.
- Confirm alert when hit the tweet button.
- Confirm alert when hit like button.
- Confirm alert when hit follow button.
- FLEX for debugging.

| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="1.png"> |  <img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="2.png">|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="3.png">|
|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="4.png">  |

# How to build the project

## Using GitHub Actions

- Fork this repository.
- Open "Actions" tab on your fork, and press "I understand my workflows, go ahead and enable them" to proceed.
- Select "Build and Release BHX" workflow.
- Press "Run workflow" menu, and enter parameters in the popup that appears.
  - Don't forget to choose deployment format (`rootfull`, `rootless`, `sideloaded`, `trollstore`).
  - For `sideloaded` and `trollstore` builds, a valid URL of decrypted IPA is required. For `rootfull` and `rootless` builds, enter any value (it won't be used).
  - For other parameters, defaults are usually sufficient.
- Press "Run workflow" button, and after a while you should see build artifacts on "Releases" page.

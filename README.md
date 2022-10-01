<p align="center"><img src="https://raw.githubusercontent.com/wger-project/wger/master/wger/core/static/images/logos/logo.png" alt="project-image" width='200'></p>
<h1 align="center" id="title">WGER-(Workout Manager)</h1>



<p id="description">wger is a free open-source flutter application that manages and tracks/logs your exercises and personal workouts weight and diet plans.</p>

<p align="center"><img src="https://img.shields.io/github/license/wger-project/flutter" alt="shields"><img src="https://img.shields.io/github/issues/wger-project/flutter" alt="shields"><img src="https://img.shields.io/github/stars/wger-project/flutter" alt="shields"></p>

<h2>🚀 Promo</h2>

h

https://user-images.githubusercontent.com/83128918/193412644-b0af4d1a-8912-4e8b-9110-881001b28710.mp4



<h2>Project Screenshots</h2>
<p align="center">
<img src="https://i.postimg.cc/wTM5zv3R/1.png" alt="project-screenshot" width="200" height="400/">

<img src="https://i.postimg.cc/PrfH5Gkw/2.png" alt="project-screenshot" width="200" height="400/">

<img src="https://raw.githubusercontent.com/wger-project/flutter/master/fastlane/metadata/android/en-US/images/phoneScreenshots/02%20-%20workout%20log.png" alt="project-screenshot" width="200" height="400/">

<img src="https://raw.githubusercontent.com/wger-project/flutter/master/fastlane/metadata/android/en-US/images/phoneScreenshots/04%20-%20nutritional%20plan.png" alt="project-screenshot" width="200" height="400/">
</p>
  
  ## Installation
[<img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png"
      alt="Get it on Google Play"
      height="80">](https://play.google.com/store/apps/details?id=de.wger.flutter)
[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png"
     alt="Get it on F-Droid"
     height="80">](https://f-droid.org/packages/de.wger.flutter/)
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Track your Workouts
*   Nutrition Diary
*   Record Measurements
*   Option to Self Host

<h2>🍰 Contribution Guidelines:</h2>

👋Want to contribute to wger-project/flutter? If you have a bug or an idea browse the open issues before opening a new one. You can also take a look at the Open Source Guide. If you're ready to tackle some open issues we've collected some good first issues for you.

  ## Development

### 1
Install the [wger server](https://github.com/wger-project/wger), the easiest way
is to start the development docker-compose: <https://github.com/wger-project/docker>

Alternatively, you can use one of our test servers, just ask us for access.

### 2
Install Flutter, and all its dependencies, and create a new virtual device:
<https://flutter.dev/docs/get-started/install>.

The app currently uses flutter 3.3

### 3
Create a new file ``wger.properties`` in ``android/fastlane/envfiles``:

```properties
WGER_API_KEY=123456
```

To just run/develop the app it only needs to have any value for WGER_API_KEY, but
you need a correct value if you want to register via the app. For this, you need
to allow (a probably dedicated) user on the wger server to register users on its
behalf. For this, generate an API KEY by visiting <http://localhost:8000/de/user/api-key>
on your local instance and then run ``python3 manage.py add-user-rest the username``

You can later list all the registered users with: ``python3 manage.py list-users-api``  


### 4
Start the application with ``flutter run`` or use your IDE
(please note that depending on how you run your emulator you will need to change the IP address of the server)

You can run the tests with the ``flutter test``


## Translation
Translate the app to your language on  [Weblate](https://hosted.weblate.org/engage/wger/).

[![translation status](https://hosted.weblate.org/widgets/wger/-/mobile/multi-blue.svg)](https://hosted.weblate.org/engage/wger/)
  
<h2>💻 Built with</h2>

Technologies used in the project:

* ![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)

<h2>🛡️ License:</h2>

The application is licensed under the GNU Affero General Public License 3 or later
(AGPL 3+) with an app store exception.

As additional permission under section 7, you are allowed to distribute the
software through an app store, even if that store has restrictive terms and
conditions that are incompatible with the AGPL, provided that the source is also
available under the AGPL with or without this permission through a channel without
those restrictive terms and conditions.


The initial exercise and ingredient data is licensed additionally under one of
the Creative Commons licenses, see the individual exercises for more details.

<h2>💖Like our work?</h2>

If you like what we do here at WGER feel free to sponsor us on Github Sponsors

<h2>☎️ Contact</h2>

Feel free to get in touch if you found this useful or if something didn't behave
as expected. We can't fix what we don't know about, so please report liberally.
If you're not sure if something is a bug or not, feel free to file a bug anyway.

* **Discord:** <https://discord.gg/rPWFv6W>
* **Issue tracker:** <https://github.com/wger-project/flutter/issues>
* **Twitter:** <https://twitter.com/wger_project>


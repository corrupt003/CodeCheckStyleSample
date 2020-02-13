# CodeCheckStyleSample
A sample to use checkstyle and ktlint in Android Studio.

## To use Checkstyle
1. Add Checkstyle plugin.
2. See the checkstyleLocal Gradle task in app/build.gradle.
3. Add the config file. See check folder.

## To use ktlint
1. Add ktlint dependency.
2. See the ktlintLocal Gradle task in app/build.gradle.
3. Optional: .editorconfig to customize some rules.

## To check code before commit
See the pre-commit file in check folder and installGitHooks Gradle task in app/build.gradle.

For more details, please read the post in [Medium](https://medium.com/@corrupt003/run-checkstyle-and-ktlint-in-android-studio-4ca409e381a0) (written in Chinese).

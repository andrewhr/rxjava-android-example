language: android
android:
  components:
    - build-tools-19.0.3
    - $ANDROID_TARGET
    - sys-img-armeabi-v7a-$ANDROID_TARGET
    - extra-android-support
    - extra-android-m2repository
    - extra-google-m2repository
env:
  matrix:
    - ANDROID_TARGET=android-19  ANDROID_ABI=armeabi-v7a
before_script:
  - echo no | android create avd --force -n test -t $ANDROID_TARGET --abi $ANDROID_ABI
  - emulator -avd test -no-skin -no-audio -no-window &
  - android-wait-for-emulator
  - adb shell input keyevent 82 &

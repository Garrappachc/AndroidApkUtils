# AndroidApkUtils
#### CMake functions to help deploy C and C++ applications for Android with some Qt goodies.

### What is that?
Deploying apps for Android devices is somehow a pain in the neck. Either we use QtCreator and tools bundled there or try to make use of `androiddeployqt` on our own.

### Yeah, we have androiddeployqt!
That is true and there are great CMake scripts that use it, like [qt-android-cmake](https://github.com/LaurentGomila/qt-android-cmake). But `androiddeployqt` is not as flexible as I wish it was. You cannot change the contents of apk package very much, as it adds some hard-coded prefixes and variables, not to mention it deploys much more than you really need, making the app a little bit heavy. Apart from that, `androiddeployqt` is for Qt projects only. This script tries to do everything CMake way.

### Great, how to use it?
I am preparing some more extensive documentation for it. As for now, you can read some drafts in the `AndroidApkUtils.cmake` file and refer to [CMakeLists.txt file](https://github.com/Vatsinator/Vatsinator/blob/develop/dist/android/CMakeLists.txt) in my project.

### Contact
Michał Garapich garrappachc@gmail.com

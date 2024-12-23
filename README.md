# Arpeggigator

## Developer Documentation

https://steinbergmedia.github.io/vst3_dev_portal/pages/index.html

---

## Push existing project to GitHub

https://www.digitalocean.com/community/tutorials/how-to-push-an-existing-project-to-github

---

## Issues and solutions

### Cmake profile not defined
Download CMake locally in Terminal

CLion > Create new project > C++ Executable

Files are automatically generated. File > Reload CMake Project and Build > Build Project.

---

### CMakeLists.txt

Manually configure like so: https://steinbergmedia.github.io/vst3_dev_portal/pages/Tutorials/Creating+a+plug-in+from+scratch.html#building-the-cmakeliststxt

Or use the project generator, which can be found VST_SDK > VST3_Project_Generator > macOS > VST3_Project_Generator: https://steinbergmedia.github.io/vst3_dev_portal/pages/Tutorials/Generate+new+plug-in+with+Project+Generator.html
It will make the project in XCode, but just open it up in CLion.
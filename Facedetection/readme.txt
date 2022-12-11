Build:
=====
mkdir build
cd build
conan install ..
cmake ..
cmake --build .

Run:
===
./bin/Facedetection -cascade=../haarcascade_frontalface_alt.xml -nested-cascade=../haarcascade_eye_tree_eyeglasses.xml

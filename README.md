# gpt4all-chat

Cross platform Qt based GUI for GPT4All versions with GPT-J as the base
model. NOTE: The model seen in the screenshot is actually the original
GPT-J model.

![image](https://user-images.githubusercontent.com/50458173/230752927-d3e8a37f-dff4-4172-a657-714478400cd5.png)

## Features

* Cross-platform (Linux, Windows, MacOSX, iOS, Android, Embedded Linux, QNX)
* Fast CPU based inference using ggml for GPT-J based models
* The UI is made to look and feel like you've come to expect from a chatty gpt
* Easy to install... The plan is to create precompiled binaries for major platforms with easy installer including model

## Building

* Install Qt 6.x for your platform https://doc.qt.io/qt-6/get-and-install-qt.html
* Install cmake for your platform https://cmake.org/install/
* Clone this repo ```git clone --recurse-submodules https://github.com/manyoso/gpt4all-chat.git```
* ```cd gpt4all-chat
     mkdir build
     cd build
     cmake ..
     cmake --build . --parallel```

## Running

* Simply place the appropriate model file named ```ggml-model-q4_0.bin``` in the same directory as the exe produced above and start the exe

## Contributing

* Pull requests welcome :)

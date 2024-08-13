#### Important NOTE:
**This edgeEngine-SE-Linux repository has been archived and is no longer maintained.**
Please visit our new repository [mimOE-SE-linux](https://github.com/mimik-mimOE/mimOE-SE-Linux) for the latest updates.

# edgeEngine-SE-Linux

edgeEngine-SE-Linux Standard Edition for Ubuntu Linux supports the following platforms and architectures.
1. edgeEngine for generic Linux x86_64 on Intel and AMD for Ubuntu 20.04 and above releases.
2. edgeEngine for Linux-ARM aarch64 for Ubuntu 20.04.2 LTS and above releases on Raspberry Pi 4.
3. edgeEngine for Linux-ARM aarch64 for Ubuntu 22.04.2 LTS and above releases on NVIDIA Jetson including Jetson Orin Nano.

## Before you start


 [explore the developer resources & documentation](https://developer.mimik.com)
 
 [sign up and create a mimik developer console account](https://developer.mimik.com/console/create_account)


## Installation Guide
1. Download the latest desired release for edgeEngine-SE-Linux  [HERE](https://github.com/edgeEngine/edgeEngine-SE-Linux/releases)
2. Create a new directory.
3. Move the package to the newly created directory.
4. Open a terminal and navigate to the newly created directory with the downloaded .tar file.
5. *Untar package (ex:)
   Use the command say 'tar xvf <dowloaded edgeEngine tar file for the desired platform>'
   As an example for X86 Linux Ubuntu, run the following command.

```
tar xvf edgeEngine-SE-linux-developer-x86-v3.10.0.tar
```

6. Run the start script to start edgeEngine
```
./start.sh
```
7. Please visit [Developer Console](https://developer.mimik.com/console/create_account) to create an account and get started with your projects


## Notes:
* A directory may be made after untaring. Navigate into that directory to find the `start.sh` script.
- Do not close the terminal window where edgeEngine is running. Closing this window will terminate the edgeEngine process.
- To stop edgeEngine, in the terminal where it is running, either close the terminal or use the keyboard shortcut CTRL + C.

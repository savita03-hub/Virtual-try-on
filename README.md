#### Download unity
- Download Link: https://unity3d.com/get-unity/download
- We can download unity with different ways (select download unity Hub)
- Once it's done open up the folder that contains this file.
- I agree -> Install -> Finish

After installing unity-hub create unity account by sign in on unity hub

#### Installing unity editor
unity-hub -> installs -> install editor -> official releases -> 2021.3.20f1(lts) install -> check microsoft visual studio community -> check android build support ->  check windows build support -> continue -> install

#### install or import some packages
unity-hub -> create project -> 3d -> window -> package manager -> device simulator -> install

#### Sign in unity

#### Working with vuforia engine for image targets
- Vuforia doveloper portal : https://developer.vuforia.com/
- Sign in 
- All the keys and license managers are present there.
- ** downloads -> Add Vuforia Engine to a Unity Project or upgrade to the latest version **
- This will download the package of vuforia engine for unity
- Unity -> assets -> import package -> custom package -> select the downloaded vuforia package.

#### Datasets and checkpoint links for vton-2d
- python file for results :https://colab.research.google.com/drive/1AntuTyqF6wkxtRk-4gWAfbGBEAKk9-eT?authuser=5
- dataset flder link : https://drive.google.com/drive/folders/1vLR4XOM0miCuLJa-qQ7oo7NP5Qb5D_1H?usp=share_link
- checkpoints folder link : https://drive.google.com/drive/folders/1WyhfmCQc1j3hNEOuZvWHjm0Y2HMqhWBY?usp=share_link

1. Install the requirements
2. Download/Prepare the dataset
3. Train GMM network
4. Get warped clothes for training set with trained GMM network, and copy warped clothes & masks inside data/train directory
5. Train TOM network
6. Test GMM for testing set
7. Get warped clothes for testing set, copy warped clothes & masks inside data/test directory
8. Test TOM testing set


Final Folder link for training and testing code and results of characteristic-preserving image-based virtual try-on network and virtual try on 3d using unity.
https://drive.google.com/drive/folders/17mhOF6sYYX421NS55mNI1kGM6JXaensJ?usp=share_link






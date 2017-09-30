Local manifest for Meizu M2 Note (LineageOS 14.1)
===========================

Getting Started
---------------

Initialize a repository with LineageOS:

    repo init -u git://github.com/LineageOS/android.git -b cm-14.1
  
Copy "m2note.xml" under android_src/.repo/local_manifests  

    repo sync   


Build the code:

    source build/envsetup.sh
    breakfast m2note
    make -j4 bacon showcommands 2>&1 | tee build.log
  

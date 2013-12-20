Getting Started
---------------

To get started with Android/CyanogenMod for golfu, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the CyanogenMod trees, use a command like this:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-10.2
    curl --create-dirs -L -o ~/cm-10.2/.repo/local_manifests/golfu.xml -O -L https://raw.github.com/CyanCom/roomservice/cm-10.2/golfu.xml

Then to sync up:

    repo sync
    

WORK IN PROGRESS. WILL EAT YOUR CAT.

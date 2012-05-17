OpenIntents Convert CSV Repo Manifest
=====================================

This manifest will check out OI Convert CSV and the associated projects. You will
need to use repo (installation instructions can be found at the top of
http://source.android.com/source/downloading.html).

Getting all of the projects is achieved by running the following

    mkdir convertcsv
    cd convertcsv
    repo init -u https://github.com/openintents/convertcsv-repo-manifest.git
    repo sync

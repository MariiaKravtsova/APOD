# Download Astronomy Picture of the Day

APOD is a python3 script that scraps http://apod.nasa.gov for astronomy pictures,
and saves it into a directory.

log.txt shows when the connection was opened and closed, which file was downloaded, and if it was successful.

Personal use: set the pictures as screen savers and desktop wallpapers.

Note: by default the directory for the images is named apod. The directory will be created where the script is being run.
For example if you set cron to run the script, then the apod directory will be created in your home directory. Unless you specified otherwise on line 42.

Release Date: 1/23/2017

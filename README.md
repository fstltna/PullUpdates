# PullUpdates
Downloads a new version of mobius from the master server to the local server and restarts the Hotline process.

Set up cronjob:
        1 */12 * * * /home/hotlineuser/PullUpdates/check4update > /dev/null 2>&1


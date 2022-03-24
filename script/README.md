# Hotfix-Processing Scripts

## `grab_hotfixes.py`

This is the utility which is used to check for EGS hotfixes and
update this repo as-needed.  It currently runs at 15 after the hour via
cron, on a local box of mine.  It populates the main
`hotfixes_current.json` file in the main dir, and also an individual file
inside `point_in_time`.

`requirements.txt` lists the Python dependencies required to run this util.


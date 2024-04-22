# Synology Downloader for Alfred

Creating download tasks in Synology has a lot of frictions. One needs to keeps a Synology page logged in and switch between tabs to start a file download.
This Alfred workflow automate that into simple commands to be invoked anytime without context switching.

## Installation
To install, use the build-workflow.py scripts. You would need python and pip environment pre-installed.
In the end, you will see a `Synology-Downloader.alfredworkflow` file which you can double click to install. 
```bash
git clone https://github.com/buszk/synology-downloader-alfred/
cd synology-downloader-alfred
pip install  docopt
python workflow-build.py .
```

## Supported shortcuts
We currently support the following commands
```
# Download link on Synology
sd <link>
# List download tasks on Synology & copy task ids
sl
# Delete tasks by id
sdel <task_id_list>
```

## Acknowledgement
Thanks to xaozai for the bash script project [ds-cli](https://github.com/xaozai/ds-cli).
Thanks to deanishe and muyuxi for the workflow building [script](https://gist.github.com/deanishe/b16f018119ef3fe951af).

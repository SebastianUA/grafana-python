#  Work with grafana dashboadrs (export and import)
-------------------------------------------------

## Usage

To get a help, run:
 ```$ python3 grafana_dashboards_without_git.py -h```

 Examples:
 ```
 usage: python3 script_name.py {ARGS}

optional arguments:
  -h, --help            show this help message and exit
  --version             show program's version number and exit
  --dash DASHBOARD [DASHBOARD ...], --dashboard DASHBOARD [DASHBOARD ...]
                        Indicate a dashboard(s)
  --gtoken GTOKEN, --token GTOKEN
                        Token of grafana server
  --gurl GURL, --url GURL
                        URL from grafana
  --dir folder, --directory folder
                        Indicate a folder for dashboard(s)
  --i                   Import function
  --import              Import function
  --e                   Export function
  --export              Export function

created by Vitalii Natarov
```

## Export dashboadrs
-------------------
```
$ python3 grafana_dashboards_without_git.py --gtoken YOUR_GRAFANA_TOKEN --gurl YOUR_GRAFANA_URL --e
```

## Import dashboadrs
-------------------
```
$ python3 grafana_dashboards_without_git.py --gtoken YOUR_GRAFANA_TOKEN --gurl YOUR_GRAFANA_URL --i
```

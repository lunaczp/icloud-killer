# <cite>iCloud Universal Tools</cite> 
<p align="center">
    <img width="300" src="assets/41166dada6559cb93c7a4ff0ea681e52.png">
</p>

## Usage
```shell
Usage: icloud.py <options>

Options:
  -u, --username <username>    Your iCloud username or email address
  -p, --password <password>    Your iCloud password (default: use PyiCloud
                               keyring or prompt for password)
  --china-account              Specify the "HOME_ENDPOINT" and
                               "SETUP_ENDPOINT" for the "China Mainland
                               Accounts".
  -d, --directory <directory>  Local directory that should be used for
                               download
  --recent INTEGER RANGE       Number of recent photos to download (default:
                               download all photos)  [x>=0]
  --auto-delete                Scans the "Recently Deleted" folder and deletes
                               any files found in there. (If you restore the
                               photo in iCloud, it will be downloaded again.)
  --modify-olds                Modify the "Created Time" of the old files that
                               already been in the folder.
  --version                    Show the version and exit.
  -h, --help                   Show this message and exit.
```
## <img width="50" src="assets/1c11f0fa22d4e93f8dc179b8ff84791d.png"> Photos Download
```shell
icloud -d /external/SADAM/icloud/photos/ --recent 500
```

```shell
icloud -u <username> -p <password> -d /external/SADAM/icloud/photos/ --recent 500
```


## <img width="50" src="assets/dccb81ba3f0f63e9a50c162007f59c4a.png"> Driver (Files)



## <img width="50" src="assets/ddc3380f93d44a376c586796bb7c16a7.png"> Reminds

## <img width="50" src="assets/4b1d90456b68a8d4d4b91adb39e60b70.png"> Contact



## <img width="50" src="https://www.icloud.com.cn/system/icloud.com/2302Hotfix226/en-us/32f2db22e40a7765c151f4d947c2be50.png"> Location



[//]: # (![]&#40;https://www.icloud.com.cn/system/icloud.com/2302Hotfix226/en-us/32f2db22e40a7765c151f4d947c2be50.png&#41;)

```python
api.iphone.location()
```

```json
{
  'isOld': True,
  'isInaccurate': False,
  'positionType': 'Wifi',
  'secureLocation': None,
  'secureLocationTs': 0,
  'altitude': 0.0,
  'latitude': 43.894873066105184,//纬度
  'longitude': 87.58595865485619,
  //经度
  'horizontalAccuracy': 65.0,
  //水平精度
  'verticalAccuracy': 0.0,
  //垂直精度
  'timeStamp': 1670048465162,
  //时间戳
  'floorLevel': 0,
  'locationType': '',
  'locationFinished': True,
  'locationMode': None
}
```

## links

1. [PyiCloud PyPI Home Page](https://pypi.org/project/pyicloud/)
2. [PyiCloud GitHub Home Page](https://pypi.org/project/pyicloud/) 

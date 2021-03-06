<!-- README.md, PureTV/, <https://github.com/PureTV/PureTV_Helper>
   - author PureTV <Hyperay@Hyperay.cc>
   - test201601031830
  -->

# PureTV_Helper 1.0


## Description

`PureTV_Helper` is used to get video information (video file download URL) from some web sites. 

**Supported** (5)

| site | quality | format | method | `--more` mode |
| :--- | :------ | :----- | :----- | :------------ |
| *271*     | `4K`                   | *flv*              | `pc_flash_gate`            | *first json* |
| *letv*    | `1080p`                | *ts* (m3u8), *mp4* | `pc_flash_gate`, `flvsp`   | *vid*        |
| *hunantv* | `720p`                 | *m3u8*, *mp4*      | `pc_flash_gate`, `flvsp`   | *vid*        |
| *tvsohu*  | `4K` (h265)            | *mp4*              | `pc_flash_gate`, `flvsp`   | *first json* |
| *pptv*    | *high bitrate* `1080p` | *mp4*              | `pc_flash_gate`, `android` | *vid*        |


**TODO**

+ TODO


## Install

`PureTV_Helper` runs under `python 3.5`. 
<https://www.python.org/>


## Usage

```
$ ./parsev --help
Usage: parsev [OPTION]... URL
PureTV_Helper: get video info from some web sites. 

  -i, --min HD       set min hd number for video formats
  -M, --max HD       set max hd
      --i-min INDEX  set min index number for part video files
      --i-max INDEX  set max index
  
  -e, --extractor EXTRACTOR  set extractor (and extractor arguments)
  -m, --method METHOD        set method (and method arguments)
  
  -o, --output FILE  write result (video info) to file (default to stdout)
      --more FILE    input more info from file to enable more mode
  
  -d, --debug  set log level to debug
  -q, --quiet  set log level to quiet
      
      --help     display this help and exit
      --version  output version information and exit
      --license  show license information and exit

More information online: <https://github.com/PureTV/PureTV_Helper> 
$ 
```


## Tests

Please run `make test` 


## LICENSE

```
$ ./parsev --license
    PureTV : get video info from some web sites. 
    Copyright (C) 2016 PureTV <Hyperay@Hyperay.cc>

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>. 
$ 
```


<!-- end README.md -->



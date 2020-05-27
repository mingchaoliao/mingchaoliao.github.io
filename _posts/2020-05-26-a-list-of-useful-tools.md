---
layout: post
title: "A List Of Useful Tools"
date: 2020-05-26 00:12:46 -0500
---

Recently, when I need to use a certain tool, I found that I always forget the name of the tools I used before. For example, I wanted to move some free space at the end of "D drive" into "C drive" on Windows. I could not remember the name of the tool, although I believe that I did a similar thing years ago. I tried to search on Google. Then I downloaded and tried several apps found online. Some asked for registration. Some were opened with lots of ads. I was frustrated at that moment. To not be frustrated again, I decided to put those useful tools in this post. So that I will have a place to look it up. 

## on Windows
 1. **[DiskGenius](https://www.diskgenius.com/)**: It is a powerful tool with GUI that provides an all-in-one solution for data recovery, disk partition management, and backup for Windows. Most common functionalities are:
    - data recovery: if a file is deleted accidentally, the tool can help to bring it back. 
      > **Note:** The data recovery works if and only if the disk is HDD or SSD with `trim` function disabled. The files will be permanently trimmed as soon as it is deleted when `trim` is enabled for the SSD. 
    - Resize a partition: for expend the partition, it supports space that is not adjacent to it. Many other tools found online do not support this function.
    
    ![](https://www.diskgenius.com/public/images/download_interface.png)
    
 1. **[ThrottleStop](https://www.techpowerup.com/download/techpowerup-throttlestop/)**: A convenient tool to monitor CPU temperature and check CPU overheat reason. It also provides the option to disable the system's overheat protection. 
 
    ![ThrottleStop](https://tpucdn.com/download/images/69_small-v1584122851.png)
 
 1. **[SpaceSniffer](http://www.uderzo.it/main_products/space_sniffer/)**: monitor how disks are used. It is useful to find those large files on the disks.
 
    ![SpaceSniffer](http://www.uderzo.it/main_products/space_sniffer/media/download_screenshot.jpg)
 1. ...
 
## on Linux
 1. **[Glances](https://nicolargo.github.io/glances/)**: a command-line tool that shows system information. It is a top/htop alternative. You will be able to see (not limit to):
    - CPU info
    - memory info
    - network traffic
    - tcp connections
    - disk/IOs
    - sensors
    - processes  
    
    It also provides a web interface and RESTful APIs: `glances -w`
    
    ![glances](https://raw.githubusercontent.com/nicolargo/glances/develop/docs/_static/glances-summary.png)
 1. ...

## on Mac 
...
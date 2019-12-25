<!--- Please do not ask questions or create discussion in the bug tracker. Use https://nukkitx.com -->
<!--- ONLY POST ISSUES WITH A CLEAN SERVER ON THE LATEST VERSION -->
## Generated Bug Report

<!--- DO NOT OPEN A ISSUE IF THIS IS A PLUGIN ERROR -->
PLUGIN ERROR: TRUE

### Expected Behavior
<!--- What would you expect to happen -->


### Actual Behavior
<!--- What actually happened -->


### Steps to Reproduce
<!--- Reliable steps which someone can use to reproduce the issue. Please do not create issues for non reproducible bug! -->


### OS and Versions

* Nukkit Version: git-8088000 
* Java Version: Java HotSpot(TM) Client VM (1.8.0_211-b12)

* Host Configuration: 

| Item | Value |
|:----:|:-----:|
| Host OS | Windows 10-x86 [10.0] |  
| Memory(RAM) | 8.5 GB | 
| Storage Size | 498.8 GB | 
| Storage Type | Disk 0:(avail=50.1 GB, total=486.0 GB) Disk 1:(avail=1.6 GB, total=12.8 GB)  | 
| CPU Type | Intel64 Family 6 Model 55 Stepping 8, GenuineIntel | 
| CPU Core Count | 4 | 

### Crashdump, Backtrace or Other Files

```
java.lang.NullPointerException
	at zen.zchat.Utils.getFormat(Utils.java:59)
	at zen.zchat.NameTag.run(NameTag.java:20)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(Unknown Source)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(Unknown Source)
	at java.lang.Thread.run(Unknown Source)

```
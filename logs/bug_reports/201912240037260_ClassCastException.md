<!--- Please do not ask questions or create discussion in the bug tracker. Use https://nukkitx.com -->
<!--- ONLY POST ISSUES WITH A CLEAN SERVER ON THE LATEST VERSION -->
## Generated Bug Report

<!--- DO NOT OPEN A ISSUE IF THIS IS A PLUGIN ERROR -->
PLUGIN ERROR: FALSE

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
| Storage Type | Disk 0:(avail=50.0 GB, total=486.0 GB) Disk 1:(avail=1.6 GB, total=12.8 GB)  | 
| CPU Type | Intel64 Family 6 Model 55 Stepping 8, GenuineIntel | 
| CPU Core Count | 4 | 

### Crashdump, Backtrace or Other Files

```
java.lang.ClassCastException: java.lang.String cannot be cast to java.util.List
	at cn.nukkit.utils.ConfigSection.getList(ConfigSection.java:367)
	at cn.nukkit.utils.ConfigSection.getList(ConfigSection.java:356)
	at cn.nukkit.utils.ConfigSection.getStringList(ConfigSection.java:388)
	at ru.nukkit.multipass.data.yaml.YamlSource.sectionToPass(YamlSource.java:204)
	at ru.nukkit.multipass.data.yaml.YamlSource.lambda$loadGroups$3(YamlSource.java:142)
	at java.util.LinkedHashMap$LinkedEntrySet.forEach(Unknown Source)
	at ru.nukkit.multipass.data.yaml.YamlSource.loadGroups(YamlSource.java:141)
	at ru.nukkit.multipass.data.Providers$7.onRun(Providers.java:156)
	at cn.nukkit.scheduler.AsyncTask.run(AsyncTask.java:23)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(Unknown Source)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(Unknown Source)
	at java.lang.Thread.run(Unknown Source)

```
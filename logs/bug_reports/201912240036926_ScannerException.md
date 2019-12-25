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
| Storage Type | Disk 0:(avail=50.0 GB, total=486.0 GB) Disk 1:(avail=1.6 GB, total=12.8 GB)  | 
| CPU Type | Intel64 Family 6 Model 55 Stepping 8, GenuineIntel | 
| CPU Core Count | 4 | 

### Crashdump, Backtrace or Other Files

```
while scanning a simple key
 in 'string', line 30, column 2:
     prefix:''
     ^
could not find expected ':'
 in 'string', line 31, column 2:
     suffix:''
     ^

	at org.yaml.snakeyaml.scanner.ScannerImpl.stalePossibleSimpleKeys(ScannerImpl.java:465)
	at org.yaml.snakeyaml.scanner.ScannerImpl.needMoreTokens(ScannerImpl.java:280)
	at org.yaml.snakeyaml.scanner.ScannerImpl.checkToken(ScannerImpl.java:225)
	at org.yaml.snakeyaml.parser.ParserImpl$ParseBlockMappingKey.produce(ParserImpl.java:558)
	at org.yaml.snakeyaml.parser.ParserImpl.peekEvent(ParserImpl.java:158)
	at org.yaml.snakeyaml.parser.ParserImpl.checkEvent(ParserImpl.java:143)
	at org.yaml.snakeyaml.composer.Composer.composeMappingNode(Composer.java:224)
	at org.yaml.snakeyaml.composer.Composer.composeNode(Composer.java:155)
	at org.yaml.snakeyaml.composer.Composer.composeMappingNode(Composer.java:229)
	at org.yaml.snakeyaml.composer.Composer.composeNode(Composer.java:155)
	at org.yaml.snakeyaml.composer.Composer.composeDocument(Composer.java:122)
	at org.yaml.snakeyaml.composer.Composer.getSingleNode(Composer.java:105)
	at org.yaml.snakeyaml.constructor.BaseConstructor.getSingleData(BaseConstructor.java:120)
	at org.yaml.snakeyaml.Yaml.loadFromReader(Yaml.java:450)
	at org.yaml.snakeyaml.Yaml.loadAs(Yaml.java:427)
	at cn.nukkit.utils.Config.parseContent(Config.java:554)
	at cn.nukkit.utils.Config.load(Config.java:160)
	at cn.nukkit.utils.Config.<init>(Config.java:98)
	at cn.nukkit.utils.Config.<init>(Config.java:89)
	at ru.nukkit.multipass.data.yaml.YamlSource.loadGroups(YamlSource.java:140)
	at ru.nukkit.multipass.data.Providers$7.onRun(Providers.java:156)
	at cn.nukkit.scheduler.AsyncTask.run(AsyncTask.java:23)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(Unknown Source)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(Unknown Source)
	at java.lang.Thread.run(Unknown Source)

```
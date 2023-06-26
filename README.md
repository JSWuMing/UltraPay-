# 抄作业党有话说
在下没有空手开发的能力，所以只会抄作业
抄作业能力有限
不过目的已经达到
秉承能用就行
所以 理论上不会再修改了
注意 point会报错 
报错内容 

[00:28:14 WARN]: [UltraPay] Task #21 for UltraPay v1.0.0 generated an exception
java.lang.IndexOutOfBoundsException: Index 2 out of bounds for length 2
        at jdk.internal.util.Preconditions.outOfBounds(Preconditions.java:64) ~[?:?]
        at jdk.internal.util.Preconditions.outOfBoundsCheckIndex(Preconditions.java:70) ~[?:?]
        at jdk.internal.util.Preconditions.checkIndex(Preconditions.java:266) ~[?:?]
        at java.util.Objects.checkIndex(Objects.java:361) ~[?:?]
        at java.util.ArrayList.get(ArrayList.java:427) ~[?:?]
        at org.fastmcmirror.ultrapay.utils.RewardParser$Companion$parseReward$1.invoke(RewardParser.kt:64) ~[UltraPay-1.0.0.jar:?]
        at org.fastmcmirror.ultrapay.taboolib.common.util.ExecutorKt$sync$1.invoke(Executor.kt:20) ~[UltraPay-1.0.0.jar:?]
        at org.fastmcmirror.ultrapay.taboolib.common.util.ExecutorKt$sync$1.invoke(Executor.kt:20) ~[UltraPay-1.0.0.jar:?]
        at org.fastmcmirror.ultrapay.taboolib.platform.BukkitExecutor$submit$7.run(BukkitExecutor.kt:98) ~[UltraPay-1.0.0.jar:?]
        at org.bukkit.craftbukkit.v1_20_R1.scheduler.CraftTask.run(CraftTask.java:101) ~[purpur-1.20.1.jar:git-Purpur-1996]
        at org.bukkit.craftbukkit.v1_20_R1.scheduler.CraftScheduler.mainThreadHeartbeat(CraftScheduler.java:480) ~[purpur-1.20.1.jar:git-Purpur-1996]
        at net.minecraft.server.MinecraftServer.tickChildren(MinecraftServer.java:1507) ~[purpur-1.20.1.jar:git-Purpur-1996]
        at net.minecraft.server.dedicated.DedicatedServer.tickChildren(DedicatedServer.java:487) ~[purpur-1.20.1.jar:git-Purpur-1996]
        at net.minecraft.server.MinecraftServer.tickServer(MinecraftServer.java:1421) ~[purpur-1.20.1.jar:git-Purpur-1996]
        at net.minecraft.server.MinecraftServer.runServer(MinecraftServer.java:1192) ~[purpur-1.20.1.jar:git-Purpur-1996]
        at net.minecraft.server.MinecraftServer.lambda$spin$0(MinecraftServer.java:323) ~[purpur-1.20.1.jar:git-Purpur-1996]
        at java.lang.Thread.run(Thread.java:833) ~[?:?]

        

# Building

* [Gradle](https://gradle.org/) - Dependency Management

The GradleWrapper in included in this project.

**Windows:**

```
gradlew.bat clean build
```

**macOS/Linux:**

```
./gradlew clean build
```

Build artifacts should be found in `./build/libs` folder.

# How to build MC Mod coding environment

------

> This tutorial is based on **Forge**
> 
> Using IDE: IntelliJ IDEA

1. Go to [Minecraft Forge website](http://files.minecraftforge.net), and download any version **Mdk** you want to code with.

![1.png](https://github.com/Zhouyuankun/Start-MC-Mod-Coding-/blob/main/res/1.png)

2. Once complete, you can delete some files that is not essential. But at least preserve these.

![截屏2021-04-04 上午9.08.14.png](/Users/celeglow/Desktop/MC%20build/截屏2021-04-04%20上午9.08.14.png)

3. Get [jdk8](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html) , install it.

![截屏2021-04-05 上午11.18.32.png](/Users/celeglow/Desktop/MC%20build/截屏2021-04-05%20上午11.18.32.png)

4. Modify some files in forge mdk.

**IN build.gradle**

```group
group = The reverse of your domain,last part is the name of your mod
archivesBaseName = your mod name
```

![截屏2021-04-04 上午9.09.01.png](/Users/celeglow/Desktop/MC%20build/截屏2021-04-04%20上午9.09.01.png)

relace all "examplemod" with your mod name, please **exact match** "examplemod" in case you mischange some words contain it)

![截屏2021-04-04 上午9.11.08.png](/Users/celeglow/Desktop/MC%20build/截屏2021-04-04%20上午9.11.08.png)

5. Launch IDEA and OPEN the forge directory as project, open mods.toml(under /src/main/resources/META-INF/mods.toml). Modify or comment contents with red underlines according to yourself. If the parameter is optional, comment it, else modify if needed.

![截屏2021-04-05 上午11.51.04.png](/Users/celeglow/Desktop/MC%20build/截屏2021-04-05%20上午11.51.04.png)

![截屏2021-04-04 上午10.01.40.png](/Users/celeglow/Desktop/MC%20build/截屏2021-04-04%20上午10.01.40.png)

6. Finally modify ExampleMod.java according to yourself

![截屏2021-04-04 上午10.04.20.png](/Users/celeglow/Desktop/MC%20build/截屏2021-04-04%20上午10.04.20.png)

7. Start to see whether it works.

![截屏2021-04-05 上午11.55.01.png](/Users/celeglow/Desktop/MC%20build/截屏2021-04-05%20上午11.55.01.png)

8. Well done!

![截屏2021-04-05 上午11.56.40.png](/Users/celeglow/Desktop/MC%20build/截屏2021-04-05%20上午11.56.40.png)
# Start-MC-Mod-Coding-

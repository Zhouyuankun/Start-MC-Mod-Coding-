# How to build MC Mod coding environment

------

> This tutorial is based on **Forge**
> 
> Using IDE: IntelliJ IDEA

1. Go to [Minecraft Forge website](http://files.minecraftforge.net), and download any version **Mdk** you want to code with.

![1.png](https://github.com/Zhouyuankun/Start-MC-Mod-Coding-/blob/main/res/1.png)

2. Once complete, you can delete some files that is not essential. But at least preserve these.

![2.png](https://github.com/Zhouyuankun/Start-MC-Mod-Coding-/blob/main/res/2.png)

3. Get [jdk8](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html) , install it.

![3.png](https://github.com/Zhouyuankun/Start-MC-Mod-Coding-/blob/main/res/3.png)

4. Modify some files in forge mdk.

**IN build.gradle**

```group
group = The reverse of your domain,last part is the name of your mod
archivesBaseName = your mod name
```

![4.png](https://github.com/Zhouyuankun/Start-MC-Mod-Coding-/blob/main/res/4.png)

relace all "examplemod" with your mod name, please **exact match** "examplemod" in case you mischange some words contain it)

![5.png](https://github.com/Zhouyuankun/Start-MC-Mod-Coding-/blob/main/res/5.png)

5. Launch IDEA and OPEN the forge directory as project, open mods.toml(under /src/main/resources/META-INF/mods.toml). Modify or comment contents with red underlines according to yourself. If the parameter is optional, comment it, else modify if needed.

![6.png](https://github.com/Zhouyuankun/Start-MC-Mod-Coding-/blob/main/res/6.png)

![7.png](https://github.com/Zhouyuankun/Start-MC-Mod-Coding-/blob/main/res/7.png)

6. Finally modify ExampleMod.java according to yourself

![8.png](https://github.com/Zhouyuankun/Start-MC-Mod-Coding-/blob/main/res/8.png)

7. Start to see whether it works.

![9.png](https://github.com/Zhouyuankun/Start-MC-Mod-Coding-/blob/main/res/9.png)

8. Well done!

![10.png](https://github.com/Zhouyuankun/Start-MC-Mod-Coding-/blob/main/res/10.png)


# tpl
Create project form template, such buildSrc plugin

## 1. Install the buildSrc

Install the buildSrc into current folder, copy and past the commands into your terminal.

```bash
echo "$(curl -fsSL https://raw.githubusercontent.com/hacktons/tpl/master/install-buildsrc)" | bash
```

**PS**: *Inspired by the [homebrew](https://brew.sh/) installation way*

Now you will have some generated files:

![](doc/buildsrc-tree.svg)

## 2. Apply the plugin

Apply the plugin into your project.

```groovy
apply plugin: 'com.android.application'
apply plugin: 'hi' // 'hi' is our plugin name 
```

## 3. Happy coding

Now your can build/sync within Android Studio, the buildSrc should just work fine.

![](doc/instruction.png)

 
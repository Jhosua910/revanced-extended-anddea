#### ⚠️ Do not download modules from 3rd party sources like random websites you found on Google. There are many that uses my modules and impersonates ReVanced.

# ReVanced eXtended anddea Magisk Modules and Apks
[![CI](https://github.com/Jhosua910/revanced-extended-anddea/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/Jhosua910/revanced-extended-anddea/actions/workflows/ci.yml)


Get the [latest CI release](https://github.com/Jhosua910/revanced-extended-anddea/releases).

Use [**zygisk-detach**](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music from Play Store if you are using magisk modules. 

<details><summary><big>Features</big></summary>
<ul>
 <li>Support all present and future ReVanced and <a href="https://github.com/anddea/revanced-patches">ReVanced Extended</a> apps</li>
 <li> Can build Magisk modules and non-root APKs</li>
 <li> Updated daily with the latest versions of apps and patches</li>
 <li> Optimize APKs and modules for size</li>
 <li> Modules</li>
    <ul>
     <li> recompile invalidated odex for faster usage</li>
     <li> receive updates from Magisk app</li>
     <li> do not break safetynet or trigger root detections</li>
     <li> handle installation of the correct version of the stock app and all that</li>
     <li> support Magisk and KernelSU</li>
    </ul>
</ul>
Note that the <a href="../../actions/workflows/ci.yml">CI workflow</a> is scheduled to build the modules and APKs everyday using GitHub Actions if there is a change in ReVanced patches. You may want to disable it.
</details>

## Building Locally
### On Termux
```console
bash <(curl -sSf https://raw.githubusercontent.com/j-hc/revanced-magisk-module/main/build-termux.sh)
```

### On Desktop
```console
$ git clone https://github.com/j-hc/revanced-magisk-module
$ cd revanced-magisk-module
$ ./build.sh
```
## Credits
[j-hc](https://github.com/j-hc) for
[zygisk-detach](https://github.com/j-hc/zygisk-detach) and the [script on which this is based on](https://github.com/j-hc/revanced-magisk-module).

[anddea](https://github.com/anddea) for [revanced-extended patches](https://github.com/anddea/revanced-patches). 

[ReVanced](https://github.com/ReVanced) for
[GmsCore](https://github.com/ReVanced/GmsCore/releases) and the initial proyect.

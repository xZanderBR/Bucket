# Zander's Scoop Bucket

<!-- Uncomment the following line after replacing placeholders -->
<!-- [![Tests](https://github.com/<username>/<bucketname>/actions/workflows/ci.yml/badge.svg)](https://github.com/<username>/<bucketname>/actions/workflows/ci.yml) [![Excavator](https://github.com/<username>/<bucketname>/actions/workflows/excavator.yml/badge.svg)](https://github.com/<username>/<bucketname>/actions/workflows/excavator.yml) -->

Bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## Available Tools
- [USB Device Tree Viewer](https://www.uwe-sieber.de/usbtreeview_e.html)
- [GoInterruptPolicy](https://github.com/spddl/GoInterruptPolicy)
- [MouseTester](https://github.com/valleyofdoom/MouseTester)

## How do I install these tools?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add zander https://github.com/xZanderBR/Bucket
scoop install zander/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.

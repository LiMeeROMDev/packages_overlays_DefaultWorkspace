## Default Workspace for Pixel Launcher

This overlay modify default Google Camera package name, which let you pin your custom Google Camera in favorites bar by default.

Of cause, you can pin any other application.

## How to use

Add inherit on your device makefile:

```makefile
$(call inherit-product, packages/overlays/DefaultWorkspace/config.mk)
```
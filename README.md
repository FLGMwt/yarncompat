# yarncompat

Test the top 1000 depended upon packages from npm. For [https://github.com/yarnpkg/yarn/issues/392](https://github.com/yarnpkg/yarn/issues/392)

```
# OS: Windows 10
# Shell: PowerShell

> node -v
v6.7.0
> npm -v
3.10.3
> yarn --version
0.15.1
```

Packages included in the package.json all fail with yarn but not with npm.
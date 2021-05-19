[![codecov](https://codecov.io/gh/szczepix/SimpleTcpPortFinder/branch/master/graph/badge.svg?token=XPKLQ2B5WN)](https://codecov.io/gh/szczepix/SimpleTcpPortFinder)


## Simple Tcp Port Finder (Fork from: [briansworth](https://github.com/briansworth/SimpleTcpPortFinder))

Small module for getting an active / available TCP port numbers.

Helpful if you are wanting to find a usable ephemeral port,
or want to see all TCP ports currently in use.

### Example

Get an available ephemeral TCP port number.

```powershell
Get-InactiveTcpPortNumber -Random
```

```
57992
```

### Example

List all TCP port numbers currently in use.

```powershell
Get-ActiveTcpPortNumber
```

```
53
22
60664
37839
48314
...
```

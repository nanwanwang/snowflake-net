# Snowflake.Net

[![Latest version](https://img.shields.io/nuget/v/Snowflake.Core.svg)](https://www.nuget.org/packages/Snowflake.Core/)

# Usage

```csharp
long id = IdWorker.Instance.NextId();
```
if use different workerId and datacenterId ,can use a config for new IdWorker(x,y) in Idworker class.

A port of  Twitter's [Snowflake](https://github.com/twitter/snowflake)  algorithm to C#.

Snowflake is a service for generating unique ID numbers at high scale.

### License
Apache 2.0

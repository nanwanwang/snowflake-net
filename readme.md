# Snowflake.Net

# Usage

```csharp
long id = IdWorker.Instance.NextId();
```
if use different workerId and datacenterId ,can use a config for new IdWorker(x,x) in Idworker class.

A port of  Twitter's [Snowflake](https://github.com/twitter/snowflake)  algorithm to C#.

Snowflake is a service for generating unique ID numbers at high scale.

### License
Apache 2.0

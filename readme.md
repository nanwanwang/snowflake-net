# Snowflake.Net

[![Latest version](https://img.shields.io/nuget/v/Snowflake.Core.svg)](https://www.nuget.org/packages/Snowflake.Core/)

# Usage

```csharp
var worker = new IdWorker(1, 1);
long id = worker.NextId();
```
`IdWorker` should be instantiated once.Otherwise,there will be repeat.

A port of  Twitter's [Snowflake](https://github.com/twitter/snowflake)  algorithm to C#.

Snowflake is a service for generating unique ID numbers at high scale.

### License
Apache 2.0

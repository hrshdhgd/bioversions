---
layout: page
title: Download
permalink: /download/
---
## Download

This table can be downloaded as structured YAML from
[here](https://github.com/cthoyt/bioversions/blob/main/docs/_data/versions.yml).

## Programmatic Access

You can install the client with `pip install bioversions`.
The following code can be used in your own programs to access the latest database versions.

```python
import bioversions

assert bioversions.get_version('biogrid') == '4.2.192', 'This was true on Dec 5th, 2020!'
```

The source code can be found at [https://github.com/cthoyt/bioversions](https://github.com/cthoyt/bioversions).
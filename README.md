# FE-Configuration

The strucute used for maintaining configuration baselines is:

## TRUNK (initial configuration)
|
|--> Enterprise Configuration (branch)
|.   --> Workstations configuration (json)
|.   --> DXC servers configuration (json)
|.   --> Policy for transiant configurations (E.g.: specific exclusions, enabling/disabling features)
|
|--> CNI configuration (branch)
|.   --> UK configuration baseline (json)
|.   --> US configuration baseline (json)
|
|--> Cloud configuration (branch)
|.   --> Azure baseline (json)
|.   --> OCI baseline (json)

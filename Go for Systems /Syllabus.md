# Go for Systems (short course, \~6 weeks)

**Backbone:** *The Go Programming Language* (Donovan & Kernighan); Go by Example; Go's official concurrency material.

**Topics:** goroutines, channels, context cancellation, gRPC/protobuf, profiling with pprof, writing CLIs and daemons.

**Project**

- **gNMI telemetry collector in Go:** subscribe to streaming telemetry from a containerlab device (SR Linux or cEOS), store it in PostgreSQL or a time-series DB, and alert on link flaps. This maps directly to Apstra device-agent work.

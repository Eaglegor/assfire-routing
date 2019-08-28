# Assfire routing

The main purpose of this repo is to host my experiments in the area of creating the fast routing engine that can be used for automatic logistics scheduling software (Rich VRP solvers).

It has to support:
- query-scoped statistical traffic patterns
- query-scoped realtime traffic data
- query-scoped graph modifications (restricted zones, dynamic edge penalties etc.) 
- turn costs
- road side consideration

It can be possibly be boosted by the GPGPU at the preprocessing and query times.

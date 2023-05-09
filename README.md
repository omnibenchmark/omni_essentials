# omni_essentials

## Aim

This project contains all benchmark-specific resources for `omnibenchmark`.
Each benchmark has a separate subfolder in `schemas` with all relevant schema definitions.
These schema are used by [omniValidator](https://pypi.org/project/omniValidator/) and define all benchmark-specific 
requirements. 
Overall resources such as the mapping of orchestrator urls and benchmark categories can be found in `general`. 

## Contribution

### Missing requirement

Did you find a bug caused by a missing requirement? 
Open an issue or add the missing content as part of a pull request.
Add the corresponding benchmarks tag or directly tag the responsible `benchmarker` in the issue.

### Add requirments of a new benchmark

Benchmark-specific requirements are independent of each other and can be adjusted at any timepoint. 
To get started please fork this project and follow the below steps: 
1. Add the `orchestrator_url`, and all valid `benchmark_names` to `general/benchmark_categories.json` 
2. Generate a new subdirectory in `schemas/` for you benchmark. The name must be one of the valid `benchmark_names` (see 1.)
3. Add all relevant schemas to your benchmark (see next section).
4. Create a pull request with the tag `new_benchmark`  

## Schema checks
...

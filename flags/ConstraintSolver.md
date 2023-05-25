# Stability change report for package `ConstraintSolver`

### Signature `Tuple{typeof(ConstraintSolver.prune!), ConstraintSolver.CoM}`

Commit `921136a`: | => unstable (`ConstraintSolver` at `/tmp/jl_I1cLGvGVyl/src/ConstraintSolver.jl:307`)  
Commit `8e0fca0`: unstable => | (`ConstraintSolver` at `/tmp/jl_2pkDcbcvmz/src/ConstraintSolver.jl:365`)  

### Signature `Tuple{typeof(ConstraintSolver.compress_var_string), ConstraintSolver.Variable}`

Commit `15dff8e`: | => unstable (`ConstraintSolver` at `/tmp/jl_uDCr4FenqN/src/printing.jl:8`)  
Commit `8e0fca0`: unstable => stable (`ConstraintSolver` at `/tmp/jl_2pkDcbcvmz/src/printing.jl:8` => `ConstraintSolver` at `/tmp/jl_C9CjyBS1yB/src/printing.jl:8`)  

### Signature `Tuple{typeof(ConstraintSolver.add2priorityqueue), ConstraintSolver.ConstraintSolverModel, ConstraintSolver.BacktrackObj}`

Commit `10288bb`: nofuel => unstable (`ConstraintSolver` at `/tmp/jl_AtW5w945E3/src/traversing.jl:64` => `ConstraintSolver` at `/tmp/jl_s5U3SBKT0P/src/traversing.jl:64`)  

### Signature `Tuple{typeof(ConstraintSolver.addupd_var_in_inner_model), ConstraintSolver.Optimizer, Int64}`

Commit `8e0fca0`: | => unstable (`ConstraintSolver` at `/tmp/jl_C9CjyBS1yB/src/MOI_wrapper/variables.jl:33`)  

### Signature `Tuple{typeof(ConstraintSolver.get_traverse_strategy)}`

Commit `cfad5ec`: | => unstable (`ConstraintSolver` at `/tmp/jl_wBuvi7UvOd/src/options.jl:18`)  
Commit `22498b8`: unstable => | (`ConstraintSolver` at `/tmp/jl_YlYxI76zip/src/options.jl:21`)  

### Signature `Tuple{typeof(ConstraintSolver.get_inner_model), JuMP.Model}`

Commit `b351b92`: | => unstable (`ConstraintSolver` at `/tmp/jl_SBm5EfCPuN/src/ConstraintSolver.jl:76`)  

### Signature `Tuple{typeof(ConstraintSolver.get_branch_strategy)}`

Commit `20449b2`: | => unstable (`ConstraintSolver` at `/tmp/jl_AtW5w945E3/src/options.jl:16`)  

### Signature `Tuple{typeof(ConstraintSolver.get_branch_split)}`

Commit `45d9898`: | => unstable (`ConstraintSolver` at `/tmp/jl_aFIPKvebEV/src/options.jl:23`)  

### Signature `Tuple{typeof(ConstraintSolver.get_best_bound), ConstraintSolver.CoM}`

Commit `921136a`: | => unstable (`ConstraintSolver` at `/tmp/jl_I1cLGvGVyl/src/ConstraintSolver.jl:426`)  
Commit `8e0fca0`: unstable => | (`ConstraintSolver` at `/tmp/jl_2pkDcbcvmz/src/ConstraintSolver.jl:493`)  

### Signature `Tuple{typeof(ConstraintSolver.constraint_hash), ConstraintSolver.LinearConstraint}`

Commit `7335717`: | => unstable (`ConstraintSolver` at `/tmp/jl_2pkDcbcvmz/src/hashes.jl:5`)  
Commit `76e45db`: unstable => | (`ConstraintSolver` at `/tmp/jl_81AryRCzoR/src/hashes.jl:9`)  

### Signature `Tuple{typeof(ConstraintSolver.simplify), ConstraintSolver.LinearCombination}`

Commit `8e0fca0`: | => unstable (`ConstraintSolver` at `/tmp/jl_C9CjyBS1yB/src/linearcombination.jl:67`)  
Commit `76e45db`: unstable => | (`ConstraintSolver` at `/tmp/jl_81AryRCzoR/src/linearcombination.jl:67`)  

### Signature `Tuple{typeof(ConstraintSolver.get_row), ConstraintSolver.TableSetup, Vector{ConstraintSolver.TableEntry}}`

Commit `b04070d`: | => unstable (`ConstraintSolver` at `/tmp/jl_8dU5OdGdYL/src/TableLogger.jl:146`)  
Commit `ff7131f`: unstable => | (`ConstraintSolver` at `/tmp/jl_APSFEjODqx/src/tablelogger.jl:165`)  

### Signature `Tuple{typeof(ConstraintSolver.get_fixed_rhs), ConstraintSolver.ConstraintSolverModel, ConstraintSolver.Constraint}`

Commit `b351b92`: | => unstable (`ConstraintSolver` at `/tmp/jl_SBm5EfCPuN/src/constraints/linear_constraints.jl:103`)  

### Signature `Tuple{typeof(ConstraintSolver.constraint_hash), ConstraintSolver.IndicatorConstraint}`

Commit `587dbc8`: | => unstable (`ConstraintSolver` at `/tmp/jl_EZyrktAnkj/src/hashes.jl:24`)  
Commit `8d4bd27`: unstable => | (`ConstraintSolver` at `/tmp/jl_EZyrktAnkj/src/hashes.jl:24`)  

### Signature `Tuple{typeof(ConstraintSolver.get_best_bound), ConstraintSolver.ConstraintSolverModel}`

Commit `8e0fca0`: | => unstable (`ConstraintSolver` at `/tmp/jl_C9CjyBS1yB/src/ConstraintSolver.jl:624`)  
Commit `c502afc`: unstable => | (`ConstraintSolver` at `/tmp/jl_ATi3WVqJaH/src/ConstraintSolver.jl:372`)  

### Signature `Tuple{typeof(ConstraintSolver.set_update_backtrack_pq!), ConstraintSolver.ConstraintSolverModel, ConstraintSolver.BacktrackObj}`

Commit `10288bb`: nofuel => unstable (`ConstraintSolver` at `/tmp/jl_AtW5w945E3/src/traversing.jl:34` => `ConstraintSolver` at `/tmp/jl_s5U3SBKT0P/src/traversing.jl:34`)  

### Signature `Tuple{typeof(ConstraintSolver.constraint_hash), ConstraintSolver.BasicConstraint}`

Commit `7335717`: | => unstable (`ConstraintSolver` at `/tmp/jl_2pkDcbcvmz/src/hashes.jl:1`)  
Commit `8e0fca0`: unstable => | (`ConstraintSolver` at `/tmp/jl_2pkDcbcvmz/src/hashes.jl:1`)  

### Signature `Tuple{typeof(ConstraintSolver.constraint_hash), ConstraintSolver.TableConstraint}`

Commit `fc3f4ce`: | => unstable (`ConstraintSolver` at `/tmp/jl_23qDInm1QZ/src/hashes.jl:5`)  
Commit `76e45db`: unstable => | (`ConstraintSolver` at `/tmp/jl_81AryRCzoR/src/hashes.jl:5`)  

### Signature `Tuple{typeof(ConstraintSolver.probe), ConstraintSolver.ConstraintSolverModel}`

Commit `20449b2`: | => unstable (`ConstraintSolver` at `/tmp/jl_AtW5w945E3/src/branching.jl:281`)  

### Signature `Tuple{typeof(ConstraintSolver.get_weak_ind), ConstraintSolver.CoM}`

Commit `db6f3ff`: unstable => stable (`ConstraintSolver` at `/tmp/jl_olylKHSdsL/src/ConstraintSolver.jl:157` => `ConstraintSolver` at `/tmp/jl_CFqdihmHIv/src/ConstraintSolver.jl:163`)  

### Signature `Tuple{typeof(ConstraintSolver.init_constraints!), ConstraintSolver.ConstraintSolverModel}`

Commit `8d4bd27`: partial => unstable (`ConstraintSolver` at `/tmp/jl_EZyrktAnkj/src/MOI_wrapper/constraints.jl:447` => `ConstraintSolver` at `/tmp/jl_81AryRCzoR/src/MOI_wrapper/constraints.jl:500`)  

### Signature `Tuple{typeof(ConstraintSolver.constraint_hash), ConstraintSolver.SingleVariableConstraint}`

Commit `8e0fca0`: | => unstable (`ConstraintSolver` at `/tmp/jl_C9CjyBS1yB/src/hashes.jl:16`)  
Commit `76e45db`: unstable => | (`ConstraintSolver` at `/tmp/jl_81AryRCzoR/src/hashes.jl:20`)  

### Signature `Tuple{typeof(ConstraintSolver.get_inner_model), MathOptInterface.Bridges.LazyBridgeOptimizer{ConstraintSolver.Optimizer}}`

Commit `b351b92`: | => unstable (`ConstraintSolver` at `/tmp/jl_SBm5EfCPuN/src/ConstraintSolver.jl:80`)  

### Signature `Tuple{typeof(ConstraintSolver.prune!), ConstraintSolver.ConstraintSolverModel}`

Commit `8e0fca0`: | => unstable (`ConstraintSolver` at `/tmp/jl_C9CjyBS1yB/src/ConstraintSolver.jl:498`)  

### Signature `Tuple{typeof(ConstraintSolver.bfs_list), ConstraintSolver.TreeLogNode}`

Commit `dd3ee36`: | => unstable (`ConstraintSolver` at `/tmp/jl_wHMPSRylGd/src/logs.jl:46`)  
Commit `8e0fca0`: unstable => partial (`ConstraintSolver` at `/tmp/jl_2pkDcbcvmz/src/logs.jl:46` => `ConstraintSolver` at `/tmp/jl_C9CjyBS1yB/src/logs.jl:53`)  

### Signature `Tuple{typeof(ConstraintSolver.get_best_bound), ConstraintSolver.ConstraintSolverModel, ConstraintSolver.BacktrackObj}`

Commit `10288bb`: nofuel => unstable (`ConstraintSolver` at `/tmp/jl_AtW5w945E3/src/ConstraintSolver.jl:154` => `ConstraintSolver` at `/tmp/jl_s5U3SBKT0P/src/ConstraintSolver.jl:154`)  

### Signature `Tuple{typeof(ConstraintSolver.set_pvals!), ConstraintSolver.ConstraintSolverModel, ConstraintSolver.Constraint}`

Commit `8e0fca0`: | => unstable (`ConstraintSolver` at `/tmp/jl_C9CjyBS1yB/src/ConstraintSolver.jl:357`)  
Commit `8d4bd27`: unstable => partial (`ConstraintSolver` at `/tmp/jl_EZyrktAnkj/src/ConstraintSolver.jl:126` => `ConstraintSolver` at `/tmp/jl_81AryRCzoR/src/ConstraintSolver.jl:126`)  


# Stability change report for package `PowerSimulations`

### Signature `Tuple{typeof(get_timestamp), Type{InfrastructureSystems.TimeSeriesFormatYMDPeriodAsColumn}, CSV.File, Int64}`

Commit `960af70a7`: | => unstable (`InfrastructureSystems` at `/home/jecmejan/.julia/packages/InfrastructureSystems/7B8ZK/src/time_series_formats.jl:143`)  

### Signature `Tuple{typeof(get_timestamp), Type{InfrastructureSystems.TimeSeriesFormatYMDPeriodAsHeader}, CSV.File, Int64}`

Commit `960af70a7`: | => unstable (`InfrastructureSystems` at `/home/jecmejan/.julia/packages/InfrastructureSystems/7B8ZK/src/time_series_formats.jl:161`)  

### Signature `Tuple{typeof(PowerSimulations.get_jump_model), OperationsProblem}`

Commit `16e1b453e`: | => unstable (`PowerSimulations` at `/tmp/jl_w7EnyVch0r/src/core/operations_problem.jl:213`)  

### Signature `Tuple{typeof(PowerSimulations.ps_cost!), PowerSimulations.PSIContainer, Symbol, String, Float64, Float64, Float64}`

Commit `16e1b453e`: | => unstable (`PowerSimulations` at `/tmp/jl_w7EnyVch0r/src/devices_models/devices/common/cost_functions.jl:25`)  
Commit `960af70a7`: unstable => | (`PowerSimulations` at `/tmp/jl_qF8xwrSnkF/src/devices_models/devices/common/cost_functions.jl:25`)  

### Signature `Tuple{typeof(PowerSimulations.get_interval), PowerSimulations.SimulationStoreStageParams}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/simulation_store.jl:41`)  

### Signature `Tuple{typeof(PowerSimulations._get_pwl_vars_container), PowerSimulations.PSIContainer}`

Commit `960af70a7`: | => unstable (`PowerSimulations` at `/tmp/jl_YL6LKhK5mH/src/devices_models/devices/common/cost_functions.jl:108`)  

### Signature `Tuple{typeof(PowerSimulations.ps_cost), PowerSimulations.PSIContainer, Symbol, String, Float64, Float64, Float64}`

Commit `bff50b7ff`: | => unstable (`PowerSimulations` at `/tmp/jl_0Xu9ILEhgb/src/devices_models/devices/common/cost_functions.jl:30`)  
Commit `16e1b453e`: unstable => | (`PowerSimulations` at `/tmp/jl_SzEjoHszaJ/src/devices_models/devices/common/cost_functions.jl:32`)  

### Signature `Tuple{typeof(PowerSimulations.ps_cost!), PowerSimulations.PSIContainer, Symbol, String, PowerSystems.VariableCost{Float64}, Float64, Float64}`

Commit `16e1b453e`: | => unstable (`PowerSimulations` at `/tmp/jl_w7EnyVch0r/src/devices_models/devices/common/cost_functions.jl:55`)  
Commit `960af70a7`: unstable => | (`PowerSimulations` at `/tmp/jl_qF8xwrSnkF/src/devices_models/devices/common/cost_functions.jl:55`)  

### Signature `Tuple{typeof(PowerSimulations._read_length), Type{PowerSimulations.OptimizerStats}, PowerSimulations.HdfSimulationStore}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/hdf_simulation_store.jl:550`)  

### Signature `Tuple{typeof(PowerSimulations.get_timeseries), PowerSimulations.DeviceTimeSeriesConstraintInfo}`

Commit `960af70a7`: stable => unstable (`PowerSimulations` at `/tmp/jl_qF8xwrSnkF/src/devices_models/devices/common/constraints_structs.jl:49` => `PowerSimulations` at `/tmp/jl_YL6LKhK5mH/src/devices_models/devices/common/constraints_structs.jl:49`)  
Commit `407ed31f0`: unstable => stable (`PowerSimulations` at `/tmp/jl_i5OHAJmbUT/src/devices_models/devices/common/constraints_structs.jl:49` => `PowerSimulations` at `/tmp/jl_2jErIVY56z/src/devices_models/devices/common/constraints_structs.jl:51`)  

### Signature `Tuple{typeof(read_dual), StageResults, Symbol}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/simulation_results.jl:342`)  

### Signature `Tuple{typeof(read_variable), StageResults, Symbol}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/simulation_results.jl:331`)  

### Signature `Tuple{typeof(get_realized_timestamps), StageResults}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/simulation_results.jl:388`)  

### Signature `Tuple{typeof(read_parameter), StageResults, Symbol}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/simulation_results.jl:352`)  

### Signature `Tuple{typeof(PowerSimulations.get_jump_model), PowerSimulations.PSIContainer}`

Commit `16e1b453e`: | => unstable (`PowerSimulations` at `/tmp/jl_w7EnyVch0r/src/core/psi_container.jl:222`)  

### Signature `Tuple{typeof(get_name), PowerSystems.DynamicBranch}`

Commit `716759627`: | => unstable (`PowerSystems` at `/home/jecmejan/.julia/packages/PowerSystems/SNjYq/src/models/dynamic_branch.jl:44`)  

### Signature `Tuple{typeof(get_total_cost), PowerSimulations.SimulationResults}`

Commit `90b648cd8`: unstable => | (`PowerSimulations` at `/tmp/jl_2jErIVY56z/src/core/simulation_results.jl:152`)  

### Signature `Tuple{typeof(read_variables), PowerSimulations.PSIContainer}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/psi_container.jl:502`)  

### Signature `Tuple{typeof(PowerSimulations.ps_cost), PowerSimulations.PSIContainer, Symbol, String, PowerSystems.VariableCost{Float64}, Float64, Float64}`

Commit `bff50b7ff`: | => unstable (`PowerSimulations` at `/tmp/jl_0Xu9ILEhgb/src/devices_models/devices/common/cost_functions.jl:65`)  
Commit `16e1b453e`: unstable => | (`PowerSimulations` at `/tmp/jl_SzEjoHszaJ/src/devices_models/devices/common/cost_functions.jl:69`)  

### Signature `Tuple{PowerSimulations.var"##get_realized_timestamps#244", Union{Nothing, DateTime}, Union{Nothing, Int64}, typeof(get_realized_timestamps), StageResults}`

Commit `4dcbea990`: | => unstable (`PowerSimulations` at `/tmp/jl_ohQzULkFiJ/src/core/simulation_results.jl:388`)  

### Signature `Tuple{typeof(PowerSimulations._convert_variable_cost), PowerSystems.VariableCost{Vector{Tuple{Float64, Float64}}}}`

Commit `d7c7585ec`: | => unstable (`PowerSimulations` at `/tmp/jl_O9kHwzitKJ/src/devices_models/devices/thermal_generation.jl:1171`)  

### Signature `Tuple{typeof(PowerSimulations.reserve_slacks), PowerSimulations.PSIContainer, String}`

Commit `16e1b453e`: | => unstable (`PowerSimulations` at `/tmp/jl_w7EnyVch0r/src/services_models/service_slacks.jl:1`)  

### Signature `Tuple{PowerSimulations.var"##get_realized_timestamps#242", Union{Nothing, DateTime}, Union{Nothing, Int64}, typeof(get_realized_timestamps), StageResults}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/simulation_results.jl:388`)  
Commit `4dcbea990`: unstable => | (`PowerSimulations` at `/tmp/jl_O9kHwzitKJ/src/core/simulation_results.jl:388`)  

### Signature `Tuple{typeof(PowerSimulations._get_dataset), Type{PowerSimulations.OptimizerStats}, PowerSimulations.HdfSimulationStore}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/hdf_simulation_store.jl:484`)  

### Signature `Tuple{typeof(PowerSimulations.get_ic_power), PowerSimulations.DeviceRampConstraintInfo}`

Commit `4eb7b6070`: | => unstable (`PowerSimulations` at `/tmp/jl_4pY5SLafwZ/src/devices_models/devices/common/constraints_structs.jl:139`)  

### Signature `Tuple{typeof(read_variables), OperationsProblem}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/operations_problem.jl:450`)  

### Signature `Tuple{typeof(PowerSimulations._get_root), PowerSimulations.HdfSimulationStore}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/hdf_simulation_store.jl:531`)  

### Signature `Tuple{typeof(PowerSimulations._process_timestamps), StageResults, Union{Nothing, DateTime}, Union{Nothing, Int64}}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/simulation_results.jl:172`)  

### Signature `Tuple{typeof(PowerSimulations._get_ref_ace_error), Type{PowerSystems.AGC}, PowerSimulations.InitialConditions}`

Commit `16e1b453e`: | => unstable (`PowerSimulations` at `/tmp/jl_w7EnyVch0r/src/core/update_initial_conditions.jl:390`)  

### Signature `Tuple{typeof(get_variable), PowerSimulations.PSIContainer, Symbol}`

Commit `6dbcf8105`: | => unstable (`PowerSimulations` at `/tmp/jl_4JK7kr4n2p/src/core/psi_container.jl:284`)  
Commit `893cfc97e`: unstable => | (`PowerSimulations` at `/tmp/jl_4hU7iT6tOv/src/core/psi_container.jl:300`)  

### Signature `Tuple{typeof(PowerSimulations.get_reference), SimulationResultsReference, String, Int64, Symbol}`

Commit `90b648cd8`: unstable => | (`PowerSimulations` at `/tmp/jl_2jErIVY56z/src/core/simulation_results.jl:447`)  

### Signature `Tuple{typeof(PowerSimulations.get_resolution), Stage}`

Commit `16e1b453e`: | => unstable (`PowerSimulations` at `/tmp/jl_w7EnyVch0r/src/core/simulation_stages.jl:140`)  
Commit `90b648cd8`: unstable => | (`PowerSimulations` at `/tmp/jl_2jErIVY56z/src/core/simulation_stages.jl:140`)  

### Signature `Tuple{typeof(PowerSimulations._get_optimizer_stats_path), PowerSimulations.HdfSimulationStore}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/hdf_simulation_store.jl:529`)  

### Signature `Tuple{typeof(PowerSimulations.get_variable_initial_value), PowerSimulations.ActivePowerVariable, PowerSystems.ThermalMultiStart, PowerSimulations.WarmStartVariable}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/devices_models/devices/thermal_generation.jl:35`)  

### Signature `Tuple{typeof(PowerSimulations.ps_cost), PowerSimulations.PSIContainer, Symbol, String, PowerSystems.VariableCost{Tuple{Float64, Float64}}, Float64, Float64}`

Commit `bff50b7ff`: | => unstable (`PowerSimulations` at `/tmp/jl_0Xu9ILEhgb/src/devices_models/devices/common/cost_functions.jl:106`)  
Commit `16e1b453e`: unstable => | (`PowerSimulations` at `/tmp/jl_SzEjoHszaJ/src/devices_models/devices/common/cost_functions.jl:112`)  

### Signature `Tuple{typeof(PowerSimulations._get_optimizer_data_path), PowerSimulations.HdfSimulationStore}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/hdf_simulation_store.jl:530`)  

### Signature `Tuple{typeof(PowerSimulations.get_resolution), PowerSimulations.SimulationStoreStageParams}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/simulation_store.jl:42`)  

### Signature `Tuple{typeof(PowerSimulations.ps_cost!), PowerSimulations.PSIContainer, Symbol, String, PowerSystems.VariableCost{Tuple{Float64, Float64}}, Float64, Float64}`

Commit `16e1b453e`: | => unstable (`PowerSimulations` at `/tmp/jl_w7EnyVch0r/src/devices_models/devices/common/cost_functions.jl:91`)  
Commit `960af70a7`: unstable => | (`PowerSimulations` at `/tmp/jl_qF8xwrSnkF/src/devices_models/devices/common/cost_functions.jl:91`)  

### Signature `Tuple{typeof(PowerSimulations.get_variable), PowerSimulations.PSIContainer, Symbol}`

Commit `6dbcf8105`: unstable => | (`PowerSimulations` at `/tmp/jl_kJcnw1AbUJ/src/core/psi_container.jl:284`)  
Commit `893cfc97e`: | => unstable (`PowerSimulations` at `/tmp/jl_iLiJWt8dCz/src/core/psi_container.jl:300`)  

### Signature `Tuple{typeof(get_optimizer_log), PowerSimulations.SimulationResults}`

Commit `90b648cd8`: unstable => | (`PowerSimulations` at `/tmp/jl_2jErIVY56z/src/core/simulation_results.jl:153`)  

### Signature `Tuple{typeof(PowerSimulations._read_column_names), Type{PowerSimulations.OptimizerStats}, PowerSimulations.HdfSimulationStore}`

Commit `90b648cd8`: | => unstable (`PowerSimulations` at `/tmp/jl_ABqpaLkDEV/src/core/hdf_simulation_store.jl:533`)  


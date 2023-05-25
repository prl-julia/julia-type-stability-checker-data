# Stability change report for package `ModelingToolkit`

### Signature `Tuple{typeof(simplify), Equation}`

Commit `70d876beb`: stable => unstable (`ModelingToolkit` at `/tmp/jl_di1SRApOR4/src/simplify.jl:39` => `ModelingToolkit` at `/tmp/jl_50J2nYPUP6/src/equations.jl:18` )  

### Signature `Tuple{typeof(variable_dependencies), ModelingToolkit.AbstractSystem}`

Commit `0aa831423`: | => unstable (`ModelingToolkit` at `/tmp/jl_HWNo5Sxgl2/src/systems/dependency_graphs.jl:56` )  

### Signature `Tuple{typeof(ModelingToolkit.get_iv), Difference}`

Commit `456f00fa1`: | => unstable (`ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/utils.jl:2` )  

### Signature `Tuple{typeof(simplify), Num}`

Commit `7331b0c96`: stable => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/x4trB/src/num.jl:78` => `Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/H8dtg/src/Symbolics.jl:45` )  

### Signature `Tuple{typeof(ModelingToolkit.get_systems), ModelingToolkit.AbstractSystem}`

Commit `935a32ea2`: partial => unstable (`ModelingToolkit` at `/tmp/jl_xivadeZClm/src/systems/abstractsystem.jl:165` => `ModelingToolkit` at `/tmp/jl_HYveX2v8N4/src/systems/abstractsystem.jl:165` )  
Commit `4292bf86e`: unstable => partial (`ModelingToolkit` at `/tmp/jl_RYdelylSrY/src/systems/abstractsystem.jl:194` => `ModelingToolkit` at `/tmp/jl_nA70VUZWl8/src/systems/abstractsystem.jl:194` )  
Commit `fff670e88`: partial => unstable (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/abstractsystem.jl:229` => `ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:227` )  

### Signature `Tuple{typeof(calculate_hessian), NonlinearSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/nonlinear/nonlinearsystem.jl:162` )  

### Signature `Tuple{typeof(parameters), ModelingToolkit.AbstractSystem}`

Commit `fc5a147a8`: | => unstable (`ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/abstractsystem.jl:57` )  

### Signature `Tuple{typeof(calculate_gradient), OptimizationSystem}`

Commit `487f67f4d`: | => unstable (`ModelingToolkit` at `/tmp/jl_P6P6B8TCdq/src/systems/optimization/optimizationsystem.jl:42` )  

### Signature `Tuple{typeof(simplify), Complex{Num}}`

Commit `7331b0c96`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/H8dtg/src/Symbolics.jl:45` )  

### Signature `Tuple{typeof(calculate_factorized_W), ModelingToolkit.AbstractODESystem}`

Commit `229ab2066`: | => unstable (`ModelingToolkit` at `/tmp/jl_Hu523MHUlk/src/systems/diffeqs/abstractodesystem.jl:62` )  
Commit `5f4999377`: unstable => | (`ModelingToolkit` at `/tmp/jl_lYb2tENWD4/src/systems/diffeqs/abstractodesystem.jl:62` )  

### Signature `Tuple{typeof(equations), ConstraintsSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/optimization/constraints_system.jl:88` )  

### Signature `Tuple{typeof(ModelingToolkit.isvariable), Num}`

Commit `456f00fa1`: | => unstable (`ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/utils.jl:252` )  
Commit `fff670e88`: unstable => stable (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/utils.jl:252` => `ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/utils.jl:359` )  

### Signature `Tuple{typeof(simplified_expr), ModelingToolkit.Constant}`

Commit `5a06b38a3`: | => unstable (`ModelingToolkit` at `/tmp/jl_xkh09SdGVG/src/direct.jl:28` )  
Commit `70d876beb`: unstable => | (`ModelingToolkit` at `/tmp/jl_di1SRApOR4/src/direct.jl:205` )  

### Signature `Tuple{typeof(calculate_control_jacobian), ModelingToolkit.AbstractODESystem}`

Commit `38ac57174`: | => unstable (`ModelingToolkit` at `/tmp/jl_7w9atCzAR6/src/systems/diffeqs/abstractodesystem.jl:41` )  

### Signature `Tuple{typeof(ModelingToolkit.namespace_objective), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/optimization/optimizationsystem.jl:146` )  

### Signature `Tuple{typeof(ModelingToolkit.get_eqs), ModelingToolkit.AbstractSystem}`

Commit `c107932bf`: partial => unstable (`ModelingToolkit` at `/tmp/jl_RutanofMXs/src/systems/abstractsystem.jl:141` => `ModelingToolkit` at `/tmp/jl_JuRs5oBgFE/src/systems/abstractsystem.jl:141` )  

### Signature `Tuple{typeof(ModelingToolkit.namespace_controls), ModelingToolkit.AbstractSystem}`

Commit `6c5935afb`: | => unstable (`ModelingToolkit` at `/tmp/jl_vIH0J8BOPW/src/systems/control/controlsystem.jl:3` )  
Commit `fff670e88`: unstable => partial (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/abstractsystem.jl:381` => `ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:454` )  

### Signature `Tuple{typeof(ModelingToolkit.default_u0), ModelingToolkit.AbstractSystem}`

Commit `f6802a5ff`: | => unstable (`ModelingToolkit` at `/tmp/jl_nmtihmtOBQ/src/systems/abstractsystem.jl:263` )  
Commit `89c03eab8`: unstable => | (`ModelingToolkit` at `/tmp/jl_lM3s1m1Sz4/src/systems/abstractsystem.jl:347` )  

### Signature `Tuple{typeof(ModelingToolkit.calculate_factorized_W), ODESystem}`

Commit `2cd451f29`: | => unstable (`ModelingToolkit` at `/tmp/jl_jOLA38fEXO/src/systems/diffeqs/diffeqsystem.jl:167` )  
Commit `fd72716d7`: unstable => | (`ModelingToolkit` at `/tmp/jl_bWzy9AzYNU/src/systems/diffeqs/diffeqsystem.jl:194` )  

### Signature `Tuple{typeof(ModelingToolkit.default_p), ModelingToolkit.AbstractSystem}`

Commit `f6802a5ff`: | => unstable (`ModelingToolkit` at `/tmp/jl_nmtihmtOBQ/src/systems/abstractsystem.jl:269` )  
Commit `89c03eab8`: unstable => | (`ModelingToolkit` at `/tmp/jl_lM3s1m1Sz4/src/systems/abstractsystem.jl:353` )  

### Signature `Tuple{typeof(expand_derivatives), Operation}`

Commit `70d876beb`: unstable => | (`ModelingToolkit` at `/tmp/jl_di1SRApOR4/src/differentials.jl:58` )  

### Signature `Tuple{typeof(ModelingToolkit.generate_factorized_W), ODESystem}`

Commit `1a4865335`: unstable => stable (`ModelingToolkit` at `/tmp/jl_jOLA38fEXO/src/systems/diffeqs/diffeqsystem.jl:191` => `ModelingToolkit` at `/tmp/jl_BI7cPUBiR4/src/systems/diffeqs/diffeqsystem.jl:193` )  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.Func}`

Commit `456f00fa1`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156` )  

### Signature `Tuple{typeof(ModelingToolkit.get_Wfact_t), ModelingToolkit.AbstractSystem}`

Commit `f6802a5ff`: | => unstable (`ModelingToolkit` at `/tmp/jl_nmtihmtOBQ/src/systems/abstractsystem.jl:141` )  

### Signature `Tuple{typeof(ModelingToolkit.namespace_expr), OptimizationSystem}`

Commit `70d876beb`: | => unstable (`ModelingToolkit` at `/tmp/jl_50J2nYPUP6/src/systems/optimization/optimizationsystem.jl:81` )  
Commit `fff670e88`: unstable => | (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/optimization/optimizationsystem.jl:121` )  

### Signature `Tuple{typeof(ModelingToolkit.affects), Vector{ModelingToolkit.SymbolicContinuousCallback}}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/callbacks.jl:123` )  

### Signature `Tuple{typeof(ModelingToolkit._toexpr), Num}`

Commit `b12c854a3`: | => unstable (`ModelingToolkit` at `/tmp/jl_9Ejgv6hm3C/src/direct.jl:284` )  
Commit `83312e349`: unstable => | (`ModelingToolkit` at `/tmp/jl_543KVovEVM/src/direct.jl:284` )  

### Signature `Tuple{typeof(calculate_jacobian), ModelingToolkit.AbstractODESystem}`

Commit `fd72716d7`: | => unstable (`ModelingToolkit` at `/tmp/jl_7qp8ba5MPU/src/systems/diffeqs/abstractodesystem.jl:11` )  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.SetArray}`

Commit `456f00fa1`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156` )  

### Signature `Tuple{typeof(equations), OptimizationSystem}`

Commit `70d876beb`: stable => unstable (`ModelingToolkit` at `/tmp/jl_di1SRApOR4/src/systems/optimization/optimizationsystem.jl:82` => `ModelingToolkit` at `/tmp/jl_50J2nYPUP6/src/systems/optimization/optimizationsystem.jl:80` )  
Commit `fff670e88`: unstable => | (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/optimization/optimizationsystem.jl:120` )  

### Signature `Tuple{typeof(ModelingToolkit.value), Num}`

Commit `70d876beb`: | => unstable (`ModelingToolkit` at `/tmp/jl_50J2nYPUP6/src/ModelingToolkit.jl:49` )  
Commit `83312e349`: unstable => | (`ModelingToolkit` at `/tmp/jl_543KVovEVM/src/ModelingToolkit.jl:59` )  

### Signature `Tuple{typeof(generate_diffusion_function), SDESystem}`

Commit `fc5a147a8`: stable => unstable (`ModelingToolkit` at `/tmp/jl_fifo9Mdsr6/src/systems/diffeqs/sdesystem.jl:55` => `ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/diffeqs/sdesystem.jl:55` )  
Commit `868e59e50`: unstable => stable (`ModelingToolkit` at `/tmp/jl_tmT8vIjQ9O/src/systems/diffeqs/sdesystem.jl:55` => `ModelingToolkit` at `/tmp/jl_fUPORWTEtE/src/systems/diffeqs/sdesystem.jl:83` )  
Commit `31365cabe`: stable => unstable (`ModelingToolkit` at `/tmp/jl_j8VYfiVyT4/src/systems/diffeqs/sdesystem.jl:115` => `ModelingToolkit` at `/tmp/jl_5CZiLI9ErA/src/systems/diffeqs/sdesystem.jl:115` )  
Commit `456f00fa1`: unstable => stable (`ModelingToolkit` at `/tmp/jl_robiVQ5wPa/src/systems/diffeqs/sdesystem.jl:142` => `ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/systems/diffeqs/sdesystem.jl:143` )  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.Assignment}`

Commit `456f00fa1`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156` )  

### Signature `Tuple{typeof(ModelingToolkit.get_default_u0), ModelingToolkit.AbstractSystem}`

Commit `f6802a5ff`: | => unstable (`ModelingToolkit` at `/tmp/jl_nmtihmtOBQ/src/systems/abstractsystem.jl:141` )  
Commit `89c03eab8`: unstable => | (`ModelingToolkit` at `/tmp/jl_lM3s1m1Sz4/src/systems/abstractsystem.jl:162` )  

### Signature `Tuple{typeof(equations), ModelingToolkit.AbstractODESystem}`

Commit `3d3dbffa4`: | => unstable (`ModelingToolkit` at `/tmp/jl_7WVeNMVYNI/src/systems/diffeqs/abstractodesystem.jl:197` )  
Commit `fc5a147a8`: unstable => | (`ModelingToolkit` at `/tmp/jl_fifo9Mdsr6/src/systems/diffeqs/abstractodesystem.jl:147` )  

### Signature `Tuple{typeof(ModelingToolkit.affects), Vector{ModelingToolkit.SymbolicDiscreteCallback}}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/callbacks.jl:215` )  

### Signature `Tuple{typeof(ModelingToolkit._isone), Num}`

Commit `efda9247f`: | => unstable (`ModelingToolkit` at `/tmp/jl_FcBqZAHm96/src/solve.jl:104` )  
Commit `83312e349`: unstable => | (`ModelingToolkit` at `/tmp/jl_543KVovEVM/src/solve.jl:113` )  

### Signature `Tuple{typeof(dae_index_lowering), ODESystem}`

Commit `626009820`: stable => unstable (`ModelingToolkit.StructuralTransformations` at `/tmp/jl_reVWHuZ41y/src/structural_transformation/pantelides.jl:169` => `ModelingToolkit.StructuralTransformations` at `/tmp/jl_ZqHUrCFAlM/src/structural_transformation/pantelides.jl:166` )  

### Signature `Tuple{typeof(get_variables), Num}`

Commit `70d876beb`: | => unstable (`ModelingToolkit` at `/tmp/jl_50J2nYPUP6/src/utils.jl:60` )  

### Signature `Tuple{typeof(ModelingToolkit.get_ps), ModelingToolkit.AbstractSystem}`

Commit `f6802a5ff`: | => unstable (`ModelingToolkit` at `/tmp/jl_nmtihmtOBQ/src/systems/abstractsystem.jl:141` )  

### Signature `Tuple{typeof(ModelingToolkit.calculate_tgrad), ModelingToolkit.AbstractODESystem}`

Commit `fd72716d7`: | => unstable (`ModelingToolkit` at `/tmp/jl_7qp8ba5MPU/src/systems/diffeqs/abstractodesystem.jl:1` )  
Commit `fc5a147a8`: unstable => | (`ModelingToolkit` at `/tmp/jl_fifo9Mdsr6/src/systems/diffeqs/abstractodesystem.jl:1` )  

### Signature `Tuple{typeof(arguments), Metatheory.Patterns.PatTerm}`

Commit `456f00fa1`: | => unstable (`Metatheory.Patterns` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/Patterns.jl:101` )  
Commit `fff670e88`: unstable => | (`Metatheory.Patterns` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/Patterns.jl:101` )  

### Signature `Tuple{typeof(dae_order_lowering), ODESystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/diffeqs/first_order_transform.jl:15` )  

### Signature `Tuple{typeof(generate_difference_cb), ODESystem}`

Commit `549885dc3`: | => unstable (`ModelingToolkit` at `/tmp/jl_xujkf87234/src/systems/diffeqs/abstractodesystem.jl:122` )  

### Signature `Tuple{typeof(ModelingToolkit.get_var_to_name), ModelingToolkit.AbstractSystem}`

Commit `628669165`: | => unstable (`ModelingToolkit` at `/tmp/jl_fMvwn0XWJi/src/systems/abstractsystem.jl:180` )  

### Signature `Tuple{typeof(independent_variables), AbstractMultivariateSystem}`

Commit `89fdee8bd`: | => unstable (`ModelingToolkit` at `/tmp/jl_v814x2fqh8/src/systems/abstractsystem.jl:162` )  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.MakeArray}`

Commit `456f00fa1`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156` )  

### Signature `Tuple{typeof(ModelingToolkit.toparam), Num}`

Commit `fff670e88`: stable => unstable (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/parameters.jl:24` => `ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/parameters.jl:43` )  

### Signature `Tuple{typeof(simplify_fractions), Complex{Num}}`

Commit `456f00fa1`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/UrqtQ/src/Symbolics.jl:156` )  

### Signature `Tuple{typeof(calculate_massmatrix), ModelingToolkit.AbstractODESystem}`

Commit `9ae43bc85`: | => unstable (`ModelingToolkit` at `/tmp/jl_B0Rir6N4jw/src/systems/diffeqs/abstractodesystem.jl:92` )  

### Signature `Tuple{typeof(extend), ModelingToolkit.AbstractSystem, ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: partial => unstable (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/abstractsystem.jl:961` => `ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:1572` )  

### Signature `Tuple{typeof(generate_function), OptimizationSystem}`

Commit `70d876beb`: stable => unstable (`ModelingToolkit` at `/tmp/jl_di1SRApOR4/src/systems/optimization/optimizationsystem.jl:75` => `ModelingToolkit` at `/tmp/jl_50J2nYPUP6/src/systems/optimization/optimizationsystem.jl:75` )  

### Signature `Tuple{typeof(isdisturbance), Num}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/variables.jl:205` )  

### Signature `Tuple{typeof(equation_dependencies), ModelingToolkit.AbstractSystem}`

Commit `0aa831423`: | => unstable (`ModelingToolkit` at `/tmp/jl_HWNo5Sxgl2/src/systems/dependency_graphs.jl:3` )  

### Signature `Tuple{typeof(ModelingToolkit.namespace_parameters), ModelingToolkit.AbstractODESystem}`

Commit `7f051bb34`: stable => unstable (`ModelingToolkit` at `/tmp/jl_X8titk3A5i/src/systems/diffeqs/abstractodesystem.jl:174` => `ModelingToolkit` at `/tmp/jl_nK9wfszYx8/src/systems/diffeqs/abstractodesystem.jl:174` )  
Commit `fc5a147a8`: unstable => | (`ModelingToolkit` at `/tmp/jl_fifo9Mdsr6/src/systems/diffeqs/abstractodesystem.jl:120` )  

### Signature `Tuple{typeof(simplified_expr), Operation}`

Commit `5a06b38a3`: | => unstable (`ModelingToolkit` at `/tmp/jl_xkh09SdGVG/src/direct.jl:16` )  
Commit `70d876beb`: unstable => | (`ModelingToolkit` at `/tmp/jl_di1SRApOR4/src/direct.jl:188` )  

### Signature `Tuple{typeof(ModelingToolkit._isone), ModelingToolkit.Constant}`

Commit `258d8a8ad`: | => unstable (`ModelingToolkit` at `/tmp/jl_lYb2tENWD4/src/differentials.jl:69` )  
Commit `70d876beb`: unstable => | (`ModelingToolkit` at `/tmp/jl_di1SRApOR4/src/differentials.jl:136` )  

### Signature `Tuple{typeof(ModelingToolkit.get_reduced_states), ModelingToolkit.AbstractSystem}`

Commit `336e5cb93`: | => unstable (`ModelingToolkit` at `/tmp/jl_543KVovEVM/src/systems/abstractsystem.jl:162` )  
Commit `24d5041a6`: unstable => | (`ModelingToolkit` at `/tmp/jl_LQTutQlsZo/src/systems/abstractsystem.jl:165` )  

### Signature `Tuple{typeof(ModelingToolkit._iszero), ModelingToolkit.Constant}`

Commit `258d8a8ad`: | => unstable (`ModelingToolkit` at `/tmp/jl_lYb2tENWD4/src/differentials.jl:68` )  
Commit `70d876beb`: unstable => | (`ModelingToolkit` at `/tmp/jl_di1SRApOR4/src/differentials.jl:135` )  

### Signature `Tuple{typeof(ModelingToolkit.rename), Expression}`

Commit `7f051bb34`: stable => unstable (`ModelingToolkit` at `/tmp/jl_X8titk3A5i/src/systems/diffeqs/first_order_transform.jl:53` => `ModelingToolkit` at `/tmp/jl_nK9wfszYx8/src/systems/diffeqs/first_order_transform.jl:53` )  
Commit `2b59e8ae7`: unstable => | (`ModelingToolkit` at `/tmp/jl_j0tU527Qhm/src/systems/diffeqs/first_order_transform.jl:53` )  

### Signature `Tuple{typeof(generate_hessian), OptimizationSystem}`

Commit `fc5a147a8`: | => unstable (`ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/optimization/optimizationsystem.jl:46` )  
Commit `7c5db6f57`: unstable => stable (`ModelingToolkit` at `/tmp/jl_rmD2jyFE9i/src/systems/optimization/optimizationsystem.jl:56` => `ModelingToolkit` at `/tmp/jl_ZCP6LGxg1G/src/systems/optimization/optimizationsystem.jl:56` )  
Commit `978d54056`: stable => unstable (`ModelingToolkit` at `/tmp/jl_dWleRAJi7O/src/systems/optimization/optimizationsystem.jl:85` => `ModelingToolkit` at `/tmp/jl_pQtmfSlWV8/src/systems/optimization/optimizationsystem.jl:85` )  
Commit `f42e3f885`: unstable => stable (`ModelingToolkit` at `/tmp/jl_pQtmfSlWV8/src/systems/optimization/optimizationsystem.jl:85` => `ModelingToolkit` at `/tmp/jl_reVWHuZ41y/src/systems/optimization/optimizationsystem.jl:85` )  

### Signature `Tuple{typeof(generate_function), ModelingToolkit.AbstractODESystem}`

Commit `fc5a147a8`: stable => unstable (`ModelingToolkit` at `/tmp/jl_fifo9Mdsr6/src/systems/diffeqs/abstractodesystem.jl:47` => `ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/diffeqs/abstractodesystem.jl:47` )  

### Signature `Tuple{typeof(getbounds), Num}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/variables.jl:172` )  

### Signature `Tuple{typeof(ModelingToolkit.alias_elimination!), TearingState}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/alias_elimination.jl:48` )  

### Signature `Tuple{typeof(ModelingToolkit.condition), ModelingToolkit.SymbolicDiscreteCallback}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/callbacks.jl:208` )  

### Signature `Tuple{typeof(operation), Metatheory.EMatchCompiler.ENodePat}`

Commit `456f00fa1`: | => unstable (`Metatheory.EMatchCompiler` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/ematch_compiler.jl:47` )  
Commit `fff670e88`: unstable => | (`Metatheory.EMatchCompiler` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/ematch_compiler.jl:47` )  

### Signature `Tuple{typeof(ModelingToolkit.define_params), Number}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/diffeqs/modelingtoolkitize.jl:137` )  

### Signature `Tuple{typeof(ModelingToolkit.get_tearing_state), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:227` )  

### Signature `Tuple{typeof(ModelingToolkit.pantelides), ODESystem}`

Commit `192441f42`: | => unstable (`ModelingToolkit` at `/tmp/jl_3Mh0vcPq3s/src/systems/diffeqs/index_reduction.jl:105` )  
Commit `f0b733fa1`: unstable => | (`ModelingToolkit` at `/tmp/jl_JUbezmpgxi/src/systems/diffeqs/index_reduction.jl:105` )  

### Signature `Tuple{typeof(ModelingToolkit.get_structure), ModelingToolkit.AbstractSystem}`

Commit `f6802a5ff`: | => unstable (`ModelingToolkit` at `/tmp/jl_nmtihmtOBQ/src/systems/abstractsystem.jl:141` )  
Commit `fff670e88`: unstable => partial (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/abstractsystem.jl:229` => `ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:227` )  

### Signature `Tuple{typeof(states), ModelingToolkit.AbstractSystem}`

Commit `fc5a147a8`: | => unstable (`ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/abstractsystem.jl:56` )  

### Signature `Tuple{typeof(ModelingToolkit.get_cmap), ConstraintsSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/optimization/constraints_system.jl:213` )  

### Signature `Tuple{typeof(equations), SystemStructure}`

Commit `ea7207d67`: | => unstable (`ModelingToolkit` at `/tmp/jl_xQXeLON0lW/src/systems/systemstructure.jl:18` )  
Commit `f6802a5ff`: unstable => | (`ModelingToolkit` at `/tmp/jl_pURKJoFovK/src/systems/systemstructure.jl:18` )  

### Signature `Tuple{typeof(ModelingToolkit.affects), ModelingToolkit.SymbolicDiscreteCallback}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/callbacks.jl:213` )  

### Signature `Tuple{typeof(ModelingToolkit.clean), Operation}`

Commit `fc5a147a8`: unstable => | (`ModelingToolkit` at `/tmp/jl_fifo9Mdsr6/src/utils.jl:68` )  

### Signature `Tuple{typeof(ModelingToolkit.isparameter), Num}`

Commit `7e7fb1740`: | => unstable (`ModelingToolkit` at `/tmp/jl_5SFYpwVw7c/src/parameters.jl:4` )  
Commit `fff670e88`: unstable => | (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/parameters.jl:4` )  

### Signature `Tuple{typeof(ModelingToolkit.get_indvars), ModelingToolkit.AbstractSystem}`

Commit `89c03eab8`: | => unstable (`ModelingToolkit` at `/tmp/jl_5mBwzqjqZw/src/systems/abstractsystem.jl:165` )  
Commit `89fdee8bd`: unstable => partial (`ModelingToolkit` at `/tmp/jl_v0Zev2FkTC/src/systems/abstractsystem.jl:180` => `ModelingToolkit` at `/tmp/jl_v814x2fqh8/src/systems/abstractsystem.jl:200` )  

### Signature `Tuple{typeof(generate_hessian), NonlinearSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/nonlinear/nonlinearsystem.jl:173` )  

### Signature `Tuple{typeof(expand), Complex{Num}}`

Commit `7331b0c96`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/H8dtg/src/Symbolics.jl:46` )  

### Signature `Tuple{typeof(independent_variables), ModelingToolkit.AbstractSystem}`

Commit `89fdee8bd`: | => unstable (`ModelingToolkit` at `/tmp/jl_v814x2fqh8/src/systems/abstractsystem.jl:148` )  

### Signature `Tuple{typeof(isbinaryvar), Num}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/variables.jl:366` )  

### Signature `Tuple{typeof(calculate_hessian), OptimizationSystem}`

Commit `fc5a147a8`: | => unstable (`ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/optimization/optimizationsystem.jl:42` )  
Commit `70d876beb`: unstable => stable (`ModelingToolkit` at `/tmp/jl_di1SRApOR4/src/systems/optimization/optimizationsystem.jl:60` => `ModelingToolkit` at `/tmp/jl_50J2nYPUP6/src/systems/optimization/optimizationsystem.jl:60` )  
Commit `978d54056`: stable => unstable (`ModelingToolkit` at `/tmp/jl_dWleRAJi7O/src/systems/optimization/optimizationsystem.jl:81` => `ModelingToolkit` at `/tmp/jl_pQtmfSlWV8/src/systems/optimization/optimizationsystem.jl:81` )  
Commit `f42e3f885`: unstable => stable (`ModelingToolkit` at `/tmp/jl_pQtmfSlWV8/src/systems/optimization/optimizationsystem.jl:81` => `ModelingToolkit` at `/tmp/jl_reVWHuZ41y/src/systems/optimization/optimizationsystem.jl:81` )  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.MakeTuple}`

Commit `456f00fa1`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156` )  

### Signature `Tuple{typeof(ModelingToolkit.hasshift), Equation}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/discretedomain.jl:60` )  

### Signature `Tuple{typeof(getdescription), Num}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/variables.jl:345` )  

### Signature `Tuple{typeof(ModelingToolkit.unknown_states), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:625` )  

### Signature `Tuple{typeof(generate_control_jacobian), ModelingToolkit.AbstractODESystem}`

Commit `38ac57174`: | => unstable (`ModelingToolkit` at `/tmp/jl_7w9atCzAR6/src/systems/diffeqs/abstractodesystem.jl:75` )  

### Signature `Tuple{typeof(ModelingToolkit.generate_rootfinding_callback), ModelingToolkit.AbstractODESystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/callbacks.jl:363` )  

### Signature `Tuple{typeof(ModelingToolkit.instantiate), Operation}`

Commit `9616b0130`: | => unstable (`ModelingToolkit` at `/tmp/jl_j0tU527Qhm/src/systems/diffeqs/validation.jl:6` )  
Commit `70d876beb`: unstable => | (`ModelingToolkit` at `/tmp/jl_di1SRApOR4/src/systems/diffeqs/validation.jl:6` )  

### Signature `Tuple{typeof(get_variables), Inequality}`

Commit `456f00fa1`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/UrqtQ/src/inequality.jl:111` )  

### Signature `Tuple{typeof(expand), Num}`

Commit `7331b0c96`: stable => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/x4trB/src/num.jl:79` => `Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/H8dtg/src/Symbolics.jl:46` )  

### Signature `Tuple{typeof(generate_jacobian), ConstraintsSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/optimization/constraints_system.jl:155` )  

### Signature `Tuple{typeof(ModelingToolkit.normalize_to_differential), Shift}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/discretedomain.jl:30` )  

### Signature `Tuple{typeof(ModelingToolkit.get_unit), Num}`

Commit `88fe45e52`: | => unstable (`ModelingToolkit` at `/tmp/jl_VMjerMN83m/src/systems/validation.jl:23` )  

### Signature `Tuple{typeof(ModelingToolkit.sampletime), ShiftIndex}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/discretedomain.jl:237` )  

### Signature `Tuple{typeof(ModelingToolkit.get_tgrad), ModelingToolkit.AbstractSystem}`

Commit `f6802a5ff`: | => unstable (`ModelingToolkit` at `/tmp/jl_nmtihmtOBQ/src/systems/abstractsystem.jl:141` )  

### Signature `Tuple{typeof(operation), Expr}`

Commit `456f00fa1`: | => unstable (`TermInterface` at `/home/jecmejan/.julia/packages/TermInterface/hZ5oG/src/expr.jl:7` )  
Commit `fff670e88`: unstable => | (`TermInterface` at `/home/jecmejan/.julia/packages/TermInterface/hZ5oG/src/expr.jl:7` )  

### Signature `Tuple{typeof(getbounds), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/variables.jl:318` )  

### Signature `Tuple{typeof(ModelingToolkit.get_iv), ModelingToolkit.AbstractSystem}`

Commit `f6802a5ff`: | => unstable (`ModelingToolkit` at `/tmp/jl_nmtihmtOBQ/src/systems/abstractsystem.jl:141` )  
Commit `fff670e88`: unstable => partial (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/abstractsystem.jl:229` => `ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:227` )  

### Signature `Tuple{typeof(ModelingToolkit.is_timed_condition), ModelingToolkit.SymbolicDiscreteCallback}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/callbacks.jl:170` )  

### Signature `Tuple{typeof(ModelingToolkit.affects), ModelingToolkit.SymbolicContinuousCallback}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/callbacks.jl:122` )  

### Signature `Tuple{typeof(generate_jacobian), NonlinearSystem}`

Commit `fc5a147a8`: stable => unstable (`ModelingToolkit` at `/tmp/jl_fifo9Mdsr6/src/systems/nonlinear/nonlinear_system.jl:75` => `ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/nonlinear/nonlinearsystem.jl:50` )  

### Signature `Tuple{typeof(calculate_jacobian), ODESystem}`

Commit `fd72716d7`: unstable => | (`ModelingToolkit` at `/tmp/jl_bWzy9AzYNU/src/systems/diffeqs/diffeqsystem.jl:151` )  

### Signature `Tuple{typeof(ModelingToolkit.get_iv), Differential}`

Commit `456f00fa1`: | => unstable (`ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/utils.jl:1` )  

### Signature `Tuple{typeof(parameters), ModelingToolkit.AbstractODESystem}`

Commit `7f051bb34`: stable => unstable (`ModelingToolkit` at `/tmp/jl_X8titk3A5i/src/systems/diffeqs/abstractodesystem.jl:197` => `ModelingToolkit` at `/tmp/jl_nK9wfszYx8/src/systems/diffeqs/abstractodesystem.jl:197` )  
Commit `fc5a147a8`: unstable => | (`ModelingToolkit` at `/tmp/jl_fifo9Mdsr6/src/systems/diffeqs/abstractodesystem.jl:145` )  

### Signature `Tuple{typeof(ModelingToolkit.get_op), ModelingToolkit.AbstractSystem}`

Commit `0176fef5a`: | => unstable (`ModelingToolkit` at `/tmp/jl_9SvuJy76dk/src/systems/abstractsystem.jl:161` )  

### Signature `Tuple{typeof(structural_simplify), OptimizationSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/optimization/optimizationsystem.jl:592` )  

### Signature `Tuple{typeof(expand_connections), ModelingToolkit.AbstractSystem}`

Commit `456f00fa1`: | => unstable (`ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/systems/connectors.jl:194` )  

### Signature `Tuple{typeof(getdist), Num}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/variables.jl:252` )  

### Signature `Tuple{typeof(ModelingToolkit.isautonomous), ModelingToolkit.AbstractODESystem}`

Commit `f9e4e190f`: | => unstable (`ModelingToolkit` at `/tmp/jl_vGhqP2zYDK/src/systems/diffeqs/abstractodesystem.jl:102` )  

### Signature `Tuple{typeof(ModelingToolkit.flowvar), ModelingToolkit.AbstractSystem}`

Commit `456f00fa1`: | => unstable (`ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/systems/connectors.jl:171` )  

### Signature `Tuple{typeof(independent_variables), AbstractTimeDependentSystem}`

Commit `89fdee8bd`: | => unstable (`ModelingToolkit` at `/tmp/jl_v814x2fqh8/src/systems/abstractsystem.jl:160` )  
Commit `fff670e88`: unstable => partial (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/abstractsystem.jl:153` => `ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:169` )  

### Signature `Tuple{typeof(ModelingToolkit.get_preface), ModelingToolkit.AbstractSystem}`

Commit `5a47dd69a`: | => unstable (`ModelingToolkit` at `/tmp/jl_by9enEZgfm/src/systems/abstractsystem.jl:194` )  

### Signature `Tuple{typeof(compose), ModelingToolkit.AbstractSystem, AbstractArray{<:ModelingToolkit.AbstractSystem}}`

Commit `d74ab35ca`: | => unstable (`ModelingToolkit` at `/tmp/jl_ralc7KRyhw/src/systems/abstractsystem.jl:920` )  
Commit `bbc88969e`: unstable => partial (`ModelingToolkit` at `/tmp/jl_ralc7KRyhw/src/systems/abstractsystem.jl:920` => `ModelingToolkit` at `/tmp/jl_z45Q9SlWXS/src/systems/abstractsystem.jl:920` )  

### Signature `Tuple{typeof(ModelingToolkit.get_observed), ModelingToolkit.AbstractSystem}`

Commit `f6802a5ff`: | => unstable (`ModelingToolkit` at `/tmp/jl_nmtihmtOBQ/src/systems/abstractsystem.jl:141` )  
Commit `38ac57174`: unstable => partial (`ModelingToolkit` at `/tmp/jl_NSBoVa50Xo/src/systems/abstractsystem.jl:165` => `ModelingToolkit` at `/tmp/jl_7w9atCzAR6/src/systems/abstractsystem.jl:179` )  

### Signature `Tuple{typeof(calculate_hessian), ConstraintsSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/optimization/constraints_system.jl:161` )  

### Signature `Tuple{typeof(equations), ModelingToolkit.AbstractSystem}`

Commit `fc5a147a8`: | => unstable (`ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/abstractsystem.jl:59` )  

### Signature `Tuple{typeof(ModelingToolkit.get_loss), ModelingToolkit.AbstractSystem}`

Commit `0176fef5a`: | => unstable (`ModelingToolkit` at `/tmp/jl_9SvuJy76dk/src/systems/abstractsystem.jl:161` )  
Commit `fff670e88`: unstable => partial (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/abstractsystem.jl:229` => `ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:227` )  

### Signature `Tuple{typeof(add_accumulations), ODESystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/diffeqs/odesystem.jl:457` )  

### Signature `Tuple{typeof(calculate_jacobian), ConstraintsSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/optimization/constraints_system.jl:138` )  

### Signature `Tuple{typeof(debug_system), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:1132` )  

### Signature `Tuple{typeof(ModelingToolkit.get_controls), ModelingToolkit.AbstractSystem}`

Commit `0176fef5a`: | => unstable (`ModelingToolkit` at `/tmp/jl_9SvuJy76dk/src/systems/abstractsystem.jl:161` )  
Commit `fff670e88`: unstable => partial (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/abstractsystem.jl:229` => `ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:227` )  

### Signature `Tuple{typeof(parameters), ModelingToolkit.FunctionalAffect}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/callbacks.jl:38` )  

### Signature `Tuple{typeof(ModelingToolkit.debug_sub), Equation}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/debugging.jl:29` )  

### Signature `Tuple{typeof(ModelingToolkit.isstreamconnection), Connection}`

Commit `456f00fa1`: | => unstable (`ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/systems/connectors.jl:154` )  
Commit `fff670e88`: unstable => | (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/connectors.jl:154` )  

### Signature `Tuple{typeof(ModelingToolkit.to_diffeq), Equation}`

Commit `fd72716d7`: unstable => | (`ModelingToolkit` at `/tmp/jl_bWzy9AzYNU/src/systems/diffeqs/diffeqsystem.jl:22` )  

### Signature `Tuple{typeof(ModelingToolkit._iszero), Num}`

Commit `efda9247f`: | => unstable (`ModelingToolkit` at `/tmp/jl_FcBqZAHm96/src/solve.jl:103` )  
Commit `83312e349`: unstable => | (`ModelingToolkit` at `/tmp/jl_543KVovEVM/src/solve.jl:112` )  

### Signature `Tuple{typeof(ModelingToolkit.generate_control_function), ModelingToolkit.AbstractODESystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/inputoutput.jl:194` )  

### Signature `Tuple{typeof(ModelingToolkit._positivemax), Num, Num}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/Symbolics/VIBnK/src/register.jl:51` )  

### Signature `Tuple{typeof(ModelingToolkit.get_connection_type), ModelingToolkit.AbstractSystem}`

Commit `f12f472f6`: | => unstable (`ModelingToolkit` at `/tmp/jl_LYZEJYhst6/src/systems/abstractsystem.jl:165` )  
Commit `456f00fa1`: unstable => | (`ModelingToolkit` at `/tmp/jl_robiVQ5wPa/src/systems/abstractsystem.jl:194` )  

### Signature `Tuple{typeof(generate_gradient), OptimizationSystem}`

Commit `487f67f4d`: | => unstable (`ModelingToolkit` at `/tmp/jl_P6P6B8TCdq/src/systems/optimization/optimizationsystem.jl:46` )  

### Signature `Tuple{typeof(ModelingToolkit.get_depvars), ModelingToolkit.AbstractSystem}`

Commit `89c03eab8`: | => unstable (`ModelingToolkit` at `/tmp/jl_5mBwzqjqZw/src/systems/abstractsystem.jl:165` )  
Commit `89fdee8bd`: unstable => partial (`ModelingToolkit` at `/tmp/jl_v0Zev2FkTC/src/systems/abstractsystem.jl:180` => `ModelingToolkit` at `/tmp/jl_v814x2fqh8/src/systems/abstractsystem.jl:200` )  

### Signature `Tuple{typeof(ModelingToolkit.mydiv), Num, Num}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/Symbolics/VIBnK/src/register.jl:51` )  

### Signature `Tuple{typeof(ModelingToolkit.tosymbolic), Num}`

Commit `70d876beb`: | => unstable (`ModelingToolkit` at `/tmp/jl_50J2nYPUP6/src/ModelingToolkit.jl:105` )  
Commit `83312e349`: unstable => | (`ModelingToolkit` at `/tmp/jl_543KVovEVM/src/ModelingToolkit.jl:158` )  

### Signature `Tuple{typeof(generate_jacobian), ModelingToolkit.AbstractODESystem}`

Commit `fc5a147a8`: stable => unstable (`ModelingToolkit` at `/tmp/jl_fifo9Mdsr6/src/systems/diffeqs/abstractodesystem.jl:42` => `ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/diffeqs/abstractodesystem.jl:42` )  

### Signature `Tuple{typeof(ModelingToolkit.namespace_parameters), ModelingToolkit.AbstractSystem}`

Commit `fc5a147a8`: | => unstable (`ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/abstractsystem.jl:34` )  

### Signature `Tuple{typeof(ModelingToolkit.aag_bareiss), ModelingToolkit.AbstractSystem}`

Commit `456f00fa1`: | => unstable (`ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/systems/alias_elimination.jl:17` )  
Commit `fff670e88`: unstable => partial (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/alias_elimination.jl:17` => `ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/alias_elimination.jl:26` )  
Commit `25099f8fa`: partial => unstable (`ModelingToolkit` at `/tmp/jl_J27kTuT8zi/src/systems/alias_elimination.jl:26` => `ModelingToolkit` at `/tmp/jl_dKj6vmNY7O/src/systems/alias_elimination.jl:24` )  

### Signature `Tuple{typeof(tearing_assignments), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit.StructuralTransformations` at `/tmp/jl_jKHsZuDEz4/src/structural_transformation/symbolics_tearing.jl:121` )  

### Signature `Tuple{typeof(ModelingToolkit.flatten_differential), Operation}`

Commit `70d876beb`: unstable => | (`ModelingToolkit` at `/tmp/jl_di1SRApOR4/src/systems/diffeqs/first_order_transform.jl:7` )  

### Signature `Tuple{typeof(ModelingToolkit.get_ctrls), ModelingToolkit.AbstractSystem}`

Commit `38ac57174`: | => unstable (`ModelingToolkit` at `/tmp/jl_7w9atCzAR6/src/systems/abstractsystem.jl:179` )  

### Signature `Tuple{typeof(ModelingToolkit.namespace_pins), ModelingToolkit.AbstractSystem}`

Commit `c26cde7c1`: | => unstable (`ModelingToolkit` at `/tmp/jl_XqbwZG56Ro/src/systems/abstractsystem.jl:168` )  
Commit `f6802a5ff`: unstable => | (`ModelingToolkit` at `/tmp/jl_pURKJoFovK/src/systems/abstractsystem.jl:180` )  

### Signature `Tuple{typeof(ModelingToolkit.get_inequality_constraints), ModelingToolkit.AbstractSystem}`

Commit `0176fef5a`: | => unstable (`ModelingToolkit` at `/tmp/jl_9SvuJy76dk/src/systems/abstractsystem.jl:161` )  
Commit `fff670e88`: unstable => | (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/abstractsystem.jl:229` )  

### Signature `Tuple{typeof(toexpr), Num}`

Commit `70d876beb`: | => unstable (`ModelingToolkit` at `/tmp/jl_50J2nYPUP6/src/direct.jl:230` )  

### Signature `Tuple{typeof(ModelingToolkit.eliminate_constants), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:1145` )  

### Signature `Tuple{typeof(ModelingToolkit.defaults), ModelingToolkit.AbstractSystem}`

Commit `89c03eab8`: | => unstable (`ModelingToolkit` at `/tmp/jl_5mBwzqjqZw/src/systems/abstractsystem.jl:347` )  

### Signature `Tuple{typeof(ModelingToolkit.isconstant), Num}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/constants.jl:4` )  

### Signature `Tuple{typeof(ModelingToolkit.generate_dae_jacobian), ModelingToolkit.AbstractODESystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/diffeqs/abstractodesystem.jl:104` )  

### Signature `Tuple{typeof(simplify), Expression}`

Commit `dc0bcf68f`: | => unstable (`ModelingToolkit` at `/tmp/jl_zSNELMJgNG/src/simplify.jl:38` )  
Commit `70d876beb`: unstable => | (`ModelingToolkit` at `/tmp/jl_di1SRApOR4/src/simplify.jl:38` )  

### Signature `Tuple{typeof(tearing), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit.StructuralTransformations` at `/tmp/jl_jKHsZuDEz4/src/structural_transformation/symbolics_tearing.jl:700` )  

### Signature `Tuple{typeof(ModelingToolkit.get_ivs), ModelingToolkit.AbstractSystem}`

Commit `8d5661f4d`: | => unstable (`ModelingToolkit` at `/tmp/jl_1Wvkfat0Hi/src/systems/abstractsystem.jl:194` )  

### Signature `Tuple{typeof(ModelingToolkit.get_domain), ModelingToolkit.AbstractSystem}`

Commit `89c03eab8`: | => unstable (`ModelingToolkit` at `/tmp/jl_5mBwzqjqZw/src/systems/abstractsystem.jl:165` )  

### Signature `Tuple{typeof(ModelingToolkit.get_time_domain), Num}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/clock.jl:32` )  

### Signature `Tuple{typeof(generate_function), DiscreteSystem}`

Commit `c0fe23654`: | => unstable (`ModelingToolkit` at `/tmp/jl_RcVULoBGXe/src/systems/discrete_system/discrete_system.jl:130` )  

### Signature `Tuple{typeof(ModelingToolkit.get_connector_type), ModelingToolkit.AbstractSystem}`

Commit `456f00fa1`: | => unstable (`ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/systems/abstractsystem.jl:229` )  

### Signature `Tuple{typeof(equations), ModelingToolkit.AbstractOptimizationSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/optimization/optimizationsystem.jl:69` )  

### Signature `Tuple{typeof(ModelingToolkit.get_connections), ModelingToolkit.AbstractSystem}`

Commit `456f00fa1`: | => unstable (`ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/systems/abstractsystem.jl:229` )  
Commit `fff670e88`: unstable => partial (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/abstractsystem.jl:229` => `ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:227` )  

### Signature `Tuple{typeof(ModelingToolkit.connector_type), ModelingToolkit.AbstractSystem}`

Commit `456f00fa1`: | => unstable (`ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/systems/connectors.jl:33` )  

### Signature `Tuple{typeof(ModelingToolkit.get_dvs), ModelingToolkit.AbstractSystem}`

Commit `8d5661f4d`: | => unstable (`ModelingToolkit` at `/tmp/jl_1Wvkfat0Hi/src/systems/abstractsystem.jl:194` )  

### Signature `Tuple{typeof(generate_hessian), ConstraintsSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/optimization/constraints_system.jl:172` )  

### Signature `Tuple{typeof(ModelingToolkit.namespace_variables), ModelingToolkit.AbstractODESystem}`

Commit `7f051bb34`: stable => unstable (`ModelingToolkit` at `/tmp/jl_X8titk3A5i/src/systems/diffeqs/abstractodesystem.jl:170` => `ModelingToolkit` at `/tmp/jl_nK9wfszYx8/src/systems/diffeqs/abstractodesystem.jl:170` )  
Commit `fc5a147a8`: unstable => | (`ModelingToolkit` at `/tmp/jl_fifo9Mdsr6/src/systems/diffeqs/abstractodesystem.jl:116` )  

### Signature `Tuple{typeof(ModelingToolkit.alias_eliminate_graph), ModelingToolkit.AbstractSystem}`

Commit `456f00fa1`: | => unstable (`ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/systems/alias_elimination.jl:5` )  
Commit `fff670e88`: unstable => | (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/alias_elimination.jl:5` )  

### Signature `Tuple{typeof(toexpr), Complex{Num}}`

Commit `7331b0c96`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/H8dtg/src/Symbolics.jl:51` )  

### Signature `Tuple{typeof(equations), ReactionSystem}`

Commit `935a32ea2`: | => unstable (`ModelingToolkit` at `/tmp/jl_HYveX2v8N4/src/systems/reaction/reactionsystem.jl:165` )  
Commit `9771134c0`: unstable => | (`ModelingToolkit` at `/tmp/jl_JMlETOrG1U/src/systems/reaction/reactionsystem.jl:176` )  

### Signature `Tuple{typeof(simplify_fractions), Num}`

Commit `456f00fa1`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/UrqtQ/src/Symbolics.jl:156` )  

### Signature `Tuple{typeof(independent_variable), ModelingToolkit.AbstractODESystem}`

Commit `7f051bb34`: stable => unstable (`ModelingToolkit` at `/tmp/jl_X8titk3A5i/src/systems/diffeqs/abstractodesystem.jl:195` => `ModelingToolkit` at `/tmp/jl_nK9wfszYx8/src/systems/diffeqs/abstractodesystem.jl:195` )  
Commit `fc5a147a8`: unstable => | (`ModelingToolkit` at `/tmp/jl_fifo9Mdsr6/src/systems/diffeqs/abstractodesystem.jl:143` )  

### Signature `Tuple{typeof(ModelingToolkit.namespace_variables), ModelingToolkit.AbstractSystem}`

Commit `fc5a147a8`: | => unstable (`ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/abstractsystem.jl:30` )  

### Signature `Tuple{typeof(ModelingToolkit.instantiate), Num}`

Commit `70d876beb`: | => unstable (`ModelingToolkit` at `/tmp/jl_50J2nYPUP6/src/systems/diffeqs/validation.jl:5` )  
Commit `88fe45e52`: unstable => | (`ModelingToolkit` at `/tmp/jl_xCbOr0vOha/src/systems/diffeqs/validation.jl:5` )  

### Signature `Tuple{typeof(ModelingToolkit.instantiate), ModelingToolkit.Constant}`

Commit `9616b0130`: | => unstable (`ModelingToolkit` at `/tmp/jl_j0tU527Qhm/src/systems/diffeqs/validation.jl:3` )  
Commit `70d876beb`: unstable => | (`ModelingToolkit` at `/tmp/jl_di1SRApOR4/src/systems/diffeqs/validation.jl:3` )  

### Signature `Tuple{typeof(ModelingToolkit.get_defaults), ModelingToolkit.AbstractSystem}`

Commit `89c03eab8`: | => unstable (`ModelingToolkit` at `/tmp/jl_5mBwzqjqZw/src/systems/abstractsystem.jl:165` )  

### Signature `Tuple{typeof(ModelingToolkit.get_default_p), ModelingToolkit.AbstractSystem}`

Commit `f6802a5ff`: | => unstable (`ModelingToolkit` at `/tmp/jl_nmtihmtOBQ/src/systems/abstractsystem.jl:141` )  
Commit `89c03eab8`: unstable => | (`ModelingToolkit` at `/tmp/jl_lM3s1m1Sz4/src/systems/abstractsystem.jl:162` )  

### Signature `Tuple{typeof(ModelingToolkit.validate), ModelingToolkit.AbstractODESystem}`

Commit `9616b0130`: | => unstable (`ModelingToolkit` at `/tmp/jl_j0tU527Qhm/src/systems/diffeqs/validation.jl:24` )  
Commit `88fe45e52`: unstable => | (`ModelingToolkit` at `/tmp/jl_xCbOr0vOha/src/systems/diffeqs/validation.jl:24` )  

### Signature `Tuple{typeof(ModelingToolkit.toconstant), Num}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/constants.jl:24` )  

### Signature `Tuple{typeof(ModelingToolkit.makesym), Num}`

Commit `f38063941`: | => unstable (`ModelingToolkit` at `/tmp/jl_bmboRmvoRU/src/systems/diffeqs/abstractodesystem.jl:108` )  
Commit `83312e349`: unstable => | (`ModelingToolkit` at `/tmp/jl_543KVovEVM/src/utils.jl:259` )  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.Let}`

Commit `456f00fa1`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156` )  

### Signature `Tuple{typeof(ModelingToolkit.get_torn_matching), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:227` )  

### Signature `Tuple{typeof(ModelingToolkit.output_timedomain), Sample}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/discretedomain.jl:226` )  

### Signature `Tuple{typeof(ModelingToolkit.generate_connection_set), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/connectors.jl:207` )  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.DestructuredArgs}`

Commit `456f00fa1`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156` )  

### Signature `Tuple{typeof(ModelingToolkit.get_bcs), ModelingToolkit.AbstractSystem}`

Commit `89c03eab8`: | => unstable (`ModelingToolkit` at `/tmp/jl_5mBwzqjqZw/src/systems/abstractsystem.jl:165` )  

### Signature `Tuple{typeof(structural_simplify), ModelingToolkit.AbstractSystem}`

Commit `bb4fb15cf`: | => unstable (`ModelingToolkit` at `/tmp/jl_3itmF0nu7U/src/systems/abstractsystem.jl:472` )  

### Signature `Tuple{typeof(ModelingToolkit.rename_lower_order), Expression}`

Commit `2b59e8ae7`: | => unstable (`ModelingToolkit` at `/tmp/jl_fifo9Mdsr6/src/systems/diffeqs/first_order_transform.jl:53` )  
Commit `70d876beb`: unstable => | (`ModelingToolkit` at `/tmp/jl_di1SRApOR4/src/systems/diffeqs/first_order_transform.jl:65` )  

### Signature `Tuple{typeof(states), ModelingToolkit.AbstractODESystem}`

Commit `7f051bb34`: stable => unstable (`ModelingToolkit` at `/tmp/jl_X8titk3A5i/src/systems/diffeqs/abstractodesystem.jl:196` => `ModelingToolkit` at `/tmp/jl_nK9wfszYx8/src/systems/diffeqs/abstractodesystem.jl:196` )  
Commit `fc5a147a8`: unstable => | (`ModelingToolkit` at `/tmp/jl_fifo9Mdsr6/src/systems/diffeqs/abstractodesystem.jl:144` )  

### Signature `Tuple{typeof(ModelingToolkit.__init__)}`

Commit `df03a125f`: | => unstable (`ModelingToolkit` at `/tmp/jl_vu7Czk1K5s/src/ModelingToolkit.jl:155` )  
Commit `ae4f53cad`: unstable => | (`ModelingToolkit` at `/tmp/jl_9SvuJy76dk/src/ModelingToolkit.jl:300` )  

### Signature `Tuple{typeof(ModelingToolkit.get_unit), SciMLBase.NullParameters}`

Commit `456f00fa1`: | => unstable (`ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/systems/validation.jl:45` )  
Commit `fff670e88`: unstable => stable (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/validation.jl:45` => `ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/validation.jl:55` )  

### Signature `Tuple{typeof(ModelingToolkit.conditions), Vector{<:ModelingToolkit.SymbolicDiscreteCallback}}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/callbacks.jl:209` )  

### Signature `Tuple{typeof(independent_variable), ModelingToolkit.AbstractSystem}`

Commit `fc5a147a8`: | => unstable (`ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/abstractsystem.jl:55` )  
Commit `fff670e88`: unstable => partial (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/abstractsystem.jl:135` => `ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:150` )  

### Signature `Tuple{typeof(calculate_tgrad), ModelingToolkit.AbstractODESystem}`

Commit `fc5a147a8`: | => unstable (`ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/diffeqs/abstractodesystem.jl:1` )  

### Signature `Tuple{typeof(controls), ModelingToolkit.AbstractSystem}`

Commit `38ac57174`: | => unstable (`ModelingToolkit` at `/tmp/jl_7w9atCzAR6/src/systems/abstractsystem.jl:371` )  

### Signature `Tuple{typeof(pins), ModelingToolkit.AbstractSystem}`

Commit `c26cde7c1`: | => unstable (`ModelingToolkit` at `/tmp/jl_XqbwZG56Ro/src/systems/abstractsystem.jl:193` )  
Commit `f6802a5ff`: unstable => | (`ModelingToolkit` at `/tmp/jl_pURKJoFovK/src/systems/abstractsystem.jl:220` )  

### Signature `Tuple{typeof(get_variables), Equation}`

Commit `456f00fa1`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/UrqtQ/src/equations.jl:131` )  

### Signature `Tuple{typeof(ModelingToolkit.func), ModelingToolkit.FunctionalAffect}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/callbacks.jl:36` )  

### Signature `Tuple{typeof(parse_expr_to_symbolic), Symbol, Module}`

Commit `456f00fa1`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/UrqtQ/src/parsing.jl:70` )  

### Signature `Tuple{typeof(ModelingToolkit.get_Wfact), ModelingToolkit.AbstractSystem}`

Commit `f6802a5ff`: | => unstable (`ModelingToolkit` at `/tmp/jl_nmtihmtOBQ/src/systems/abstractsystem.jl:141` )  

### Signature `Tuple{typeof(generate_function), ConstraintsSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/optimization/constraints_system.jl:178` )  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.AtIndex}`

Commit `456f00fa1`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156` )  

### Signature `Tuple{typeof(ModelingToolkit.get_jac), ModelingToolkit.AbstractSystem}`

Commit `f6802a5ff`: | => unstable (`ModelingToolkit` at `/tmp/jl_nmtihmtOBQ/src/systems/abstractsystem.jl:141` )  

### Signature `Tuple{typeof(ModelingToolkit.namespace_equations), ModelingToolkit.AbstractODESystem}`

Commit `416f5e849`: stable => unstable (`ModelingToolkit` at `/tmp/jl_7WVeNMVYNI/src/systems/diffeqs/abstractodesystem.jl:176` => `ModelingToolkit` at `/tmp/jl_X8titk3A5i/src/systems/diffeqs/abstractodesystem.jl:178` )  
Commit `fc5a147a8`: unstable => | (`ModelingToolkit` at `/tmp/jl_fifo9Mdsr6/src/systems/diffeqs/abstractodesystem.jl:124` )  

### Signature `Tuple{typeof(ModelingToolkit.get_unit), Real}`

Commit `88fe45e52`: | => unstable (`ModelingToolkit` at `/tmp/jl_VMjerMN83m/src/systems/validation.jl:14` )  

### Signature `Tuple{typeof(ModelingToolkit.get_systems), Connection}`

Commit `456f00fa1`: | => unstable (`ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/systems/connectors.jl:57` )  

### Signature `Tuple{typeof(ModelingToolkit.generate_discrete_callbacks), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/callbacks.jl:482` )  

### Signature `Tuple{typeof(ode_order_lowering), ODESystem}`

Commit `fefe559e6`: stable => unstable (`ModelingToolkit` at `/tmp/jl_3WbYV0zCPO/src/systems/diffeqs/first_order_transform.jl:7` => `ModelingToolkit` at `/tmp/jl_XQdMzqFsnO/src/systems/diffeqs/first_order_transform.jl:7` )  

### Signature `Tuple{typeof(ModelingToolkit.get_metadata), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:227` )  

### Signature `Tuple{typeof(observed), ModelingToolkit.AbstractSystem}`

Commit `c26cde7c1`: | => unstable (`ModelingToolkit` at `/tmp/jl_XqbwZG56Ro/src/systems/abstractsystem.jl:194` )  

### Signature `Tuple{typeof(ModelingToolkit.generate_factorized_W), ModelingToolkit.AbstractODESystem}`

Commit `fc5a147a8`: stable => unstable (`ModelingToolkit` at `/tmp/jl_fifo9Mdsr6/src/systems/diffeqs/abstractodesystem.jl:78` => `ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/diffeqs/abstractodesystem.jl:78` )  
Commit `229ab2066`: unstable => | (`ModelingToolkit` at `/tmp/jl_fUPORWTEtE/src/systems/diffeqs/abstractodesystem.jl:81` )  

### Signature `Tuple{typeof(operation), Metatheory.EMatchCompiler.Filter}`

Commit `456f00fa1`: | => unstable (`Metatheory.EMatchCompiler` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/ematch_compiler.jl:86` )  
Commit `fff670e88`: unstable => | (`Metatheory.EMatchCompiler` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/ematch_compiler.jl:86` )  

### Signature `Tuple{typeof(ModelingToolkit.continuous_events), ModelingToolkit.AbstractSystem}`

Commit `456f00fa1`: | => unstable (`ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/systems/abstractsystem.jl:456` )  

### Signature `Tuple{typeof(ModelingToolkit.calculate_factorized_W), ModelingToolkit.AbstractODESystem}`

Commit `fd72716d7`: | => unstable (`ModelingToolkit` at `/tmp/jl_7qp8ba5MPU/src/systems/diffeqs/abstractodesystem.jl:54` )  
Commit `229ab2066`: unstable => | (`ModelingToolkit` at `/tmp/jl_fUPORWTEtE/src/systems/diffeqs/abstractodesystem.jl:57` )  

### Signature `Tuple{typeof(ModelingToolkit.get_substitutions), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:227` )  

### Signature `Tuple{typeof(ModelingToolkit.get_noiseeqs), ModelingToolkit.AbstractSystem}`

Commit `74812c4e8`: | => unstable (`ModelingToolkit` at `/tmp/jl_PwtoLkTgp8/src/systems/abstractsystem.jl:156` )  

### Signature `Tuple{typeof(ModelingToolkit.context), ModelingToolkit.FunctionalAffect}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/callbacks.jl:37` )  

### Signature `Tuple{typeof(operation), Metatheory.Patterns.PatTerm}`

Commit `456f00fa1`: | => unstable (`Metatheory.Patterns` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/Patterns.jl:100` )  
Commit `fff670e88`: unstable => | (`Metatheory.Patterns` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/Patterns.jl:100` )  

### Signature `Tuple{typeof(full_equations), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit.StructuralTransformations` at `/tmp/jl_jKHsZuDEz4/src/structural_transformation/symbolics_tearing.jl:88` )  

### Signature `Tuple{typeof(ModelingToolkit.preface), ModelingToolkit.AbstractSystem}`

Commit `5a47dd69a`: | => unstable (`ModelingToolkit` at `/tmp/jl_by9enEZgfm/src/systems/abstractsystem.jl:466` )  

### Signature `Tuple{typeof(generate_factorized_W), ModelingToolkit.AbstractODESystem}`

Commit `229ab2066`: | => unstable (`ModelingToolkit` at `/tmp/jl_Hu523MHUlk/src/systems/diffeqs/abstractodesystem.jl:86` )  
Commit `5f4999377`: unstable => | (`ModelingToolkit` at `/tmp/jl_lYb2tENWD4/src/systems/diffeqs/abstractodesystem.jl:87` )  

### Signature `Tuple{typeof(ModelingToolkit.calculate_tgrad), ODESystem}`

Commit `5a6de343b`: | => unstable (`ModelingToolkit` at `/tmp/jl_jIn63CtCpk/src/systems/diffeqs/diffeqsystem.jl:142` )  
Commit `fd72716d7`: unstable => | (`ModelingToolkit` at `/tmp/jl_bWzy9AzYNU/src/systems/diffeqs/diffeqsystem.jl:141` )  

### Signature `Tuple{typeof(ModelingToolkit.tosymbol), Num}`

Commit `f38063941`: | => unstable (`ModelingToolkit` at `/tmp/jl_bmboRmvoRU/src/systems/diffeqs/abstractodesystem.jl:74` )  
Commit `83312e349`: unstable => | (`ModelingToolkit` at `/tmp/jl_543KVovEVM/src/utils.jl:205` )  

### Signature `Tuple{typeof(ModelingToolkit.get_discrete_subsystems), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:227` )  

### Signature `Tuple{typeof(tearing_substitution), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit.StructuralTransformations` at `/tmp/jl_jKHsZuDEz4/src/structural_transformation/symbolics_tearing.jl:115` )  

### Signature `Tuple{typeof(ModelingToolkit.sampletime), Sample}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/discretedomain.jl:236` )  

### Signature `Tuple{typeof(states), ModelingToolkit.FunctionalAffect}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/callbacks.jl:40` )  

### Signature `Tuple{typeof(controls), ModelingToolkit.AbstractControlSystem}`

Commit `6c5935afb`: | => unstable (`ModelingToolkit` at `/tmp/jl_vIH0J8BOPW/src/systems/control/controlsystem.jl:19` )  
Commit `fff670e88`: unstable => | (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/control/controlsystem.jl:19` )  

### Signature `Tuple{typeof(ModelingToolkit._isone), Number}`

Commit `dba32a996`: | => unstable (`ModelingToolkit` at `/tmp/jl_1wfAnuV2ZO/src/solve.jl:85` )  
Commit `83312e349`: unstable => | (`ModelingToolkit` at `/tmp/jl_543KVovEVM/src/solve.jl:109` )  

### Signature `Tuple{typeof(ModelingToolkit._iszero), Number}`

Commit `dba32a996`: | => unstable (`ModelingToolkit` at `/tmp/jl_1wfAnuV2ZO/src/solve.jl:84` )  
Commit `83312e349`: unstable => | (`ModelingToolkit` at `/tmp/jl_543KVovEVM/src/solve.jl:108` )  

### Signature `Tuple{typeof(ModelingToolkit.discrete_events), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/callbacks.jl:231` )  

### Signature `Tuple{typeof(generate_function), NonlinearSystem}`

Commit `f6802a5ff`: stable => unstable (`ModelingToolkit` at `/tmp/jl_pURKJoFovK/src/systems/nonlinear/nonlinearsystem.jl:66` => `ModelingToolkit` at `/tmp/jl_nmtihmtOBQ/src/systems/nonlinear/nonlinearsystem.jl:84` )  

### Signature `Tuple{typeof(generate_tgrad), ModelingToolkit.AbstractODESystem}`

Commit `fc5a147a8`: | => unstable (`ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/diffeqs/abstractodesystem.jl:37` )  

### Signature `Tuple{typeof(ModelingToolkit.generate_rootfinding_callback), ODESystem}`

Commit `456f00fa1`: | => unstable (`ModelingToolkit` at `/tmp/jl_pcJungLwHE/src/systems/diffeqs/abstractodesystem.jl:156` )  
Commit `fff670e88`: unstable => | (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/diffeqs/abstractodesystem.jl:156` )  

### Signature `Tuple{typeof(isintegervar), Num}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/variables.jl:383` )  

### Signature `Tuple{typeof(ModelingToolkit.get_tspan), ModelingToolkit.AbstractSystem}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/abstractsystem.jl:227` )  

### Signature `Tuple{typeof(ModelingToolkit.namespace_equations), ModelingToolkit.AbstractSystem}`

Commit `fc5a147a8`: | => unstable (`ModelingToolkit` at `/tmp/jl_x4vgfgDA1y/src/systems/abstractsystem.jl:38` )  

### Signature `Tuple{typeof(ModelingToolkit.namespace_controls), ModelingToolkit.AbstractControlSystem}`

Commit `38ac57174`: | => unstable (`ModelingToolkit` at `/tmp/jl_7w9atCzAR6/src/systems/control/controlsystem.jl:3` )  
Commit `fff670e88`: unstable => | (`ModelingToolkit` at `/tmp/jl_F6X8lUpYp2/src/systems/control/controlsystem.jl:3` )  

### Signature `Tuple{typeof(ModelingToolkit.get_states), ModelingToolkit.AbstractSystem}`

Commit `f6802a5ff`: | => unstable (`ModelingToolkit` at `/tmp/jl_nmtihmtOBQ/src/systems/abstractsystem.jl:141` )  

### Signature `Tuple{typeof(ModelingToolkit.namespaced_var), ModelingToolkit.ConnectionElement}`

Commit `fff670e88`: | => unstable (`ModelingToolkit` at `/tmp/jl_jKHsZuDEz4/src/systems/connectors.jl:163` )  


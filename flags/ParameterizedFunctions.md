# Stability change report for package `ParameterizedFunctions`

### Signature `Tuple{typeof(simplify), Equation}`

Commit `22f7381`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/equations.jl:18`)  

### Signature `Tuple{typeof(variable_dependencies), ModelingToolkit.AbstractSystem}`

Commit `22f7381`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/dependency_graphs.jl:191`)  

### Signature `Tuple{typeof(structural_simplify), ModelingToolkit.AbstractSystem}`

Commit `b443b8b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/yGWxM/src/systems/abstractsystem.jl:766`)  

### Signature `Tuple{typeof(simplify), Num}`

Commit `b443b8b`: stable => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/ModelingToolkit.jl:58` => `Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/H8dtg/src/Symbolics.jl:45`)  

### Signature `Tuple{typeof(operation), Metatheory.EMatchCompiler.ENodePat}`

Commit `b8df68b`: | => unstable (`Metatheory.EMatchCompiler` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/ematch_compiler.jl:47`)  
Commit `5c050d0`: unstable => | (`Metatheory.EMatchCompiler` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/ematch_compiler.jl:47`)  

### Signature `Tuple{typeof(calculate_hessian), NonlinearSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/nonlinear/nonlinearsystem.jl:162`)  

### Signature `Tuple{typeof(states), ModelingToolkit.AbstractSystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/abstractsystem.jl:175`)  

### Signature `Tuple{typeof(parameters), ModelingToolkit.AbstractSystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/abstractsystem.jl:176`)  

### Signature `Tuple{typeof(independent_variable), ModelingToolkit.AbstractSystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/abstractsystem.jl:174`)  
Commit `5c050d0`: unstable => partial (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/abstractsystem.jl:144` => `ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/FbXPg/src/systems/abstractsystem.jl:158`)  

### Signature `Tuple{typeof(calculate_tgrad), ModelingToolkit.AbstractODESystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/diffeqs/abstractodesystem.jl:1`)  

### Signature `Tuple{typeof(controls), ModelingToolkit.AbstractSystem}`

Commit `b443b8b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/yGWxM/src/systems/abstractsystem.jl:385`)  

### Signature `Tuple{typeof(pins), ModelingToolkit.AbstractSystem}`

Commit `22f7381`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/abstractsystem.jl:207`)  
Commit `b443b8b`: unstable => | (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/abstractsystem.jl:207`)  

### Signature `Tuple{typeof(generate_gradient), OptimizationSystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/optimization/optimizationsystem.jl:46`)  
Commit `986dfeb`: unstable => | (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/optimization/optimizationsystem.jl:46`)  
Commit `22f7381`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/optimization/optimizationsystem.jl:54`)  

### Signature `Tuple{typeof(calculate_gradient), OptimizationSystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/optimization/optimizationsystem.jl:42`)  
Commit `986dfeb`: unstable => | (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/optimization/optimizationsystem.jl:42`)  
Commit `22f7381`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/optimization/optimizationsystem.jl:50`)  

### Signature `Tuple{typeof(simplify), Complex{Num}}`

Commit `b443b8b`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/H8dtg/src/Symbolics.jl:45`)  

### Signature `Tuple{typeof(get_variables), Equation}`

Commit `b8df68b`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/UrqtQ/src/equations.jl:131`)  

### Signature `Tuple{typeof(parse_expr_to_symbolic), Symbol, Module}`

Commit `b8df68b`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/UrqtQ/src/parsing.jl:70`)  

### Signature `Tuple{typeof(calculate_factorized_W), ModelingToolkit.AbstractODESystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/diffeqs/abstractodesystem.jl:62`)  
Commit `986dfeb`: unstable => | (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/diffeqs/abstractodesystem.jl:62`)  

### Signature `Tuple{typeof(equations), ConstraintsSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/optimization/constraints_system.jl:88`)  

### Signature `Tuple{typeof(simplified_expr), ModelingToolkit.Constant}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/direct.jl:52`)  
Commit `22f7381`: unstable => | (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/N4mo2/src/direct.jl:28`)  

### Signature `Tuple{typeof(generate_function), ConstraintsSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/optimization/constraints_system.jl:178`)  

### Signature `Tuple{typeof(calculate_control_jacobian), ModelingToolkit.AbstractODESystem}`

Commit `b443b8b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/yGWxM/src/systems/diffeqs/abstractodesystem.jl:41`)  

### Signature `Tuple{typeof(generate_jacobian), ModelingToolkit.AbstractODESystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/diffeqs/abstractodesystem.jl:45`)  

### Signature `Tuple{typeof(generate_hessian), NonlinearSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/nonlinear/nonlinearsystem.jl:173`)  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.AtIndex}`

Commit `b8df68b`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156`)  

### Signature `Tuple{typeof(expand), Complex{Num}}`

Commit `b443b8b`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/H8dtg/src/Symbolics.jl:46`)  

### Signature `Tuple{typeof(independent_variables), ModelingToolkit.AbstractSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/abstractsystem.jl:151`)  

### Signature `Tuple{typeof(isbinaryvar), Num}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/variables.jl:354`)  

### Signature `Tuple{typeof(calculate_hessian), OptimizationSystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/optimization/optimizationsystem.jl:52`)  
Commit `22f7381`: unstable => stable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/N4mo2/src/systems/optimization/optimizationsystem.jl:42` => `ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/optimization/optimizationsystem.jl:60`)  

### Signature `Tuple{typeof(tearing_assignments), ModelingToolkit.AbstractSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit.StructuralTransformations` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/structural_transformation/symbolics_tearing.jl:121`)  

### Signature `Tuple{typeof(ode_order_lowering), ODESystem}`

Commit `b443b8b`: stable => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/diffeqs/first_order_transform.jl:7` => `ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/yGWxM/src/systems/diffeqs/first_order_transform.jl:7`)  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.MakeTuple}`

Commit `b8df68b`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156`)  

### Signature `Tuple{typeof(observed), ModelingToolkit.AbstractSystem}`

Commit `22f7381`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/abstractsystem.jl:208`)  

### Signature `Tuple{typeof(operation), Metatheory.EMatchCompiler.Filter}`

Commit `b8df68b`: | => unstable (`Metatheory.EMatchCompiler` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/ematch_compiler.jl:86`)  
Commit `5c050d0`: unstable => | (`Metatheory.EMatchCompiler` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/ematch_compiler.jl:86`)  

### Signature `Tuple{typeof(getdescription), Num}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/variables.jl:333`)  

### Signature `Tuple{typeof(expand_derivatives), Operation}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/differentials.jl:39`)  
Commit `22f7381`: unstable => | (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/N4mo2/src/differentials.jl:39`)  

### Signature `Tuple{typeof(calculate_jacobian), NonlinearSystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/nonlinear/nonlinearsystem.jl:44`)  

### Signature `Tuple{typeof(generate_control_jacobian), ModelingToolkit.AbstractODESystem}`

Commit `b443b8b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/yGWxM/src/systems/diffeqs/abstractodesystem.jl:75`)  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.Func}`

Commit `b8df68b`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156`)  

### Signature `Tuple{typeof(toexpr), Num}`

Commit `22f7381`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/direct.jl:240`)  

### Signature `Tuple{typeof(get_variables), Inequality}`

Commit `b8df68b`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/UrqtQ/src/inequality.jl:111`)  

### Signature `Tuple{typeof(expand), Num}`

Commit `b443b8b`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/H8dtg/src/Symbolics.jl:46`)  

### Signature `Tuple{typeof(generate_jacobian), ConstraintsSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/optimization/constraints_system.jl:155`)  

### Signature `Tuple{typeof(calculate_jacobian), ModelingToolkit.AbstractODESystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/diffeqs/abstractodesystem.jl:11`)  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.SetArray}`

Commit `b8df68b`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156`)  

### Signature `Tuple{typeof(operation), Expr}`

Commit `b8df68b`: | => unstable (`TermInterface` at `/home/jecmejan/.julia/packages/TermInterface/hZ5oG/src/expr.jl:7`)  
Commit `5c050d0`: unstable => | (`TermInterface` at `/home/jecmejan/.julia/packages/TermInterface/hZ5oG/src/expr.jl:7`)  

### Signature `Tuple{typeof(tearing), ModelingToolkit.AbstractSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit.StructuralTransformations` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/structural_transformation/symbolics_tearing.jl:700`)  

### Signature `Tuple{typeof(equations), OptimizationSystem}`

Commit `22f7381`: stable => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/N4mo2/src/systems/optimization/optimizationsystem.jl:57` => `ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/optimization/optimizationsystem.jl:80`)  
Commit `b8df68b`: unstable => | (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/yGWxM/src/systems/optimization/optimizationsystem.jl:108`)  

### Signature `Tuple{typeof(getbounds), ModelingToolkit.AbstractSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/variables.jl:308`)  

### Signature `Tuple{typeof(operation), Metatheory.Patterns.PatTerm}`

Commit `b8df68b`: | => unstable (`Metatheory.Patterns` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/Patterns.jl:100`)  
Commit `5c050d0`: unstable => | (`Metatheory.Patterns` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/Patterns.jl:100`)  

### Signature `Tuple{typeof(generate_diffusion_function), SDESystem}`

Commit `986dfeb`: stable => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/diffeqs/sdesystem.jl:83` => `ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/N4mo2/src/systems/diffeqs/sdesystem.jl:55`)  
Commit `22f7381`: unstable => stable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/N4mo2/src/systems/diffeqs/sdesystem.jl:55` => `ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/diffeqs/sdesystem.jl:87`)  
Commit `b443b8b`: stable => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/diffeqs/sdesystem.jl:87` => `ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/yGWxM/src/systems/diffeqs/sdesystem.jl:137`)  
Commit `b8df68b`: unstable => stable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/yGWxM/src/systems/diffeqs/sdesystem.jl:137` => `ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/diffeqs/sdesystem.jl:193`)  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.Assignment}`

Commit `b8df68b`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156`)  

### Signature `Tuple{typeof(generate_function), DiscreteSystem}`

Commit `b443b8b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/yGWxM/src/systems/discrete_system/discrete_system.jl:130`)  

### Signature `Tuple{typeof(full_equations), ModelingToolkit.AbstractSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit.StructuralTransformations` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/structural_transformation/symbolics_tearing.jl:88`)  

### Signature `Tuple{typeof(equations), ModelingToolkit.AbstractOptimizationSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/optimization/optimizationsystem.jl:69`)  

### Signature `Tuple{typeof(generate_jacobian), NonlinearSystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/nonlinear/nonlinearsystem.jl:50`)  

### Signature `Tuple{typeof(generate_factorized_W), ModelingToolkit.AbstractODESystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/diffeqs/abstractodesystem.jl:86`)  
Commit `986dfeb`: unstable => | (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/diffeqs/abstractodesystem.jl:86`)  

### Signature `Tuple{typeof(structural_simplify), OptimizationSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/optimization/optimizationsystem.jl:584`)  

### Signature `Tuple{typeof(dae_index_lowering), ODESystem}`

Commit `b443b8b`: | => unstable (`ModelingToolkit.StructuralTransformations` at `/home/jecmejan/.julia/packages/ModelingToolkit/yGWxM/src/structural_transformation/pantelides.jl:149`)  

### Signature `Tuple{typeof(generate_hessian), ConstraintsSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/optimization/constraints_system.jl:172`)  

### Signature `Tuple{typeof(get_variables), Num}`

Commit `22f7381`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/utils.jl:79`)  

### Signature `Tuple{typeof(expand_connections), ModelingToolkit.AbstractSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/connectors.jl:330`)  

### Signature `Tuple{typeof(tearing_substitution), ModelingToolkit.AbstractSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit.StructuralTransformations` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/structural_transformation/symbolics_tearing.jl:115`)  

### Signature `Tuple{typeof(getdist), Num}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/variables.jl:246`)  

### Signature `Tuple{typeof(states), ModelingToolkit.FunctionalAffect}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/callbacks.jl:40`)  

### Signature `Tuple{typeof(controls), ModelingToolkit.AbstractControlSystem}`

Commit `22f7381`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/control/controlsystem.jl:19`)  
Commit `b8df68b`: unstable => | (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/yGWxM/src/systems/control/controlsystem.jl:19`)  

### Signature `Tuple{typeof(toexpr), Complex{Num}}`

Commit `b443b8b`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/H8dtg/src/Symbolics.jl:51`)  

### Signature `Tuple{typeof(arguments), Metatheory.Patterns.PatTerm}`

Commit `b8df68b`: | => unstable (`Metatheory.Patterns` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/Patterns.jl:101`)  
Commit `5c050d0`: unstable => | (`Metatheory.Patterns` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/Patterns.jl:101`)  

### Signature `Tuple{typeof(dae_order_lowering), ODESystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/diffeqs/first_order_transform.jl:15`)  

### Signature `Tuple{typeof(independent_variables), AbstractTimeDependentSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/abstractsystem.jl:163`)  
Commit `5c050d0`: unstable => partial (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/abstractsystem.jl:163` => `ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/FbXPg/src/systems/abstractsystem.jl:177`)  

### Signature `Tuple{typeof(simplify_fractions), Num}`

Commit `b8df68b`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/UrqtQ/src/Symbolics.jl:156`)  

### Signature `Tuple{typeof(generate_difference_cb), ODESystem}`

Commit `b443b8b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/yGWxM/src/systems/diffeqs/abstractodesystem.jl:122`)  

### Signature `Tuple{typeof(generate_function), NonlinearSystem}`

Commit `b443b8b`: stable => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/nonlinear/nonlinearsystem.jl:66` => `ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/yGWxM/src/systems/nonlinear/nonlinearsystem.jl:112`)  

### Signature `Tuple{typeof(generate_tgrad), ModelingToolkit.AbstractODESystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/diffeqs/abstractodesystem.jl:39`)  

### Signature `Tuple{typeof(independent_variables), AbstractMultivariateSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/abstractsystem.jl:165`)  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.MakeArray}`

Commit `b8df68b`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156`)  

### Signature `Tuple{typeof(calculate_hessian), ConstraintsSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/optimization/constraints_system.jl:161`)  

### Signature `Tuple{typeof(equations), ModelingToolkit.AbstractSystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/abstractsystem.jl:178`)  

### Signature `Tuple{typeof(simplify_fractions), Complex{Num}}`

Commit `b8df68b`: | => unstable (`Symbolics` at `/home/jecmejan/.julia/packages/Symbolics/UrqtQ/src/Symbolics.jl:156`)  

### Signature `Tuple{typeof(calculate_massmatrix), ModelingToolkit.AbstractODESystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/diffeqs/abstractodesystem.jl:102`)  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.Let}`

Commit `b8df68b`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156`)  

### Signature `Tuple{typeof(add_accumulations), ODESystem}`

Commit `5c050d0`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/FbXPg/src/systems/diffeqs/odesystem.jl:464`)  

### Signature `Tuple{typeof(extend), ModelingToolkit.AbstractSystem, ModelingToolkit.AbstractSystem}`

Commit `b8df68b`: partial => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/yGWxM/src/systems/abstractsystem.jl:903` => `ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/abstractsystem.jl:1468`)  

### Signature `Tuple{typeof(generate_function), OptimizationSystem}`

Commit `22f7381`: stable => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/N4mo2/src/systems/optimization/optimizationsystem.jl:51` => `ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/optimization/optimizationsystem.jl:75`)  

### Signature `Tuple{typeof(isdisturbance), Num}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/variables.jl:201`)  

### Signature `Tuple{typeof(equation_dependencies), ModelingToolkit.AbstractSystem}`

Commit `22f7381`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/dependency_graphs.jl:44`)  

### Signature `Tuple{typeof(isintegervar), Num}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/variables.jl:371`)  

### Signature `Tuple{typeof(calculate_jacobian), ConstraintsSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/optimization/constraints_system.jl:138`)  

### Signature `Tuple{typeof(debug_system), ModelingToolkit.AbstractSystem}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/abstractsystem.jl:1027`)  

### Signature `Tuple{typeof(simplified_expr), Operation}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/direct.jl:40`)  
Commit `22f7381`: unstable => | (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/N4mo2/src/direct.jl:16`)  

### Signature `Tuple{typeof(getbounds), Num}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/variables.jl:169`)  

### Signature `Tuple{typeof(generate_hessian), OptimizationSystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/optimization/optimizationsystem.jl:56`)  
Commit `22f7381`: unstable => stable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/N4mo2/src/systems/optimization/optimizationsystem.jl:46` => `ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/Q7n8K/src/systems/optimization/optimizationsystem.jl:64`)  

### Signature `Tuple{typeof(parameters), ModelingToolkit.FunctionalAffect}`

Commit `b8df68b`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/gZ57L/src/systems/callbacks.jl:38`)  

### Signature `Tuple{typeof(generate_function), ModelingToolkit.AbstractODESystem}`

Commit `0a0b538`: | => unstable (`ModelingToolkit` at `/home/jecmejan/.julia/packages/ModelingToolkit/aKa4S/src/systems/diffeqs/abstractodesystem.jl:54`)  

### Signature `Tuple{typeof(arguments), SymbolicUtils.Code.DestructuredArgs}`

Commit `b8df68b`: | => unstable (`SymbolicUtils.Code` at `/home/jecmejan/.julia/packages/Metatheory/wqlT2/src/utils.jl:156`)  


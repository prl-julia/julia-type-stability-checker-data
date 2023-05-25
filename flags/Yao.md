# Stability change report for package `Yao`

### Signature `Tuple{typeof(yaofromstring), String}`

Commit `9f050d2c`: unstable => | (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/usXGg/src/treeutils/load.jl:13` )  
Commit `fb21a7a5`: | => unstable (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/LfPbW/src/treeutils/load.jl:13` )  

### Signature `Tuple{YaoBlocks.var"#@yao_str", LineNumberNode, Module, String}`

Commit `9f050d2c`: unstable => | (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/usXGg/src/treeutils/load.jl:9` )  
Commit `fb21a7a5`: | => unstable (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/LfPbW/src/treeutils/load.jl:9` )  

### Signature `Tuple{typeof(igate), Int64}`

Commit `9f050d2c`: unstable => | (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/usXGg/src/primitive/identity_gate.jl:24` )  
Commit `fb21a7a5`: | => unstable (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/LfPbW/src/primitive/identity_gate.jl:20` )  

### Signature `Tuple{typeof(yaofromfile), String}`

Commit `9f050d2c`: unstable => | (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/usXGg/src/treeutils/load.jl:46` )  
Commit `fb21a7a5`: | => unstable (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/LfPbW/src/treeutils/load.jl:44` )  

### Signature `Tuple{typeof(ghz_state), Int64}`

Commit `801f34f3`: | => unstable (`YaoArrayRegister` at `/home/jecmejan/.julia/packages/YaoArrayRegister/qGeWF/src/register.jl:566` )  

### Signature `Tuple{typeof(addbit!), Int64}`

Commit `e6fbc23d`: unstable => stable (`Yao` at `deprecated.jl:70` => `Yao` at `deprecated.jl:70` )  

### Signature `Tuple{typeof(swap), Int64, Int64, Int64}`

Commit `9f050d2c`: stable => unstable (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/usXGg/src/composite/put_block.jl:133` => `YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/fjUXD/src/primitive/swap_gate.jl:25` )  
Commit `de570b82`: unstable => stable (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/UDr4d/src/composite/put_block.jl:130` => `YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/usXGg/src/composite/put_block.jl:133` )  

### Signature `Tuple{typeof(completely_mixed_state), Int64}`

Commit `801f34f3`: | => unstable (`YaoArrayRegister` at `/home/jecmejan/.julia/packages/YaoArrayRegister/qGeWF/src/density_matrix.jl:55` )  
Commit `f69a26d1`: unstable => | (`YaoArrayRegister` at `/home/jecmejan/.julia/packages/YaoArrayRegister/qGeWF/src/density_matrix.jl:55` )  
Commit `2006fd0c`: | => unstable (`YaoArrayRegister` at `/home/jecmejan/.julia/packages/YaoArrayRegister/qGeWF/src/density_matrix.jl:55` )  

### Signature `Tuple{typeof(two_qubit_depolarizing_channel), Real}`

Commit `801f34f3`: | => unstable (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/wUHRm/src/channel/error_channel.jl:98` )  
Commit `f69a26d1`: unstable => | (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/wUHRm/src/channel/error_channel.jl:98` )  
Commit `2006fd0c`: | => unstable (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/wUHRm/src/channel/error_channel.jl:98` )  

### Signature `Tuple{typeof(isreflexive), Number}`

Commit `80d320a8`: partial => unstable (`YaoBase` at `/home/jecmejan/.julia/packages/YaoBase/EotlZ/src/inspect.jl:18` => `YaoBase` at `/home/jecmejan/.julia/packages/YaoBase/EotlZ/src/inspect.jl:18` )  
Commit `6218c531`: unstable => partial (`YaoBase` at `/home/jecmejan/.julia/packages/YaoBase/PI2Cs/src/inspect.jl:18` => `YaoBase` at `/home/jecmejan/.julia/packages/YaoBase/PI2Cs/src/inspect.jl:18` )  

### Signature `Tuple{typeof(reflect), AbstractVector{<:Complex}}`

Commit `9f050d2c`: | => unstable (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/fjUXD/src/primitive/reflect_gate.jl:46` )  
Commit `975aa1d1`: unstable => | (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/LfPbW/src/primitive/reflect_gate.jl:59` )  

### Signature `Tuple{typeof(ishermitian), Number}`

Commit `9f050d2c`: unstable => partial (`LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:1253` => `LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:1253` )  
Commit `80d320a8`: partial => unstable (`LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:1253` => `LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:1253` )  

### Signature `Tuple{typeof(rand_density_matrix), Int64}`

Commit `801f34f3`: | => unstable (`YaoArrayRegister` at `/home/jecmejan/.julia/packages/YaoArrayRegister/qGeWF/src/density_matrix.jl:37` )  
Commit `f69a26d1`: unstable => | (`YaoArrayRegister` at `/home/jecmejan/.julia/packages/YaoArrayRegister/qGeWF/src/density_matrix.jl:37` )  
Commit `2006fd0c`: | => unstable (`YaoArrayRegister` at `/home/jecmejan/.julia/packages/YaoArrayRegister/qGeWF/src/density_matrix.jl:37` )  

### Signature `Tuple{typeof(norm), Number}`

Commit `9f050d2c`: unstable => | (`LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633` )  
Commit `97ff65f9`: | => unstable (`LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633` )  

### Signature `Tuple{typeof(isunitary), Number}`

Commit `80d320a8`: partial => unstable (`YaoBase` at `/home/jecmejan/.julia/packages/YaoBase/EotlZ/src/inspect.jl:10` => `YaoBase` at `/home/jecmejan/.julia/packages/YaoBase/EotlZ/src/inspect.jl:10` )  
Commit `6218c531`: unstable => partial (`YaoBase` at `/home/jecmejan/.julia/packages/YaoBase/PI2Cs/src/inspect.jl:10` => `YaoBase` at `/home/jecmejan/.julia/packages/YaoBase/PI2Cs/src/inspect.jl:10` )  

### Signature `Tuple{typeof(kron), Int64}`

Commit `9f050d2c`: unstable => | (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/usXGg/src/composite/kron.jl:81` )  
Commit `d102cfd9`: | => unstable (`YaoBlocks` at `/home/jecmejan/.julia/packages/YaoBlocks/EiEj1/src/composite/kron.jl:75` )  

### Signature `Tuple{typeof(simplify_expi), Basic}`

Commit `80d320a8`: | => unstable (`YaoSym` at `/home/jecmejan/.julia/packages/YaoSym/PVFBP/src/symengine/patch.jl:28` )  
Commit `6218c531`: unstable => | (`YaoSym` at `/home/jecmejan/.julia/packages/YaoSym/a7pjG/src/symengine/patch.jl:35` )  


# Stability change report for package `ControlSystems`

### Signature `Tuple{typeof(zpk), AbstractString, Real}`

Commit `dda8d385`: partial => unstable (`ControlSystems` at `/tmp/jl_bC9IHQ5Mnm/src/types/zpk.jl:82` => `ControlSystems` at `/tmp/jl_bsFSz0naDg/src/types/zpk.jl:82`)  
Commit `fd558636`: unstable => tc-fail (`ControlSystems` at `/tmp/jl_dox4RIxAD4/src/types/zpk.jl:73` => `ControlSystems` at `/tmp/jl_zoNY7YV2XU/src/types/zpk.jl:73`)  
Commit `40b14894`: tc-fail => unstable (`ControlSystems` at `/tmp/jl_zoNY7YV2XU/src/types/zpk.jl:73` => `ControlSystems` at `/tmp/jl_v6rKz2JUBI/src/types/zpk.jl:73`)  

### Signature `Tuple{typeof(gangoffour), LQG}`

Commit `75339570`: unstable => | (`ControlSystems` at `/tmp/jl_hGhm161IZS/src/types/lqg.jl:254`)  

### Signature `Tuple{typeof(gangoffourplot), LQG}`

Commit `75339570`: unstable => | (`ControlSystems` at `/tmp/jl_hGhm161IZS/src/types/lqg.jl:258`)  

### Signature `Tuple{typeof(getindex), Core.MethodMatch, Int64}`

Commit `6249cba0`: | => unstable (`Base` at `deprecated.jl:228`)  
Commit `75339570`: unstable => | (`Base` at `deprecated.jl:228`)  

### Signature `Tuple{typeof(denpoly), ControlSystems.SisoZpk{<:Real}}`

Commit `b788f5fb`: partial => unstable (`ControlSystems` at `/tmp/jl_nqhcpofWZ0/src/types/SisoTfTypes/SisoZpk.jl:58` => `ControlSystems` at `/tmp/jl_9C1ytwt47K/src/types/SisoTfTypes/SisoZpk.jl:58`)  
Commit `0bb596b7`: unstable => nofuel (`ControlSystems` at `/tmp/jl_5I9C7UDWps/src/types/SisoTfTypes/SisoZpk.jl:52` => `ControlSystems` at `/tmp/jl_Rw5CjQHQzA/src/types/SisoTfTypes/SisoZpk.jl:52`)  

### Signature `Tuple{typeof(getindex), TranscodingStreams.Error}`

Commit `6249cba0`: | => unstable (`TranscodingStreams` at `/home/jecmejan/.julia/packages/TranscodingStreams/2McN2/src/error.jl:31`)  
Commit `75339570`: unstable => | (`TranscodingStreams` at `/home/jecmejan/.julia/packages/TranscodingStreams/2McN2/src/error.jl:31`)  

### Signature `Tuple{typeof(getindex), Core.Compiler.Instruction, Symbol}`

Commit `6249cba0`: | => unstable (`Base.IRShow` at `show.jl:2501`)  
Commit `75339570`: unstable => | (`Base.IRShow` at `show.jl:2501`)  

### Signature `Tuple{typeof(getindex), CSV.File, String}`

Commit `6249cba0`: | => unstable (`CSV` at `/home/jecmejan/.julia/packages/CSV/7lFhM/src/file.jl:152`)  
Commit `75339570`: unstable => | (`CSV` at `/home/jecmejan/.julia/packages/CSV/7lFhM/src/file.jl:152`)  

### Signature `Tuple{typeof(getindex), Plots.Series, Symbol}`

Commit `6249cba0`: | => unstable (`Plots` at `/home/jecmejan/.julia/packages/Plots/cc8wh/src/args.jl:1365`)  
Commit `75339570`: unstable => | (`Plots` at `/home/jecmejan/.julia/packages/Plots/esM5q/src/args.jl:1771`)  

### Signature `Tuple{typeof(getindex), Distributed.Future}`

Commit `6249cba0`: | => unstable (`Distributed` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/Distributed/src/remotecall.jl:772`)  
Commit `75339570`: unstable => | (`Distributed` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/Distributed/src/remotecall.jl:772`)  

### Signature `Tuple{typeof(getindex), Plots.Axis, Symbol}`

Commit `6249cba0`: | => unstable (`Plots` at `/home/jecmejan/.julia/packages/Plots/cc8wh/src/args.jl:1352`)  
Commit `75339570`: unstable => | (`Plots` at `/home/jecmejan/.julia/packages/Plots/esM5q/src/args.jl:1760`)  

### Signature `Tuple{typeof(getindex), Base.ExceptionStack, Int64}`

Commit `6249cba0`: | => unstable (`Base` at `errorshow.jl:909`)  
Commit `75339570`: unstable => | (`Base` at `errorshow.jl:909`)  

### Signature `Tuple{typeof(getindex), Plots.GridLayout, Int64, Int64}`

Commit `6249cba0`: | => unstable (`Plots` at `/home/jecmejan/.julia/packages/Plots/cc8wh/src/layouts.jl:290`)  
Commit `75339570`: unstable => | (`Plots` at `/home/jecmejan/.julia/packages/Plots/esM5q/src/layouts.jl:238`)  

### Signature `Tuple{typeof(leadlinkcurve)}`

Commit `9297c05c`: unstable => | (`ControlSystems` at `/tmp/jl_d6ZU7QnonM/src/pid_design.jl:234`)  

### Signature `Tuple{typeof(poles), ControlSystems.SisoTf}`

Commit `75339570`: | => unstable (`ControlSystems` at `/tmp/jl_5I9C7UDWps/src/analysis.jl:6`)  
Commit `0bb596b7`: unstable => nofuel (`ControlSystems` at `/tmp/jl_5I9C7UDWps/src/analysis.jl:6` => `ControlSystems` at `/tmp/jl_Rw5CjQHQzA/src/analysis.jl:6`)  

### Signature `Tuple{typeof(ControlSystems.issemiposdef), LinearAlgebra.UniformScaling}`

Commit `40d35507`: | => unstable (`ControlSystems` at `/tmp/jl_1M1OjyT6P6/src/utilities.jl:42`)  
Commit `c18ada25`: unstable => | (`ControlSystems` at `/tmp/jl_DknG1IZoXC/src/utilities.jl:42`)  

### Signature `Tuple{typeof(getindex), CSV.Arg}`

Commit `6249cba0`: | => unstable (`CSV` at `/home/jecmejan/.julia/packages/CSV/7lFhM/src/utils.jl:593`)  
Commit `75339570`: unstable => | (`CSV` at `/home/jecmejan/.julia/packages/CSV/7lFhM/src/utils.jl:593`)  

### Signature `Tuple{typeof(norm), Polynomials.AbstractPolynomial}`

Commit `481e7206`: | => unstable (`Polynomials` at `/home/jecmejan/.julia/packages/Polynomials/nujMh/src/common.jl:262`)  
Commit `b0593127`: unstable => | (`Polynomials` at `/home/jecmejan/.julia/packages/Polynomials/nujMh/src/common.jl:262`)  

### Signature `Tuple{typeof(norm), Number}`

Commit `9fec5dea`: partial => unstable (`LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633` => `LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633`)  
Commit `246ab0fb`: unstable => partial (`LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633` => `LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633`)  
Commit `bfadc8f0`: partial => unstable (`LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633` => `LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633`)  

### Signature `Tuple{typeof(pole), ControlSystems.SisoTf}`

Commit `75339570`: unstable => | (`ControlSystems` at `/tmp/jl_hGhm161IZS/src/analysis.jl:6`)  

### Signature `Tuple{typeof(pid)}`

Commit `481e7206`: unstable => stable (`ControlSystems` at `/tmp/jl_LqPKhyPuzO/src/pid_design.jl:10` => `ControlSystems` at `/tmp/jl_B4FovAPUjC/src/pid_design.jl:10`)  
Commit `b0593127`: stable => unstable (`ControlSystems` at `/tmp/jl_B4FovAPUjC/src/pid_design.jl:10` => `ControlSystems` at `/tmp/jl_nqhcpofWZ0/src/pid_design.jl:10`)  
Commit `b788f5fb`: unstable => stable (`ControlSystems` at `/tmp/jl_nqhcpofWZ0/src/pid_design.jl:10` => `ControlSystems` at `/tmp/jl_9C1ytwt47K/src/pid_design.jl:10`)  
Commit `0bb596b7`: stable => unstable (`ControlSystems` at `/tmp/jl_5I9C7UDWps/src/pid_design.jl:10` => `ControlSystems` at `/tmp/jl_Rw5CjQHQzA/src/pid_design.jl:10`)  
Commit `20a0654f`: unstable => stable (`ControlSystems` at `/tmp/jl_7inI7GZG1c/src/pid_design.jl:10` => `ControlSystems` at `/tmp/jl_Ds1GDcv8H2/src/pid_design.jl:10`)  
Commit `133e9cf0`: stable => unstable (`ControlSystems` at `/tmp/jl_RsbatGJuVo/src/pid_design.jl:10` => `ControlSystems` at `/tmp/jl_HcTQvmL2x0/src/pid_design.jl:10`)  
Commit `9297c05c`: unstable => stable (`ControlSystems` at `/tmp/jl_d6ZU7QnonM/src/pid_design.jl:10` => `ControlSystems` at `deprecated.jl:70`)  

### Signature `Tuple{typeof(getindex), LQG, Symbol}`

Commit `6249cba0`: | => unstable (`ControlSystems` at `deprecated.jl:70`)  
Commit `75339570`: unstable => | (`ControlSystems` at `deprecated.jl:70`)  

### Signature `Tuple{typeof(zpk), AbstractString}`

Commit `dda8d385`: partial => unstable (`ControlSystems` at `/tmp/jl_bC9IHQ5Mnm/src/types/zpk.jl:81` => `ControlSystems` at `/tmp/jl_bsFSz0naDg/src/types/zpk.jl:81`)  
Commit `fd558636`: unstable => tc-fail (`ControlSystems` at `/tmp/jl_dox4RIxAD4/src/types/zpk.jl:72` => `ControlSystems` at `/tmp/jl_zoNY7YV2XU/src/types/zpk.jl:72`)  
Commit `40b14894`: tc-fail => unstable (`ControlSystems` at `/tmp/jl_zoNY7YV2XU/src/types/zpk.jl:72` => `ControlSystems` at `/tmp/jl_v6rKz2JUBI/src/types/zpk.jl:72`)  

### Signature `Tuple{typeof(getindex), Core.SimpleVector, Int64}`

Commit `6249cba0`: | => unstable (`Base` at `essentials.jl:608`)  
Commit `75339570`: unstable => | (`Base` at `essentials.jl:608`)  

### Signature `Tuple{typeof(delay), Number}`

Commit `fe4e627e`: | => unstable (`ControlSystems` at `/tmp/jl_LqPKhyPuzO/src/types/DelayLtiSystem.jl:194`)  

### Signature `Tuple{typeof(ControlSystems.plot), LQG}`

Commit `75339570`: unstable => | (`ControlSystems` at `/tmp/jl_hGhm161IZS/src/types/lqg.jl:252`)  

### Signature `Tuple{typeof(getindex), CSV.File, Symbol}`

Commit `6249cba0`: | => unstable (`CSV` at `/home/jecmejan/.julia/packages/CSV/7lFhM/src/file.jl:147`)  
Commit `75339570`: unstable => | (`CSV` at `/home/jecmejan/.julia/packages/CSV/7lFhM/src/file.jl:147`)  

### Signature `Tuple{typeof(getindex), AbstractString, Integer}`

Commit `6249cba0`: | => unstable (`Base` at `strings/basic.jl:184`)  
Commit `75339570`: unstable => | (`Base` at `strings/basic.jl:184`)  

### Signature `Tuple{typeof(getindex), SubString, Integer}`

Commit `6249cba0`: | => unstable (`Base` at `strings/substring.jl:87`)  
Commit `75339570`: unstable => | (`Base` at `strings/substring.jl:87`)  

### Signature `Tuple{typeof(norm), Number, Real}`

Commit `9fec5dea`: partial => unstable (`LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633` => `LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633`)  
Commit `246ab0fb`: unstable => partial (`LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633` => `LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633`)  
Commit `bfadc8f0`: partial => unstable (`LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633` => `LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633`)  
Commit `0bb596b7`: unstable => nofuel (`LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633` => `LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/generic.jl:633`)  


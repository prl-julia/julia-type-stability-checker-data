# Stability change report for package `DataFrames`

### Signature `Tuple{typeof(iterate), Core.MethodMatch}`

Commit `025824f8`: | => unstable (`Base` at `deprecated.jl:226` )  
Commit `fe2da010`: unstable => | (`Base` at `deprecated.jl:226` )  

### Signature `Tuple{typeof(DataFrames._vcat), AbstractVector{<:AbstractDataFrame}}`

Commit `e2047099`: nofuel => unstable (`DataFrames` at `/tmp/jl_jUlEjiFmj6/src/abstractdataframe/abstractdataframe.jl:1102` => `DataFrames` at `/tmp/jl_DMZSpAJqBs/src/abstractdataframe/abstractdataframe.jl:1102` )  
Commit `86a5ee6c`: unstable => | (`DataFrames` at `/tmp/jl_LYZMPkFk3y/src/abstractdataframe/abstractdataframe.jl:1557` )  

### Signature `Tuple{typeof(iterate), SubString, Integer}`

Commit `025824f8`: | => unstable (`Base` at `strings/substring.jl:78` )  
Commit `fe2da010`: unstable => | (`Base` at `strings/substring.jl:78` )  

### Signature `Tuple{typeof(iterate), Base.AsyncGenerator, Base.AsyncGeneratorState}`

Commit `025824f8`: | => unstable (`Base` at `asyncmap.jl:368` )  
Commit `fe2da010`: unstable => | (`Base` at `asyncmap.jl:368` )  

### Signature `Tuple{typeof(meltdf), AbstractDataFrame}`

Commit `0596bac3`: unstable => partial (`DataFrames` at `/tmp/jl_74BKJMFSj6/src/abstractdataframe/reshape.jl:579` => `DataFrames` at `/tmp/jl_NCvINqfKH0/src/abstractdataframe/reshape.jl:578` )  

### Signature `Tuple{typeof(getindex), TranscodingStreams.Error}`

Commit `b0d8a87d`: | => unstable (`TranscodingStreams` at `/home/jecmejan/.julia/packages/TranscodingStreams/2McN2/src/error.jl:31` )  
Commit `fe2da010`: unstable => | (`TranscodingStreams` at `/home/jecmejan/.julia/packages/TranscodingStreams/2McN2/src/error.jl:31` )  

### Signature `Tuple{typeof(DataFrames.find_semi_rows), DataFrames.DataFrameJoiner}`

Commit `6d5ae351`: | => unstable (`DataFrames` at `/tmp/jl_12H4NYde9S/src/join/core.jl:812` )  

### Signature `Tuple{typeof(convert), Type{Vector}, DataFrameRow}`

Commit `6237a2b4`: unstable => | (`DataFrames` at `/tmp/jl_ngFopU1SFA/src/dataframerow/dataframerow.jl:183` )  
Commit `55533d1f`: | => unstable (`DataFrames` at `/tmp/jl_v43gLMFsLK/src/dataframerow/dataframerow.jl:382` )  
Commit `2d0413a0`: unstable => | (`DataFrames` at `/tmp/jl_Pybuxij4Zs/src/dataframerow/dataframerow.jl:392` )  
Commit `ff965d5c`: | => unstable (`DataFrames` at `deprecated.jl:70` )  
Commit `73ca8f19`: unstable => | (`DataFrames` at `deprecated.jl:70` )  

### Signature `Tuple{typeof(leftjoin), AbstractDataFrame, AbstractDataFrame}`

Commit `f4db95f4`: partial => unstable (`DataFrames` at `/tmp/jl_tq5u3ylcTU/src/abstractdataframe/join.jl:681` => `DataFrames` at `/tmp/jl_xCtGRKLcZ2/src/abstractdataframe/join.jl:677` )  

### Signature `Tuple{typeof(outerjoin), AbstractDataFrame, AbstractDataFrame}`

Commit `f4db95f4`: partial => unstable (`DataFrames` at `/tmp/jl_tq5u3ylcTU/src/abstractdataframe/join.jl:932` => `DataFrames` at `/tmp/jl_xCtGRKLcZ2/src/abstractdataframe/join.jl:928` )  

### Signature `Tuple{typeof(melt), AbstractDataFrame}`

Commit `0596bac3`: unstable => partial (`DataFrames` at `/tmp/jl_74BKJMFSj6/src/abstractdataframe/reshape.jl:140` => `DataFrames` at `/tmp/jl_NCvINqfKH0/src/abstractdataframe/reshape.jl:139` )  

### Signature `Tuple{typeof(iterate), DataStructures.TrieIterator}`

Commit `025824f8`: | => unstable (`DataStructures` at `/home/jecmejan/.julia/packages/DataStructures/59MD0/src/trie.jl:112` )  
Commit `fe2da010`: unstable => | (`DataStructures` at `/home/jecmejan/.julia/packages/DataStructures/59MD0/src/trie.jl:112` )  

### Signature `Tuple{typeof(length), DataFrames.SubIndex}`

Commit `cbfef8d6`: unstable => | (`DataFrames` at `/tmp/jl_fcnSLczgZi/src/other/index.jl:372` )  
Commit `025824f8`: | => unstable (`DataFrames` at `/tmp/jl_vuvsxuxOfk/src/other/index.jl:375` )  
Commit `fe2da010`: unstable => | (`DataFrames` at `/tmp/jl_TG54ZgxmtK/src/other/index.jl:422` )  

### Signature `Tuple{typeof(keys), RegexMatch}`

Commit `fb4e184f`: | => unstable (`Base` at `regex.jl:219` )  
Commit `fe2da010`: unstable => | (`Base` at `regex.jl:219` )  

### Signature `Tuple{typeof(categorical), AbstractDataFrame}`

Commit `f10ee2e4`: partial => unstable (`DataFrames` at `/tmp/jl_ZK3Ypk3MLE/src/abstractdataframe/abstractdataframe.jl:1774` => `DataFrames` at `/tmp/jl_HYjsXkH4Jc/src/deprecated.jl:40` )  
Commit `2d0413a0`: unstable => | (`DataFrames` at `/tmp/jl_Pybuxij4Zs/src/deprecated.jl:40` )  

### Signature `Tuple{typeof(iterate), DataFrameRow}`

Commit `025824f8`: | => unstable (`DataFrames` at `/tmp/jl_vuvsxuxOfk/src/dataframerow/dataframerow.jl:171` )  
Commit `fe2da010`: unstable => | (`DataFrames` at `/tmp/jl_TG54ZgxmtK/src/dataframerow/dataframerow.jl:371` )  

### Signature `Tuple{typeof(unstack), AbstractDataFrame}`

Commit `025824f8`: partial => unstable (`DataFrames` at `/tmp/jl_xerafSBo9E/src/abstractdataframe/reshape.jl:283` => `DataFrames` at `/tmp/jl_vuvsxuxOfk/src/abstractdataframe/reshape.jl:283` )  

### Signature `Tuple{typeof(length), DataFrames.StackedVector}`

Commit `cbfef8d6`: unstable => | (`DataFrames` at `/tmp/jl_fcnSLczgZi/src/abstractdataframe/reshape.jl:400` )  
Commit `025824f8`: | => unstable (`DataFrames` at `/tmp/jl_vuvsxuxOfk/src/abstractdataframe/reshape.jl:327` )  
Commit `8bfa59e5`: unstable => partial (`DataFrames` at `/tmp/jl_hmbMlmPG52/src/abstractdataframe/reshape.jl:351` => `DataFrames` at `/tmp/jl_1Kl4fs9QrS/src/abstractdataframe/reshape.jl:354` )  

### Signature `Tuple{typeof(colmetadatakeys), DataFrame, Int64}`

Commit `b01fd382`: | => unstable (`DataFrames` at `/tmp/jl_tCjKrEFude/src/other/metadata.jl:399` )  
Commit `94ac6cce`: unstable => | (`DataFrames` at `/tmp/jl_3e9UDE5QbS/src/other/metadata.jl:399` )  

### Signature `Tuple{typeof(length), StatsBase.CoefTable}`

Commit `e2047099`: unstable => | (`StatsBase` at `/home/jecmejan/.julia/packages/StatsBase/iMkPf/src/statmodels.jl:31` )  

### Signature `Tuple{typeof(antijoin), AbstractDataFrame, AbstractDataFrame}`

Commit `f4db95f4`: partial => unstable (`DataFrames` at `/tmp/jl_tq5u3ylcTU/src/abstractdataframe/join.jl:1140` => `DataFrames` at `/tmp/jl_xCtGRKLcZ2/src/abstractdataframe/join.jl:1136` )  

### Signature `Tuple{typeof(getindex), DataFrame, typeof(!), Symbol}`

Commit `b0d8a87d`: | => unstable (`DataFrames` at `/tmp/jl_jUlEjiFmj6/src/dataframe/dataframe.jl:343` )  
Commit `b1f675d8`: unstable => | (`DataFrames` at `/tmp/jl_pMtuVsxIpi/src/dataframe/dataframe.jl:371` )  

### Signature `Tuple{typeof(keys), DataFrameRow}`

Commit `fb4e184f`: | => unstable (`DataFrames` at `/tmp/jl_pMtuVsxIpi/src/dataframerow/dataframerow.jl:248` )  
Commit `b1f675d8`: unstable => partial (`DataFrames` at `/tmp/jl_pMtuVsxIpi/src/dataframerow/dataframerow.jl:248` => `DataFrames` at `/tmp/jl_twZwNaPAXq/src/dataframerow/dataframerow.jl:262` )  

### Signature `Tuple{typeof(iterate), DataFrames.DataFrameColumns}`

Commit `04122912`: | => unstable (`DataFrames` at `/tmp/jl_1SFq5iLg3C/src/abstractdataframe/iteration.jl:191` )  
Commit `fe2da010`: unstable => | (`DataFrames` at `/tmp/jl_TG54ZgxmtK/src/abstractdataframe/iteration.jl:183` )  

### Signature `Tuple{typeof(convert), Type{RoundingMode}, Base.MPFR.MPFRRoundingMode}`

Commit `6237a2b4`: unstable => | (`Base.MPFR` at `mpfr.jl:64` )  
Commit `55533d1f`: | => unstable (`Base.MPFR` at `mpfr.jl:64` )  
Commit `2d0413a0`: unstable => | (`Base.MPFR` at `mpfr.jl:64` )  
Commit `ff965d5c`: | => unstable (`Base.MPFR` at `mpfr.jl:64` )  
Commit `73ca8f19`: unstable => | (`Base.MPFR` at `mpfr.jl:64` )  

### Signature `Tuple{typeof(DataFrames.find_missing_idxs), Vector{Int64}, Int64}`

Commit `0b4f4588`: stable => unstable (`DataFrames` at `/tmp/jl_Pcjo5YjWVK/src/join/composer.jl:132` => `DataFrames` at `/tmp/jl_F4rGlEpOzm/src/join/composer.jl:132` )  

### Signature `Tuple{typeof(DataFrames._combine), AbstractVector{<:Pair}, GroupedDataFrame, AbstractVector{Symbol}}`

Commit `894a0121`: | => unstable (`DataFrames` at `/tmp/jl_fsTaHQV6XC/src/groupeddataframe/splitapplycombine.jl:929` )  
Commit `954a2461`: unstable => | (`DataFrames` at `/tmp/jl_lElYj8bins/src/groupeddataframe/splitapplycombine.jl:1092` )  

### Signature `Tuple{typeof(stackdf), AbstractDataFrame}`

Commit `0596bac3`: unstable => partial (`DataFrames` at `/tmp/jl_74BKJMFSj6/src/abstractdataframe/reshape.jl:558` => `DataFrames` at `/tmp/jl_NCvINqfKH0/src/abstractdataframe/reshape.jl:557` )  

### Signature `Tuple{typeof(DataFrames.preprocess_columns), DataFrames.DataFrameJoiner}`

Commit `6d5ae351`: | => unstable (`DataFrames` at `/tmp/jl_12H4NYde9S/src/join/core.jl:121` )  

### Signature `Tuple{typeof(iterate), Base.AsyncGenerator}`

Commit `025824f8`: | => unstable (`Base` at `asyncmap.jl:368` )  
Commit `fe2da010`: unstable => | (`Base` at `asyncmap.jl:368` )  

### Signature `Tuple{typeof(head), AbstractDataFrame}`

Commit `e852cbad`: unstable => | (`DataFrames` at `deprecated.jl:70` )  

### Signature `Tuple{typeof(iterate), AbstractString, Integer}`

Commit `025824f8`: | => unstable (`Base` at `strings/basic.jl:157` )  
Commit `fe2da010`: unstable => | (`Base` at `strings/basic.jl:157` )  

### Signature `Tuple{typeof(getindex), CSV.Arg}`

Commit `b0d8a87d`: | => unstable (`CSV` at `/home/jecmejan/.julia/packages/CSV/b8ebJ/src/utils.jl:593` )  
Commit `fe2da010`: unstable => | (`CSV` at `/home/jecmejan/.julia/packages/CSV/b8ebJ/src/utils.jl:593` )  

### Signature `Tuple{typeof(iterate), Core.SimpleVector}`

Commit `025824f8`: | => unstable (`Base` at `essentials.jl:620` )  
Commit `fe2da010`: unstable => | (`Base` at `essentials.jl:620` )  

### Signature `Tuple{typeof(rightjoin), AbstractDataFrame, AbstractDataFrame}`

Commit `f4db95f4`: partial => unstable (`DataFrames` at `/tmp/jl_tq5u3ylcTU/src/abstractdataframe/join.jl:800` => `DataFrames` at `/tmp/jl_xCtGRKLcZ2/src/abstractdataframe/join.jl:796` )  

### Signature `Tuple{typeof(DataFrames._findall), AbstractVector{Bool}}`

Commit `0b4f4588`: | => unstable (`DataFrames` at `/tmp/jl_F4rGlEpOzm/src/other/utils.jl:184` )  

### Signature `Tuple{typeof(dropmissing), AbstractDataFrame}`

Commit `fdd9193d`: unstable => partial (`DataFrames` at `/tmp/jl_vydCFQTyB2/src/abstractdataframe/abstractdataframe.jl:970` => `DataFrames` at `/tmp/jl_pCL474lWXy/src/abstractdataframe/abstractdataframe.jl:970` )  

### Signature `Tuple{typeof(convert), Type{Tuple}, DataFrameRow}`

Commit `55533d1f`: | => unstable (`DataFrames` at `/tmp/jl_v43gLMFsLK/src/dataframerow/dataframerow.jl:428` )  
Commit `2d0413a0`: unstable => | (`DataFrames` at `/tmp/jl_Pybuxij4Zs/src/dataframerow/dataframerow.jl:438` )  
Commit `ff965d5c`: | => unstable (`DataFrames` at `deprecated.jl:70` )  
Commit `73ca8f19`: unstable => | (`DataFrames` at `deprecated.jl:70` )  

### Signature `Tuple{typeof(getindex), AbstractString, Integer}`

Commit `b0d8a87d`: | => unstable (`Base` at `strings/basic.jl:184` )  
Commit `fe2da010`: unstable => | (`Base` at `strings/basic.jl:184` )  

### Signature `Tuple{typeof(DataFrames.normalize_selection), DataFrames.AbstractIndex, Pair{typeof(nrow), <:AbstractString}}`

Commit `b1f675d8`: | => unstable (`DataFrames` at `/tmp/jl_twZwNaPAXq/src/abstractdataframe/selection.jl:55` )  
Commit `38027c7f`: unstable => | (`DataFrames` at `/tmp/jl_fmJIzynMxa/src/abstractdataframe/selection.jl:50` )  

### Signature `Tuple{typeof(codeunit), SubstitutionString}`

Commit `025824f8`: | => unstable (`Base` at `regex.jl:564` )  
Commit `fe2da010`: unstable => | (`Base` at `regex.jl:564` )  

### Signature `Tuple{typeof(metadatakeys), DataFrame}`

Commit `b01fd382`: | => unstable (`DataFrames` at `/tmp/jl_tCjKrEFude/src/other/metadata.jl:127` )  

### Signature `Tuple{typeof(getindex), Core.Compiler.Instruction, Symbol}`

Commit `b0d8a87d`: | => unstable (`Base.IRShow` at `show.jl:2501` )  
Commit `fe2da010`: unstable => | (`Base.IRShow` at `show.jl:2501` )  

### Signature `Tuple{typeof(getindex), Distributed.Future}`

Commit `b0d8a87d`: | => unstable (`Distributed` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/Distributed/src/remotecall.jl:772` )  
Commit `fe2da010`: unstable => | (`Distributed` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/Distributed/src/remotecall.jl:772` )  

### Signature `Tuple{typeof(combine), GroupedDataFrame}`

Commit `0b998c82`: unstable => partial (`DataFrames` at `/tmp/jl_p0Tm3o5oRO/src/groupeddataframe/grouping.jl:436` => `DataFrames` at `/tmp/jl_zML8TobGNk/src/groupeddataframe/grouping.jl:440` )  
Commit `e607175e`: partial => unstable (`DataFrames` at `/tmp/jl_PgxIRwRyF8/src/groupeddataframe/splitapplycombine.jl:550` => `DataFrames` at `/tmp/jl_dW5eR47Ori/src/groupeddataframe/splitapplycombine.jl:557` )  
Commit `cc835660`: unstable => | (`DataFrames` at `/tmp/jl_tadQx2hYNA/src/groupeddataframe/splitapplycombine.jl:555` )  

### Signature `Tuple{typeof(codeunit), SubString}`

Commit `025824f8`: | => unstable (`Base` at `strings/substring.jl:70` )  
Commit `fe2da010`: unstable => | (`Base` at `strings/substring.jl:70` )  

### Signature `Tuple{typeof(tail), AbstractDataFrame}`

Commit `e852cbad`: unstable => | (`DataFrames` at `deprecated.jl:70` )  

### Signature `Tuple{typeof(getindex), Base.ExceptionStack, Int64}`

Commit `b0d8a87d`: | => unstable (`Base` at `errorshow.jl:909` )  
Commit `fe2da010`: unstable => | (`Base` at `errorshow.jl:909` )  

### Signature `Tuple{typeof(stack), AbstractDataFrame}`

Commit `0596bac3`: unstable => partial (`DataFrames` at `/tmp/jl_74BKJMFSj6/src/abstractdataframe/reshape.jl:114` => `DataFrames` at `/tmp/jl_NCvINqfKH0/src/abstractdataframe/reshape.jl:113` )  

### Signature `Tuple{typeof(iterate), Core.MethodMatch, Int64}`

Commit `025824f8`: | => unstable (`Base` at `deprecated.jl:226` )  
Commit `fe2da010`: unstable => | (`Base` at `deprecated.jl:226` )  

### Signature `Tuple{typeof(convert), Type{Array}, DataFrameRow}`

Commit `6237a2b4`: unstable => | (`DataFrames` at `deprecated.jl:70` )  
Commit `55533d1f`: | => unstable (`DataFrames` at `/tmp/jl_v43gLMFsLK/src/dataframerow/dataframerow.jl:392` )  
Commit `2d0413a0`: unstable => | (`DataFrames` at `/tmp/jl_Pybuxij4Zs/src/dataframerow/dataframerow.jl:402` )  
Commit `ff965d5c`: | => unstable (`DataFrames` at `deprecated.jl:70` )  
Commit `73ca8f19`: unstable => | (`DataFrames` at `deprecated.jl:70` )  

### Signature `Tuple{typeof(DataFrames._findall), BitVector}`

Commit `ed002418`: | => unstable (`DataFrames` at `/tmp/jl_Pcjo5YjWVK/src/other/utils.jl:188` )  

### Signature `Tuple{typeof(colmetadatakeys), DataFrame}`

Commit `b01fd382`: | => unstable (`DataFrames` at `/tmp/jl_tCjKrEFude/src/other/metadata.jl:414` )  

### Signature `Tuple{typeof(DataFrames._dict_to_tuple), AbstractDict{<:AbstractString}, GroupedDataFrame}`

Commit `d156320a`: | => unstable (`DataFrames` at `/tmp/jl_ZK3Ypk3MLE/src/groupeddataframe/groupeddataframe.jl:394` )  

### Signature `Tuple{typeof(repeat), AbstractString, Integer}`

Commit `025824f8`: | => unstable (`Base` at `strings/basic.jl:715` )  
Commit `fe2da010`: unstable => | (`Base` at `strings/basic.jl:715` )  

### Signature `Tuple{typeof(findfirst), SentinelArrays.ChainedVector{Bool, A} where A<:AbstractVector{Bool}}`

Commit `fb4e184f`: | => unstable (`SentinelArrays` at `/home/jecmejan/.julia/packages/SentinelArrays/BcfVF/src/chainedvector.jl:849` )  
Commit `fe2da010`: unstable => | (`SentinelArrays` at `/home/jecmejan/.julia/packages/SentinelArrays/BcfVF/src/chainedvector.jl:849` )  

### Signature `Tuple{typeof(length), Base.AsyncGenerator}`

Commit `cbfef8d6`: unstable => | (`Base` at `asyncmap.jl:396` )  
Commit `025824f8`: | => unstable (`Base` at `asyncmap.jl:396` )  
Commit `fe2da010`: unstable => | (`Base` at `asyncmap.jl:396` )  

### Signature `Tuple{typeof(eltype), DataFrames.StackedVector}`

Commit `025824f8`: | => unstable (`DataFrames` at `/tmp/jl_vuvsxuxOfk/src/abstractdataframe/reshape.jl:328` )  
Commit `8bfa59e5`: unstable => | (`DataFrames` at `/tmp/jl_hmbMlmPG52/src/abstractdataframe/reshape.jl:352` )  

### Signature `Tuple{typeof(DataFrames._combine_multicol), Ref{Any}, Ref{Any}, GroupedDataFrame, Ref{Any}}`

Commit `50af82e4`: | => unstable (`DataFrames` at `/tmp/jl_XsVuBCRKjs/src/groupeddataframe/complextransforms.jl:7` )  
Commit `a6820227`: unstable => | (`DataFrames` at `/tmp/jl_N8TYJSvgtU/src/groupeddataframe/complextransforms.jl:7` )  

### Signature `Tuple{typeof(getindex), Core.SimpleVector, Int64}`

Commit `b0d8a87d`: | => unstable (`Base` at `essentials.jl:608` )  
Commit `fe2da010`: unstable => | (`Base` at `essentials.jl:608` )  

### Signature `Tuple{typeof(getindex), DataFrames.StackedVector, Int64}`

Commit `b0d8a87d`: | => unstable (`DataFrames` at `/tmp/jl_jUlEjiFmj6/src/abstractdataframe/reshape.jl:368` )  
Commit `8bfa59e5`: unstable => | (`DataFrames` at `/tmp/jl_hmbMlmPG52/src/abstractdataframe/reshape.jl:335` )  

### Signature `Tuple{typeof(eltypes), AbstractDataFrame}`

Commit `cc835660`: unstable => | (`DataFrames` at `deprecated.jl:70` )  

### Signature `Tuple{typeof(getindex), CSV.File, Symbol}`

Commit `b0d8a87d`: | => unstable (`CSV` at `/home/jecmejan/.julia/packages/CSV/b8ebJ/src/file.jl:147` )  
Commit `fe2da010`: unstable => | (`CSV` at `/home/jecmejan/.julia/packages/CSV/b8ebJ/src/file.jl:147` )  

### Signature `Tuple{typeof(iterate), SubString}`

Commit `025824f8`: | => unstable (`Base` at `strings/substring.jl:78` )  
Commit `fe2da010`: unstable => | (`Base` at `strings/substring.jl:78` )  

### Signature `Tuple{typeof(innerjoin), AbstractDataFrame, AbstractDataFrame}`

Commit `f4db95f4`: partial => unstable (`DataFrames` at `/tmp/jl_tq5u3ylcTU/src/abstractdataframe/join.jl:555` => `DataFrames` at `/tmp/jl_xCtGRKLcZ2/src/abstractdataframe/join.jl:551` )  

### Signature `Tuple{typeof(DataFrames._vcat), AbstractVector{AbstractDataFrame}}`

Commit `86a5ee6c`: | => unstable (`DataFrames` at `/tmp/jl_Pybuxij4Zs/src/abstractdataframe/abstractdataframe.jl:1558` )  

### Signature `Tuple{typeof(convert), Type{NamedTuple}, DataFrameRow}`

Commit `55533d1f`: | => unstable (`DataFrames` at `/tmp/jl_v43gLMFsLK/src/dataframerow/dataframerow.jl:427` )  
Commit `2d0413a0`: unstable => | (`DataFrames` at `/tmp/jl_Pybuxij4Zs/src/dataframerow/dataframerow.jl:437` )  
Commit `ff965d5c`: | => unstable (`DataFrames` at `/tmp/jl_p4RWVAvyJa/src/dataframerow/dataframerow.jl:444` )  
Commit `73ca8f19`: unstable => | (`DataFrames` at `/tmp/jl_RmjANmPcdq/src/dataframerow/dataframerow.jl:444` )  

### Signature `Tuple{typeof(convert), Type{Matrix}, AbstractDataFrame}`

Commit `6237a2b4`: unstable => | (`DataFrames` at `/tmp/jl_ngFopU1SFA/src/abstractdataframe/abstractdataframe.jl:746` )  
Commit `55533d1f`: | => unstable (`DataFrames` at `/tmp/jl_v43gLMFsLK/src/abstractdataframe/abstractdataframe.jl:1142` )  
Commit `2d0413a0`: unstable => | (`DataFrames` at `/tmp/jl_Pybuxij4Zs/src/abstractdataframe/abstractdataframe.jl:1141` )  
Commit `ff965d5c`: | => unstable (`DataFrames` at `deprecated.jl:70` )  
Commit `73ca8f19`: unstable => | (`DataFrames` at `deprecated.jl:70` )  

### Signature `Tuple{typeof(getindex), Core.MethodMatch, Int64}`

Commit `b0d8a87d`: | => unstable (`Base` at `deprecated.jl:228` )  
Commit `fe2da010`: unstable => | (`Base` at `deprecated.jl:228` )  

### Signature `Tuple{typeof(codeunit), SubstitutionString, Integer}`

Commit `025824f8`: | => unstable (`Base` at `regex.jl:565` )  
Commit `fe2da010`: unstable => | (`Base` at `regex.jl:565` )  

### Signature `Tuple{typeof(getindex), CSV.File, String}`

Commit `b0d8a87d`: | => unstable (`CSV` at `/home/jecmejan/.julia/packages/CSV/b8ebJ/src/file.jl:152` )  
Commit `fe2da010`: unstable => | (`CSV` at `/home/jecmejan/.julia/packages/CSV/b8ebJ/src/file.jl:152` )  

### Signature `Tuple{typeof(DataFrames._transformation_helper), AbstractDataFrame, AbstractVector{Int64}, Ref{Any}}`

Commit `50af82e4`: | => unstable (`DataFrames` at `/tmp/jl_XsVuBCRKjs/src/abstractdataframe/selection.jl:347` )  

### Signature `Tuple{typeof(iterate), Test.GenericString}`

Commit `025824f8`: | => unstable (`Test` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/Test/src/Test.jl:1885` )  
Commit `fe2da010`: unstable => | (`Test` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/Test/src/Test.jl:1885` )  

### Signature `Tuple{typeof(length), DataStructures.EnumerateAll}`

Commit `cbfef8d6`: unstable => | (`DataStructures` at `/home/jecmejan/.julia/packages/DataStructures/DLSxi/src/multi_dict.jl:103` )  
Commit `025824f8`: | => unstable (`DataStructures` at `/home/jecmejan/.julia/packages/DataStructures/59MD0/src/multi_dict.jl:96` )  
Commit `fe2da010`: unstable => | (`DataStructures` at `/home/jecmejan/.julia/packages/DataStructures/59MD0/src/multi_dict.jl:96` )  

### Signature `Tuple{typeof(iterate), Base.Iterators.Reverse{<:AbstractString}}`

Commit `025824f8`: | => unstable (`Base` at `strings/basic.jl:733` )  
Commit `fe2da010`: unstable => | (`Base` at `strings/basic.jl:733` )  

### Signature `Tuple{typeof(DataFrames.numeric_vars), AbstractDataFrame}`

Commit `0596bac3`: unstable => partial (`DataFrames` at `/tmp/jl_74BKJMFSj6/src/abstractdataframe/reshape.jl:110` => `DataFrames` at `/tmp/jl_NCvINqfKH0/src/abstractdataframe/reshape.jl:110` )  

### Signature `Tuple{typeof(codeunit), SubString, Integer}`

Commit `025824f8`: | => unstable (`Base` at `strings/substring.jl:73` )  
Commit `fe2da010`: unstable => | (`Base` at `strings/substring.jl:73` )  

### Signature `Tuple{typeof(DataFrames.firstcoltype), Bool}`

Commit `3b45c5bf`: | => unstable (`DataFrames` at `/tmp/jl_veh078dKXa/src/groupeddataframe/callprocessing.jl:6` )  

### Signature `Tuple{typeof(getindex), StructTypes.SubTypeClosure, Symbol}`

Commit `fb4e184f`: | => unstable (`StructTypes` at `/home/jecmejan/.julia/packages/StructTypes/AK4aM/src/StructTypes.jl:591` )  
Commit `fe2da010`: unstable => | (`StructTypes` at `/home/jecmejan/.julia/packages/StructTypes/AK4aM/src/StructTypes.jl:591` )  

### Signature `Tuple{typeof(iterate), DataStructures.EnumerateAll}`

Commit `025824f8`: | => unstable (`DataStructures` at `/home/jecmejan/.julia/packages/DataStructures/59MD0/src/multi_dict.jl:98` )  
Commit `fe2da010`: unstable => | (`DataStructures` at `/home/jecmejan/.julia/packages/DataStructures/59MD0/src/multi_dict.jl:98` )  

### Signature `Tuple{typeof(semijoin), AbstractDataFrame, AbstractDataFrame}`

Commit `f4db95f4`: partial => unstable (`DataFrames` at `/tmp/jl_tq5u3ylcTU/src/abstractdataframe/join.jl:1047` => `DataFrames` at `/tmp/jl_xCtGRKLcZ2/src/abstractdataframe/join.jl:1043` )  

### Signature `Tuple{typeof(convert), Type{Array}, AbstractDataFrame}`

Commit `6237a2b4`: unstable => | (`DataFrames` at `deprecated.jl:70` )  
Commit `55533d1f`: | => unstable (`DataFrames` at `/tmp/jl_v43gLMFsLK/src/abstractdataframe/abstractdataframe.jl:1171` )  
Commit `2d0413a0`: unstable => | (`DataFrames` at `/tmp/jl_Pybuxij4Zs/src/abstractdataframe/abstractdataframe.jl:1170` )  
Commit `ff965d5c`: | => unstable (`DataFrames` at `deprecated.jl:70` )  
Commit `73ca8f19`: unstable => | (`DataFrames` at `deprecated.jl:70` )  

### Signature `Tuple{typeof(colmetadatakeys), DataFrame, Symbol}`

Commit `b01fd382`: | => unstable (`DataFrames` at `/tmp/jl_tCjKrEFude/src/other/metadata.jl:410` )  
Commit `94ac6cce`: unstable => | (`DataFrames` at `/tmp/jl_3e9UDE5QbS/src/other/metadata.jl:410` )  

### Signature `Tuple{typeof(getindex), LinearAlgebra.UniformScaling, Integer, Integer}`

Commit `b0d8a87d`: | => unstable (`LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/uniformscaling.jl:89` )  
Commit `e2047099`: unstable => partial (`LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/uniformscaling.jl:89` => `LinearAlgebra` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/LinearAlgebra/src/uniformscaling.jl:89` )  

### Signature `Tuple{typeof(codeunit), Test.GenericString}`

Commit `025824f8`: | => unstable (`Test` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/Test/src/Test.jl:1882` )  
Commit `fe2da010`: unstable => | (`Test` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/Test/src/Test.jl:1882` )  

### Signature `Tuple{typeof(codeunit), AbstractString, Integer}`

Commit `025824f8`: | => unstable (`Base` at `strings/basic.jl:107` )  
Commit `fe2da010`: unstable => | (`Base` at `strings/basic.jl:107` )  

### Signature `Tuple{typeof(getindex), SubString, Integer}`

Commit `b0d8a87d`: | => unstable (`Base` at `strings/substring.jl:87` )  
Commit `fe2da010`: unstable => | (`Base` at `strings/substring.jl:87` )  

### Signature `Tuple{typeof(DataFrames._count_sortperm), Vector{Int64}}`

Commit `e0cd3b88`: | => unstable (`DataFrames` at `/tmp/jl_BCTQpybuPo/src/join/composer.jl:187` )  


# Stability change report for package `TSML`

### Signature `Tuple{typeof(prun)}`

Commit `8e33482`: unstable => | (`TSML.DataProc` at `/tmp/jl_Lchc3yPgdW/src/dataproc.jl:16`)  

### Signature `Tuple{typeof(fit!), DateValizer, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.ValDateFilters` at `/tmp/jl_l0lKDylCxY/src/valdatefilters.jl:372`)  

### Signature `Tuple{typeof(mean), MultivariateStats.Whitening}`

Commit `892cf9e`: | => unstable (`MultivariateStats` at `/home/jecmejan/.julia/packages/MultivariateStats/zLpz8/src/whiten.jl:79`)  
Commit `b7d03c6`: unstable => partial (`MultivariateStats` at `/home/jecmejan/.julia/packages/MultivariateStats/zLpz8/src/whiten.jl:79` => `MultivariateStats` at `/home/jecmejan/.julia/packages/MultivariateStats/BYMwD/src/whiten.jl:36`)  

### Signature `Tuple{typeof(fit!), TimescaleDB}`

Commit `8e33482`: | => unstable (`TSML.TimescaleDBs` at `/tmp/jl_TG9KpC9U34/src/timescaledb.jl:35`)  

### Signature `Tuple{typeof(transform!), DateValMultiNNer, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.ValDateFilters` at `/tmp/jl_l0lKDylCxY/src/valdatefilters.jl:859`)  

### Signature `Tuple{typeof(transform!), DateValLinearImputer, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.ValDateFilters` at `/tmp/jl_l0lKDylCxY/src/valdatefilters.jl:962`)  

### Signature `Tuple{typeof(transform!), StackEnsemble, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.EnsembleMethods` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/ensemble.jl:217`)  
Commit `bacf5e1`: unstable => stable (`AutoMLPipeline.EnsembleMethods` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/ensemble.jl:217` => `AMLPipelineBase.EnsembleMethods` at `/home/jecmejan/.julia/packages/AMLPipelineBase/sH55F/src/ensemble.jl:229`)  
Commit `41341a6`: stable => unstable (`AMLPipelineBase.EnsembleMethods` at `/home/jecmejan/.julia/packages/AMLPipelineBase/sH55F/src/ensemble.jl:229` => `AMLPipelineBase.EnsembleMethods` at `/home/jecmejan/.julia/packages/AMLPipelineBase/sH55F/src/ensemble.jl:229`)  

### Signature `Tuple{typeof(leftjoin), AbstractDataFrame, AbstractDataFrame}`

Commit `8e33482`: | => unstable (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/join/composer.jl:911`)  
Commit `892cf9e`: unstable => | (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/join/composer.jl:911`)  

### Signature `Tuple{typeof(outerjoin), AbstractDataFrame, AbstractDataFrame}`

Commit `8e33482`: | => unstable (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/join/composer.jl:1237`)  
Commit `892cf9e`: unstable => | (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/join/composer.jl:1237`)  

### Signature `Tuple{typeof(fit!), Matrifier, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.ValDateFilters` at `/tmp/jl_l0lKDylCxY/src/valdatefilters.jl:84`)  
Commit `bacf5e1`: unstable => stable (`TSML.ValDateFilters` at `/tmp/jl_fobGZCz4do/src/valdatefilters.jl:81` => `TSML.ValDateFilters` at `/tmp/jl_1e9UdubkNc/src/valdatefilters.jl:85`)  

### Signature `Tuple{typeof(transform!), FeatureSelector, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.FeatureSelectors` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/featureselector.jl:66`)  
Commit `bacf5e1`: unstable => stable (`AutoMLPipeline.FeatureSelectors` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/featureselector.jl:66` => `AMLPipelineBase.FeatureSelectors` at `/home/jecmejan/.julia/packages/AMLPipelineBase/sH55F/src/featureselector.jl:66`)  

### Signature `Tuple{typeof(transform!), AutoMLPipeline.NARemovers.NARemover, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.NARemovers` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/naremover.jl:81`)  
Commit `bacf5e1`: unstable => | (`AutoMLPipeline.NARemovers` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/naremover.jl:81`)  

### Signature `Tuple{typeof(fit!), DateValLinearImputer, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.ValDateFilters` at `/tmp/jl_l0lKDylCxY/src/valdatefilters.jl:951`)  
Commit `bacf5e1`: unstable => stable (`TSML.ValDateFilters` at `/tmp/jl_fobGZCz4do/src/valdatefilters.jl:948` => `TSML.ValDateFilters` at `/tmp/jl_1e9UdubkNc/src/valdatefilters.jl:972`)  

### Signature `Tuple{typeof(fit!), TimescaleDB, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.TimescaleDBs` at `/tmp/jl_l0lKDylCxY/src/timescaledb.jl:32`)  

### Signature `Tuple{typeof(transform!), Normalizer, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.Normalizers` at `/tmp/jl_l0lKDylCxY/src/normalizer.jl:91`)  
Commit `b7d03c6`: unstable => stable (`TSML.Normalizers` at `/tmp/jl_l0lKDylCxY/src/normalizer.jl:91` => `TSML.Normalizers` at `/tmp/jl_DOnM16Xcrq/src/normalizer.jl:91`)  

### Signature `Tuple{typeof(unstack), AbstractDataFrame}`

Commit `8e33482`: | => unstable (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/abstractdataframe/reshape.jl:499`)  
Commit `892cf9e`: unstable => | (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/abstractdataframe/reshape.jl:499`)  

### Signature `Tuple{typeof(fit!), Normalizer, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.Normalizers` at `/tmp/jl_l0lKDylCxY/src/normalizer.jl:78`)  
Commit `bacf5e1`: unstable => stable (`TSML.Normalizers` at `/tmp/jl_fobGZCz4do/src/normalizer.jl:78` => `TSML.Normalizers` at `/tmp/jl_1e9UdubkNc/src/normalizer.jl:83`)  

### Signature `Tuple{typeof(fit!), CSVDateValReader}`

Commit `8e33482`: | => unstable (`TSML.TSMLTransformers` at `/tmp/jl_TG9KpC9U34/src/valdate.jl:361`)  

### Signature `Tuple{typeof(fit!), Plotter, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.Plotters` at `/tmp/jl_l0lKDylCxY/src/plotter.jl:71`)  
Commit `b7d03c6`: unstable => | (`TSML.Plotters` at `/tmp/jl_l0lKDylCxY/src/plotter.jl:71`)  
Commit `b301f98`: | => unstable (`TSML.Plotters` at `/tmp/jl_fobGZCz4do/src/plotter.jl:86`)  
Commit `bacf5e1`: unstable => stable (`TSML.Plotters` at `/tmp/jl_fobGZCz4do/src/plotter.jl:86` => `TSML.Plotters` at `/tmp/jl_1e9UdubkNc/src/plotter.jl:90`)  

### Signature `Tuple{typeof(fit!), AutoMLPipeline.NARemovers.NARemover, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.NARemovers` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/naremover.jl:64`)  
Commit `bacf5e1`: unstable => | (`AutoMLPipeline.NARemovers` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/naremover.jl:64`)  

### Signature `Tuple{typeof(transform!), RandomForest, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.DecisionTreeLearners` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/decisiontree.jl:197`)  

### Signature `Tuple{typeof(matrifyrun)}`

Commit `8742e89`: | => unstable (`TSML.TSMLTransformers` at `/tmp/jl_Ps5wTs1Whu/src/transformers.jl:166`)  
Commit `8e33482`: unstable => | (`TSML.TSMLTransformers` at `/tmp/jl_Lchc3yPgdW/src/valdate.jl:45`)  

### Signature `Tuple{typeof(fit!), Statifier, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.Statifiers` at `/tmp/jl_l0lKDylCxY/src/statifier.jl:62`)  
Commit `bacf5e1`: unstable => stable (`TSML.Statifiers` at `/tmp/jl_fobGZCz4do/src/statifier.jl:62` => `TSML.Statifiers` at `/tmp/jl_1e9UdubkNc/src/statifier.jl:66`)  

### Signature `Tuple{typeof(fit!), Outliernicer, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.Outliernicers` at `/tmp/jl_l0lKDylCxY/src/outliernicer.jl:62`)  
Commit `bacf5e1`: unstable => stable (`TSML.Outliernicers` at `/tmp/jl_fobGZCz4do/src/outliernicer.jl:65` => `TSML.Outliernicers` at `/tmp/jl_1e9UdubkNc/src/outliernicer.jl:68`)  

### Signature `Tuple{typeof(antijoin), AbstractDataFrame, AbstractDataFrame}`

Commit `8e33482`: | => unstable (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/join/composer.jl:1488`)  
Commit `892cf9e`: unstable => | (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/join/composer.jl:1488`)  

### Signature `Tuple{typeof(transform!), TSML.BaselineAlgos.Baseline, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.BaselineAlgos` at `/tmp/jl_l0lKDylCxY/src/baseline.jl:54`)  
Commit `b7d03c6`: unstable => | (`TSML.BaselineAlgos` at `/tmp/jl_l0lKDylCxY/src/baseline.jl:54`)  

### Signature `Tuple{typeof(transform!), Wrapper, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.BaseFilters` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/basefilters.jl:217`)  
Commit `bacf5e1`: unstable => stable (`AutoMLPipeline.BaseFilters` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/basefilters.jl:217` => `AMLPipelineBase.BaseFilters` at `/home/jecmejan/.julia/packages/AMLPipelineBase/sH55F/src/basefilters.jl:256`)  

### Signature `Tuple{typeof(fit!), DateValMultiNNer, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.ValDateFilters` at `/tmp/jl_l0lKDylCxY/src/valdatefilters.jl:842`)  
Commit `bacf5e1`: unstable => stable (`TSML.ValDateFilters` at `/tmp/jl_fobGZCz4do/src/valdatefilters.jl:839` => `TSML.ValDateFilters` at `/tmp/jl_1e9UdubkNc/src/valdatefilters.jl:861`)  

### Signature `Tuple{typeof(transform!), Pipeline}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.Pipelines` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/pipelines.jl:97`)  

### Signature `Tuple{typeof(transform!), TimescaleDB}`

Commit `892cf9e`: | => unstable (`TSML.TimescaleDBs` at `/tmp/jl_l0lKDylCxY/src/timescaledb.jl:39`)  

### Signature `Tuple{typeof(transform!), TimescaleDB, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.TimescaleDBs` at `/tmp/jl_l0lKDylCxY/src/timescaledb.jl:39`)  

### Signature `Tuple{typeof(transform!), BestLearner, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.EnsembleMethods` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/ensemble.jl:431`)  

### Signature `Tuple{typeof(transform!), Pipeline, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.Pipelines` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/pipelines.jl:97`)  

### Signature `Tuple{typeof(transform!), DateValgator, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.ValDateFilters` at `/tmp/jl_l0lKDylCxY/src/valdatefilters.jl:270`)  

### Signature `Tuple{typeof(fit!), ComboPipeline, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.Pipelines` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/pipelines.jl:154`)  
Commit `bacf5e1`: unstable => stable (`AutoMLPipeline.Pipelines` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/pipelines.jl:154` => `AMLPipelineBase.Pipelines` at `/home/jecmejan/.julia/packages/AMLPipelineBase/sH55F/src/pipelines.jl:160`)  

### Signature `Tuple{typeof(shuffle), AbstractDataFrame}`

Commit `8e33482`: | => unstable (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/abstractdataframe/abstractdataframe.jl:2788`)  
Commit `892cf9e`: unstable => | (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/abstractdataframe/abstractdataframe.jl:2788`)  

### Signature `Tuple{typeof(transform!), Plotter, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.Plotters` at `/tmp/jl_l0lKDylCxY/src/plotter.jl:81`)  
Commit `b7d03c6`: unstable => | (`TSML.Plotters` at `/tmp/jl_l0lKDylCxY/src/plotter.jl:81`)  

### Signature `Tuple{typeof(transform!), AutoMLPipeline.SKPreprocessors.SKPreprocessor, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.SKPreprocessors` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/skpreprocessor.jl:166`)  
Commit `bacf5e1`: unstable => | (`AutoMLPipeline.SKPreprocessors` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/skpreprocessor.jl:166`)  

### Signature `Tuple{typeof(fit!), CSVDateValWriter, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.ValDateFilters` at `/tmp/jl_l0lKDylCxY/src/valdatefilters.jl:674`)  

### Signature `Tuple{typeof(infer_eltype), DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.Utils` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/utils.jl:135`)  

### Signature `Tuple{typeof(fit!), Statifier}`

Commit `892cf9e`: stable => unstable (`TSML.Statifiers` at `/tmp/jl_RSlCz2JQ5k/src/statifier.jl:64` => `TSML.Statifiers` at `/tmp/jl_l0lKDylCxY/src/statifier.jl:62`)  
Commit `bacf5e1`: unstable => stable (`TSML.Statifiers` at `/tmp/jl_fobGZCz4do/src/statifier.jl:62` => `TSML.Statifiers` at `/tmp/jl_1e9UdubkNc/src/statifier.jl:66`)  

### Signature `Tuple{typeof(fit!), CSVDateValWriter}`

Commit `8e33482`: | => unstable (`TSML.TSMLTransformers` at `/tmp/jl_TG9KpC9U34/src/valdate.jl:392`)  

### Signature `Tuple{typeof(fit!), TSML.BaselineAlgos.Baseline, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.BaselineAlgos` at `/tmp/jl_l0lKDylCxY/src/baseline.jl:45`)  
Commit `b7d03c6`: unstable => | (`TSML.BaselineAlgos` at `/tmp/jl_l0lKDylCxY/src/baseline.jl:45`)  

### Signature `Tuple{typeof(fit!), FeatureSelector, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.FeatureSelectors` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/featureselector.jl:59`)  
Commit `bacf5e1`: unstable => stable (`AutoMLPipeline.FeatureSelectors` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/featureselector.jl:59` => `AMLPipelineBase.FeatureSelectors` at `/home/jecmejan/.julia/packages/AMLPipelineBase/sH55F/src/featureselector.jl:58`)  

### Signature `Tuple{typeof(transform!), DateValizer, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.ValDateFilters` at `/tmp/jl_l0lKDylCxY/src/valdatefilters.jl:389`)  

### Signature `Tuple{typeof(dailyflips), DataFrame}`

Commit `8e33482`: | => unstable (`TSML.Monotonicers` at `/tmp/jl_TG9KpC9U34/src/monotonicer.jl:91`)  

### Signature `Tuple{typeof(rightjoin), AbstractDataFrame, AbstractDataFrame}`

Commit `8e33482`: | => unstable (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/join/composer.jl:1067`)  
Commit `892cf9e`: unstable => | (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/join/composer.jl:1067`)  

### Signature `Tuple{typeof(transform!), Matrifier, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.ValDateFilters` at `/tmp/jl_l0lKDylCxY/src/valdatefilters.jl:95`)  

### Signature `Tuple{typeof(fit!), DateValNNer, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.ValDateFilters` at `/tmp/jl_l0lKDylCxY/src/valdatefilters.jl:479`)  
Commit `bacf5e1`: unstable => stable (`TSML.ValDateFilters` at `/tmp/jl_fobGZCz4do/src/valdatefilters.jl:476` => `TSML.ValDateFilters` at `/tmp/jl_1e9UdubkNc/src/valdatefilters.jl:489`)  

### Signature `Tuple{typeof(TSML.__init__)}`

Commit `b7d03c6`: | => unstable (`TSML` at `/tmp/jl_DOnM16Xcrq/src/TSML.jl:97`)  
Commit `b301f98`: unstable => | (`TSML` at `/tmp/jl_DOnM16Xcrq/src/TSML.jl:97`)  

### Signature `Tuple{typeof(transform!), StandardScaler, DataFrame}`

Commit `790048b`: stable => unstable (`TSML.MLBaseWrapper` at `/tmp/jl_zORMhMBehk/src/mlbase.jl:66` => `TSML.MLBaseWrapper` at `/tmp/jl_DkJgtobEbS/src/mlbase.jl:66`)  

### Signature `Tuple{typeof(fit!), CSVDateValReader, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.ValDateFilters` at `/tmp/jl_l0lKDylCxY/src/valdatefilters.jl:605`)  

### Signature `Tuple{typeof(transform!), ComboPipeline}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.Pipelines` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/pipelines.jl:174`)  

### Signature `Tuple{typeof(transform!), SVMModel, DataFrame}`

Commit `bacf5e1`: | => unstable (`TSML.SVMModels` at `/tmp/jl_1e9UdubkNc/src/svm.jl:127`)  
Commit `3fd0ce8`: unstable => | (`TSML.SVMModels` at `/tmp/jl_1YVaVeVMDG/src/svm.jl:127`)  

### Signature `Tuple{typeof(fit!), Monotonicer, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.Monotonicers` at `/tmp/jl_l0lKDylCxY/src/monotonicer.jl:56`)  
Commit `bacf5e1`: unstable => stable (`TSML.Monotonicers` at `/tmp/jl_fobGZCz4do/src/monotonicer.jl:56` => `TSML.Monotonicers` at `/tmp/jl_1e9UdubkNc/src/monotonicer.jl:60`)  

### Signature `Tuple{typeof(transform!), NumFeatureSelector, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.FeatureSelectors` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/featureselector.jl:161`)  
Commit `bacf5e1`: unstable => stable (`AutoMLPipeline.FeatureSelectors` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/featureselector.jl:161` => `AMLPipelineBase.FeatureSelectors` at `/home/jecmejan/.julia/packages/AMLPipelineBase/sH55F/src/featureselector.jl:177`)  

### Signature `Tuple{typeof(metadatakeys), DataFrame}`

Commit `8e33482`: | => unstable (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/other/metadata.jl:151`)  
Commit `892cf9e`: unstable => | (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/other/metadata.jl:151`)  

### Signature `Tuple{typeof(transform!), CatFeatureSelector, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.FeatureSelectors` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/featureselector.jl:116`)  
Commit `bacf5e1`: unstable => stable (`AutoMLPipeline.FeatureSelectors` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/featureselector.jl:116` => `AMLPipelineBase.FeatureSelectors` at `/home/jecmejan/.julia/packages/AMLPipelineBase/sH55F/src/featureselector.jl:124`)  

### Signature `Tuple{typeof(fit!), BzCSVDateValReader}`

Commit `8e33482`: | => unstable (`TSML.TSMLTransformers` at `/tmp/jl_TG9KpC9U34/src/valdate.jl:424`)  
Commit `892cf9e`: unstable => | (`TSML.ValDateFilters` at `/tmp/jl_RSlCz2JQ5k/src/valdatefilters.jl:752`)  

### Signature `Tuple{typeof(transform!), PrunedTree, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.DecisionTreeLearners` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/decisiontree.jl:103`)  

### Signature `Tuple{typeof(colmetadatakeys), DataFrame}`

Commit `8e33482`: | => unstable (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/other/metadata.jl:436`)  
Commit `892cf9e`: unstable => | (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/other/metadata.jl:436`)  

### Signature `Tuple{typeof(+), TimeType, Period, Period}`

Commit `790048b`: | => unstable (`Dates` at `/cache/build/default-amdci4-2/julialang/julia-release-1-dot-8/usr/share/julia/stdlib/v1.8/Dates/src/periods.jl:389`)  

### Signature `Tuple{typeof(mean), MultivariateStats.PCA}`

Commit `892cf9e`: | => unstable (`MultivariateStats` at `/home/jecmejan/.julia/packages/MultivariateStats/zLpz8/src/pca.jl:41`)  
Commit `b7d03c6`: unstable => partial (`MultivariateStats` at `/home/jecmejan/.julia/packages/MultivariateStats/zLpz8/src/pca.jl:41` => `MultivariateStats` at `/home/jecmejan/.julia/packages/MultivariateStats/BYMwD/src/pca.jl:31`)  

### Signature `Tuple{typeof(tsmlmain)}`

Commit `8e33482`: | => unstable (`TSML.ArgumentParsers` at `/tmp/jl_TG9KpC9U34/src/argparse.jl:74`)  

### Signature `Tuple{typeof(tsmlrun), AbstractString}`

Commit `8e33482`: | => unstable (`TSML.CLIWrappers` at `/tmp/jl_TG9KpC9U34/src/cliwrapper.jl:24`)  

### Signature `Tuple{typeof(fit!), Pipeline, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.Pipelines` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/pipelines.jl:70`)  
Commit `bacf5e1`: unstable => stable (`AutoMLPipeline.Pipelines` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/pipelines.jl:70` => `AMLPipelineBase.Pipelines` at `/home/jecmejan/.julia/packages/AMLPipelineBase/sH55F/src/pipelines.jl:71`)  

### Signature `Tuple{typeof(transform!), Baseline, DataFrame}`

Commit `b7d03c6`: | => unstable (`AutoMLPipeline.Baselines` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/baselines.jl:59`)  

### Signature `Tuple{typeof(fit!), AutoMLPipeline.SKPreprocessors.SKPreprocessor, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.SKPreprocessors` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/skpreprocessor.jl:142`)  
Commit `bacf5e1`: unstable => | (`AutoMLPipeline.SKPreprocessors` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/skpreprocessor.jl:142`)  

### Signature `Tuple{typeof(fit!), Imputer, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.BaseFilters` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/basefilters.jl:144`)  
Commit `bacf5e1`: unstable => stable (`AutoMLPipeline.BaseFilters` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/basefilters.jl:144` => `AMLPipelineBase.BaseFilters` at `/home/jecmejan/.julia/packages/AMLPipelineBase/sH55F/src/basefilters.jl:159`)  

### Signature `Tuple{typeof(innerjoin), AbstractDataFrame, AbstractDataFrame}`

Commit `8e33482`: | => unstable (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/join/composer.jl:750`)  
Commit `892cf9e`: unstable => | (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/join/composer.jl:750`)  

### Signature `Tuple{typeof(+), Rational, Rational}`

Commit `790048b`: | => unstable (`Base` at `rational.jl:284`)  

### Signature `Tuple{typeof(fit_transform!), Machine}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.AbsTypes` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/abstracttypes.jl:41`)  

### Signature `Tuple{typeof(mrun)}`

Commit `8e33482`: unstable => | (`TSML.DataProc` at `/tmp/jl_Lchc3yPgdW/src/dataproc.jl:11`)  

### Signature `Tuple{typeof(testall)}`

Commit `2c0fff0`: unstable => stable (`TSML` at `/tmp/jl_v4t850VOxi/src/TSML.jl:48` => `TSML` at `/tmp/jl_9uJ4daBcNm/src/TSML.jl:48`)  

### Signature `Tuple{typeof(fit!), OneHotEncoder, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.BaseFilters` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/basefilters.jl:51`)  
Commit `bacf5e1`: unstable => stable (`AutoMLPipeline.BaseFilters` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/basefilters.jl:51` => `AMLPipelineBase.BaseFilters` at `/home/jecmejan/.julia/packages/AMLPipelineBase/sH55F/src/basefilters.jl:54`)  

### Signature `Tuple{typeof(transform!), Adaboost, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.DecisionTreeLearners` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/decisiontree.jl:271`)  

### Signature `Tuple{typeof(transform!), VoteEnsemble, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.EnsembleMethods` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/ensemble.jl:92`)  

### Signature `Tuple{typeof(transform!), ComboPipeline, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.Pipelines` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/pipelines.jl:174`)  

### Signature `Tuple{typeof(fit!), Pipeline}`

Commit `8e33482`: | => unstable (`TSML.TSMLTransformers` at `/tmp/jl_TG9KpC9U34/src/transformers.jl:183`)  
Commit `bacf5e1`: unstable => stable (`AutoMLPipeline.Pipelines` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/pipelines.jl:70` => `AMLPipelineBase.Pipelines` at `/home/jecmejan/.julia/packages/AMLPipelineBase/sH55F/src/pipelines.jl:71`)  

### Signature `Tuple{typeof(semijoin), AbstractDataFrame, AbstractDataFrame}`

Commit `8e33482`: | => unstable (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/join/composer.jl:1384`)  
Commit `892cf9e`: unstable => | (`DataFrames` at `/home/jecmejan/.julia/packages/DataFrames/LteEl/src/join/composer.jl:1384`)  

### Signature `Tuple{typeof(fit!), DateValgator, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.ValDateFilters` at `/tmp/jl_l0lKDylCxY/src/valdatefilters.jl:256`)  
Commit `bacf5e1`: unstable => stable (`TSML.ValDateFilters` at `/tmp/jl_fobGZCz4do/src/valdatefilters.jl:253` => `TSML.ValDateFilters` at `/tmp/jl_1e9UdubkNc/src/valdatefilters.jl:262`)  

### Signature `Tuple{typeof(getstats), AbstractString}`

Commit `8e33482`: | => unstable (`TSML.TSClassifiers.FileStats` at `/tmp/jl_TG9KpC9U34/src/filestats.jl:83`)  

### Signature `Tuple{typeof(transform!), AutoMLPipeline.Baselines.Baseline, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.Baselines` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/baselines.jl:59`)  
Commit `b7d03c6`: unstable => | (`AutoMLPipeline.Baselines` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/baselines.jl:59`)  

### Signature `Tuple{typeof(transform!), AutoMLPipeline.SKLearners.SKLearner, DataFrame}`

Commit `892cf9e`: | => unstable (`AutoMLPipeline.SKLearners` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/sklearners.jl:161`)  
Commit `bacf5e1`: unstable => | (`AutoMLPipeline.SKLearners` at `/home/jecmejan/.julia/packages/AutoMLPipeline/3Wa52/src/sklearners.jl:161`)  

### Signature `Tuple{typeof(fit!), Dateifier, DataFrame}`

Commit `892cf9e`: | => unstable (`TSML.ValDateFilters` at `/tmp/jl_l0lKDylCxY/src/valdatefilters.jl:169`)  


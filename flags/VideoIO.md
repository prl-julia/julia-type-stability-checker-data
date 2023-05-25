# Stability change report for package `VideoIO`

### Signature `Tuple{typeof(VideoIO.load), String}`

Commit `3eac5aa`: | => unstable (`VideoIO` at `/tmp/jl_AV8JU3GLUz/src/avio.jl:82`)  
Commit `33200c2`: unstable => | (`VideoIO` at `/tmp/jl_Mdupg90beT/src/avio.jl:82`)  

### Signature `Tuple{typeof(VideoIO.make_scale_function), VideoIO.GrayTransform}`

Commit `0388303`: | => unstable (`VideoIO` at `/tmp/jl_C3QLS10JMr/src/frame_graph.jl:153`)  

### Signature `Tuple{typeof(startencode!), IO}`

Commit `0388303`: | => unstable (`VideoIO` at `/tmp/jl_C3QLS10JMr/src/encoding.jl:388`)  
Commit `32a3c2a`: unstable => | (`VideoIO` at `/tmp/jl_C3QLS10JMr/src/encoding.jl:388`)  

### Signature `Tuple{typeof(VideoIO._read_packet), Ptr{VideoIO.AVInput}, Ptr{UInt8}, Int32}`

Commit `0388303`: unstable => | (`VideoIO` at `/tmp/jl_qfmpizU7YZ/src/avio.jl:128`)  

### Signature `Tuple{typeof(opencamera)}`

Commit `0a710e8`: unstable => stable (`VideoIO` at `/tmp/jl_gF8lmnotQR/src/avio.jl:1005` => `VideoIO` at `/tmp/jl_QDEbYtCXkD/src/avio.jl:1009`)  
Commit `7d790a2`: stable => unstable (`VideoIO` at `/tmp/jl_QDEbYtCXkD/src/avio.jl:1009` => `VideoIO` at `/tmp/jl_qTU7S3MnS7/src/avio.jl:1017`)  

### Signature `Tuple{typeof(VideoIO.retrieve), VideoIO.VideoReader{true}}`

Commit `0388303`: unstable => stable (`VideoIO` at `/tmp/jl_qfmpizU7YZ/src/avio.jl:367` => `VideoIO` at `/tmp/jl_C3QLS10JMr/src/avio.jl:483`)  


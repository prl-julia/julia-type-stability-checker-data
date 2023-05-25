# Stability change report for package `Gen`

### Signature `Tuple{typeof(Gen.vector_compute_retdiff), Dict{Int64, Diff}, Int64, Int64}`

Commit `64aef1ec`: | => unstable (`Gen` at `/tmp/jl_q5kRMXe90T/src/modeling_library/vector.jl:122` )  

### Signature `Tuple{typeof(get_internal_node), Gen.VectorTraceAssignment, Int64}`

Commit `08c581bb`: | => unstable (`Gen` at `/tmp/jl_UBsHi3IN0t/src/generators/vector_trace.jl:52` )  
Commit `c7597016`: unstable => | (`Gen` at `/tmp/jl_SHcRoN0DoN/src/combinators/vector_trace.jl:58` )  

### Signature `Tuple{typeof(get_internal_node), Gen.RecurseTraceAssignment, Tuple{Int64, Val{:aggregation}}}`

Commit `65b67d5f`: | => unstable (`Gen` at `/tmp/jl_0v8vGPgl6b/src/combinators/recurse/recurse.jl:64` )  
Commit `c7597016`: unstable => | (`Gen` at `/tmp/jl_SHcRoN0DoN/src/combinators/recurse/recurse.jl:64` )  

### Signature `Tuple{typeof(get_gen_fn), Gen.ChoiceAtTrace}`

Commit `c7597016`: | => unstable (`Gen` at `/tmp/jl_03oXO1uNO7/src/combinators/choice_at/choice_at.jl:14` )  

### Signature `Tuple{typeof(get_submap), Gen.RecurseTraceChoiceMap, Tuple{Int64, Val{:aggregation}}}`

Commit `82cf9f78`: | => unstable (`Gen` at `/tmp/jl_WF0rQdQVcj/src/combinators/recurse/recurse.jl:60` )  

### Signature `Tuple{typeof(Gen.get_selected_choices), AllAddressSchema, StaticIR}`

Commit `ef06cf47`: | => unstable (`Gen` at `/tmp/jl_WlSdY7QJUh/src/static_ir/backprop.jl:354` )  
Commit `52b94a71`: unstable => stable (`Gen` at `/tmp/jl_YrcrQFiLkb/src/static_ir/backprop.jl:355` => `Gen` at `/tmp/jl_ujKjYPiVo5/src/static_ir/backprop.jl:355` )  

### Signature `Tuple{typeof(get_assmt), Gen.CallAtTrace}`

Commit `c7597016`: | => unstable (`Gen` at `/tmp/jl_03oXO1uNO7/src/combinators/call_at/call_at.jl:35` )  
Commit `82cf9f78`: unstable => | (`Gen` at `/tmp/jl_sFKNQFUNgB/src/combinators/call_at/call_at.jl:35` )  

### Signature `Tuple{typeof(Gen.finish!), Gen.BasicBlockIR}`

Commit `4050dec4`: unstable => stable (`Gen` at `/tmp/jl_4H23OJyRK3/src/generators/basic/ir.jl:221` => `Gen` at `/tmp/jl_mpIFK5ypCx/src/generators/basic/ir.jl:223` )  

### Signature `Tuple{typeof(Gen.get_aux_args), Gen.JacobianPassState}`

Commit `68dd3a7c`: | => unstable (`Gen` at `/tmp/jl_kvmnCx0XYv/src/inference/trace_translators.jl:410` )  

### Signature `Tuple{typeof(get_retval), Gen.CallAtTrace}`

Commit `c7597016`: | => unstable (`Gen` at `/tmp/jl_03oXO1uNO7/src/combinators/call_at/call_at.jl:31` )  

### Signature `Tuple{typeof(get_internal_node), Gen.RecurseTraceAssignment, Tuple{Int64, Val{:production}}}`

Commit `65b67d5f`: | => unstable (`Gen` at `/tmp/jl_0v8vGPgl6b/src/combinators/recurse/recurse.jl:59` )  
Commit `c7597016`: unstable => | (`Gen` at `/tmp/jl_SHcRoN0DoN/src/combinators/recurse/recurse.jl:59` )  

### Signature `Tuple{typeof(get_param), Gen.GenFunction, Symbol}`

Commit `65b67d5f`: unstable => | (`Gen` at `/tmp/jl_GPmLGhm9Wx/src/generators/lightweight/lightweight.jl:222` )  

### Signature `Tuple{typeof(Gen.get_type), Gen.ArgumentValueNode}`

Commit `a784f5f9`: unstable => | (`Gen` at `/tmp/jl_0v8vGPgl6b/src/static_dsl/ir.jl:114` )  

### Signature `Tuple{typeof(get_choices), Gen.CallAtTrace}`

Commit `82cf9f78`: | => unstable (`Gen` at `/tmp/jl_WF0rQdQVcj/src/combinators/call_at/call_at.jl:35` )  

### Signature `Tuple{typeof(Gen.toplevel), Expr}`

Commit `f9aef08e`: | => unstable (`Gen` at `/tmp/jl_k30LQluZe7/src/inference/kernel_dsl.jl:201` )  

### Signature `Tuple{typeof(Gen.set_retchange!), Gen.BasicBlockIR, Symbol}`

Commit `a784f5f9`: unstable => | (`Gen` at `/tmp/jl_0v8vGPgl6b/src/static_dsl/ir.jl:449` )  

### Signature `Tuple{typeof(Gen.all_visited), AddressSet, Assignment}`

Commit `c7597016`: | => unstable (`Gen` at `/tmp/jl_03oXO1uNO7/src/dynamic_dsl/dynamic_dsl.jl:288` )  
Commit `82cf9f78`: unstable => | (`Gen` at `/tmp/jl_sFKNQFUNgB/src/dynamic/dynamic.jl:186` )  

### Signature `Tuple{typeof(get_call_record), Gen.GFTrace}`

Commit `c7597016`: unstable => | (`Gen` at `/tmp/jl_SHcRoN0DoN/src/dynamic_dsl/trace.jl:26` )  

### Signature `Tuple{typeof(Gen.parse_addr), Expr}`

Commit `a784f5f9`: unstable => | (`Gen` at `/tmp/jl_0v8vGPgl6b/src/static_dsl/static_dsl.jl:23` )  

### Signature `Tuple{typeof(get_submap), Gen.VectorTraceChoiceMap, Int64}`

Commit `82cf9f78`: | => unstable (`Gen` at `/tmp/jl_WF0rQdQVcj/src/combinators/vector.jl:76` )  
Commit `e5338755`: unstable => partial (`Gen` at `/tmp/jl_WJmFALujqv/src/modeling_library/vector.jl:81` => `Gen` at `/tmp/jl_gTUlkbeBCL/src/modeling_library/vector.jl:81` )  

### Signature `Tuple{typeof(Gen.set_return!), Gen.BasicBlockIR, Expr}`

Commit `45d4efe0`: unstable => | (`Gen` at `/tmp/jl_QpwLiv4vcH/src/generators/basic/ir.jl:440` )  

### Signature `Tuple{typeof(Gen.parents), Gen.AddrChangeNode}`

Commit `a784f5f9`: unstable => | (`Gen` at `/tmp/jl_0v8vGPgl6b/src/static_dsl/ir.jl:83` )  

### Signature `Tuple{typeof(get_gen_fn), Gen.CallAtTrace}`

Commit `c7597016`: | => unstable (`Gen` at `/tmp/jl_03oXO1uNO7/src/combinators/call_at/call_at.jl:33` )  

### Signature `Tuple{typeof(Gen.get_model_args), Gen.JacobianPassState}`

Commit `68dd3a7c`: | => unstable (`Gen` at `/tmp/jl_kvmnCx0XYv/src/inference/trace_translators.jl:406` )  

### Signature `Tuple{typeof(Gen.get_type), Gen.ExprValueNode}`

Commit `a784f5f9`: unstable => | (`Gen` at `/tmp/jl_0v8vGPgl6b/src/static_dsl/ir.jl:137` )  

### Signature `Tuple{typeof(Gen.get_args_change), Gen.GFUpdateState}`

Commit `69bb3185`: unstable => | (`Gen` at `/tmp/jl_AFajaVAneF/src/generators/lightweight/update.jl:21` )  

### Signature `Tuple{typeof(Gen.parse_lhs), Expr}`

Commit `a784f5f9`: unstable => | (`Gen` at `/tmp/jl_0v8vGPgl6b/src/static_dsl/static_dsl.jl:71` )  

### Signature `Tuple{typeof(zero_param_grad!), Gen.DynamicDSLFunction, Symbol}`

Commit `65b67d5f`: | => unstable (`Gen` at `/tmp/jl_0v8vGPgl6b/src/dynamic_dsl/dynamic_dsl.jl:230` )  
Commit `c7597016`: unstable => | (`Gen` at `/tmp/jl_SHcRoN0DoN/src/dynamic_dsl/dynamic_dsl.jl:224` )  

### Signature `Tuple{typeof(Gen.get_value_info), Gen.ExprNode}`

Commit `a784f5f9`: unstable => | (`Gen` at `/tmp/jl_0v8vGPgl6b/src/static_dsl/ir.jl:474` )  

### Signature `Tuple{typeof(Gen.get_model_args), Gen.FirstPassState}`

Commit `68dd3a7c`: | => unstable (`Gen` at `/tmp/jl_kvmnCx0XYv/src/inference/trace_translators.jl:271` )  

### Signature `Tuple{typeof(get_choices), Gen.ChoiceAtTrace}`

Commit `82cf9f78`: | => unstable (`Gen` at `/tmp/jl_WF0rQdQVcj/src/combinators/choice_at/choice_at.jl:21` )  

### Signature `Tuple{typeof(get_leaf_node), Gen.VectorDistTraceChoiceTrie, Int64}`

Commit `08c581bb`: unstable => | (`Gen` at `/tmp/jl_0beRiboZWh/src/generators/vector_trace.jl:111` )  

### Signature `Tuple{typeof(get_internal_nodes), Gen.TreeTraceAssignment}`

Commit `69bb3185`: | => unstable (`Gen` at `/tmp/jl_GPmLGhm9Wx/src/generators/tree/tree.jl:83` )  
Commit `65b67d5f`: unstable => | (`Gen` at `/tmp/jl_GPmLGhm9Wx/src/generators/tree/tree.jl:83` )  

### Signature `Tuple{typeof(zero_param_grad!), Gen.GenFunction, Symbol}`

Commit `65b67d5f`: unstable => | (`Gen` at `/tmp/jl_GPmLGhm9Wx/src/generators/lightweight/lightweight.jl:230` )  

### Signature `Tuple{typeof(Gen.parse_static_dsl_function), Expr}`

Commit `a784f5f9`: | => unstable (`Gen` at `/tmp/jl_ALiRIBaBYz/src/static_dsl/static_dsl.jl:385` )  
Commit `9d4f0548`: unstable => | (`Gen` at `/tmp/jl_03oXO1uNO7/src/static_dsl/static_dsl.jl:465` )  

### Signature `Tuple{typeof(get_internal_node), Gen.VectorTraceChoiceTrie, Int64}`

Commit `08c581bb`: unstable => | (`Gen` at `/tmp/jl_0beRiboZWh/src/generators/vector_trace.jl:52` )  

### Signature `Tuple{typeof(get_score), Gen.CallAtTrace}`

Commit `c7597016`: | => unstable (`Gen` at `/tmp/jl_03oXO1uNO7/src/combinators/call_at/call_at.jl:32` )  

### Signature `Tuple{typeof(Gen.get_type), Gen.ParamValueNode}`

Commit `a784f5f9`: unstable => | (`Gen` at `/tmp/jl_0v8vGPgl6b/src/static_dsl/ir.jl:151` )  

### Signature `Tuple{typeof(Gen.compute_retdiff), Dict{Int64, Any}, Int64, Int64}`

Commit `69bb3185`: | => unstable (`Gen` at `/tmp/jl_GPmLGhm9Wx/src/generators/plate/plate.jl:93` )  
Commit `c7597016`: unstable => | (`Gen` at `/tmp/jl_SHcRoN0DoN/src/combinators/map/map.jl:89` )  

### Signature `Tuple{typeof(Gen.get_args_change), Gen.GFRegenerateState}`

Commit `69bb3185`: unstable => | (`Gen` at `/tmp/jl_AFajaVAneF/src/generators/lightweight/regenerate.jl:20` )  

### Signature `Tuple{typeof(Gen.strip_marked_for_ad), Expr}`

Commit `738572dd`: unstable => | (`Gen` at `/tmp/jl_cNczOTqRy5/src/dynamic_dsl/dynamic_dsl.jl:145` )  

### Signature `Tuple{typeof(Gen.parents), Gen.ExprValueNode}`

Commit `a784f5f9`: unstable => | (`Gen` at `/tmp/jl_0v8vGPgl6b/src/static_dsl/ir.jl:136` )  

### Signature `Tuple{typeof(Gen.get_aux_args), Gen.FirstPassState}`

Commit `68dd3a7c`: | => unstable (`Gen` at `/tmp/jl_kvmnCx0XYv/src/inference/trace_translators.jl:275` )  

### Signature `Tuple{typeof(get_param_grad), Gen.GenFunction, Symbol}`

Commit `65b67d5f`: unstable => | (`Gen` at `/tmp/jl_GPmLGhm9Wx/src/generators/lightweight/lightweight.jl:226` )  

### Signature `Tuple{typeof(get_args), Gen.CallAtTrace}`

Commit `c7597016`: | => unstable (`Gen` at `/tmp/jl_03oXO1uNO7/src/combinators/call_at/call_at.jl:30` )  

### Signature `Tuple{typeof(get_subassmt), Gen.RecurseTraceAssignment, Tuple{Int64, Val{:aggregation}}}`

Commit `c7597016`: | => unstable (`Gen` at `/tmp/jl_03oXO1uNO7/src/combinators/recurse/recurse.jl:60` )  
Commit `82cf9f78`: unstable => | (`Gen` at `/tmp/jl_sFKNQFUNgB/src/combinators/recurse/recurse.jl:60` )  

### Signature `Tuple{typeof(Gen.all_indices), Gen.TransformedArg}`

Commit `8ca4dc24`: | => unstable (`Gen` at `/tmp/jl_UZYFkbcL6V/src/modeling_library/dist/dist_dsl.jl:27` )  
Commit `bc3a558c`: unstable => partial (`Gen` at `/tmp/jl_4boLqLqpE7/src/modeling_library/dist/dist_dsl.jl:27` => `Gen` at `/tmp/jl_EHyT6TUvmD/src/modeling_library/dist/dist_dsl.jl:26` )  

### Signature `Tuple{typeof(get_internal_node), Gen.TreeTraceAssignment, Tuple{Int64, Val{:aggregation}}}`

Commit `69bb3185`: | => unstable (`Gen` at `/tmp/jl_GPmLGhm9Wx/src/generators/tree/tree.jl:64` )  
Commit `65b67d5f`: unstable => | (`Gen` at `/tmp/jl_GPmLGhm9Wx/src/generators/tree/tree.jl:64` )  

### Signature `Tuple{typeof(Gen.get_args_change), Gen.GFFixUpdateState}`

Commit `a985feb3`: | => unstable (`Gen` at `/tmp/jl_uPG163yVO5/src/generators/lightweight/fix_update.jl:23` )  
Commit `69bb3185`: unstable => | (`Gen` at `/tmp/jl_AFajaVAneF/src/generators/lightweight/fix_update.jl:23` )  

### Signature `Tuple{typeof(get_internal_node), Gen.TreeTraceAssignment, Tuple{Int64, Val{:production}}}`

Commit `69bb3185`: | => unstable (`Gen` at `/tmp/jl_GPmLGhm9Wx/src/generators/tree/tree.jl:59` )  
Commit `65b67d5f`: unstable => | (`Gen` at `/tmp/jl_GPmLGhm9Wx/src/generators/tree/tree.jl:59` )  

### Signature `Tuple{typeof(get_internal_nodes), Gen.RecurseTraceAssignment}`

Commit `65b67d5f`: | => unstable (`Gen` at `/tmp/jl_0v8vGPgl6b/src/combinators/recurse/recurse.jl:83` )  
Commit `c7597016`: unstable => | (`Gen` at `/tmp/jl_SHcRoN0DoN/src/combinators/recurse/recurse.jl:83` )  

### Signature `Tuple{typeof(Gen.get_args_change), Gen.GFExtendState}`

Commit `08c581bb`: | => unstable (`Gen` at `/tmp/jl_UBsHi3IN0t/src/generators/lightweight/extend.jl:20` )  
Commit `69bb3185`: unstable => | (`Gen` at `/tmp/jl_AFajaVAneF/src/generators/lightweight/extend.jl:20` )  

### Signature `Tuple{typeof(Gen.expr_read_from_trace), Gen.JuliaNode, Symbol}`

Commit `a784f5f9`: unstable => | (`Gen` at `/tmp/jl_0v8vGPgl6b/src/static_dsl/ir.jl:98` )  

### Signature `Tuple{typeof(Gen.set_return!), Gen.BasicBlockIR, Symbol}`

Commit `a784f5f9`: unstable => | (`Gen` at `/tmp/jl_0v8vGPgl6b/src/static_dsl/ir.jl:431` )  

### Signature `Tuple{typeof(get_submaps_shallow), Gen.RecurseTraceChoiceMap}`

Commit `82cf9f78`: | => unstable (`Gen` at `/tmp/jl_WF0rQdQVcj/src/combinators/recurse/recurse.jl:84` )  

### Signature `Tuple{typeof(Gen.vector_compute_retdiff), Dict{Int64, Any}, Int64, Int64}`

Commit `c7597016`: | => unstable (`Gen` at `/tmp/jl_03oXO1uNO7/src/combinators/vector.jl:135` )  
Commit `64aef1ec`: unstable => | (`Gen` at `/tmp/jl_wjodQj4hGp/src/combinators/vector.jl:160` )  

### Signature `Tuple{typeof(get_internal_nodes), Gen.VectorTraceChoiceTrie}`

Commit `08c581bb`: unstable => | (`Gen` at `/tmp/jl_0beRiboZWh/src/generators/vector_trace.jl:76` )  

### Signature `Tuple{typeof(get_args), Gen.ChoiceAtTrace}`

Commit `c7597016`: | => unstable (`Gen` at `/tmp/jl_03oXO1uNO7/src/combinators/choice_at/choice_at.jl:11` )  

### Signature `Tuple{typeof(get_subassmt), Gen.VectorTraceAssignment, Int64}`

Commit `c7597016`: | => unstable (`Gen` at `/tmp/jl_03oXO1uNO7/src/combinators/vector.jl:76` )  
Commit `82cf9f78`: unstable => | (`Gen` at `/tmp/jl_sFKNQFUNgB/src/combinators/vector.jl:76` )  

### Signature `Tuple{typeof(get_subassmts_shallow), Gen.RecurseTraceAssignment}`

Commit `c7597016`: | => unstable (`Gen` at `/tmp/jl_03oXO1uNO7/src/combinators/recurse/recurse.jl:84` )  
Commit `82cf9f78`: unstable => | (`Gen` at `/tmp/jl_sFKNQFUNgB/src/combinators/recurse/recurse.jl:84` )  

### Signature `Tuple{typeof(get_submap), Gen.RecurseTraceChoiceMap, Tuple{Int64, Val{:production}}}`

Commit `82cf9f78`: | => unstable (`Gen` at `/tmp/jl_WF0rQdQVcj/src/combinators/recurse/recurse.jl:50` )  

### Signature `Tuple{typeof(Gen.all_visited), Selection, ChoiceMap}`

Commit `0657fb2a`: partial => unstable (`Gen` at `/tmp/jl_SRobizEvy1/src/dynamic/dynamic.jl:112` => `Gen` at `/tmp/jl_8dgnmTw3ar/src/dynamic/dynamic.jl:112` )  

### Signature `Tuple{typeof(get_param), Gen.DynamicDSLFunction, Symbol}`

Commit `65b67d5f`: | => unstable (`Gen` at `/tmp/jl_0v8vGPgl6b/src/dynamic_dsl/dynamic_dsl.jl:222` )  
Commit `c7597016`: unstable => | (`Gen` at `/tmp/jl_SHcRoN0DoN/src/dynamic_dsl/dynamic_dsl.jl:216` )  

### Signature `Tuple{typeof(Gen.all_visited), AddressSet, ChoiceMap}`

Commit `82cf9f78`: | => unstable (`Gen` at `/tmp/jl_WF0rQdQVcj/src/dynamic/dynamic.jl:204` )  
Commit `ef06cf47`: unstable => | (`Gen` at `/tmp/jl_S9cBQ1iha7/src/dynamic/dynamic.jl:109` )  

### Signature `Tuple{typeof(get_param_grad), Gen.DynamicDSLFunction, Symbol}`

Commit `65b67d5f`: | => unstable (`Gen` at `/tmp/jl_0v8vGPgl6b/src/dynamic_dsl/dynamic_dsl.jl:226` )  
Commit `c7597016`: unstable => | (`Gen` at `/tmp/jl_SHcRoN0DoN/src/dynamic_dsl/dynamic_dsl.jl:220` )  

### Signature `Tuple{typeof(get_retval), Gen.ChoiceAtTrace}`

Commit `c7597016`: | => unstable (`Gen` at `/tmp/jl_03oXO1uNO7/src/combinators/choice_at/choice_at.jl:12` )  

### Signature `Tuple{typeof(Gen.read), Gen.FirstPassState, Gen.ModelInputTraceRetValToken, Gen.DiscreteAnn}`

Commit `d948cf3b`: | => unstable (`Gen` at `/tmp/jl_49avoPW30j/src/inference/trace_translators.jl:271` )  

### Signature `Tuple{typeof(Gen.set_retchange!), Gen.BasicBlockIR, Expr}`

Commit `45d4efe0`: unstable => | (`Gen` at `/tmp/jl_QpwLiv4vcH/src/generators/basic/ir.jl:460` )  

### Signature `Tuple{typeof(get_internal_nodes), Gen.VectorTraceAssignment}`

Commit `08c581bb`: | => unstable (`Gen` at `/tmp/jl_UBsHi3IN0t/src/generators/vector_trace.jl:76` )  
Commit `69bb3185`: unstable => stable (`Gen` at `/tmp/jl_AFajaVAneF/src/generators/vector_trace.jl:76` => `Gen` at `/tmp/jl_GPmLGhm9Wx/src/generators/vector_trace.jl:66` )  

### Signature `Tuple{typeof(Gen.read), Gen.FirstPassState, Gen.AuxInputTraceRetValToken, Gen.DiscreteAnn}`

Commit `d948cf3b`: | => unstable (`Gen` at `/tmp/jl_49avoPW30j/src/inference/trace_translators.jl:275` )  

### Signature `Tuple{typeof(Gen.parse_arg_expr), Expr}`

Commit `a784f5f9`: | => unstable (`Gen` at `/tmp/jl_ALiRIBaBYz/src/static_dsl/static_dsl.jl:19` )  
Commit `738572dd`: unstable => | (`Gen` at `/tmp/jl_cNczOTqRy5/src/static_dsl/static_dsl.jl:19` )  

### Signature `Tuple{typeof(get_assmt), Gen.ChoiceAtTrace}`

Commit `c7597016`: | => unstable (`Gen` at `/tmp/jl_03oXO1uNO7/src/combinators/choice_at/choice_at.jl:21` )  
Commit `82cf9f78`: unstable => | (`Gen` at `/tmp/jl_sFKNQFUNgB/src/combinators/choice_at/choice_at.jl:21` )  

### Signature `Tuple{typeof(get_subassmt), Gen.RecurseTraceAssignment, Tuple{Int64, Val{:production}}}`

Commit `c7597016`: | => unstable (`Gen` at `/tmp/jl_03oXO1uNO7/src/combinators/recurse/recurse.jl:50` )  
Commit `82cf9f78`: unstable => | (`Gen` at `/tmp/jl_sFKNQFUNgB/src/combinators/recurse/recurse.jl:50` )  

### Signature `Tuple{typeof(get_leaf_node), Gen.VectorDistTraceAssignment, Int64}`

Commit `08c581bb`: | => unstable (`Gen` at `/tmp/jl_UBsHi3IN0t/src/generators/vector_trace.jl:111` )  
Commit `c7597016`: unstable => | (`Gen` at `/tmp/jl_SHcRoN0DoN/src/combinators/vector_trace.jl:118` )  

### Signature `Tuple{typeof(Gen.typed), Symbol}`

Commit `d948cf3b`: | => unstable (`Gen` at `/tmp/jl_49avoPW30j/src/inference/trace_translators.jl:171` )  


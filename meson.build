project('SPIRV-Headers', 'c',
    version : '1.5.1',
)

spirv_headers_dep = declare_dependency(
    include_directories : include_directories('include')
)

spirv_include_path = join_paths(meson.current_source_dir(), 'include')

file_spir_v_xml = files('include/spirv/spir-v.xml')
file_unified1_spirv_core_grammar_json = files('include/spirv/unified1/spirv.core.grammar.json')
file_unified1_extinst_glsl_std_450_grammar_json = files('include/spirv/unified1/extinst.glsl.std.450.grammar.json')
file_unified1_extinst_opencl_std_100_grammar_json = files('include/spirv/unified1/extinst.opencl.std.100.grammar.json')

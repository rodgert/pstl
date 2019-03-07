add_subdirectory(alg.copy)
add_subdirectory(alg.partitions)
add_subdirectory(alg.reverse)

set(PASS_SOURCES
	replace.pass.cpp;
	transform_unary.pass.cpp;
	unique_copy_equal.pass.cpp;
	swap_ranges.pass.cpp;
	copy_move.pass.cpp;
	generate.pass.cpp;
	rotate.pass.cpp;
	remove_copy.pass.cpp;
	fill.pass.cpp;
	rotate_copy.pass.cpp;
	transform_binary.pass.cpp;
	replace_copy.pass.cpp;
	remove.pass.cpp;
	unique.pass.cpp
)

foreach(test_source ${PASS_SOURCES})
  add_pass_test(${test_source})
endforeach(test_source ${PASS_SOURCES})


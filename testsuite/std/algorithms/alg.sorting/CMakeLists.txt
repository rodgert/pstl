add_subdirectory(alg.heap.operations)
add_subdirectory(alg.lex.comparison)
add_subdirectory(alg.min.max)
add_subdirectory(alg.set.operations)

set(PASS_SOURCES
	sort.pass.cpp;
	partial_sort.pass.cpp;
	partial_sort_copy.pass.cpp;
	is_sorted.pass.cpp
)

foreach(test_source ${PASS_SOURCES})
  add_pass_test(${test_source})
endforeach(test_source ${PASS_SOURCES})


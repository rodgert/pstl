set(PASS_SOURCES
	scan.pass.cpp;
	transform_scan.pass.cpp;
	transform_reduce.pass.cpp;
	reduce.pass.cpp;
	adjacent_difference.pass.cpp
)

foreach(test_source ${PASS_SOURCES})
  add_pass_test(${test_source})
endforeach(test_source ${PASS_SOURCES})


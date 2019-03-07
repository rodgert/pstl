set(PASS_SOURCES
	partition_copy.pass.cpp;
	partition.pass.cpp;
	is_partitioned.pass.cpp
)

foreach(test_source ${PASS_SOURCES})
  add_pass_test(${test_source})
endforeach(test_source ${PASS_SOURCES})


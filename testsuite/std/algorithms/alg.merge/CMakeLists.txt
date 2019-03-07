set(PASS_SOURCES
	inplace_merge.pass.cpp;
	merge.pass.cpp
)

foreach(test_source ${PASS_SOURCES})
  add_pass_test(${test_source})
endforeach(test_source ${PASS_SOURCES})


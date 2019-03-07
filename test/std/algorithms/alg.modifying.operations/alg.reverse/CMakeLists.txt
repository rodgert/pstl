set(PASS_SOURCES
	reverse_copy.pass.cpp;
	reverse.pass.cpp
)

foreach(test_source ${PASS_SOURCES})
  add_pass_test(${test_source})
endforeach(test_source ${PASS_SOURCES})


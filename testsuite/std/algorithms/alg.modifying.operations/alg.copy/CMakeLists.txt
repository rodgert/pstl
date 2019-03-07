set(PASS_SOURCES
	copy_if.pass.cpp
)

foreach(test_source ${PASS_SOURCES})
  add_pass_test(${test_source})
endforeach(test_source ${PASS_SOURCES})


set(PASS_SOURCES
	uninitialized_construct.pass.cpp;
	uninitialized_copy_move.pass.cpp;
	uninitialized_fill_destroy.pass.cpp
)

foreach(test_source ${PASS_SOURCES})
  add_pass_test(${test_source})
endforeach(test_source ${PASS_SOURCES})


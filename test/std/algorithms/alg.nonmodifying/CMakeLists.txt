set(PASS_SOURCES
	mismatch.pass.cpp;
	nth_element.pass.cpp;
	equal.pass.cpp;
	find_first_of.pass.cpp;
	find_if.pass.cpp;
	for_each.pass.cpp;
	find_end.pass.cpp;
	count.pass.cpp;
	search_n.pass.cpp;
	adjacent_find.pass.cpp;
	any_of.pass.cpp;
	none_of.pass.cpp;
	all_of.pass.cpp;
	find.pass.cpp
)

foreach(test_source ${PASS_SOURCES})
  add_pass_test(${test_source})
endforeach(test_source ${PASS_SOURCES})


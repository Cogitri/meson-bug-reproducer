project(
	'reproducer-d',
	'd',
)

testlib = shared_library(
	'tester',
	'lib.d',
)

executable(
	'tester',
	'main.d',
	link_with: testlib,
)

IF(XPM_FOUND)
SET(TESTS_FILES
	bug00166
	bug00185
	color_name
)
ENDIF(XPM_FOUND)

ADD_GD_TESTS()

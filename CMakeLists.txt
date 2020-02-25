project(usertemplate)

install(DIRECTORY Non_localized/
	DESTINATION "libexec/darling/System/Library/User Template"
	PATTERN ".gitignore" EXCLUDE
)


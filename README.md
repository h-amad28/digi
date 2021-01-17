# digi

# the filtering portion is expanded unexpectedly
# we can create centralize filtering portion to AVOID the usage of too much if conditions
# I do prefer to use the data filteration checks/verifiction on controller level
# we can utilize Inner Join/leftjoin instead of calling a query on different aspects like we have process the
#		users in certain criteria
#	As for dynamic filtering the user can quickly judge the criteria rather than falling in to analysing code row by row
#	and commenting using Documentation Params will be great like using the API DOC/SWAGGER which in turn an Engineer can come to concllusion immediately regarding to the process flow
# for calling same instance in EAGER loading "with" we can use $append property which load the related portion without mentioning it every time
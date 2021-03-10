Enable policy based data structures in windows: \
\
if after #include<ext/pb_ds/assoc_container.hpp> has error "cannot open source file hash_standard_resize_policy_imp.hpp " then, \
\
Go to the dir -> C:\MinGW\lib\gcc\mingw32\8.2.0\include\c++\ext\pb_ds\detail\resize_policy\
\
There u will see a file similar to -> "hash_standard_resize_policy_imp.hpp0000644" \
\
Rename it to hash_standard_resize_policy_imp.hpp \
\
Save and run again

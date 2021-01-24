aslr-harden:

A small Linux kernel patch that hardens the built-in ASLR implementation against
entropy reduction and leakage of several critical addresses.

Update (January, 2021):

Initially created in the April of 2017 in response to GRSecurity / PAX going fully private during the next few months of 2017, this patch
is still of use today and can be applied to modern kernels with little modifications required. During the last 4 years,
a few security enhancements initially developed by the GRSecurity team have been merged into the Linux kernel, however
security still does not have the priority it deserves when it comes to Linux kernel development.

This is a repo I can use for automated tests on the programs that 
automatically push to git repos.

I created this as a separate repo because I didn't want test runs
to show up as a huge list of commits on the main project repo.

NOTE: This is _not_ a submodule. Since the tests need to push to
this repo, it needs to be writable by whomever is running the tests.
To the best of my knowledge, the best way to do this is to have
each person create his/her own repo.
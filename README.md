# pledge

porting [jart's port of openbsd pledge for linux](https://justine.lol/pledge/) to a normal libc

this project targets musl libc, the reasoning being that since musl pedantically follows
standards, it should hopefully work on any reasonably POSIX-y libc.

i am not a security expert and this project has not been audited by one. use at your own risk!

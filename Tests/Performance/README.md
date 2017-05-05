Performance Tests
=================

To run those tests, install FMDB, SQLite.swift, and Realm:

```sh
git submodule update --init --recursive Tests/Performance/fmdb
git submodule update --init --recursive Tests/Performance/Realm
git submodule update --init --recursive Tests/Performance/SQLite.swift
cd Tests/Performance/Realm
git submodule update --init --recursive
sh build.sh osx-swift
```

Then open GRDB.xcworkspace, and test the GRDBOSXPerformanceTests target.

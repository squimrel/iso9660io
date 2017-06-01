cc_library(
    name="iso9660",
    srcs=glob(["src/*.cc"]),
    hdrs=glob(["include/*.h"]),
    copts=["-std=c++11", "-Wall", "-O3"],
    visibility=["//visibility:public"], )

cc_binary(
    name="persistent-storage",
    srcs=["example/persistent-storage.cc"],
    copts=["-std=c++11", "-Wall", "-O3"],
    deps=[":iso9660"], )

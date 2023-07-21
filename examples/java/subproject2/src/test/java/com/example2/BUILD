filegroup(
    name = "java_test_srcs",
    srcs = glob(["*.java"]),
    visibility = ["//visibility:public"],
)

java_test(
    name = "AppTest",
    srcs = ["AppTest.java"],
    deps = [
        "//subproject2/src/main/java/com/example2:app",
        "@maven//:junit_junit",
    ],
    size = "small",
    visibility = [ "//visibility:public" ],
)

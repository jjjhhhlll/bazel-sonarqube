load("@bazel_sonarqube//:defs.bzl", "sq_project")

sq_project(
    name = "sq_subproject",
    srcs = ["//subproject2/src/main/java/com/example2:java_srcs"],
    project_key = "com.example.project:subproject",
    project_name = "My Project :: Sub-Project",
    tags = ["manual"],
    targets = ["//subproject2/src/main/java/com/example2:app"],
    test_reports = ["//:test_reports"],
    test_srcs = ["//subproject2/src/test/java/com/example2:java_test_srcs"],
    test_targets = [
        "//subproject2/src/test/java/com/example2:AppTest",
    ],
    visibility = ["//visibility:public"],
    testonly = True,
)

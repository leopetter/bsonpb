load("@io_bazel_rules_go//go:def.bzl", "go_binary")

go_binary(
    name = "marshal",
    srcs = [
        "marshal.go",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "//:go_default_library",
        "//test_protos:test_objects_go_proto",
    ],
)

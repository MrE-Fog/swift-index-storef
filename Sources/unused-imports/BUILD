load("@build_bazel_rules_swift//swift:swift.bzl", "swift_binary")

swift_binary(
    name = "unused-imports",
    srcs = [
        "main.swift",
    ],
    tags = [
        "manual",
    ],
    deps = [
        "//:IndexStore",
    ],
)

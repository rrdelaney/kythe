package(default_visibility = ["//visibility:public"])

exports_files([
    "node_configure.bzl",
    "kythe_pkg_config.bzl",
    "check_bazel_versions.sh",
])

# A binary that will cat or zcat arguments, based on file suffix.
sh_binary(
    name = "zcatext",
    srcs = ["zcatext.sh"],
)

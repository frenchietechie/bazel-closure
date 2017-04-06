load("@io_bazel_rules_closure//closure:defs.bzl", "closure_js_library")
load("@io_bazel_rules_closure//closure:defs.bzl", "closure_js_binary")

closure_js_library(
  name = "example_lib",
  srcs = [
    "library.js",
  ],
  deps = [
  ],
  language = "ECMASCRIPT5_STRICT",
  suppress = [],
  convention = "GOOGLE",
)

closure_js_binary(
  name = "example_project",
  deps = [
    ":example_lib",
  ],
  language = "ECMASCRIPT5_STRICTs",
)

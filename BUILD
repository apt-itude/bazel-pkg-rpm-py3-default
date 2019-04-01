py_runtime(
    name = "target-based-runtime",
    interpreter_path = select({
        "@bazel_tools//tools/python:PY2": "/usr/bin/python2",
        "@bazel_tools//tools/python:PY3": "/usr/bin/python3",
    }),
    visibility = ["//visibility:public"],
)

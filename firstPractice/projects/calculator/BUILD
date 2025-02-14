#load("@pip//:requirements.bzl", "requirement")
#load("@rules_python//python:py_library.bzl", "py_library")
#load("@rules_python//python:py_test.bzl", "py_test")

py_library(
    name = "calculator",
    srcs = ["calculator.py"],
    visibility = ["//visibility:public"],
)

py_test(
    name = "calculator_test",
    srcs = ["calculator_test.py"],
    deps = ["//projects/calculator"],
)

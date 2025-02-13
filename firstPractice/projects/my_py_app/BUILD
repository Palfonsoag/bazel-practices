
load("@pypi//:requirements.bzl", "requirement")

py_binary(
  name = "main",
  srcs = ["main.py"],
  deps = [
    "//projects/calculator:calculator",
    requirement("flask"),
  ]
)
load("@rules_go//go:def.bzl", "go_binary")

go_binary(
    name = "go_web",
	srcs = ["main.go"],
    visibility = ["//visibility:public"],
	deps = [
        "//projects/go_hello_world",
        "@com_github_gorilla_mux//:mux",
    ],
)



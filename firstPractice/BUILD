load("@rules_uv//uv:pip.bzl", "pip_compile")
load("@gazelle//:def.bzl", "gazelle")


gazelle(name = "gazelle")


exports_files([
    "requirements.txt",
])

pip_compile(
    name = "generate_requirements_txt",
    requirements_in = "//:requirements.in",  # default
    requirements_txt = "//:requirements.txt",  # default
)




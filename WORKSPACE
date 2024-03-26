workspace(name = "google_jsonnet_go")

load(
    "@google_jsonnet_go//bazel:repositories.bzl",
    "jsonnet_go_repositories",
)

jsonnet_go_repositories()

load(
    "@google_jsonnet_go//bazel:deps.bzl",
    "jsonnet_go_dependencies",
)

jsonnet_go_dependencies(go_sdk_version="1.21.6")

#gazelle:repository_macro bazel/deps.bzl%jsonnet_go_dependencies

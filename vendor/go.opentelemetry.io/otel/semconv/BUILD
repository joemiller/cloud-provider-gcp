load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "semconv",
    srcs = [
        "doc.go",
        "exception.go",
        "http.go",
        "resource.go",
        "trace.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/go.opentelemetry.io/otel/semconv",
    importpath = "go.opentelemetry.io/otel/semconv",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/go.opentelemetry.io/otel/attribute",
        "//vendor/go.opentelemetry.io/otel/codes",
    ],
)

package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = [
        "clientset_generated.go",
        "doc.go",
    ],
    tags = ["automanaged"],
    deps = [
        "//federation/client/clientset_generated/federation_clientset:go_default_library",
        "//federation/client/clientset_generated/federation_clientset/typed/autoscaling/v1:go_default_library",
        "//federation/client/clientset_generated/federation_clientset/typed/autoscaling/v1/fake:go_default_library",
        "//federation/client/clientset_generated/federation_clientset/typed/batch/v1:go_default_library",
        "//federation/client/clientset_generated/federation_clientset/typed/batch/v1/fake:go_default_library",
        "//federation/client/clientset_generated/federation_clientset/typed/core/v1:go_default_library",
        "//federation/client/clientset_generated/federation_clientset/typed/core/v1/fake:go_default_library",
        "//federation/client/clientset_generated/federation_clientset/typed/extensions/v1beta1:go_default_library",
        "//federation/client/clientset_generated/federation_clientset/typed/extensions/v1beta1/fake:go_default_library",
        "//federation/client/clientset_generated/federation_clientset/typed/federation/v1beta1:go_default_library",
        "//federation/client/clientset_generated/federation_clientset/typed/federation/v1beta1/fake:go_default_library",
        "//pkg/api:go_default_library",
        "//vendor:k8s.io/apimachinery/pkg/runtime",
        "//vendor:k8s.io/apimachinery/pkg/watch",
        "//vendor:k8s.io/client-go/discovery",
        "//vendor:k8s.io/client-go/discovery/fake",
        "//vendor:k8s.io/client-go/testing",
    ],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [":package-srcs"],
    tags = ["automanaged"],
)

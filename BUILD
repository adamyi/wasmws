load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")
load("@bazel_gazelle//:def.bzl", "gazelle")

# gazelle:prefix github.com/productimon/wasmws
gazelle(
    name = "gazelle",
)

go_library(
    name = "go_default_library",
    srcs = [
        "arrayreader_js.go",
        "dial_js.go",
        "doc.go",
        "helpertypes_js.go",
        "sockettype_js.go",
        "streamreader_js.go",
        "websock_js.go",
        "wslistener.go",
    ],
    importpath = "github.com/productimon/wasmws",
    visibility = ["//visibility:public"],
    deps = select({
        "@io_bazel_rules_go//go/platform:aix_ppc64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:android_386": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:android_amd64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:android_arm": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:android_arm64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:darwin_386": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:darwin_amd64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:darwin_arm": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:darwin_arm64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:dragonfly_amd64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:freebsd_386": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:freebsd_amd64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:freebsd_arm": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:freebsd_arm64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:illumos_amd64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:ios_386": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:ios_amd64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:ios_arm": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:ios_arm64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:linux_386": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:linux_amd64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:linux_arm": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:linux_arm64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:linux_mips": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:linux_mips64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:linux_mips64le": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:linux_mipsle": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:linux_ppc64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:linux_ppc64le": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:linux_riscv64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:linux_s390x": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:nacl_386": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:nacl_amd64p32": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:nacl_arm": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:netbsd_386": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:netbsd_amd64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:netbsd_arm": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:netbsd_arm64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:openbsd_386": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:openbsd_amd64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:openbsd_arm": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:openbsd_arm64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:plan9_386": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:plan9_amd64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:plan9_arm": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:solaris_amd64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:windows_386": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:windows_amd64": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "@io_bazel_rules_go//go/platform:windows_arm": [
            "@io_nhooyr_websocket//:go_default_library",
        ],
        "//conditions:default": [],
    }),
)

go_test(
    name = "go_default_test",
    srcs = ["websock_js_test.go"],
    embed = [":go_default_library"],
)

# bgfx.bazel - bgfx building in bazel
# Author: Alex Rozgo <alex.rozgo@gmail.com>

load("@rules_cc//cc:defs.bzl", "cc_binary")

cc_binary(
    name = "texturec",
    srcs = glob([
        "*.h",
        "texturec.cpp*",
    ]),
    linkopts = [
        "-ldl",
    ],
    deps = [
        "//bgfx:common-linux",
    ],
)

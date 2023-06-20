load("@npm//:mocha/package_json.bzl", mocha_bin = "bin")

mocha_bin.mocha_test(
    name = "mocha",
    args = ["./test/test.js"],
    data = [":test.js"],
    patch_node_fs = False
)

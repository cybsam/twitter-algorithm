scala_library(
    sources = ["*.scala"],
    compiler_option_sets = ["fatal_warnings"],
    platform = "java8",
    strict_deps = True,
    tags = ["bazel-compatible"],
    dependencies = [
        "featureswitches/featureswitches-core/src/main/scala",
        "src/thrift/com/twitter/spam/rtf:safety-result-scala",
        "stitch/stitch-core",
        "visibility/common/src/main/scala/com/twitter/visibility/common",
        "visibility/common/src/main/scala/com/twitter/visibility/common/actions",
        "visibility/common/src/main/scala/com/twitter/visibility/common/actions/converter/scala",
        "visibility/lib/src/main/scala/com/twitter/visibility",
        "visibility/lib/src/main/scala/com/twitter/visibility/builder",
        "visibility/lib/src/main/scala/com/twitter/visibility/builder/tweets",
        "visibility/lib/src/main/scala/com/twitter/visibility/features",
        "visibility/lib/src/main/scala/com/twitter/visibility/rules",
        "visibility/results/src/main/scala/com/twitter/visibility/results/richtext",
    ],
    exports = [
        "featureswitches/featureswitches-core/src/main/scala",
        "visibility/lib/src/main/scala/com/twitter/visibility/builder",
    ],
)

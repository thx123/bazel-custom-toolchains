load("@bazel_skylib//rules:native_binary.bzl", "native_binary")

native_binary(
    name = "gdb",
    # Warning:: this would cause bazel build to fail as it comes from the "arm_none_eabi" repo.
    # Q: What's the right way to reuse platforms defined in the "arm_none_eabi" repo?
    src = "@arm_none_eabi//:gdb",
    out = "gdb",
    visibility = ["//visibility:public"],
)

native_binary(
    name = "readelf",
    # Warning:: this would cause bazel build to fail as it comes from the "arm_none_eabi" repo.
    # Q: What's the right way to reuse platforms defined in the "arm_none_eabi" repo?
    src = "@arm_none_eabi//:readelf",
    out = "readelf",
    visibility = ["//visibility:public"],
)

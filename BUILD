# BUILD file for use with https://github.com/dejwk/roo_testing.

cc_library(
    name = "roo_dallas_temperature",
    includes = [
        ".",
    ],
    srcs =
        glob(["*.cpp"]) + 
        glob(["*.h"]),
    visibility = ["//visibility:public"],
    defines = [
        "ROO_TESTING",
    ],
    deps = [
        "//roo_testing/buses/onewire",
        "//roo_testing/devices/onewire/thermometer",
        "//roo_testing/frameworks/arduino-esp32-2.0.4/cores/esp32",
    ],
)

load("@io_bazel_rules_kotlin//kotlin:kotlin.bzl", "kt_jvm_binary")

kt_jvm_binary (
    name = "BazelApp",
    srcs = glob(["kotlin/**/*.kt"]),
    main_class = "example.AppKt",
    deps = [
      "@maven//:org_springframework_boot_spring_boot_starter_activemq",
      "@maven//:org_apache_commons_commons_text",
      "@maven//:com_google_code_gson_gson",
    ],
)

# Copyright 2016 Google Inc. All Rights Reserved.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#    http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

load("@io_bazel_rules_dart//dart/build_rules:core.bzl", "dart_library")

dart_library(
    name = "yaml",
    srcs = glob(["lib/**"]),
    pub_pkg_name = "yaml",
    visibility = ["//visibility:public"],
    deps = [
        "@org_dartlang_pub_charcode//:charcode",
        "@org_dartlang_pub_collection//:collection",
        "@org_dartlang_pub_source_span//:source_span",
        "@org_dartlang_pub_string_scanner//:string_scanner",
    ],
)

# Copyright 2021 Google LLC
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     https://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

# Description:
# Build rules for the utitility component of CARLS.

# Placeholder for internal Python strict & test compatibility macro.

package(
    default_visibility = ["//research/carls:internal"],
    licenses = ["notice"],  # Apache 2.0
)

py_library(
    name = "array_ops",
    srcs = ["array_ops.py"],
    srcs_version = "PY3",
    deps = [
        # package tensorflow
    ],
)

py_test(
    name = "array_ops_test",
    srcs = ["array_ops_test.py"],
    python_version = "PY3",
    srcs_version = "PY3",
    deps = [
        ":array_ops",
        # package tensorflow
    ],
)

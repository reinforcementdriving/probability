# Copyright 2018 The TensorFlow Probability Authors.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
# ============================================================================
# Description:
#   TensorFlow Probability implements probabilistic and statistical
#   methods, including modeling and Bayesian inference. APIs here are
#   meant to evolve over time.

licenses(["notice"])  # Apache 2.0

package(
    default_visibility = [
        "//tensorflow_probability:__subpackages__",
    ],
)

exports_files(["LICENSE"])

py_library(
    name = "python",
    srcs = ["__init__.py"],
    srcs_version = "PY2AND3",
    visibility = ["//tensorflow_probability:__pkg__"],
    deps = [
        ":monte_carlo",
        ":trainable_distributions",
        ":version",
        "//tensorflow_probability/python/distributions",
        "//tensorflow_probability/python/edward2",
        "//tensorflow_probability/python/glm",
        "//tensorflow_probability/python/internal",
        "//tensorflow_probability/python/layers",
        "//tensorflow_probability/python/math",
        "//tensorflow_probability/python/mcmc",
        "//tensorflow_probability/python/optimizer",
        "//tensorflow_probability/python/positive_semidefinite_kernels",
        "//tensorflow_probability/python/sts",
        "//tensorflow_probability/python/util",
        "//tensorflow_probability/python/vi",
    ],
)

py_library(
    name = "version",
    srcs = ["version.py"],
    srcs_version = "PY2AND3",
)

py_library(
    name = "monte_carlo",
    srcs = ["monte_carlo.py"],
    srcs_version = "PY2AND3",
    deps = [
        # numpy dep,
        # tensorflow dep,
    ],
)

py_test(
    name = "monte_carlo_test",
    size = "small",
    srcs = ["monte_carlo_test.py"],
    deps = [
        # numpy dep,
        # tensorflow dep,
        "//tensorflow_probability",
    ],
)

py_library(
    name = "trainable_distributions",
    srcs = ["trainable_distributions.py"],
    srcs_version = "PY2AND3",
    deps = [
        # numpy dep,
        # tensorflow dep,
    ],
)

py_test(
    name = "trainable_distributions_test",
    size = "small",
    srcs = ["trainable_distributions_test.py"],
    deps = [
        # numpy dep,
        # tensorflow dep,
        "//tensorflow_probability",
    ],
)

<!--
#
# Licensed to the Apache Software Foundation (ASF) under one or more
# contributor license agreements.  See the NOTICE file distributed with
# this work for additional information regarding copyright ownership.
# The ASF licenses this file to You under the Apache License, Version 2.0
# (the "License"); you may not use this file except in compliance with
# the License.  You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#
-->

# Java 8 OpenWhisk Runtime Container

# 1.19.0
 - use `ibm-semeru-runtimes:open-8u382-b05-jdk-focal` as baseimage
 - update go proxy 1.21@1.23.0 (#157)

# 1.18.0
  - Use `ibm-semeru-runtimes:open-8u362-b09-jdk-focal` as baseimage (#151)
  - Support array result include sequence action (#140)
  - update gson version to 2.9.0 (#139)
  - update Proxy to 1.20 and release 1.22.0

## 1.17.0
  - Build actionloop from 1.16@1.18.0 (#125)
  - Resolve akka versions explicitly. (#124, #123)

## 1.16.0
  - Use adoptopenjdk/openjdk8-openj9:x86_64-ubuntu-jdk8u282-b08_openj9-0.24.0
  - Use 1.17.0 release of openwhisk-runtime-go (#117)

## 1.15.0
  - Include latest security fixes with every build.
  - Use adoptopenjdk/openjdk8-openj9:x86_64-ubuntu-jdk8u262-b10_openj9-0.21.0
  - Build proxy using go 1.15 and openwhisk-runtime-go 1.16.0

## 1.14.0
  - Initial release of actionloop-based Java Action
  - Use adoptopenjdk/openjdk8-openj9:x86_64-ubuntu-jdk8u222-b10_openj9-0.15.1

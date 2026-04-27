<!--
Copyright (c) 2024-2026 The Johns Hopkins University Applied Physics
Laboratory LLC.

This file is part of the Delay-Tolerant Networking Management
Architecture (DTNMA) documentation project.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at
    http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->
This organization hosts repositories, issue tracking, and planning related to reference implementations of the DTN Management Architecture (DTNMA) in various languages for various runtime environments.

Formal specifications are managed by the IETF and its [Datatracker tool](https://datatracker.ietf.org/doc/search?name=dtnma).
Additional explanations are provided by the [DTNMA Documentation](https://jhuapl-dtnma.github.io/.github/) project, including an introductory explanation with examples.

The repositories in this organization include:

- A C11 [reference implementation](https://github.com/JHUAPL-DTNMA/dtnma-tools) of [ARI processing (CACE)](https://jhuapl-dtnma.github.io/dtnma-tools/html/cace.html) with a command-line tool [`cace_ari`](https://jhuapl-dtnma.github.io/dtnma-tools/html/cace_ari.html), a [reference agent (REFDA)](https://jhuapl-dtnma.github.io/dtnma-tools/html/refda.html), and a [reference manager (REFDM)](https://jhuapl-dtnma.github.io/dtnma-tools/html/refdm.html) all available for use as staic or shared libraries. These include example daemons for specific test transport bindings (for example, local Unix domain sockets).
- The [AMM Codec Engine (ACE)](https://github.com/JHUAPL-DTNMA/dtnma-ace) with [Python API](https://jhuapl-dtnma.github.io/dtnma-ace/) and command-line tools `ace_adm` and [`ace_ari`](https://jhuapl-dtnma.github.io/dtnma-ace/ace_ari.html).
- A template-based code generator [CAMP](https://github.com/JHUAPL-DTNMA/dtnma-camp) which generates C11 source for the REFDA and SQL DDL source for the REFDM.

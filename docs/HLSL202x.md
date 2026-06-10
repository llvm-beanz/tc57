---
title: HLSL 202x
---

HLSL 202x is the working name for the first Ecma standard draft for HLSL.

The primary goal of HLSL 202x is to define a regular and consistent set of
behaviors and semantics to enable implementations to align on a common language
definition.

Following our [Design
Considerations](DesignConsiderations.md#viability-of-implementation-matters),
the feasibility of implementation matters deeply when assessing HLSL 202x
specification language.

HLSL 202x will provide a high level of source compatibility with existing
implementations but may seek to deviate to avoid obvious defects or
implementation complexity. When deviating from existing implementations HLSL
202x will prefer alignment with C and C++ to leverage familiarity with users.

In cases where there is a tension between matching DXC's current behaviors and
implementation complexity in Clang, TC57 adopts a pragmatic bias toward the
Clang-based HLSL implementation being the preferred conforming implementation
since it will have more long-term investment.

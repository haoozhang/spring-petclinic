# Security Assessment Report

**Generated:** 2026-06-22T06:59:33.0000000Z

## Summary

| Metric | Count |
|--------|-------|
| Total Findings | 57 |
| CVE Vulnerabilities | 53 |
| CWE Vulnerabilities | 4 |
| Total Rules Assessed | 59 |
| Rules Passed | 55 |

### By Severity

| Severity | Count |
|----------|-------|
| mandatory | 53 |
| optional | 2 |
| potential | 2 |

## CVE Findings (Dependency Vulnerabilities)

### CVE-2023-20873: Spring Boot Security Bypass with Wildcard Pattern Matching on Cloud Foundry
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-20873](https://github.com/advisories/GHSA-g5h3-w546-pj7f): Spring Boot Security Bypass with Wildcard Pattern Matching on Cloud Foundry

Severity: CRITICAL

Affected dependencies:
  - org.springframework.boot:spring-boot-actuator-autoconfigure (range: >= 3.0.0, < 3.0.6) → upgrade to 3.0.6
  - org.springframework.boot:spring-boot-actuator-autoconfigure (range: >= 2.7.0, < 2.7.11) → upgrade to 2.7.11
  - org.springframework.boot:spring-boot-actuator-autoconfigure (range: >= 2.6.0, < 2.6.15) → upgrade to 2.6.15
  - org.springframework.boot:spring-boot-actuator-autoconfigure (range: < 2.5.15) → upgrade to 2.5.15

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-43512: Apache Tomcat - Digest authenticator will authenticate any unknown user
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-43512](https://github.com/advisories/GHSA-h6fc-48rj-7qqh): Apache Tomcat - Digest authenticator will authenticate any unknown user

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22
  - org.apache.tomcat:tomcat (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat:tomcat (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat:tomcat (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22
  - org.apache.tomcat:tomcat-catalina (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat:tomcat-catalina (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-43515: Apache Tomcat - Security constraints not correctly applied
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-43515](https://github.com/advisories/GHSA-5m62-pw8w-7w9f): Apache Tomcat - Security constraints not correctly applied

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22
  - org.apache.tomcat:tomcat (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat:tomcat (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat:tomcat (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22
  - org.apache.tomcat:tomcat-catalina (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat:tomcat-catalina (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-41293: Apache Tomcat - HTTP/2 request headers not validated
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-41293](https://github.com/advisories/GHSA-r29c-68gh-xp6x): Apache Tomcat - HTTP/2 request headers not validated

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22
  - org.apache.tomcat:tomcat (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat:tomcat (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat:tomcat (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22
  - org.apache.tomcat:tomcat-catalina (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat:tomcat-catalina (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-41901: Sandboxed Thymeleaf expressions vulnerable to improper recognition of unauthorized syntax patterns
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml, pom.xml:56

[CVE-2026-41901](https://github.com/advisories/GHSA-c9ph-gxww-7744): Sandboxed Thymeleaf expressions vulnerable to improper recognition of unauthorized syntax patterns

Severity: CRITICAL

Affected dependencies:
  - org.thymeleaf:thymeleaf (range: <= 3.1.4.RELEASE) → upgrade to 3.1.5.RELEASE
  - org.thymeleaf:thymeleaf-spring5 (range: <= 3.1.4.RELEASE) → upgrade to 3.1.5.RELEASE
  - org.thymeleaf:thymeleaf-spring6 (range: <= 3.1.4.RELEASE) → upgrade to 3.1.5.RELEASE

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-40478: Improper neutralization of specific syntax patterns for unauthorized expressions in Thymeleaf
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml, pom.xml:56

[CVE-2026-40478](https://github.com/advisories/GHSA-xjw8-8c5c-9r79): Improper neutralization of specific syntax patterns for unauthorized expressions in Thymeleaf

Severity: CRITICAL

Affected dependencies:
  - org.thymeleaf:thymeleaf (range: <= 3.1.3.RELEASE) → upgrade to 3.1.4.RELEASE
  - org.thymeleaf:thymeleaf-spring5 (range: <= 3.1.3.RELEASE) → upgrade to 3.1.4.RELEASE
  - org.thymeleaf:thymeleaf-spring6 (range: <= 3.1.3.RELEASE) → upgrade to 3.1.4.RELEASE

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-40477: Improper restriction of the scope of accessible objects in Thymeleaf expressions
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml, pom.xml:56

[CVE-2026-40477](https://github.com/advisories/GHSA-r4v4-5mwr-2fwr): Improper restriction of the scope of accessible objects in Thymeleaf expressions

Severity: CRITICAL

Affected dependencies:
  - org.thymeleaf:thymeleaf (range: <= 3.1.3.RELEASE) → upgrade to 3.1.4.RELEASE
  - org.thymeleaf:thymeleaf-spring5 (range: <= 3.1.3.RELEASE) → upgrade to 3.1.4.RELEASE
  - org.thymeleaf:thymeleaf-spring6 (range: <= 3.1.3.RELEASE) → upgrade to 3.1.4.RELEASE

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2025-24813: Apache Tomcat: Potential RCE and/or information disclosure and/or information corruption with partial PUT
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-24813](https://github.com/advisories/GHSA-83qj-6fr2-vhqg): Apache Tomcat: Potential RCE and/or information disclosure and/or information corruption with partial PUT

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat:tomcat-catalina (range: >= 11.0.0-M1, < 11.0.3) → upgrade to 11.0.3
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0-M1, < 10.1.35) → upgrade to 10.1.35
  - org.apache.tomcat:tomcat-catalina (range: >= 9.0.0.M1, < 9.0.99) → upgrade to 9.0.99
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.3) → upgrade to 11.0.3
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.35) → upgrade to 10.1.35
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 9.0.0.M1, < 9.0.99) → upgrade to 9.0.99
  - org.apache.tomcat:tomcat-catalina (range: >= 8.5.0, <= 8.5.100)
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 8.5.0, <= 8.5.100)

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2023-20860: Spring Framework is vulnerable to security bypass via mvcRequestMatcher pattern mismatch
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml, pom.xml:4

[CVE-2023-20860](https://github.com/advisories/GHSA-7phw-cxx7-q9vq): Spring Framework is vulnerable to security bypass via mvcRequestMatcher pattern mismatch

Severity: CRITICAL

Affected dependencies:
  - org.springframework:spring (range: >= 6.0.0, < 6.0.7) → upgrade to 6.0.7
  - org.springframework:spring (range: >= 5.3.0, < 5.3.26) → upgrade to 5.3.26
  - org.springframework:spring-webmvc (range: >= 6.0.0, < 6.0.7) → upgrade to 6.0.7
  - org.springframework:spring-webmvc (range: >= 5.3.0, < 5.3.26) → upgrade to 5.3.26

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2016-1000027: Pivotal Spring Framework contains unsafe Java deserialization methods
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2016-1000027](https://github.com/advisories/GHSA-4wrc-f8pq-fpqp): Pivotal Spring Framework contains unsafe Java deserialization methods

Severity: CRITICAL

Affected dependencies:
  - org.springframework:spring-web (range: < 6.0.0) → upgrade to 6.0.0

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2024-1597: org.postgresql:postgresql vulnerable to SQL Injection via line comment generation
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:76

[CVE-2024-1597](https://github.com/advisories/GHSA-24rp-q3w6-vc56): org.postgresql:postgresql vulnerable to SQL Injection via line comment generation

Severity: CRITICAL

Affected dependencies:
  - org.postgresql:postgresql (range: < 42.2.28) → upgrade to 42.2.28
  - org.postgresql:postgresql (range: >= 42.3.0, < 42.3.9) → upgrade to 42.3.9
  - org.postgresql:postgresql (range: >= 42.4.0, < 42.4.4) → upgrade to 42.4.4
  - org.postgresql:postgresql (range: >= 42.5.0, < 42.5.5) → upgrade to 42.5.5
  - org.postgresql:postgresql (range: >= 42.6.0, < 42.6.1) → upgrade to 42.6.1
  - org.postgresql:postgresql (range: >= 42.7.0, < 42.7.2) → upgrade to 42.7.2

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-22733: Spring Boot has an Authentication Bypass under Actuator CloudFoundry endpoints
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:36

[CVE-2026-22733](https://github.com/advisories/GHSA-mgvc-8q2h-5pgc): Spring Boot has an Authentication Bypass under Actuator CloudFoundry endpoints

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot-starter-actuator (range: >= 4.0.0-M1, < 4.0.4) → upgrade to 4.0.4
  - org.springframework.boot:spring-boot-starter-actuator (range: >= 3.5.0, < 3.5.12) → upgrade to 3.5.12
  - org.springframework.boot:spring-boot-starter-actuator (range: >= 3.4.0, <= 3.4.13)
  - org.springframework.boot:spring-boot-starter-actuator (range: >= 3.0.0, <= 3.3.13)
  - org.springframework.boot:spring-boot-starter-actuator (range: <= 2.7.18)

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2023-6378: logback serialization vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-6378](https://github.com/advisories/GHSA-vmq6-5m68-f53m): logback serialization vulnerability

Severity: HIGH

Affected dependencies:
  - ch.qos.logback:logback-classic (range: >= 1.4.0, < 1.4.12) → upgrade to 1.4.12
  - ch.qos.logback:logback-core (range: >= 1.4.0, < 1.4.12) → upgrade to 1.4.12
  - ch.qos.logback:logback-classic (range: >= 1.3.0, < 1.3.12) → upgrade to 1.3.12
  - ch.qos.logback:logback-core (range: >= 1.3.0, < 1.3.12) → upgrade to 1.3.12
  - ch.qos.logback:logback-core (range: < 1.2.13) → upgrade to 1.2.13
  - ch.qos.logback:logback-classic (range: < 1.2.13) → upgrade to 1.2.13

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2022-1471: SnakeYaml Constructor Deserialization Remote Code Execution
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-1471](https://github.com/advisories/GHSA-mjmj-j48q-9wg2): SnakeYaml Constructor Deserialization Remote Code Execution

Severity: HIGH

Affected dependencies:
  - org.yaml:snakeyaml (range: <= 1.33) → upgrade to 2.0

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2022-42003: Uncontrolled Resource Consumption in Jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-42003](https://github.com/advisories/GHSA-jjjh-jjxp-wpff): Uncontrolled Resource Consumption in Jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind (range: >= 2.4.0-rc1, < 2.12.7.1) → upgrade to 2.12.7.1
  - com.fasterxml.jackson.core:jackson-databind (range: >= 2.13.0, < 2.13.4.2) → upgrade to 2.13.4.2

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2022-42004: Uncontrolled Resource Consumption in FasterXML jackson-databind
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-42004](https://github.com/advisories/GHSA-rgv9-q543-rqg4): Uncontrolled Resource Consumption in FasterXML jackson-databind

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind (range: >= 2.13.0, < 2.13.4) → upgrade to 2.13.4
  - com.fasterxml.jackson.core:jackson-databind (range: >= 2.4.0-rc1, < 2.12.7.1) → upgrade to 2.12.7.1

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2022-25857: Uncontrolled Resource Consumption in snakeyaml
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-25857](https://github.com/advisories/GHSA-3mc7-4q67-w48m): Uncontrolled Resource Consumption in snakeyaml

Severity: HIGH

Affected dependencies:
  - org.yaml:snakeyaml (range: < 1.31) → upgrade to 1.31

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-41284: Apache Tomcat: Unbounded read in WebDAV LOCK and  PROPFIND handling
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-41284](https://github.com/advisories/GHSA-gx5v-xp9w-j4cg): Apache Tomcat: Unbounded read in WebDAV LOCK and  PROPFIND handling

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22
  - org.apache.tomcat:tomcat (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat:tomcat (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat:tomcat (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22
  - org.apache.tomcat:tomcat-catalina (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat:tomcat-catalina (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-43513: Apache Tomcat: LockOutRealm treats user names as case-sensitive
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-43513](https://github.com/advisories/GHSA-5mp6-jrq3-r938): Apache Tomcat: LockOutRealm treats user names as case-sensitive

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22
  - org.apache.tomcat:tomcat (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat:tomcat (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat:tomcat (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22
  - org.apache.tomcat:tomcat-catalina (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat:tomcat-catalina (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-42498: Apache Tomcat - WebSocket authentication header exposure
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-42498](https://github.com/advisories/GHSA-fv25-8xcx-gqjc): Apache Tomcat - WebSocket authentication header exposure

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22
  - org.apache.tomcat:tomcat (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat:tomcat (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat:tomcat (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22
  - org.apache.tomcat:tomcat-catalina (range: < 9.0.118) → upgrade to 9.0.118
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0-M1, < 10.1.55) → upgrade to 10.1.55
  - org.apache.tomcat:tomcat-catalina (range: >= 11.0.0-M1, < 11.0.22) → upgrade to 11.0.22

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-34483: Apache Tomcat has an Improper Encoding or Escaping of Output vulnerability in the JsonAccessLogValve
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-34483](https://github.com/advisories/GHSA-rv64-5gf8-9qq8): Apache Tomcat has an Improper Encoding or Escaping of Output vulnerability in the JsonAccessLogValve

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-catalina (range: >= 9.0.40, < 9.0.116) → upgrade to 9.0.116
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0-M1, < 10.1.54) → upgrade to 10.1.54
  - org.apache.tomcat:tomcat-catalina (range: >= 11.0.0-M1, < 11.0.21) → upgrade to 11.0.21
  - org.apache.tomcat:tomcat (range: >= 9.0.40, < 9.0.116) → upgrade to 9.0.116
  - org.apache.tomcat:tomcat (range: >= 10.1.0-M1, < 10.1.54) → upgrade to 10.1.54
  - org.apache.tomcat:tomcat (range: >= 11.0.0-M1, < 11.0.21) → upgrade to 11.0.21
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 9.0.40, < 9.0.116) → upgrade to 9.0.116
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.54) → upgrade to 10.1.54
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.21) → upgrade to 11.0.21

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-24880: Apache Tomcat has an HTTP Request/Response Smuggling vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-24880](https://github.com/advisories/GHSA-563x-q5rq-57qp): Apache Tomcat has an HTTP Request/Response Smuggling vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-coyote (range: >= 7.0.0, < 9.0.116) → upgrade to 9.0.116
  - org.apache.tomcat:tomcat-coyote (range: >= 10.1.0-M1, < 10.1.52) → upgrade to 10.1.52
  - org.apache.tomcat:tomcat-coyote (range: >= 11.0.0-M1, <= 11.0.18) → upgrade to 11.0.20
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 7.0.0, < 9.0.116) → upgrade to 9.0.116
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.52) → upgrade to 10.1.52
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, <= 11.0.18) → upgrade to 11.0.20

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-0603: Hibernate vulnerable to SQL Injection
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-0603](https://github.com/advisories/GHSA-2p5w-cvg5-gc5c): Hibernate vulnerable to SQL Injection

Severity: HIGH

Affected dependencies:
  - org.hibernate:hibernate-core (range: >= 5.2.8, <= 5.6.15)

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2025-55752: Apache Tomcat Vulnerable to Relative Path Traversal
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-55752](https://github.com/advisories/GHSA-wmwf-9ccg-fff5): Apache Tomcat Vulnerable to Relative Path Traversal

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat (range: >= 11.0.0-M1, < 11.0.11) → upgrade to 11.0.11
  - org.apache.tomcat:tomcat (range: >= 10.1.0-M1, < 10.1.45) → upgrade to 10.1.45
  - org.apache.tomcat:tomcat-catalina (range: >= 11.0.0-M1, < 11.0.11) → upgrade to 11.0.11
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0-M1, < 10.1.45) → upgrade to 10.1.45
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.11) → upgrade to 11.0.11
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.45) → upgrade to 10.1.45
  - org.apache.tomcat:tomcat (range: >= 9.0.0-M11, < 9.0.109) → upgrade to 9.0.109
  - org.apache.tomcat:tomcat-catalina (range: >= 9.0.0-M11, < 9.0.109) → upgrade to 9.0.109
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 9.0.0-M11, < 9.0.109) → upgrade to 9.0.109
  - org.apache.tomcat:tomcat (range: >= 8.5.6, <= 8.5.100)
  - org.apache.tomcat:tomcat-catalina (range: >= 8.5.6, <= 8.5.100)
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 8.5.6, <= 8.5.100)

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2025-48989: Apache Tomcat Improper Resource Shutdown or Release vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-48989](https://github.com/advisories/GHSA-gqp3-2cvr-x8m3): Apache Tomcat Improper Resource Shutdown or Release vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-coyote (range: >= 11.0.0-M1, < 11.0.10) → upgrade to 11.0.10
  - org.apache.tomcat:tomcat-coyote (range: >= 10.1.0-M1, < 10.1.44) → upgrade to 10.1.44
  - org.apache.tomcat:tomcat-coyote (range: >= 9.0.0.M1, < 9.0.108) → upgrade to 9.0.108
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.10) → upgrade to 11.0.10
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.44) → upgrade to 10.1.44
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 9.0.0.M1, < 9.0.108) → upgrade to 9.0.108

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2025-53506: Apache Tomcat Coyote vulnerable to Denial of Service via excessive HTTP/2 streams
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-53506](https://github.com/advisories/GHSA-25xr-qj8w-c4vf): Apache Tomcat Coyote vulnerable to Denial of Service via excessive HTTP/2 streams

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-coyote (range: >= 11.0.0-M1, < 11.0.9) → upgrade to 11.0.9
  - org.apache.tomcat:tomcat-coyote (range: >= 10.1.0-M1, < 10.1.43) → upgrade to 10.1.43
  - org.apache.tomcat:tomcat-coyote (range: >= 9.0.0.M1, < 9.0.107) → upgrade to 9.0.107
  - org.apache.tomcat:tomcat-coyote (range: >= 8.5.0, <= 8.5.100)
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 8.5.0, <= 8.5.100)
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 9.0.0.M1, < 9.0.107) → upgrade to 9.0.107
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.43) → upgrade to 10.1.43
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.9) → upgrade to 11.0.9

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2025-52520: Apache Tomcat Catalina is vulnerable to DoS attack through bypassing of size limits
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-52520](https://github.com/advisories/GHSA-wr62-c79q-cv37): Apache Tomcat Catalina is vulnerable to DoS attack through bypassing of size limits

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-catalina (range: >= 11.0.0-M1, < 11.0.9) → upgrade to 11.0.9
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0-M1, < 10.1.43) → upgrade to 10.1.43
  - org.apache.tomcat:tomcat-catalina (range: >= 9.0.0.M1, < 9.0.107) → upgrade to 9.0.107
  - org.apache.tomcat:tomcat-catalina (range: >= 8.5.0, <= 8.5.100)
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.9) → upgrade to 11.0.9
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.43) → upgrade to 10.1.43
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 9.0.0.M1, < 9.0.107) → upgrade to 9.0.107
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 8.5.0, <= 8.5.100)

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2025-48988: Apache Tomcat - DoS in multipart upload
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-48988](https://github.com/advisories/GHSA-h3gc-qfqq-6h8f): Apache Tomcat - DoS in multipart upload

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-catalina (range: >= 11.0.0-M1, <= 11.0.7) → upgrade to 11.0.8
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0-M1, <= 10.1.41) → upgrade to 10.1.42
  - org.apache.tomcat:tomcat-catalina (range: >= 9.0.0.M1, <= 9.0.105) → upgrade to 9.0.106
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, <= 11.0.7) → upgrade to 11.0.8
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, <= 10.1.41) → upgrade to 10.1.42
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 9.0.0.M1, <= 9.0.105) → upgrade to 9.0.106
  - org.apache.tomcat:tomcat-catalina (range: >= 8.5.0, <= 8.5.100)
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 8.5.0, <= 8.5.100)

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2024-56337: Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-56337](https://github.com/advisories/GHSA-27hp-xhwr-wr2m): Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-catalina (range: >= 11.0.0-M1, < 11.0.2) → upgrade to 11.0.2
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0-M1, < 10.1.34) → upgrade to 10.1.34
  - org.apache.tomcat:tomcat-embed-core (range: >= 9.0.0.M1, < 9.0.98) → upgrade to 9.0.98
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.2) → upgrade to 11.0.2
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.34) → upgrade to 10.1.34
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 9.0.0.M1, < 9.0.98) → upgrade to 9.0.98

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2024-38819: Spring Framework Path Traversal vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-38819](https://github.com/advisories/GHSA-g5vr-rgqm-vf78): Spring Framework Path Traversal vulnerability

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-webflux (range: >= 6.1.0, < 6.1.14) → upgrade to 6.1.14
  - org.springframework:spring-webmvc (range: >= 6.1.0, < 6.1.14) → upgrade to 6.1.14
  - org.springframework:spring-webflux (range: <= 5.3.39)
  - org.springframework:spring-webmvc (range: <= 5.3.39)
  - org.springframework:spring-webflux (range: >= 6.0.0, <= 6.0.23)
  - org.springframework:spring-webmvc (range: >= 6.0.0, <= 6.0.23)

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2024-50379: Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-50379](https://github.com/advisories/GHSA-5j33-cvvr-w245): Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-catalina (range: >= 11.0.0-M1, < 11.0.2) → upgrade to 11.0.2
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0-M1, < 10.1.34) → upgrade to 10.1.34
  - org.apache.tomcat:tomcat-catalina (range: >= 9.0.0.M1, < 9.0.98) → upgrade to 9.0.98
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.2) → upgrade to 11.0.2
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.34) → upgrade to 10.1.34
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 9.0.0.M1, < 9.0.98) → upgrade to 9.0.98
  - org.apache.tomcat:tomcat-catalina (range: >= 8.5.0, <= 8.5.100)
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 8.5.0, <= 8.5.100)

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2024-38816: Path traversal vulnerability in functional web frameworks
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-38816](https://github.com/advisories/GHSA-cx7f-g6mp-7hqm): Path traversal vulnerability in functional web frameworks

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-webmvc (range: >= 6.1.0, < 6.1.13) → upgrade to 6.1.13
  - org.springframework:spring-webflux (range: >= 6.1.0, < 6.1.13) → upgrade to 6.1.13
  - org.springframework:spring-webmvc (range: >= 6.0.0, <= 6.0.23)
  - org.springframework:spring-webflux (range: >= 6.0.0, <= 6.0.23)
  - org.springframework:spring-webmvc (range: >= 5.3.0, <= 5.3.39)
  - org.springframework:spring-webflux (range: >= 5.3.0, <= 5.3.39)

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2024-34750: Apache Tomcat - Denial of Service
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-34750](https://github.com/advisories/GHSA-wm9w-rjj3-j356): Apache Tomcat - Denial of Service

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.0-M21) → upgrade to 11.0.0-M21
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.25) → upgrade to 10.1.25
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 9.0.0-M1, < 9.0.90) → upgrade to 9.0.90
  - org.apache.tomcat:tomcat-coyote (range: >= 11.0.0-M1, < 11.0.0-M21) → upgrade to 11.0.0-M21
  - org.apache.tomcat:tomcat-coyote (range: >= 10.1.0-M1, < 10.1.25) → upgrade to 10.1.25
  - org.apache.tomcat:tomcat-coyote (range: >= 9.0.0-M1, < 9.0.90) → upgrade to 9.0.90
  - org.apache.tomcat:tomcat-coyote (range: >= 8.5.0, <= 8.5.100)
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 8.5.0, <= 8.5.100)

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2024-22262: Spring Framework URL Parsing with Host Validation
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-22262](https://github.com/advisories/GHSA-2wrp-6fg6-hmc5): Spring Framework URL Parsing with Host Validation

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web (range: < 5.3.34) → upgrade to 5.3.34
  - org.springframework:spring-web (range: >= 6.0.0, < 6.0.19) → upgrade to 6.0.19
  - org.springframework:spring-web (range: >= 6.1.0, < 6.1.6) → upgrade to 6.1.6

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2024-22259: Spring Framework URL Parsing with Host Validation Vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-22259](https://github.com/advisories/GHSA-hgjh-9rj2-g67j): Spring Framework URL Parsing with Host Validation Vulnerability

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web (range: >= 6.1.0, < 6.1.5) → upgrade to 6.1.5
  - org.springframework:spring-web (range: >= 6.0.0, < 6.0.18) → upgrade to 6.0.18
  - org.springframework:spring-web (range: < 5.3.33) → upgrade to 5.3.33

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2024-22243: Spring Web vulnerable to Open Redirect or Server Side Request Forgery
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-22243](https://github.com/advisories/GHSA-ccgv-vj62-xf9h): Spring Web vulnerable to Open Redirect or Server Side Request Forgery

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web (range: >= 6.1.0, < 6.1.4) → upgrade to 6.1.4
  - org.springframework:spring-web (range: >= 6.0.0, < 6.0.17) → upgrade to 6.0.17
  - org.springframework:spring-web (range: >= 5.3.0, < 5.3.32) → upgrade to 5.3.32
  - org.springframework:spring-web (range: <= 5.2.25.RELEASE)

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2023-46589: Apache Tomcat Improper Input Validation vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-46589](https://github.com/advisories/GHSA-fccv-jmmp-qg76): Apache Tomcat Improper Input Validation vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat:tomcat-catalina (range: >= 11.0.0-M1, < 11.0.0-M11) → upgrade to 11.0.0-M11
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0-M1, < 10.1.16) → upgrade to 10.1.16
  - org.apache.tomcat:tomcat-catalina (range: >= 9.0.0-M1, < 9.0.83) → upgrade to 9.0.83
  - org.apache.tomcat:tomcat-catalina (range: >= 8.5.0, < 8.5.96) → upgrade to 8.5.96
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M1, < 11.0.0-M11) → upgrade to 11.0.0-M11
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.16) → upgrade to 10.1.16
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 9.0.0-M1, < 9.0.83) → upgrade to 9.0.83
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 8.5.0, < 8.5.96) → upgrade to 8.5.96

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2023-20863: Spring Framework vulnerable to denial of service
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-20863](https://github.com/advisories/GHSA-wxqc-pxw9-g2p8): Spring Framework vulnerable to denial of service

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-expression (range: >= 6.0.0, < 6.0.8) → upgrade to 6.0.8
  - org.springframework:spring-expression (range: >= 5.3.0, < 5.3.27) → upgrade to 5.3.27
  - org.springframework:spring-expression (range: < 5.2.24.RELEASE) → upgrade to 5.2.24.RELEASE

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2023-24998: Apache Commons FileUpload denial of service vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-24998](https://github.com/advisories/GHSA-hfrx-6qgj-fp6c): Apache Commons FileUpload denial of service vulnerability

Severity: HIGH

Affected dependencies:
  - commons-fileupload:commons-fileupload (range: < 1.5) → upgrade to 1.5
  - org.apache.tomcat:tomcat-coyote (range: >= 10.1.0-M1, < 10.1.5) → upgrade to 10.1.5
  - org.apache.tomcat:tomcat-coyote (range: >= 11.0.0-M2, < 11.0.0-M5) → upgrade to 11.0.0-M5
  - org.apache.tomcat:tomcat-coyote (range: >= 8.5.85, < 8.5.88) → upgrade to 8.5.88
  - org.apache.tomcat:tomcat-coyote (range: >= 9.0.0-M1, < 9.0.71) → upgrade to 9.0.71
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.5) → upgrade to 10.1.5
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 11.0.0-M2, < 11.0.0-M5) → upgrade to 11.0.0-M5
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 8.5.85, < 8.5.88) → upgrade to 8.5.88
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 9.0.0-M1, < 9.0.71) → upgrade to 9.0.71
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0-M1, < 10.1.5) → upgrade to 10.1.5
  - org.apache.tomcat:tomcat-catalina (range: >= 11.0.0-M2, < 11.0.0-M5) → upgrade to 11.0.0-M5
  - org.apache.tomcat:tomcat-catalina (range: >= 8.5.85, < 8.5.88) → upgrade to 8.5.88
  - org.apache.tomcat:tomcat-catalina (range: >= 9.0.0-M1, < 9.0.71) → upgrade to 9.0.71

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2022-45143: Apache Tomcat improperly escapes input from JsonErrorReportValve
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-45143](https://github.com/advisories/GHSA-rq2w-37h9-vg94): Apache Tomcat improperly escapes input from JsonErrorReportValve

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (range: = 8.5.83) → upgrade to 8.5.84
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 9.0.40, <= 9.0.68) → upgrade to 9.0.69
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0, <= 10.1.1) → upgrade to 10.1.2
  - org.apache.tomcat:tomcat-catalina (range: >= 10.1.0, <= 10.1.1) → upgrade to 10.1.2
  - org.apache.tomcat:tomcat-util (range: = 8.5.83) → upgrade to 8.5.84
  - org.apache.tomcat:tomcat-util (range: >= 9.0.40, < 9.0.69) → upgrade to 9.0.69

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2022-42252: Apache Tomcat may reject request containing invalid Content-Length header
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-42252](https://github.com/advisories/GHSA-p22x-g9px-3945): Apache Tomcat may reject request containing invalid Content-Length header

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 8.5.0, < 8.5.83) → upgrade to 8.5.83
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 9.0.0-M1, < 9.0.68) → upgrade to 9.0.68
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.0.0-M1, < 10.0.27) → upgrade to 10.0.27
  - org.apache.tomcat.embed:tomcat-embed-core (range: >= 10.1.0-M1, < 10.1.1) → upgrade to 10.1.1
  - org.apache.tomcat:tomcat-coyote (range: >= 9.0.0-M1, < 9.0.68) → upgrade to 9.0.68
  - org.apache.tomcat:tomcat-coyote (range: >= 10.0.0-M1, < 10.0.27) → upgrade to 10.0.27
  - org.apache.tomcat:tomcat-coyote (range: >= 10.1.0-M1, < 10.1.1) → upgrade to 10.1.1

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-24400: AssertJ has XML External Entity (XXE) vulnerability when parsing untrusted XML via isXmlEqualTo assertion
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-24400](https://github.com/advisories/GHSA-rqfh-9r24-8c9r): AssertJ has XML External Entity (XXE) vulnerability when parsing untrusted XML via isXmlEqualTo assertion

Severity: HIGH

Affected dependencies:
  - org.assertj:assertj-core (range: >= 1.4.0, <= 3.27.6) → upgrade to 3.27.7

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2025-41249: Spring Framework annotation detection mechanism may result in improper authorization
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-41249](https://github.com/advisories/GHSA-jmp9-x22r-554x): Spring Framework annotation detection mechanism may result in improper authorization

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-core (range: >= 5.3.0, <= 5.3.44)
  - org.springframework:spring-core (range: >= 6.0.0, <= 6.1.22)
  - org.springframework:spring-core (range: >= 6.2.0, <= 6.2.10) → upgrade to 6.2.11

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2023-1370: json-smart Uncontrolled Recursion vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-1370](https://github.com/advisories/GHSA-493p-pfq6-5258): json-smart Uncontrolled Recursion vulnerability

Severity: HIGH

Affected dependencies:
  - net.minidev:json-smart (range: < 2.4.9) → upgrade to 2.4.9

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-42198: pgjdbc: Unbounded PBKDF2 iterations in SCRAM authentication allows CPU exhaustion DoS
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:76

[CVE-2026-42198](https://github.com/advisories/GHSA-98qh-xjc8-98pq): pgjdbc: Unbounded PBKDF2 iterations in SCRAM authentication allows CPU exhaustion DoS

Severity: HIGH

Affected dependencies:
  - org.postgresql:postgresql (range: >= 42.2.0, < 42.7.11) → upgrade to 42.7.11

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-40973: Spring Boot accepts predictable temp directory without ownership verification
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:10

[CVE-2026-40973](https://github.com/advisories/GHSA-wwpq-f5c3-7hvx): Spring Boot accepts predictable temp directory without ownership verification

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot (range: >= 4.0.0, < 4.0.6) → upgrade to 4.0.6
  - org.springframework.boot:spring-boot (range: >= 3.5.0, < 3.5.14) → upgrade to 3.5.14
  - org.springframework.boot:spring-boot (range: >= 3.4.0, <= 3.4.15)
  - org.springframework.boot:spring-boot (range: >= 3.3.0, <= 3.3.18)
  - org.springframework.boot:spring-boot (range: <= 2.7.32)

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2026-40972: Spring Boot DevTools remote secret comparison is vulnerable to timing attacks
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:110

[CVE-2026-40972](https://github.com/advisories/GHSA-56v8-86gj-66jp): Spring Boot DevTools remote secret comparison is vulnerable to timing attacks

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot-devtools (range: >= 4.0.0, < 4.0.6) → upgrade to 4.0.6
  - org.springframework.boot:spring-boot-devtools (range: >= 3.5.0, < 3.5.14) → upgrade to 3.5.14
  - org.springframework.boot:spring-boot-devtools (range: >= 3.4.0, <= 3.4.15)
  - org.springframework.boot:spring-boot-devtools (range: >= 3.3.0, <= 3.3.18)
  - org.springframework.boot:spring-boot-devtools (range: <= 2.7.32)

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2025-52999: jackson-core can throw a StackoverflowError when processing deeply nested data
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-52999](https://github.com/advisories/GHSA-h46c-h94j-95f3): jackson-core can throw a StackoverflowError when processing deeply nested data

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-core (range: < 2.15.0) → upgrade to 2.15.0

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2025-22235: Spring Boot EndpointRequest.to() creates wrong matcher if actuator endpoint is not exposed
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:10

[CVE-2025-22235](https://github.com/advisories/GHSA-rc42-6c7j-7h5r): Spring Boot EndpointRequest.to() creates wrong matcher if actuator endpoint is not exposed

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot (range: <= 2.7.24.2)
  - org.springframework.boot:spring-boot (range: >= 3.1.0, <= 3.1.15.2)
  - org.springframework.boot:spring-boot (range: >= 3.2.0, <= 3.2.13.2)
  - org.springframework.boot:spring-boot (range: >= 3.3.0, <= 3.3.10) → upgrade to 3.3.11
  - org.springframework.boot:spring-boot (range: >= 3.4.0, <= 3.4.4) → upgrade to 3.4.5

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2023-22102: MySQL Connectors takeover vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:72

[CVE-2023-22102](https://github.com/advisories/GHSA-m6vm-37g8-gqvh): MySQL Connectors takeover vulnerability

Severity: HIGH

Affected dependencies:
  - com.mysql:mysql-connector-j (range: < 8.2.0) → upgrade to 8.2.0
  - mysql:mysql-connector-java (range: <= 8.0.33)

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2023-20883: Spring Boot Welcome Page Denial of Service
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-20883](https://github.com/advisories/GHSA-xf96-w227-r7c4): Spring Boot Welcome Page Denial of Service

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot-autoconfigure (range: >= 3.0.0, < 3.0.7) → upgrade to 3.0.7
  - org.springframework.boot:spring-boot-autoconfigure (range: >= 2.7.0, < 2.7.12) → upgrade to 2.7.12
  - org.springframework.boot:spring-boot-autoconfigure (range: >= 2.6.0, < 2.6.15) → upgrade to 2.6.15
  - org.springframework.boot:spring-boot-autoconfigure (range: < 2.5.15) → upgrade to 2.5.15

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2022-45868: Password exposure in H2 Database 
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:66

[CVE-2022-45868](https://github.com/advisories/GHSA-22wj-vf5f-wrvj): Password exposure in H2 Database 

Severity: HIGH

Affected dependencies:
  - com.h2database:h2 (range: >= 1.4.198, < 2.2.220) → upgrade to 2.2.220

Recommended fix: Upgrade affected dependencies to patched versions.

### CVE-2022-31197: PostgreSQL JDBC Driver SQL Injection in ResultSet.refreshRow() with malicious column names
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml:76

[CVE-2022-31197](https://github.com/advisories/GHSA-r38f-c4h4-hqq2): PostgreSQL JDBC Driver SQL Injection in ResultSet.refreshRow() with malicious column names

Severity: HIGH

Affected dependencies:
  - org.postgresql:postgresql (range: < 42.2.26) → upgrade to 42.2.26
  - org.postgresql:postgresql (range: >= 42.4.0, < 42.4.1) → upgrade to 42.4.1
  - org.postgresql:postgresql (range: >= 42.3.0, < 42.3.7) → upgrade to 42.3.7

Recommended fix: Upgrade affected dependencies to patched versions.

## CWE Findings (Code-Level Vulnerabilities)

### CWE-1057: Data Access Operations Outside of Expected Data Manager Component
- **Category:** Code Quality
- **Severity:** potential
- **Story Points:** 5
- **Files:** src/main/java/org/springframework/samples/petclinic/owner/OwnerController.java, src/main/java/org/springframework/samples/petclinic/owner/PetController.java, src/main/java/org/springframework/samples/petclinic/vet/VetController.java

Controllers directly inject and use JPA Repository interfaces (data access objects) without an intermediate service layer. In OwnerController (line 48), PetController (line 38), and VetController (line 38), repository beans are injected directly, performing data-access operations (findById, findByLastName, save, findAll) outside of any dedicated service/manager component. The expected pattern for a layered architecture would interpose a @Service component between the controller and the repository.

### CWE-259: Use of Hard-coded Password
- **Category:** Credentials & Secrets
- **Severity:** optional
- **Story Points:** 5
- **Files:** src/main/resources/application-mysql.properties, src/main/resources/application-postgres.properties

Both database profile property files contain hard-coded default passwords embedded as fallback values in Spring property expressions. In application-mysql.properties: `spring.datasource.****** defaults to 'petclinic' when MYSQL_PASS env var is absent. In application-postgres.properties: `spring.datasource.****** defaults to 'petclinic' when POSTGRES_PASS is absent. These hard-coded fallback passwords are used to connect to the database.

### CWE-778: Insufficient Logging
- **Category:** Credentials & Secrets
- **Severity:** potential
- **Story Points:** 3
- **Files:** src/main/java/org/springframework/samples/petclinic/owner/OwnerController.java, src/main/java/org/springframework/samples/petclinic/vet/VetController.java, src/main/java/org/springframework/samples/petclinic/owner/PetController.java

None of the application's controller classes (OwnerController, PetController, VetController, VisitController) use any logging framework (no SLF4J Logger, no Log4j, no java.util.logging). Security-critical events such as form submission errors, data creation/updates, and application errors are not logged, making it impossible to audit or detect suspicious activity.

### CWE-798: Use of Hard-coded Credentials
- **Category:** Credentials & Secrets
- **Severity:** optional
- **Story Points:** 5
- **Files:** src/main/resources/application-mysql.properties, src/main/resources/application-postgres.properties

Both database profile property files embed hard-coded default credentials. application-mysql.properties sets `spring.datasource.username=${MYSQL_USER:petclinic}` and `spring.datasource.****** application-postgres.properties sets `spring.datasource.username=${POSTGRES_USER:petclinic}` and `spring.datasource.****** When the corresponding environment variables are not provided, these hard-coded username/password values are used for database authentication.

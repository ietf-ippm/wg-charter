# BPM: IPPM and BMWG Joint WG Charter

## Scope

The Benchmarking & Performance Measurements Working Group (BPM WG) develops and maintains metrics, methodologies, and protocols that can be applied to the quality, performance, reliability, and scalability of data delivery services and applications running over public and private networks using IETF technologies. These metrics, methodologies, and protocols are designed as such that they can be used by network operators and end users in production or independent testing groups in lab environments.

The methodologies cover management, control, and forwarding planes and they apply to hardware, virtualized, and containerized network infrastructure (such as Data Center network fabrics, controllers, routers, and firewalls), including Network Management software systems and endpoints in production and lab environments. Where in lab environments, the testing procedures ensure consistent, reproducible, and reportable benchmarking results including system calibration. Where in production environments, measurement and system calibration procedures ensure that production management, control, and data plane performance impact is as minimal as possible. The metrics are intended to provide unbiased, quantitative performance measurements.

The BPM WG fosters commonality and comparability of metrics and measurements across IETF protocols at different layers. The WG is also responsible for documenting guidance for methodologies and measurement protocols, including guidance on how to handle sensitive and vulnerable metrics, that methodologies are safe and cannot be easily abused, and that the results are trustworthy. In addition, the WG provides guidance on the interpretation of measurement results and the use of relevant operational context.

## Work Items

The WG is responsible for the development and maintenance of active, passive, and hybrid performance measurement protocols, as defined in RFC 7799 (Standards Track or Experimental). The WG will also produce terminology documents and recommendations on key performance characteristics of internetworking technologies, on frameworks for assessing these characteristics, and on benchmarks for network devices, systems, and services (Informational or Best Current Practices (BCP)). In addition, the WG will specify related manageability aspects such as YANG data models for configuration, operation, and IPFIX entities for Network Telemetry data export (Standards Track or Experimental).

The work scope is limited to protocols, metrics, and methodologies that are applicable to the IP and MPLS data plane and its upper-layer protocols. Layer 2 applications can be covered as well but require explicit approval from the Responsible Area Director. This WG does not specify encapsulations required for measurements over non-IP and non-MPLS layers.

The WG is responsible for the maintenance of RFCs published by the concluded BMWG and IPPM WGs (including updating those published as Proposed Standard to Internet Standard and Informational to BCP) and the maintenance of BCP 170 (Guidelines for Considering New Performance Metric Development).

In general, the WG expects an implementation for Standards Track documents. In some cases an implementation proof might not be needed. Whenever such an exception applies, the exception justification must be included in the specification document or its write-up.

## Relationship With Existing WGs, Coordination, and Liaisons

The WG will follow transport-related BCPs (mainly, BCP 133 on Specifying New Congestion Control Algorithms, BCP 145 on UDP Usage Guidelines, and BCP 208 on Network Transport Circuit Breakers) and will seek advice from the WIT area as needed.

The WG coordinates performance measurement-related work within the IETF. It specifically coordinates with other WGs such as MPLS, 6MAN, and SPRING, where data plane encapsulations are specified. Also, the WG will seek feedback from other OPS WGs such as V6OPS or SRV6OPS as needed. The WG closely collaborates with the Performance Metrics Directorate per the guidance in BCP 170.

The WG liaises with other Standards Development Organizations such as ITU-T, IEEE, 3GPP, and BBF and reaches out to other operator communities such as NANOG, RIPE, and APRICOT.

## Milestones

| Date     | Milestone                                                                                                               | Associated documents                        | Intended Track        |
|----------|-------------------------------------------------------------------------------------------------------------------------|---------------------------------------------|:---------------------:|
| Oct 2026 | Submit Simple Two-Way Active Measurement Protocol (STAMP) Extensions for Reflecting STAMP Packet IP Headers to the IESG | draft-ietf-ippm-stamp-ext-hdr               | Standards Track       |
| Nov 2026 | Submit Alternate Marking Deployment Framework to the IESG                                                               | draft-ietf-ippm-alt-mark-deployment         | Informational         |
| Nov 2026 | Submit A YANG Data Model for the Alternate-Marking Method to the IESG                                                   | draft-ietf-ippm-alt-mark-yang               | Standards Track       |
| Dec 2026 | Submit Considerations for Benchmarking Network Performance in Containerized Infrastructures to the IESG                 | draft-ietf-bmwg-containerized-infra         | Informational         |
| Jan 2027 | Submit IPv6 Performance and Diagnostic Metrics Version 2 (PDMv2) Destination Option to the IESG                         | draft-ietf-ippm-encrypted-pdmv2             | Standards Track       |
| Feb 2027 | Submit Characterization and Benchmarking Methodology for Power in Networking Devices to the IESG                        | draft-ietf-bmwg-powerbench                  | Informational       |
| Mar 2027 | Submit RFC7799bis to the IESG                                                                                           | draft-fioccola-ippm-rfc7799bis              | Best Current Practice |
| Mar 2027 | Submit Update of the Simple Two-way Active Measurement Protocol Class-of-Service Extension - ECN to the IESG            | draft-ietf-ippm-stamp-cos-ecn               | Standards Track       |
| Apr 2027 | Submit On-Path Telemetry YANG Data Model to the IESG                                                                    | draft-ietf-ippm-on-path-telemetry-yang      | Standards Track       |
| Apr 2027 | Submit On-Path Telemetry for Active Performance Measurements to the IESG                                                | draft-ietf-ippm-on-path-active-measurements | Informational         |
| May 2027 | Submit Benchmarking Methodology for Intra-domain and Inter-domain Source Address Validation to the IESG                 | draft-ietf-bmwg-savnet-sav-benchmarking     | Informational         |


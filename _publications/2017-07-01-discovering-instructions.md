---
title: "Discovering instructions for robust binary-level coverage criteria"
collection: publications
permalink: /publication/2017-07-01-discovering-instructions
excerpt: 'Object-Branch Coverage (OBC) is often used to measure effectiveness of test suites, when source code is unavailable. The traditional OBC definition can be made more resilient to variations in compilers and the structure of generated code by creating more robust definitions. However finding which instructions should be included in each new definition is laborious, error-prone, and architecture-dependent. We automate the discovery of instructions to be included for an improved OBC definition on the X86 and ARM architectures. We discover all possible valid instructions by symbolically executing instruction decoders for X86 and ARM instructions. For each discovered instruction, we translate it to Vine IR, and check if the Vine IR translation satisfies the OBC definition. We verify the correctness of our tool by comparing its output with the X86 and ARM architecture manuals. Our automated instruction classification facilitates development of more robust OBC definitions with better bug-finding ability and lesser sensitivity to compiler variations.'
date: 2017-07-01
venue: 'TECPS 2017: Proceedings of the 1st ACM SIGSOFT International Workshop on Testing Embedded and Cyber-Physical Systems'
paperurl: 'https://dl.acm.org/doi/pdf/10.1145/3107091.3107092'
citation: '.'
---

<a href='https://dl.acm.org/doi/pdf/10.1145/3107091.3107092'>Download paper here</a>

Object-Branch Coverage (OBC) is often used to measure effectiveness of test suites, when source code is unavailable. The traditional OBC definition can be made more resilient to variations in compilers and the structure of generated code by creating more robust definitions. However finding which instructions should be included in each new definition is laborious, error-prone, and architecture-dependent. We automate the discovery of instructions to be included for an improved OBC definition on the X86 and ARM architectures. We discover all possible valid instructions by symbolically executing instruction decoders for X86 and ARM instructions. For each discovered instruction, we translate it to Vine IR, and check if the Vine IR translation satisfies the OBC definition. We verify the correctness of our tool by comparing its output with the X86 and ARM architecture manuals. Our automated instruction classification facilitates development of more robust OBC definitions with better bug-finding ability and lesser sensitivity to compiler variations.

Recommended citation: .
# DevCoach

A comprehensive code analysis and technical interview preparation tool built on PartyRock.

## What It Does

DevCoach takes any code snippet or programming concept and provides four-dimensional analysis:

## Features

### Core Diagnostic Modes

1. **Source Code Review** - Deep dive into code logic, execution flow, and implementation patterns
2. **Data Structures and Algorithms** - Algorithmic complexity analysis and data structure evaluation  
3. **System Architecture & Framework Analysis** - Architectural patterns, scalability, and framework-specific insights

### Specialized Analysis Widgets

1. **Structural Logic & Framework Breakdown**
   - Plain-language explanation followed by systematic technical analysis
   - Control flow and data structure pattern identification
   - Step-by-step execution sequence decomposition

2. **Algorithmic Efficiency & Complexity Audit**
   - Time and space complexity with Big O notation
   - Mathematical justification for complexity analysis
   - Throughput and latency characteristics for system architectures

3. **Data Structure & Execution Visual Simulation Syntax**
   - Auto-generates Mermaid.js diagram code
   - Flowcharts, tree diagrams, sequence diagrams, and architecture visualizations
   - Copy-paste ready for documentation

4. **Production Optimization & Refactored Blueprint**
   - Identifies anti-patterns and inefficiencies
   - Experience-level tailored optimization (Junior/Mid/Senior)
   - Production-ready refactored code with annotations

5. **Security & System Edge Case Validation**
   - Vulnerability assessment (injection, authentication, data exposure)
   - Unhandled exceptions and error scenarios
   - Resource leak detection and boundary condition analysis

6. **Targeted Technical Interview Simulator**
   - Three custom interview questions per analysis
   - Ideal answer frameworks and key concepts
   - Common mistakes and misconceptions to avoid

7. **Explain Like Five Year Old**
   - Complex concepts in simple everyday language that are perfect for teaching or understanding fundamentals.

## Why I Built It

Technical interview prep often focuses on "what does this code do" without explaining how to think about it systematically. DevCoach bridges that gap by providing structured analysis from multiple angles simultaneously - like having a technical mentor who always covers the same comprehensive checklist.

## Try It

[Live App on PartyRock](https://partyrock.aws/u/g1oangelo/y7I7C3IlW/DevCoach)

## How to Use

1. **Select Core Diagnostic Mode**: Choose your analysis focus (Source Code, Data Structures, or System Architecture)
2. **Specify Target Technology**: Enter your programming language or framework (Python, Java, SQL, React, etc.)
3. **Choose Experience Level**: Select Junior Developer, Mid-Level Engineer, or Senior Systems Architect
4. **Paste Your Code/Concept**: Input source code, architectural diagrams, database schemas, or technical concepts

## Limitations
- DevCoach analyzes code structure and logic, but cannot execute or test code.
- Best suited for code snippets and system designs rather than full applications.
- Mermaid diagrams require a Mermaid renderer to visualize (available in most modern markdown editors).
- Security analysis is educational; always conduct professional security audits for production systems.

## Technical Details

- Built on Amazon Bedrock using Claude 4.5 Sonnet
- Temperature-optimized per analysis type (0.4-0.6)
- Formal academic tone without decorative elements
- All widgets generate in parallel for efficiency

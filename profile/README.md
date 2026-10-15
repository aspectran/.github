# Aspectran: A Concise and Powerful Java Application Framework

![Aspectran logo](https://aspectran.com/images/header_aspectran.png)

[![Web Frameworks Benchmark](https://web-frameworks-benchmark.vercel.app/frameworks/java/aspectran/badge-language.svg)](https://web-frameworks-benchmark.vercel.app/frameworks/java/aspectran/)
[![Build Status](https://github.com/aspectran/aspectran/workflows/Java%20CI/badge.svg)](https://github.com/aspectran/aspectran/actions?query=workflow%3A%22Java+CI%22)
[![Maven Central Version](https://img.shields.io/maven-central/v/com.aspectran/aspectran-project)](https://central.sonatype.com/artifact/com.aspectran/aspectran-project)
[![javadoc](https://javadoc.io/badge2/com.aspectran/aspectran-all/javadoc.svg)](https://javadoc.io/doc/com.aspectran/aspectran-all)
[![License](https://img.shields.io/:license-apache-brightgreen.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

## Overview

Aspectran is a lightweight, high-performance JVM framework designed to efficiently build everything from simple command-line tools to complex enterprise web services. It delivers rapid startup times and a minimal memory footprint through minimal dependencies and optimized resource usage, making it ideal for microservices and cloud-native environments.

At its core, Aspectran emphasizes an intuitive **POJO-centric programming model**. By leveraging enterprise architectural patterns such as **Inversion of Control (IoC)**, **Dependency Injection (DI)**, and **Aspect-Oriented Programming (AOP)**, it maximizes code modularity and reusability. A signature strength is its **Adapter Pattern for environment abstraction**, which allows the exact same business logic to run without modification across diverse runtimes—whether in embedded web servers (Netty, Undertow, Jetty), standard Servlet containers, command-line shells, or background daemon processes.

## Ecosystem

The Aspectran organization provides a modular suite of projects to support every stage of application development:

### Core Framework & Enterprise Platform
- **[aspectran/aspectran](https://github.com/aspectran/aspectran)**: The foundational JVM framework providing core IoC, DI, AOP, rule-based Translet processing, and multi-environment runtime abstraction.
- **[aspectran/aspectow](https://github.com/aspectran/aspectow)**: An enterprise WAS and distributed cluster control platform built on Aspectran. It integrates the visual web management console (**Aspectow Console**), the **Node Manager** control plane (supporting both Direct P2P and Redis-backed Gateway modes for Kubernetes and cloud autoscaling), and built-in real-time **AppMon** monitoring.

### Starter Projects (Skeletons)
- **[Aspectow Enterprise](https://github.com/aspectran/aspectow-enterprise)**: Full-featured Enterprise Edition starter powered by JBoss Undertow and Apache Jasper (JSP engine), with built-in visual cluster control via Aspectow Console.
- **[Aspectow Edge](https://github.com/aspectran/aspectow-edge)**: Ultra-lightweight, non-servlet runtime starter powered by embedded Netty and Java 21 Virtual Threads, optimized for high-throughput microservices and REST APIs with minimal resource overhead.
- **[Aspectow Jetty](https://github.com/aspectran/aspectow-jetty)**: Robust Servlet 6.0 web application starter specifically pre-configured with the embedded Jetty 12 server.

### Demo & Sample Applications
- **[Aspectow Demo Site](https://github.com/aspectran/aspectow-demo)**: A comprehensive reference application demonstrating JPetStore, PetClinic, various feature examples, and AppMon running together in a live enterprise cluster.
- **[ToDo Webapp](https://github.com/aspectran/aspectow-todo-webapp)**: Standard MVC web application example based on the Aspectow Enterprise Edition.
- **[JPetStore](https://github.com/aspectran/aspectran-jpetstore)**: Full database integration demo application using MyBatis and Aspectran.
- **[Petclinic](https://github.com/aspectran/aspectran-petclinic)**: Modern Spring PetClinic equivalent built with Aspectran, utilizing JPA and Thymeleaf.

## Quick Start & Guides

- **[Getting Started with Aspectran](https://aspectran.com/en/docs/guides/aspectran-getting-started/)**: Step-by-step tutorial for setting up your development environment and creating your first application.
- **[Why Aspectran](https://aspectran.com/en/why-aspectran/)**: Discover Aspectran's design philosophy of "sustainable simplicity", core architectural principles, and its intuitive alternative to complex enterprise frameworks.
- **[Why Aspectow](https://aspectran.com/en/why-aspectow/)**: Learn about Aspectow's architectural vision, editions, self-contained management console, and dynamic clustering.
- **[Documentation Index](https://aspectran.com/en/docs/)**: Comprehensive technical guides and reference documentation for both Aspectran and Aspectow.

## Resources

- **Official Website**: [https://aspectran.com](https://aspectran.com)
- **Interactive Demo**: [https://public.aspectran.com](https://public.aspectran.com)
- **Official Blog**: [https://aspectran.com/blog/](https://aspectran.com/blog/)
- **API Documentation (Javadoc)**: [https://javadoc.io/doc/com.aspectran/aspectran-all](https://javadoc.io/doc/com.aspectran/aspectran-all)
- **Benchmark**: [Aspectran on Web Frameworks Benchmark](https://web-frameworks-benchmark.vercel.app/frameworks/java/aspectran/)

Thank you for your interest in Aspectran! We are excited to see the amazing applications you build.

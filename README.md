# Java Dev Containers with Spring Boot Demo and Gradle

## Description

This project is a demo of Java Dev Containers with Gradle. It contains a demo of Spring Boot.

## Features

- Java 21
- Gradle

## Requirement

- [Visual Studio Code](https://code.visualstudio.com/Download)
- [Docker](https://www.docker.com/)

Tested environment:

- Ubuntu 24.04

## Usage

### 1. Open / Rebuild Dev Container

```shell
Ctrl + Shift + p
```

Select the option:

```text
> Dev Containers: Rebuild and Reopen in Container
```

### 2. Open terminal

```shell
Ctrl + Shift + p
```

Select the option:

```text
> Terminal: Create New Terminal
```

### 3. Create Java Project with Gradle


```shell
vscode ➜ /workspace $ mkdir myproject
vscode ➜ /workspace $ cd myproject
vscode ➜ /workspace/myproject $ gradle init
```

### 4. Generate `.gitignore` file

```shell
curl -L http://www.gitignore.io/api/macos,linux,visualstudiocode --output gitignore
```

## Licence

Released under the [MIT license](https://mit-license.org/)

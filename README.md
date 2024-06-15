# E-Tag Vehicle Access System - Formal Methods

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

This project involves the formal specification of an E-Tag Vehicle Access System using Protégé, followed by modeling and verification using UPPAAL. The goal is to demonstrate the application of formal methods to ensure the correctness and reliability of the E-Tag system. This was developed as an end semester project for formal methods.

## Project Structure

The repository is organized into the following folders:

- `protege`: Contains the formal specification file `FMprotege.rdf` created using Protégé.
- `uppaal`: Contains the UPPAAL model `E-tag_updated.xml`, which includes the timed automata simulations and verifications.

## Features

- Formal specification of an E-Tag Vehicle Access System using Protégé.
- Modeling and verification of the E-Tag system using UPPAAL.
- Timed automata simulations and verification for system correctness.

## Installation

To explore the formal specifications and models, follow these steps:

### Protégé

1. Download and install [Protégé](https://protege.stanford.edu/).
2. Open the `FMprotege.rdf` file located in the `protege` folder with Protégé:
    ```bash
    cd etag_system_fm/protege
    open FMprotege.rdf
    ```

### UPPAAL

1. Download and install [UPPAAL](http://www.uppaal.org/).
2. Open the `E-tag_updated.xml` file located in the `uppaal` folder with UPPAAL:
    ```bash
    cd etag_system_fm/uppaal
    open E-tag_updated.xml
    ```

## Usage

### Formal Specification with Protégé

Open the `FMprotege.rdf` file in Protégé to explore the formal specification of the E-Tag Vehicle Access System. You can examine the classes, properties, and instances that define the system.

### Modeling and Verification with UPPAAL

Open the `E-tag_updated.xml` file in UPPAAL to view and interact with the timed automata models. You can run simulations and verifications to check the correctness and performance of the E-Tag system.

## Contributing

Contributions are welcome! If you would like to contribute to this repository, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Create a new Pull Request





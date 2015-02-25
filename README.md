# VED

Command-line validation of structured text files

# Description

ved works by applying rules written on a validation language (similar to rspec) to a set of text files that need single or cross-file checks. It outputs a report with errors and warnings on these files.

## Install

    gem instal ved

## Creating a project

    ved create <projectname>

## Project structure

    - project name
        - config
        - input
        - lib
        - log
        - output
        - pak

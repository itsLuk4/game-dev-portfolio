---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
description: "Brief description of the design document"
# Document metadata
docType: "GDD" # GDD, Technical Design, Level Design, System Design, Narrative Design, etc.
game: "" # Link to related game project
status: "Draft" # Draft, In Review, Approved, Archived, Implemented
version: "0.1"
# Organization
tags: []
categories: []
series: ""
---
## Executive Summary

High-level summary of this design document.

## Context & Goals

Why does this design exist? What problem does it solve?

## Design Details

### Core Concept

### Systems & Mechanics

### User Experience / Player Journey

### Technical Considerations

## Diagrams & References

Add diagrams, flowcharts, or reference materials here.

## Change Log

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 0.1 | {{ .Date | dateFormat "2006-01-02" }} | Your Name | Initial draft |
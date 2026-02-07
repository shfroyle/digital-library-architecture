# digital-library-architecture
Digital library architecture and metadata schema design for nonprofit resource collection
Digital Library Architecture Project – Humane Choices Resource Library
Overview

This project documents the design and implementation of a structured digital resource library for The Humane Choices organization. The goal was to create a scalable, metadata-driven system for organizing articles, open-access books, videos, and educational materials into a searchable online library.

The project focuses on information architecture, metadata schema design, and sustainable content management workflows.


Objectives
- Develop a structured resource library rather than a blog-style resource page
- Implement metadata fields aligned with digital library standards
- Enable future migration into dedicated digital collection platforms (e.g., Omeka)
- Improve discoverability through taxonomy and tagging systems


Information Architecture

The resource library is organized using a dual taxonomy approach:

- Subject Categories (Primary)
-- Ethics
-- Animal welfare
-- Environmental impact
-- Advocacy

- Resource Types (Secondary)
-- Articles
-- Books
-- Videos
-- Toolkits


Metadata Schema

A lightweight Dublin Core-inspired schema was used.

Key fields include:
- Title
- Creator
- Resource type
- Subject category
- Tags
- Description
- URL
- License
- Date added

See metadata-schema.xlsx for full structure.


Workflow Design
1. Resource identified
2. Metadata entered into master spreadsheet
3. Tags and subject categories assigned
4. Resource reviewed and published


Tools Used
- Excel (metadata management)
- Web CMS (implementation)
- GitHub (documentation)


Future Development
- Potential migration to Omeka for enhanced digital collection features
- API-based metadata export
- Improved filtering/search functionality

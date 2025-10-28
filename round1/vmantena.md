# Crowdsourcing Project Idea: Missing Menu Mapper

## Author
Veda, vmantena

## Problem Statement
Food delivery apps often show incomplete or outdated restaurant menus. This frustrates customers and reduces sales for small restaurants that rely on delivery platforms. My project will crowdsource accurate, up-to-date menu information for local restaurants that lack strong digital presence.

## Core Concept
**One-line pitch:** Users upload and verify real restaurant menus to keep delivery platforms accurate and current.

**Target users:** Food delivery customers and small restaurants that need reliable digital menus.

**The crowd:** Volunteers, local diners, and social media users who visit restaurants and capture menu information.

**The task:** Workers photograph a menu or receipt, transcribe prices and items into structured fields, and validate entries submitted by others.

## Key Features
1. Menu upload and transcription workflow
2. Redundancy-based validation system
3. Priority focus on restaurants with missing or outdated menus

## Feasibility Check
**Data source:** Photos of physical menus, screenshots, Google Maps business listings, Yelp photos.

**Budget reality:** Free volunteers + very small MTurk budget for validation tasks if needed.

**Crowd size needed:** Hundreds. Most restaurants only require a few submissions each.

**Quality control approach:** Redundant submissions, consensus voting, gold-standard items seeded in the workflow.

## Technical Approach
**Human tasks:** Upload menu photo, transcribe text and prices, verify other people’s entries.

**Automated tasks:** Basic OCR to pre-fill text, flag inconsistencies, cluster menus by restaurant.

**Aggregation method:** Majority vote on each menu item field plus confidence scoring from multiple submissions.

## Prior Work
**Similar projects:** OpenStreetMap for mapping civic infrastructure, Google Local Guides for business info. My project differs by specializing in menu accuracy and adding structured transcription tasks.

**Lessons from past course projects:** Scope must be tight with a clear, repetitive microtask. Provide workers feedback and show immediate progress to keep motivation high.

## Why This Could Work
Menu data is constantly being posted online by ordinary people already. A lightweight pipeline that collects and verifies this information can produce a valuable resource very quickly. The task is simple, highly repeatable, and doesn’t require specialized skill from workers.

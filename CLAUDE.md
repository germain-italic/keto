# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a simple static website repository for keto diet resources containing two main HTML files:
- `epices.html` - A French guide for keto-friendly spice combinations and salt alternatives
- `menu-2200cal.html` - A French daily keto meal plan targeting 2000-2200 calories

## Architecture

This is a static HTML website with embedded CSS styling. The files are:
- Self-contained HTML documents with inline CSS
- Designed for print layout (A4 format)
- Responsive design with mobile viewport support
- No external dependencies or JavaScript
- French language content focused on ketogenic diet guidance

## Content Structure

### epices.html
- Spice combination guide organized by food categories (vegetables, meats, fish)
- Includes sweet spices section for beverages and desserts
- Usage tips and alternatives for salt reduction
- Print-friendly layout with page break controls

### menu-2200cal.html
- Daily meal plan structure (breakfast, main meals, snacks)
- Macro nutrient targets and calorie tracking
- Exercise guidelines and hydration recommendations
- Sodium reduction warnings and portion guidelines

## Development Notes

- Files use French language throughout
- Designed for printing on A4 paper with 1cm margins
- CSS uses CSS Grid and Flexbox for layouts
- Color-coded sections for different meal types and information categories
- No build process required - direct HTML files
- Hosted on GitHub Pages at https://germain-italic.github.io

## File Management

Since this is a simple static site, files can be edited directly. The HTML includes embedded CSS, so style changes should be made within the `<style>` sections of each file.
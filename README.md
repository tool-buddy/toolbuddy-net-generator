[![Deploy Website](https://github.com/tool-buddy/toolbuddy-net-generator/actions/workflows/deploy.yml/badge.svg)](https://github.com/tool-buddy/toolbuddy-net-generator/actions/workflows/deploy.yml)

# ToolBuddy Website

This repository contains the source code for the [ToolBuddy](https://toolbuddy.net/) website, a website providing expertise and products for video game creators.

## Dependencies

- [Hugo 0.147.9](https://gohugo.io/) - Static site generator

## Local Development


### Getting Started

1. Clone the repository:
   ```bash
   git clone --recurse-submodules https://github.com/tool-buddy/toolbuddy-net-generator.git
   cd toolbuddy-net-generator
   ```

2. Start the Hugo development server:
   ```bash
   hugo server -D
   ```

3. Open your browser and visit `http://localhost:1313`

### Common Commands

- `hugo new content/<section>/<filename>.md` - Create new content
- `hugo server` - Start development server
- `hugo` - Build the site for production
- `hugo --minify` - Build the site with minification

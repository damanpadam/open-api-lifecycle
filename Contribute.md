# Documenting changes in the .md files
Use the following Markdown guide as reference to update the project documentation files
    https://guides.github.com/features/mastering-markdown/

# Setup Development Environment
Installed Node 8.11.x using.
Downloading the tar ball from Node.js site
On Ubuntu run the following command
    sudo tar -xf node-v8.11.3-linux-x64.tar.xz --directory /usr/local --strip-components 1

# Clone Git Repository
    git clone https://github.com/damanpadam/open-api-lifecycle.git

# Install VSCode
Download .deb package file
    sudo dpkg -i <file>.deb
    sudo apt-get install -f # Install dependencies
Install Swagger Viewer Extenstion
    Swagger Viewer 1.7.0
Install OpenAPI linter
    openapi-lint 0.3.0

# Install typescript
    sudo npm install -g typescript

# Development guidelines

## Documentation
    * README.md file is used for high level project log commentary (also called the captain's log)
    * Contribute.md file has all the project related configurations to get this project operational

## Change Management
    * All the code development is in the "development" branch. No feature branches at this point to keep things simple. Unless I want to try out a parallel approach
    * Stable code will be moved to the "master" branch through pull request     
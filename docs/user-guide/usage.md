# Usage Guide

This guide provides an overview of how to use our software effectively.

## Getting Started

After installation, you can start the software by running:

```bash
our-software
```

## Basic Commands

Here are some basic commands to get you started:

- `our-software new <project-name>`: Create a new project
- `our-software run <project-name>`: Run an existing project
- `our-software list`: List all projects
- `our-software help`: Display help information

## Configuration

### Configuration File

The software uses a configuration file located at `~/.our-software/config.yml`. Here's an example configuration:

```yaml
output_directory: ~/projects
default_template: basic
log_level: info
```

### Environment Variables

You can also use environment variables to configure the software:

- `OUR_SOFTWARE_OUTPUT_DIR`: Set the output directory
- `OUR_SOFTWARE_LOG_LEVEL`: Set the log level (debug, info, warning, error)

## Advanced Usage

### Custom Templates

You can create custom templates in the `~/.our-software/templates` directory. Use the `--template` flag to specify a custom template:

```bash
our-software new myproject --template custom
```

### Plugins

Our software supports plugins. To use a plugin, install it and add it to your configuration file:

```yaml
plugins:
  - my-awesome-plugin
  - another-great-plugin
```

## Best Practices

1. Always use version control for your projects.
2. Regularly update the software to get the latest features and security patches.
3. Use meaningful names for your projects and files.

## Troubleshooting

If you encounter any issues while using the software, try the following:

1. Check the log files in `~/.our-software/logs/`
2. Run the software with the `--debug` flag for more detailed output
3. Consult our [online documentation](https://example.com/docs) for more information

If the problem persists, please open an issue on our [GitHub repository](https://github.com/example/our-software/issues).
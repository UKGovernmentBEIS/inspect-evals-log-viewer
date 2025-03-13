# Log Viewer

This directory contains the log viewer interface for the Control Arena project. The viewer is automatically built and deployed to GitHub Pages using GitHub Actions.

## Structure

- `logs/`: Directory containing the log files to be visualized
- `logs-www/`: Generated directory containing the built viewer interface (created during the build process)

## Local Development

To build and view the logs locally, run:

```bash
uv run inspect view bundle --log-dir logs --output-dir logs-www
```

Then serve the `logs-www` directory using a web server of your choice.

## Deployment

The log viewer is automatically deployed to GitHub Pages when changes are pushed to the `log-viewer` directory. You can also manually trigger the deployment through the GitHub Actions interface.

The deployed site can be accessed at: [https://[your-username].github.io/[your-repo-name]/](https://[your-username].github.io/[your-repo-name]/)

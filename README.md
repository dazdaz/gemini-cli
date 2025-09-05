# gemini-cli


* https://github.com/google-gemini/gemini-cli/blob/main/docs/cli/configuration.md
* https://github.com/google-gemini/gemini-cli/releases
* https://cloud.google.com/blog/topics/developers-practitioners/gemini-cli-custom-slash-commands


## MCP Servers
* https://github.com/GoogleCloudPlatform/cloud-run-mcp

### Installation of cloud run mcp gemini-cli extension
```bash
mkdir -p ~/.gemini/extensions/cloud-run/gemini-extension && \
curl -s -L https://raw.githubusercontent.com/GoogleCloudPlatform/cloud-run-mcp/main/gemini-extension.json > ~/.gemini/extensions/cloud-run/gemini-extension.json && \
curl -s -L https://raw.githubusercontent.com/GoogleCloudPlatform/cloud-run-mcp/main/gemini-extension/GEMINI.md > ~/.gemini/extensions/cloud-run/gemini-extension/GEMINI.md
```

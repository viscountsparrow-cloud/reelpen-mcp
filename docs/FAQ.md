# Reelpen FAQ

## What is Reelpen?
A browser-based 3D scene builder for AI video previsualization, character blocking and camera motion references.

## Can an AI assistant edit a scene?
Yes, through the authenticated remote MCP server, with the relevant permissions and an allowed editor tab for live scene operations. See the [connection guide](https://beta.reelpen.ai/guides/connect-your-ai).

## What is the MCP address?
`https://beta.reelpen.ai/mcp`, using Streamable HTTP and OAuth. Opening this URL as a webpage is not a connection test.

## Is it free?
Reelpen is currently in free beta with no payment card required. External AI clients and video generators have separate terms and charges. See [current beta access](https://beta.reelpen.ai/pricing).

## Does it generate final AI video?
It creates editable 3D scenes and reference outputs. Use a separate generation service that accepts your exported input format for the final look.

## Is every AI application supported?
Compatibility requires remote MCP and the supported OAuth flow. Client features and plan restrictions vary. A URL configuration alone does not prove a successful authenticated connection.

## Is Reelpen open source?
This repository publishes documentation; it does not publish or license the hosted application's source code.

## Does it import DWG?
A local DWG experiment has been performed, but a general DWG importer is not advertised as a released feature.

## Can I stop the AI?
Use Stop to close live editor access. To revoke the account connection, remove it in Connected apps. Separately granted saved-project and film-board permissions are distinct from live access.

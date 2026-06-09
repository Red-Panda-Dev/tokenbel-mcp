# tokenbel-mcp
TokenBel Financial Data

Read-only MCP server providing access to Belarusian securities data: tokens, shares, bonds, companies, ticker search, and company name or UNP search.

## Endpoint

https://mcp.tokenbel.info/mcp

Transport: Streamable HTTP  
Authentication: none

## Available tools

- token_get_by_uuid
- token_list
- share_get_by_uuid
- share_list
- bond_get_by_uuid
- bond_list
- company_get_by_uuid
- company_list
- search_by_ticker
- search_by_name

## Example client configuration

Remote MCP URL:

https://mcp.tokenbel.info/mcp

## Data scope

The server exposes public financial reference data about tokens, shares, bonds and companies.

## Limitations

This server is read-only. It does not provide investment advice. Data may be delayed or incomplete.

## Support

Open an issue in this repository.

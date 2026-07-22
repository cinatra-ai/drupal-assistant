# Drupal Assistant

The Cinatra Drupal authoring assistant — a chat assistant that drafts, structures, and publishes Drupal content (nodes, content types, fields, taxonomy terms, and media) against a connected Drupal site.

**Install.** Add `@cinatra-ai/drupal-assistant` from the Cinatra marketplace. It requires `@cinatra-ai/drupal-assistant-connector`, which resolves the site connection and credentials — this package handles no credentials of its own.

**Configuration.** The assistant is declared in `cinatra/config.json`: its persona, its Drupal authoring skill bundle, a `remote` launch topology targeting the connected Drupal site, and `webhook` turn delivery. There is nothing to configure per install beyond connecting a Drupal site through the connector.

## Works with

- Drupal

## Capabilities

- Draft and structure Drupal content — nodes, content types, fields, taxonomy terms, and media — from natural language
- Publish against a connected Drupal site, preferring the site's own content model
- Ships as a declarative assistant (persona plus skill bundle) with no credential handling of its own
